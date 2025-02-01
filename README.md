<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Result</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 0;
            background-color: #f8f9fa; /* Light gray background */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .result-container {
            max-width: 450px; /* Slightly smaller max-width */
            border: 1px solid #ddd;
            border-radius: 8px;
            background-color: #fff; /* White background */
             padding: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            margin: 20px; /* Margin around container */
            position: relative;
        }

         .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 10px;
        }

         .header h1 {
           font-size: 1.4rem;
           margin-bottom: 2px;
            color: #343a40; /* Darker header text */
        }


           .header p:first-child {
            font-size: 0.8rem;
            margin-bottom: 2px;
              color: #6c757d;
         }
          .header p:last-child {
             background-color: #f0f0f0; /* Lighter gray background for the circle */
            color: #6c757d;
            border-radius: 50%;
            width: 25px; /* Adjust as needed */
            height: 25px;
            display: flex;
            align-items: center;
            justify-content: center;
             font-size: 0.9rem;
         }


       .section-header {
            margin-bottom: 15px;
            font-weight: bold;
            color: #343a40; /* Darker section header text */
           }
            .section-header h2 {
                 font-size: 1.2rem;
                margin-bottom: 4px;
              }
                .section-header p {
                font-size: 0.8rem;
                margin-bottom: 2px;

              }


        table {
            width: 100%;
            border-collapse: collapse;
           margin-top: 10px;
        }

        th, td {
            padding: 10px;
            border: 1px solid #ddd;
            text-align: left;
            font-size: 0.9em; /* Smaller font for table data */
             vertical-align: top; /* Align text to the top */
        }      
    
    th {
            background-color: #f2f2f2; /* Lighter gray for table header */
            font-weight: bold;
        }
        td{
            line-height: 1.4;
        }
        .gpa-info {
            margin-top: 20px;
            font-size: 1em;
            font-weight: bold;
            color: #343a40;
            display: flex;
            justify-content: space-between;
              align-items: baseline;
        }
        .gpa-info p b {
           font-size: 1.1em;
        }
    </style>
</head>
<body>
    <div class="result-container">
           <div class="header">
              <div>
                 <h1>Ramat Isah</h1>
                 <p>Profile</p>
               </div>
              <p>RI</p>
           </div>


        <div class="section-header">
           <h2>2024/25</h2>
             <p><b>200 Level LEVEL</b></p>
             <p>First Semester</p>
          </div>
          <div class="section-header">
           <p><b>Result</b></p>
          </div>


        <p><b>Department of Mathematical Sciences</b></p>
        <p>Second Semester, 2023/2024 Session</p>
        <p>100 Level</p>
        <p>Mat. Number: MTHU/23/0913</p>

        <div class="gpa-info">
            <p>Courses offered: <b>8</b></p>
            <p>G.P.A <b>3.57</b></p>
        </div>

        <table>
            <thead>
                <tr>
                    <th>Course Code & Title</th>
                    <th>Credit</th>
                    <th>Grade</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>BASUG-MTH104 <br> Introduction To Economics Principles</td>
                    <td>2</td>
                    <td>B</td>
                </tr>
                <tr>
                    <td>BIO102 <br> General Biology li</td>
                    <td>2</td>
                    <td>D</td>
                </tr>
                <tr>
                    <td>BIO108 <br> General Biology Practical li</td>
                    <td>1</td>
                    <td>C</td>
                </tr>
                 <tr>
                    <td>GST112 <br> Nigerian Peoples And Culture</td>
                    <td>2</td>
                    <td>A</td>
                </tr>
                 <tr>
                    <td>MTH102 <br> Elementary Mathematics li</td>
                    <td>2</td>
                    <td>C</td>
                </tr>
                <tr>
                    <td>PHY102 <br> General Physics li</td>
                    <td>2</td>
                    <td>B</td>
                </tr>
                <tr>
                     <td>PHY108 <br> General Physics Practical li</td>
                    <td>1</td>
                    <td>C</td>
                </tr>
                  <tr>
                    <td>STA112 <br> Probability I</td>
                    <td>3</td>
                    <td>C</td>
                </tr>
            </tbody>
        </table>
    </div>
</body>
</html>

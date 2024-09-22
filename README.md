<!DOCTYPE html>
<html lang="en">
    <head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width initial-scale=1.0">
    <title>
        Admission Form
    </title>
    <style>
         @keyframes colorChange {
            0% {
                color: rgb(247, 28, 28);
            }
            100% {
                color: darkblue;
            }
        }

    h1{
        color: darkblue;
        background-color: rgb(234, 170, 228);
        padding: 10px;
        margin: 50px;
        border-radius: 4px;
        text-align: center;
        animation: colorChange 2s infinite; 
    }
    h2{
        text-align: center;
        font-size: 30px;
        font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font-variant: small-caps;
        font-synthesis: style;
        color: rgb(255, 14, 14);
        text-shadow: 
                1px 1px 0 rgb(25, 24, 24), /* Bottom right shadow */
                -1px -1px 0 rgb(25, 24, 24), /* Top left shadow */
                -1px 1px 0 rgb(25, 24, 24), /* Bottom left shadow */
                1px -1px 0 rgb(25, 24, 24);/* Top right shadow */
            font-size: 50px;
        
    }
    h3{
        font-size: 30px;
        text-align: center;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        text-decoration: underline;
        text-underline-offset: 6px;
        text-decoration-color: red;
        text-decoration-thickness: 1px;
    }
    body{
        font-family: Arial, sans-serif;
        margin: 0px;
        padding: 0px;
        background-color: rgb(255, 255, 255);
        width: 100%;
        

    }
    .container{
        width: 50%;
        margin: 50px auto;
        background-color: white;
        padding: 20px;
        box-shadow: 0px 0px 10px 0px #fcabab;
    }
    form{
        width: 96.5%;
        display: flex;
        flex-direction: column;
        padding: 20px;
        align-content: center;
    }
    label{
        margin-top: 15px;
        font-weight: bold;
        font-size: 20px;
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    input, select, textarea{
        width: 96.5%;
        padding: 10px;
        margin-top: 10px;
        border: 1px solid rgb(58, 57, 57);
        border-radius: 5px;
        display: flex;
        
    }
    input[type="button"]{
        background-color: darkgoldenrod;
        color: black;
        border: none;
        border-radius: 15px;
        cursor: pointer;
        padding: 15px;
        margin-top: 20px;
        width: 100px;
        font-size: 20px;
        margin-left: auto;
        
    }
    input[type="button"] :hover{
        background-color: lightgreen;
    }

    input:focus {
        border-color: red; 
        outline: none; 
    }
    </style>
    </head>

    <body>
        <div class="container">
            <h1>
                Admission Form 2025-26
            </h1>
            <h2>
                New University
            </h2>
            <form action="#" method="post">
            <!---Personal Information Section--->
                <h3>
                    Personal Information
                </h3>
                <label for="name">First name:</label>
                <input type="text" id="name" name="first name" placeholder="First" style="font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; font-size: 20px; ">
                
                
         
                <label for="name">Last name:</label>
                <input type="text" id="name" name="name" placeholder="Last" style="font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; font-size: 20px;">
                

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" placeholder="Enter email" style="font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; font-size: 20px;">
                
                <label for="phone">Phone number:</label>
                <input type="tel" id="number" name="number" placeholder="Enter Phone number" style="font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; font-size: 20px;">
                
                <label for="address">Address:</label>
                <textarea id="address" name="address" rows="4" placeholder="Enter current address..." style="font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; resize: none; width: 96.5%; height: 100px; font-size: 20px;"></textarea>
                <br>
                <!--Course information Section-->
                <h3>
                    Course Information
                </h3>
                <label for="course" >Select Course:</label>
                <select id="course" name="course" style="font-size: 20px;">
                    <option value="msc-mathematics" style=" font-size: 20px; font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;">M.sc. Mathematics</option>
                    <option value="msc-chemistry" style=" font-size: 20px; font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;">M.sc.Chemistry</option>
                    <option value="msc-physics" style=" font-size: 20px; font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;">M.sc. Physics</option>
                </select>
                <br>
                <!--Acadamic Information Section-->
                <h3>
                    Acadamic Information
                </h3>
                <label for="degree">Graduation degree:</label>
                <input type="text" id="degree" name="degree" placeholder="Enter your Graduation degree" style="font-size: 20px; font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;">
                <br>
                <label for="university">University name:</label>
                <input type="text" id="university" name="university" placeholder="Enter your University name" style="font-size: 20px; font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;">
                <br>
                <label for="percentage">Percentage/CGPA:</label>
                <input type="text" id="percentage" name="percentage" placeholder="Enter your percentage/CGPA" style="font-size: 20px; font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;">
                <br>

                <!--Submission Button-->
                <input type="button" id="submit" name="submit" value="Submit" style="font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;">
            </form>
        </div>
    </body>

</html>


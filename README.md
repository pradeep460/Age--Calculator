# Age--Calculator
Take the age of user as a input and find whether he/she is a Senior Citizen or not
<! DOCKTYPE html>
<html>
    <head>
        <title>
            Age Calculator
        </title>
    </head>
    <body>
        <center>
            <h3>
                <u>Age Calculator(Senior Or Not)</u>
            </h3>
        </center>
        <script>
            var Age;
            Age = prompt("Enter Your Age");
            if(Age>=60)
            {
                document.write("Your age is "+Age+" And you are a Senior Citizen");
            }
            else
            {
                document.write("Your age is "+Age+" And You are not a Senior Citizen");
            }
        </script>
    </body>
</html>

# JS-Intro<html>
<head>
 <style>
body {
  background-image: url('https://techozu.com/wp-content/uploads/2020/11/JavaScript_Featured-1.jpg');
  background-repeat:no-repeat;
  background-attachment: fixed;
  background-size: cover;
}
        .a{
font-size:30px;
        }
    </style>
    <title>Javascript Introduction</title>
</head>
<body class="a">
    <script language="JavaScript">
        function guessNumber() {
            const random = Math.floor(Math.random() * 10) + 1;
            let number = document.form1.txtrandom.value;
            if (number == random) {
                documnet.write("<p>Matched" + "</p>" + "<br>")
            }
            else {
                document.write("<p>Not Matched" + "</p>" + "<br>");
            }
        }
        document.write("<p> URL of the current Loading page:    " + document.URL + "</p>")
 function CalculateArea() {
  var radius = document.form1.txtRadius.value;
            document.write("<P>The area of the circle is " + (radius * radius * Math.PI) + "</p>");
        }
        function datatypes() {
            const n = document.form1.txttype.value;
            document.write("<p>Data Type Of the given value is: " + typeof n);
        }
    </script>
    <form name=form1 class="a">
        Enter your Guess between 1-10:
        <input type="text" name="txtrandom" size=10><br>
        <input type="button" value="Check if it is matched with the random number" onClick='guessNumber();'> <br>
        Enter the radius of circle:<br>
        <input type="text" name="txtRadius" size=10><br>
        <input type="button" value="Find the Area with given radius" onClick='CalculateArea();'><br>
        Enter a value to know the datatype:<br>
        <input type="text" name="txttype" size=10><br>
        <input type="button" value="Find the datatype of the given value" onClick='datatypes();'><br>
    </form>
    </script.
</body>
</html>

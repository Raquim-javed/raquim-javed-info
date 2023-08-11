<!DOCTYPE html>
<html>
<head>
    <link id=pagestyle rel="stylesheet" type="text/css" href="darktheme.css">
    <title>Rquim Javed info</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script>
       function colortheme(){
           let theme = document.getElementById("pagestyle").getAttribute("href");
           if( theme == "darktheme.css"){
               document.getElementById("pagestyle").setAttribute("href","lighttheme.css");
               document.getElementById("tx4").innerHTML="Dark Mode";
           }
            else if(theme == "lighttheme.css"){
               document.getElementById("pagestyle").setAttribute("href","darktheme.css");
               document.getElementById("tx4").innerHTML="Light Mode";
            }
       }
       function about(){
        let theme = document.getElementById("pagestyle").getAttribute("href");
           
           if(theme == "darktheme.css"){
           location.href="about.html";
           }
           else if(theme == "lighttheme.css"){
            location.href="aboutlight.html";
           }
       }

    </script>

 
</head>
<body>
<div id=dv1>
    <textarea readonly id=tx4>Light Mode</textarea>
    <button id=btn2 onclick="colortheme();"></button>
    <button id=btn3 onclick="colortheme();"></button>
    <div id=divimg > <image id=img src=bit-removebg-preview.png></image> </div></br></br>
    <div readonly id=dtx1>Hello, I am</div></br>
    <div readonly id=dtxh>Raquim Javed</div></br>
    <div readonly id=dtx2>Student web developer</div></br>
    <div readonly id=dtx3>I help myself to bring my ideas to worldwide web</div></br>
    <div id=divbtn> <button id=btn1 onclick="about();">Get Familiar</button> </div></br></br>
    <div id=dv4>Designed and coded by <a id=a1>Raquim Javed</a> © 2022</div>
</div>
<div id=dv2></div>
<div id=dv3></div>
<div id=dv5></div>


</body>    
</html>

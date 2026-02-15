<!DOCTYPE html>
<html>
<head>
    <style>
body{
background:black;
color:white;
text-align:center;
font-family:Arial;
}

.fade-in{
animation: fadeIn 2s ease-in;
}

@keyframes fadeIn{
from{opacity:0; transform:translateY(30px);}
to{opacity:1; transform:translateY(0);}
}
</style>
    <title>My First Website</title>
    <style>
        body{
            background:black;
            color:white;
            text-align:center;
            font-family:Arial;
            margin-top:100px;
        }
        h1{
            color:cyan;
            font-size:50px;
        }
        p{
            font-size:20px;
        }
        button{
            padding:10px 20px;
            background:cyan;
            border:none;
            font-size:18px;
            cursor:pointer;
        }
    </style>
</head>
<body>
<section>
  <h2>About Me</h2>
  <p>
    Hi, I am Abin Mazroor. I am a creative video editor and beginner web developer.
    I love creating cinematic edits and designing cool projects. IM 15 YEARS OLD
      ANY EDITING OR BASE WEB DEVELOPING PROJECTS CONTACT ME ON INSTAGRAM ABINMAZROOR
  </p>
</section>

<section>
  <h2>My Skills</h2>
  <ul>
    <li>Video Editing</li>
    <li>Logo Designing</li>
    <li>HTML & CSS</li>
  </ul>
</section>

<section>
  <h2>Contact</h2>
  <p>Email: ABINMAZROOR91@gmail.com</p>
  <p>Instagram: @WALTER.EFX</p>
</section>

<h1 class="fade-in">ABIN MAZROOR</h1>
<p>This is my first website</p>
<button onclick="alert('Website Working 😎')">Click Me</button>

</body>
</html>

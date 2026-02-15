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

<h1 class="fade-in">ABIN MAZROOR</h1>
<p>This is my first website</p>
<button onclick="alert('Website Working 😎')">Click Me</button>

</body>
</html>

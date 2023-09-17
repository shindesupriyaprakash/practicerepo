# practicerepo
 I make the clone of a website from internet for practice purpose using HTML and CSS.
<!DOCTYPE html>
<html>
    <head>
        <title>
            tutorial
        </title>
        <meta charset="UTF-8">
        <meta name keyword ="html, css , javascript">
        <meta author="supriya">
<style>
*{
    margin:0;
}

.main{
    position:reletive;
    margin:2px;
}

img{
    font-size: large;
    font-family:'Times New Roman', Times, serif;
    height:90%;
    width:100%;
    background-color:linear-gradient(rgb(223, 101, 101),rgb(183, 239, 16));
    position: fixed;
}

/*.img{
    position: fixed;
}*/

.text{
    position:relative;
    top: 30px;
    left: 40px;
    color: aliceblue;
}

nav{
    position: absolute;
    top: 30px;
    right:40px;
}

ul a{
    color: aliceblue;
    padding-left: 20px;
    padding-right: 20px;
    margin: 5px;
    padding-block:   20px;
    background-color:transparent;
    border-color: black;
    text-decoration: none;
}

ul a:hover{
    background-color:rgb(132, 159, 229);
    color:rgb(15, 2, 2);
    border-radius: 15px;
    animation-delay:inherit;
}

.cont{
    position: absolute;
    top:30%;
    left: 40px;
    color: white;
    font-size: 25px;
}

p{
    position:absolute;
    color: rgb(235, 227, 227);
    top: 50%;
    left: 40px;
    font-size: 20px;
}

button{
    position: absolute;
    padding: 10px 5px;
    text-align: center;
    margin: 20px 10px;
    border-radius: 20px;
    font-size: 20px;
    padding: 20px;
    text-decoration: none;
    background-color: transparent;
    color: aliceblue;
}

#btn1{top: 60%;
    left: 40px;
    }

#btn2{
    top: 60%;
    left:200px;
}

button:hover{
   background-color:rgba(81, 188, 224, 0.58);
}



</style>
    </head>
<body>
    <div class="main">
        <div class="img">
        <img src="C:\Users\DELL\Downloads/web img.jpg">
        <div class="text">
            <h1>ARSHA</h1>
        </div>
        <nav>
            <ul type="dics">
                <a href ="array.js">about</a>
                <a href ="array.js">Portfolio</a>
                <a href ="array.js">Team</a>
                <a href ="array.js">Service</a>
                <a href ="array.js">contact</a>
            </ul>
        </nav>
        <div class="cont">
        <h1>Better Solution For<br> Your Business</h1>
        </div>
        <p>We are team of talented designers making<br> websites with Bootstap</p>
        <div class="btn">
            <button id="btn1">
                Get Started
            </button>
            <button id="btn2">
                Watch Video
            </button>
        </div>
</div>
<footer>
   this is a footer side
</footer>
</body>
</html>
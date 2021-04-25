## Web page that shows LAN network diagram

<img width="1414" alt="Screen Shot 2021-04-15 at 20 56 22" src="https://user-images.githubusercontent.com/60457723/114865582-6af39f80-9e2d-11eb-8c82-4b6581cebb68.png">

### HTML code
```.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    <title>LAN network</title>
    <link href="main.css" rel="stylesheet">
</head>
<body data-new-gr-c-s-check-loaded="14.1002.0" data-gr-ext-installed="">
<!-- header -->
<header>
    <div id="head">
        <a href="main.html"><h1>LAN network</h1></a>
        <nav>
            <ul>
                <li><a href="https://www.computerhope.com/jargon/c/cloudcom.htm">Cloud</a></li>
                <li><a href="https://www.computerhope.com/jargon/s/server.htm">Server</a></li>
                <li><a href="https://www.computerhope.com/jargon/s/switch.htm">Switch</a></li>
                <li><a href="https://www.computerhope.com/jargon/r/router.htm">Router</a></li>
                <li><a href="https://www.computerhope.com/jargon/p/pc.htm">PC</a></li>
                <li><a href="https://www.computerhope.com/jargon/l/laptop.htm">Laptop</a></li>

            </ul>
        </nav>
    </div>
</header>
<!-- /header -->
<!-- contents-->
<div id="contents">
    <!-- top -->
    <div id="top">
        <img src="i_Computer-Network-Diagram_full%20copy.jpg" alt="top">
    </div>
    <!-- /top -->

</div>
```

### CSS code
```.css
@charset "utf-8";
/* CSS Document */

/* overall */
body{
    background-color: #c1de98;

}
img { max-width : 100% }
#contents{
    max-width: 1200px;
    margin: 0 auto;
    padding-top:80px;
    background-color: #f8f8f8;
}
h2{
    text-align: center;
    font-size: 25px;
    color: #f8f8f8;
    font-weight: bold;
    padding-top: 25px;
}
/* /page */
/* header section */
header{
    width: 100%;
    height: 80px;
    margin: 0 auto;
    background: #2A2B33;
    position:fixed;
}
#head{
    max-width: 1200px;
    height: 80px;
    margin: 0 auto;
}
h1{
    width: 300px;
    height: 60px;
    padding-top: 5px;
    font-size: 25px;
    color: #f8f8f8;
    font-weight: bold;
    text-align: center;
    float:left;
}


nav ul li{
    width: 100px;
    height: 80px;
    float: right;
    text-align: center;
}
nav ul li a{
    display: block;
    font-size: 25px;
    color: #f8f8f8;
    padding-top: 25px ;
    text-decoration: none;
}
nav ul li a:hover{
    color: #dbc574;
}

/* top */
#top{
    max-width: 1200px;
    margin: 0 auto;
    background-color: #f8f8f8;
}
```

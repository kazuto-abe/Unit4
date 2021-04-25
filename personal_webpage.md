#### main.html file

```.html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <title>Kazu's portfolio</title>
        <link href="reset.css" rel="stylesheet">
        <link href="style.css" rel="stylesheet">
        <link href="contact.css" rel="stylesheet">
    </head>
    <body data-new-gr-c-s-check-loaded="14.1002.0" data-gr-ext-installed="">
    <!-- header -->
    <header>
        <div id="head">
            <a href="index.html"><h1>Kazu's portfolio</h1></a>
            <nav>
                <ul>
                    <li><a href="#contact">contact</a></li>
                    <li><a href="#profile">profile</a></li>
                    <li><a href="#works">works</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <!-- /header -->
    <!-- contents-->
    <div id="contents">
        <!-- top -->
        <div id="top">
            <img src="images/DSC01484.JPG" alt="top">
        </div>
        <!-- /top -->

        <!-- works -->
        <div id="works">
            <div id="worktitle">
                <h2>works</h2>
            </div>
            <div id="worksimagesub">

            </div>
        </div>
        <!-- /works -->
        <!-- profile -->
        <div id="profile">
            <div id="protitle">
                <h2>profile</h2>
            </div>
            <div id="proimage">
                <img src="images/DSC04663.jpg">
            </div>
            <div id="promoji">
                <h3>Kazuto Abe</h3>
                <p>Hi, I'm Kazuto Abe from Japan, please call me Kazu.</p>
                <p>text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text text</p>
                <p>text text text text text text text text text text text text text text text texttext text text text text text text texttext text text text text text text texttext text text text text text text text</p>
            </div>
        </div>
        <!-- /profile -->
        <!-- contact -->
        <div id="contact">
            <div id="contacttitle">
                <h2>contact</h2>
            </div>
            <div id="contactform">
                <div id="formWrap">
                    <h3>Please contact me if you have some questions about me.</h3>

                    <form>
                        <table class="formTable">

                            <tbody><tr>
                                <th>Name</th>
                                <td><input size="30" type="text" name="お名前"> </td>
                            </tr>

                            <tr>
                                <th>Mail</th>
                                <td><input size="30" type="text" name="Email"></td>
                            </tr>

                            <tr>
                                <th>Content</th>
                                <td><textarea name="お問い合わせ内容" cols="50" rows="5"></textarea></td>
                            </tr>
                            </tbody></table>
                        <p align="center">
                            <input type="submit" value="　 submit 　">　<input type="reset" value="Erase all">
                        </p>
                    </form>
                </div>
            </div>

        </div>
        <!-- contact -->
        <!-- footer -->
        <footer>
            <div id="footermoji">
                <p><small>2021 Kazuto Abe. All Rights Reserved.</small></p>
            </div>
        </footer>

        <!-- /footer -->
    </div>
    <!-- /contents-->


    </body>
</html>
```

#### stylesheet.css file

```.css
@charset "utf-8";
/* CSS Document */

/* 全体 */
body{
    background-color: #E3D3E9;

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
/* /全体 */
/* ヘッダー */
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
    padding-top: 25px;
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
    color: #E3D3E9;
}

/* /ヘッダー */
/* コンテンツ */
/* トップ */
#top{
    max-width: 1200px;
    margin: 0 auto;
    background-color: #f8f8f8;
}
/* /トップ */
/* プロフィール */
#profile{
    padding-top: 80px;
}
#protitle{
    height: 80px;
    margin: 0 auto;
    background: #BB8DCC;
}
#proimage{
    max-width: 500px;
    margin: 0 auto;
}
#promoji{

    max-width: 500px;
    margin: 0 auto;
}
h3{
    text-align: center;
    font-weight: bold;
    margin: 20px;
    color: #555;
}
p{
    color:#555;
    font-size:12px;
    margin: 10px;
}
/* /プロフィール */
/* 作品 */
#worktitle{
    height: 80px;
    margin: 0 auto;
    background: #BB8DCC;
}
#worksimagesub{
    max-width: 1020px;
    margin: 70px auto;
}

#worksimagesub a:hover img {
    opacity: 0.7;
    -ms-filter: "worksimagesub(opacity=70)";
}

/* /作品 */
/* コンタクト */
#contact{
    padding-top: 80px;
    max-width: 1200px;
}
#contacttitle{
    height: 80px;
    margin: 0 auto;
    background: #BB8DCC;
}
/* /コンタクト */



/* /コンテンツ */



/* ワークページ */
#worksimage{
    max-width: 980px;
    margin: 0 auto;
}
.yohaku{
    padding-top:100px;
    font-size: 25px;
}

/* /ワークページ */


/* フッター*/
footer {
    text-align : center;
    padding : 1.5em 0;
    background : #2A2B33;
}
p small{
    color: #f8f8f8;
}
/* /フッター*/

```

#### contact.css file

```.css
@charset "utf-8";


#formWrap {
    width:700px;
    margin:0 auto;
    color:#555;
    line-height:120%;
    font-size:90%;
}
table.formTable{
    width:100%;
    margin:0 auto;
    border-collapse:collapse;
}
table.formTable td,table.formTable th{
    border:1px solid #ccc;
    padding:10px;
}
table.formTable th{
    width:30%;
    font-weight:normal;
    background:#2A2B33;
    text-align:center;
    color:#F8F8F8
}
p.error_messe{
    margin:5px 0;
    color:red;
}
#contactform{
    width: 100%;
    margin: 100px 20px;
}
```

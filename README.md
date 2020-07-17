<html lang="ja">
 <head>
 <meta charset="UTF-8">
 <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE10" />
 <title>再スタート</title>

<style type="text/css">
 p {
color: #fffafa;
font-size: 1.5em;
 }
 
<!--
 .red {color:#ff0000;}
 .grey {color:#ffffff; background:#999999;}
 .snow {color:#fffafa;}
 .yellow {color:#ff0000; background:#ffff00;}
 .blue {color:#0000ff;}
 .white {color:#ffffff; blinking;}
 .waku {border:2px dotted #99cc66;
　　　　　　line-height: 200%;
　　　　　　padding: 10px;}
 -->
 
 main {
background-color: rgba(255, 255, 255, 0.5);
}

section {
background-color: rgba(0, 225, 0, 0.3);
}
 

/* 点滅 */
.blinking{
	-webkit-animation:blink 1.5s ease-in-out infinite alternate;
    -moz-animation:blink 1.5s ease-in-out infinite alternate;
    animation:blink 1.5s ease-in-out infinite alternate;
}
@-webkit-keyframes blink{
    0% {opacity:0;}
    100% {opacity:1;}
}
@-moz-keyframes blink{
    0% {opacity:0;}
    100% {opacity:1;}
}
@keyframes blink{
    0% {opacity:0;}
    100% {opacity:1;}
}

#wrap {background:none} /*PC用の背景はオフ*/
body::before {
  content:"";
  display:block;
  position:fixed;
  top:0;
  left:0;
  z-index:-1;
  width:100%;
  height:100vh;
  background:url(https://peyng.github.io/Gai_lunch/20200717_001.JPG) center/cover no-repeat; /*fixedをトル！*/
  -webkit-background-size:cover;/*Android4*/
  }
  
a.p:hover {
    position: relative;
    text-decoration: none;
}
a.p span {
    display: none;
    position: relative;
    top: -0.5em;
    left: 2em;
}
a.p:hover span {
    border: none;
    display: block;
    width: 800px;
}   
 

@media	screen and (min-width: 540px),
	screen and (orientation: landscape) {
   p.note { display: none; }
}

</style>

<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">

</head>

<!--
<body onload="alert('長い間、お疲れ様でした！')" onunload="alert('再会の時まで、元気でお過ごしくださいませ〜(^o^)/')">-->
<p class="note">
  モバイル端末をお使いの場合は、画面を横向きにすると
  より見やすくご覧頂けます。
</p>
	
<h1><span class="yellow"><marquee behavior="left">!!! ガイおべんとうのHPへようこそ !!!</marquee></span></h1>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<font color="blue"><h2>料理</h2></font>
<a href="20200717_002.JPG" data-lightbox="abc"><img src="20200717_002.JPG" alt="サンプル画像" width="900" /></a>
<a href="20200717_003.JPG" data-lightbox="abc"><img src="20200717_003.JPG" alt="サンプル画像" width="900" /></a>
<!--
<a href="20190830_009.jpg" data-lightbox="abc"><img src="20190830_009.jpg" alt="サンプル画像" width="300" /></a>
<a href="20190830_010.jpg" data-lightbox="abc"><img src="20190830_010.jpg" alt="サンプル画像" width="300" /></a>
<a href="20190830_006.jpg" data-lightbox="abc"><img src="20190830_006.jpg" alt="サンプル画像" width="600" /></a>-->


<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<section>
<h2>気象庁、高解像度降水ナウキャスト</h2>
 <iframe src="https://www.jma.go.jp/jp/highresorad/" width="900" height="1500" frameborder="0" style="border:0" allowfullscreen></iframe>
       </section>
   <p>&#160;</p>

       <p>&#160;</p>
<main><span class="blue">
<!-- begin wwww.htmlcommentbox.com -->
 <div id="HCB_comment_box"><a href="http://www.htmlcommentbox.com">HTML Comment Box</a> is loading comments...</div>
 <link rel="stylesheet" type="text/css" href="//www.htmlcommentbox.com/static/skins/bootstrap/twitter-bootstrap.css?v=0" />
 <script type="text/javascript" id="hcb"> /*<!--*/ if(!window.hcb_user){hcb_user={};} (function(){var s=document.createElement("script"), l=hcb_user.PAGE || (""+window.location).replace(/'/g,"%27"), h="//www.htmlcommentbox.com";s.setAttribute("type","text/javascript");s.setAttribute("src", h+"/jread?page="+encodeURIComponent(l).replace("+","%2B")+"&opts=16862&num=10&ts=1549107119172");if (typeof s!="undefined") document.getElementsByTagName("head")[0].appendChild(s);})(); /*-->*/ </script>
<!-- end www.htmlcommentbox.com -->
</span></main>
       
       
<p>&#160;</p><p>&#160;</p>

<p>&#160;</p><p>&#160;</p><p>&#160;</p><p>&#160;</p><p>&#160;</p><p>&#160;</p><p>&#160;</p>
       <p>&#160;</p><p>&#160;</p><p>&#160;</p><p>&#160;</p><p>&#160;</p><p>&#160;</p><p>&#160;</p><p>&#160;</p>


<!--      
<p align="right"><marquee direction="left" scrollamount="10" width="80%">背景は佐々木正美 送別会@なかはら、2011/01/14撮影 ~~~ (^^)/</marquee></p>-->


<script src="https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js" type="text/javascript"></script>


<script type='text/javascript' src='https://peyng.github.io/restart/jquery.js?ver=1.12.4'></script>
<script src="https://peyng.github.io/restart/jquery.goup.min.js"></script>
<script src="https://peyng.github.io/restart/my.js"></script> 

<!-- フッタ -->
 <footer>
	<span class="white">Copyright 2020/07/17 peyng</span>
 </footer>

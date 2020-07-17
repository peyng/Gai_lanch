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
<!--
<a href="20190830_001.jpg" data-lightbox="abc"><img src="20190830_001.jpg" alt="サンプル画像" width="900" /></a>
<a href="20190830_002.jpg" data-lightbox="abc"><img src="20190830_002.jpg" alt="サンプル画像" width="900" /></a>
<a href="20190830_003.jpg" data-lightbox="abc"><img src="20190830_003.jpg" alt="サンプル画像" width="900" /></a>
<a href="20190830_004.jpg" data-lightbox="abc"><img src="20190830_004.jpg" alt="サンプル画像" width="900" /></a>
<a href="20190830_005.jpg" data-lightbox="abc"><img src="20190830_005.jpg" alt="サンプル画像" width="900" /></a>
<a href="20190830_011.jpg" data-lightbox="abc"><img src="20190830_011.jpg" alt="サンプル画像" width="900" /></a>
<a href="20190830_012.jpg" data-lightbox="abc"><img src="20190830_012.jpg" alt="サンプル画像" width="900" /></a>
<a href="20190830_013.jpg" data-lightbox="abc"><img src="20190830_013.jpg" alt="サンプル画像" width="900" /></a>
<a href="20190830_014.jpg" data-lightbox="abc"><img src="20190830_014.jpg" alt="サンプル画像" width="900" /></a>
<a href="20190830_015.jpg" data-lightbox="abc"><img src="20190830_015.jpg" alt="サンプル画像" width="900" /></a>
<font color="blue"><h2>動画, youtube リンク↓</h2></font>
<iframe width="840" height="473" src="https://www.youtube.com/embed/BckX9Er7g6Q" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br/>
-->
<font color="blue"><h2>料理</h2></font>
<a href="20200717_002.jpg" data-lightbox="abc"><img src="20200717_002.jpg" alt="サンプル画像" width="300" /></a>
<a href="20200717_003.jpg" data-lightbox="abc"><img src="20200717_003.jpg" alt="サンプル画像" width="300" /></a>
<!--
<a href="20190830_009.jpg" data-lightbox="abc"><img src="20190830_009.jpg" alt="サンプル画像" width="300" /></a>
<a href="20190830_010.jpg" data-lightbox="abc"><img src="20190830_010.jpg" alt="サンプル画像" width="300" /></a>
<a href="20190830_006.jpg" data-lightbox="abc"><img src="20190830_006.jpg" alt="サンプル画像" width="600" /></a>-->
<!--
 <br><br>
<section>
	<font color="red"><h3>・・・開催通知・・・</h3></font>
	 <font color="white">	
From: Yuichi Yoshimura (吉村 祐一) <br>
Sent: Monday, June 17, 2019 12:18 PM<br>
To: Satoshi Takizawa (滝澤 敏) <satoshi_takizawa@n.t.rd.honda.co.jp>; Hirohiko Takaku (高久 裕彦) <hirohiko_takaku@n.t.rd.honda.co.jp>; Kanji Kita (北 貫二) <kanji_kita@n.t.rd.honda.co.jp>; Fumio Tozaki (戸崎 文雄) <fumio_tozaki@n.t.rd.honda.co.jp>; Minoru Higuchi (樋口 実) <minoru_higuchi@n.t.rd.honda.co.jp>; KOJI HIGUCHI (樋口 浩二) <koji_higuchi@hm.honda.co.jp>; Masahiro Sato (佐藤 雅弘) <masahiro_sato@n.t.rd.honda.co.jp>; Yuta Urushiyama (漆山 雄太) <yuta_urushiyama@n.t.rd.honda.co.jp>; Satoshi Hada (羽田 智) <satoshi_hada@n.t.rd.honda.co.jp>; Yoshikazu_Matsumura@honda-tft.co.jp<br>
Cc: Yukihiko Hanzawa (半沢 幸彦) <yukihiko_hanzawa@n.t.rd.honda.co.jp><br>
Subject: 半澤幸彦さん退職祝いのご案内<br><br>

1983年HGT7研配属の皆さんへ<br>
HGT11G開戦BLの吉村です、ご無沙汰しています。<br><br>

さて同期入社メンバーもそろそろ還暦を迎える方もおり、定年延長、退職、それぞれの道を選択していると思います。<br>
11G2BLの半澤幸彦さんにおかれましては、本年9月の誕生月をもって退職する道を選ばれました。<br>
そこでこれまでの活躍を称え、また今後の第二の人生での活躍を祈り、同期メンバーでの壮行会を企画しようと思います。<br>
僭越ではありますが、私が幹事を努めさせていただきます。<br>
ちなみに私は7月末で還暦を迎えますが、1年延長を申告しています。<br><br>

壮行会の日時はちょっと先ですが、8月30日(金)、場所は宇都宮駅近辺を予定しています。<br>
参加いただける方は本メールの投票ボタンをポチっと押していただきたく思います。もちろん返信メールでも結構です。<br><br>

余談ですが、半澤さんは退職にあたり、ファイナンシャルプランナーさんと数多くの相談を実施し、退職後の生活資金について綿密な計画を立案した模様です。<br>
これから退職する我々のために、有益な話をしていただけるものと期待します。金融庁試算の老後生活資金2000万円要についても真偽を語っていただけるものと思います。<br><br>

ちなみに、おいおい待てよ、半澤だけじゃないよ俺も退職だよ、という方がいれば申し出ください。<br>
また、都合により不参加となる方は、返信メールで近況を一報ください。<br>
以上よろしくお願いします。<br><br>

ーーーーーーーーーーーーーーーーーーーーーーーーーーーーー<br>
吉村　祐一<br>
株式会社　本田技術研究所　オートモービルセンター<br>
第11技術開発室　開発戦略ブロック<br>
〒321-3393　栃木県芳賀郡芳賀町下高根沢4630番地<br>
TEL (028)677-3311　内線8764406<br>
携帯 080-4105-3838<br>
E-mail Yuichi_Yoshimura@n.t.rd.honda.co.jp<br>
ーーーーーーーーーーーーーーーーーーーーーーーーーーーーー<br><br>
</font>
</section>
 
 <img src="https://peyng.github.io/restart/キャプチャ.JPG">
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<h1><span class="yellow"><marquee behavior="left">!!! 1983年_HGT_7K配属者、定年退職祝いの記録 !!!</marquee></span></h1>
<p align="right"><marquee direction="right" scrollamount="20" width="30%">(^_^)/~hada</marquee></p>
-->


<section>
<h2>気象庁、高解像度降水ナウキャスト</h2>
 <iframe src="https://www.jma.go.jp/jp/highresorad/" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
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
	<span class="white">Copyright 2019/07/08 S.Hada</span>
 </footer>

<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">

<title>The Business of Carbon Capture and Storage</title>

<link href="https://fonts.googleapis.com/css2?family=Libre+Baskerville:wght@400;700&family=Source+Sans+3:wght@400;600&display=swap" rel="stylesheet">

<style>

/* PAGE */

body{
margin:0;
color:#111;
background:#fff;
}

/* SCROLL PROGRESS */

#progress{
position:fixed;
top:0;
left:0;
height:4px;
background:#0a7;
width:0%;
z-index:9999;
}

/* TOP BAR */

.topbar{
font-family:"Source Sans 3",sans-serif;
font-size:13px;
border-bottom:1px solid #e6e6e6;
padding:14px;
text-align:center;
letter-spacing:.5px;
color:#666;
position:sticky;
top:0;
background:white;
z-index:100;
}

/* HERO */

.hero img{
width:100%;
display:block;
}

/* CAPTION */

.caption{
max-width:720px;
margin:auto;
padding:10px 20px;
font-family:"Source Sans 3";
font-size:12px;
color:#777;
}

/* ARTICLE */

.container{
max-width:720px;
margin:auto;
padding:20px;
}

/* TITLE */

h1{
font-family:"Libre Baskerville",serif;
font-size:46px;
line-height:1.15;
margin-top:25px;
margin-bottom:10px;
}

/* META */

.meta{
font-family:"Source Sans 3";
font-size:14px;
color:#777;
margin-bottom:30px;
}

/* SHARE BUTTONS */

.share{
display:flex;
gap:10px;
margin-bottom:30px;
}

.share button{
border:1px solid #ddd;
background:white;
padding:8px 12px;
cursor:pointer;
font-family:"Source Sans 3";
}

/* ARTICLE BODY */

.article{
font-family:"Libre Baskerville",serif;
font-size:20px;
line-height:1.8;
}

.article p{
margin-bottom:28px;
}

/* DROP CAP */

.article p:first-child:first-letter{
float:left;
font-size:64px;
line-height:48px;
padding-right:8px;
font-weight:bold;
}

/* PULL QUOTE */

.quote{
font-size:30px;
font-style:italic;
margin:50px 0;
border-left:4px solid #ddd;
padding-left:20px;
color:#444;
}

/* FOOTER */

.footer{
margin-top:80px;
border-top:1px solid #eee;
padding:30px;
text-align:center;
font-family:"Source Sans 3";
font-size:13px;
color:#777;
}

/* MOBILE */

@media(max-width:768px){

h1{font-size:34px;}

.article{font-size:18px;}

}

</style>

</head>

<body>

<div id="progress"></div>

<div class="topbar">
The Wall Street Journal | Partner Content
</div>

<div class="hero">

<img src="https://partners.wsj.com/exxonmobil/business-of-carbon-capture-and-storage/wp-content/uploads/sites/828/2022/05/EXXONMOBIL_Article2_Hero_1600x930b.jpg">

</div>

<div class="caption">
Carbon capture technology can reduce industrial emissions while supporting energy demand.
</div>

<div class="container">

<h1>
The Business of Carbon Capture and Storage
</h1>

<div class="meta">
By ExxonMobil | May 2022
</div>

<div class="share">
<button onclick="shareTwitter()">Twitter</button>
<button onclick="shareFacebook()">Facebook</button>
<button onclick="copyLink()">Copy Link</button>
</div>

<div class="article">

<p>
Carbon capture and storage (CCS) is emerging as a powerful tool in the global effort to reduce emissions while supporting economic growth. By capturing carbon dioxide from industrial processes and storing it safely underground, companies can significantly reduce their carbon footprint.
</p>

<p>
Many industries—from energy production to manufacturing—are exploring CCS as a solution that balances environmental responsibility with continued demand for energy and materials.
</p>

<div class="quote">
“Carbon capture could play a major role in helping the world reach net-zero emissions.”
</div>

<p>
Projects around the world are demonstrating how captured carbon can be transported and stored deep underground, preventing it from entering the atmosphere.
</p>

<p>
As technology improves and investment grows, CCS is expected to play a critical role in achieving global climate goals while maintaining reliable energy supplies.
</p>

</div>

</div>

<div class="footer">
Partner Content | © The Wall Street Journal
</div>

<script>

/* SCROLL PROGRESS BAR */

window.onscroll = function(){

let winScroll = document.body.scrollTop || document.documentElement.scrollTop;

let height = document.documentElement.scrollHeight - document.documentElement.clientHeight;

let scrolled = (winScroll / height) * 100;

document.getElementById("progress").style.width = scrolled + "%";

};

/* SHARE BUTTONS */

function shareTwitter(){
window.open("https://twitter.com/intent/tweet?url="+location.href);
}

function shareFacebook(){
window.open("https://www.facebook.com/sharer/sharer.php?u="+location.href);
}

function copyLink(){
navigator.clipboard.writeText(location.href);
alert("Link copied!");
}

</script>

</body>
</html>

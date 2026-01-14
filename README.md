# banglafatafat
banglafatafat
<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<title>বাংলা ফটাফট | আজকের ফটাফট রেজাল্ট</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body{
    font-family:sans-serif;
    background:#f2f2f2;
    margin:0;
}

/* Header & Logo */
.site-header{
    background:linear-gradient(135deg,#c40000,#ff3b3b);
    padding:16px 10px;
    text-align:center;
    color:#fff;
}
.logo{
    font-size:28px;
    font-weight:900;
}
.logo span{
    background:#fff;
    color:#c40000;
    padding:2px 10px;
    border-radius:6px;
    margin-left:6px;
}
.tagline{
    font-size:14px;
    margin-top:6px;
}

/* Date */
#today-date{
    background:#fff;
    text-align:center;
    padding:8px;
    font-weight:bold;
}

/* Result Box */
.result-box{
    background:#fff;
    margin:12px;
    padding:14px;
    border-radius:10px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    box-shadow:0 3px 8px rgba(0,0,0,0.15);
}
.time{
    font-size:16px;
    color:#333;
}
.number{
    background:#c40000;
    color:#fff;
    font-size:26px;
    font-weight:bold;
    padding:8px 16px;
    border-radius:8px;
    min-width:60px;
    text-align:center;
}

/* Links */
.link-box{
    text-align:center;
    margin:15px;
}
.link-box a{
    text-decoration:none;
    color:#c40000;
    font-weight:bold;
}

/* Footer */
footer{
    text-align:center;
    font-size:13px;
    padding:12px;
    color:#555;
}
</style>
</head>

<body>

<header class="site-header">
    <div class="logo">বাংলা <span>ফটাফট</span></div>
    <div class="tagline">আজকের সঠিক ফটাফট রেজাল্ট</div>
</header>

<div id="today-date"></div>

<!-- Result Boxes -->
<div class="result-box">
    <div class="time">১:০০ PM</div>
    <div class="number">45</div>
</div>

<div class="result-box">
    <div class="time">৩:০০ PM</div>
    <div class="number">78</div>
</div>

<div class="result-box">
    <div class="time">৬:০০ PM</div>
    <div class="number">12</div>
</div>

<div class="result-box">
    <div class="time">৮:০০ PM</div>
    <div class="number">90</div>
</div>

<div class="link-box">
    <a href="old-result.html">👉 আগের দিনের ফটাফট রেজাল্ট</a>
</div>

<footer>
⚠️ এটি শুধুমাত্র তথ্যের জন্য। এটি কোনো সরকারি বা অফিসিয়াল ওয়েবসাইট নয়।
</footer>

<script>
const days=["রবিবার","সোমবার","মঙ্গলবার","বুধবার","বৃহস্পতিবার","শুক্রবার","শনিবার"];
const months=["জানুয়ারি","ফেব্রুয়ারি","মার্চ","এপ্রিল","মে","জুন","জুলাই","আগস্ট","সেপ্টেম্বর","অক্টোবর","নভেম্বর","ডিসেম্বর"];
const d=new Date();
document.getElementById("today-date").innerHTML=
"আজ: "+days[d.getDay()]+", "+d.getDate()+" "+months[d.getMonth()]+" "+d.getFullYear();
</script>

</body>
</html>

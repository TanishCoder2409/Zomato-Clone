# Zomato-Clone
This Repository contains the HTML and CSS code i used to develop a basic Zomato Clone
HTML CODE:
<html>
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<link rel="stylesheet" href="zomato.css">
</head>
<body>
<header>
<div id="navbar">
<div id="icon">
<i class="fa-solid fa-mobile"></i>
<a href="https://www.zomato.com/mobile">Get the App</a>
</div>
<a href="https://www.zomato.com/investor-relations">Investor Relations</a>
<a href="https://www.zomato.com/partner-with-us">Add restaurant</a>
<a>Log in</a>
<a>Sign up</a>
<div id="image">
</div>
<div id="belowimage">
<p>Discover the best food & drinks in Delhi NCR</p>
</div>
<div id="border">
<div id="locationicon">
<i class="fa-solid fa-location-dot"></i>
</div>
<div id="input">
<input style="border:none; outline:none; font-size:16px; font-family:verdana,sans-serif;" type="text" placeholder="Ywca, 1, Ashoka Rd, Hanu">
</div>
<div id="arrowdown">
<i class="fa-solid fa-caret-down"></i>
</div>
<div id="line">
<p>|</p>
</div>
<div id="searchicon">
<i class="fa-solid fa-magnifying-glass"></i>
</div>
<div id="aftersearch">
<input  style="border:none; font-size:18px; outline:none; width:150%; font-family:verdana,sans-serif;" type="text" placeholder="Search for restaurant, cuisine or a dish">
</div>
</div>
</header>
<div id="belowheader">
<div id="box1">
<div id="image1">
<img style="border:1px solid black;
border-top-left-radius:10px;
border-top-right-radius:10px;
border:none;" src="food.jpg" height="100%" width="100%">
</div>
<div id="belowimage1">
<p style="font-size:20px; color:363636; font-weight:550;">Order Online</p>
<P style="color:4f4f4f;">Stay home and order to your doorstep</p>
</div>
</div>
<div id="box2">
<div id="image2">
<img style="border:1px solid black;
border-top-left-radius:10px;
border-top-right-radius:10px;
border:none;" src="dining.jpg" height="100%" width="100%">
</div>
<div id="belowimage2">
<p style="font-size:20px; color:363636; font-weight:550;">Dining</p>
<P style="color:4f4f4f;">View the city's favourite dining venues</p>
</div>
</div>
<div id="box3">
<div id="image3">
<img style="border:1px solid black;
border-top-left-radius:10px;
border-top-right-radius:10px;
border:none;" src="cod.jpg" height="100%" width="100%">
</div>
<div id="belowimage3">
<p style="font-size:20px; color:363636; font-weight:550;">Live Events</p>
<P style="color:4f4f4f;">Discover India's best events & concerts</p>
</div>
</div>
</div>
<div id="belowimages">
<div id="twoptags">
<p id="uparvaalap">Collections</p>
<p id="neechevaalap">Explore curated lists of top restaurants, cafes, pubs, and bars in Delhi NCR, based on trends <a style="font-size:16px; margin-left:200px; text-decoration:none;
 color:e03546;" href="https://www.zomato.com/ncr/collections">All collections in Delhi NCR <i class="fa-solid fa-caret-right"></i></a></p>
</div>
<div id="againboxes">
<div id="boxone">
<div id="imageone">
<a href="href="https://www.zomato.com/ncr/trending-this-week"><img style="border:2px solid black;
border-top-left-radius:10px;
border-bottom-left-radius:10px;
border-top-right-radius:10px;
border-bottom-right-radius:10px; border:none;"src="box1image.jpg" alt="boxoneimage" height="100%" width="100%"></a>
</div>
<div id="heading">
<h2>Top Trending Spots <i style="font-size:20px;" class="fa-solid fa-caret-up"></i></h2>
</div>
</div>
<div id="boxtwo">
<div id="imagetwo">
<a href="https://www.zomato.com/ncr/insta-worthy"><img  style="border:2px solid black;
border-top-left-radius:10px;
border-bottom-left-radius:10px;
border-top-right-radius:10px;
border-bottom-right-radius:10px; border:none" src="box2image.jpg" alt="boxoneimage" height="100%" width="100%"></a>
</div>
<div id="heading2">
<h2>Best insta-worthy Places <i style="font-size:20px;" class="fa-solid fa-caret-up"></i></h2>
</div>
</div>
<div id="boxthree">
<div id="imagethree">
<a href="https://www.zomato.com/ncr/newly-opened"><img style="border:2px solid black;
border-top-left-radius:10px;
border-bottom-left-radius:10px;
border-top-right-radius:10px;
border-bottom-right-radius:10px; border:none;" src="box3image.jpg" alt="boxoneimage" height="100%" width="100%"></a>
</div>
<div id="heading3">
<h2>Newly Opened Places <i style="font-size:20px;" class="fa-solid fa-caret-up"></i></h2>
</div>
</div>
</div>
</div>
<div id="ptag">
Popular localities in and around Delhi NCR
</div>
<div id="multiplesboxes">
<a href="https://www.zomato.com/ncr/connaught-place-delhi-restaurants"><div id="insidebox1">
<p>Connaught Place</p>
<div id="belowp">
<P>282 places</p>
<div id="itag">
<i class="fa-solid fa-chevron-right"></i>
</div>
</div>
</div></a>
<a href="https://www.zomato.com/ncr/sector-29-gurgaon-gurugram-restaurants"><div id="insidebox2">
<p>Sector 29</p>
<div id="belowp">
<P>148 places</p>
<div id="itag">
<i class="fa-solid fa-chevron-right"></i>
</div>
</div>
</div></a>
<a href="https://www.zomato.com/ncr/sector-18-noida-restaurants"><div id="insidebox3">
<p>Sector 18, Noida</p>
<div id="belowp">
<P>235 places</p>
<div id="itag">
<i class="fa-solid fa-chevron-right"></i>
</div>
</div>
</div></a>
<a href="https://www.zomato.com/ncr/rajouri-garden-delhi-restaurants"><div id="insidebox4">
<p>Rajouri Garden</p>
<div id="belowp">
<P>394 places</p>
<div id="itag">
<i class="fa-solid fa-chevron-right"></i>
</div>
</div>
</div></a>
<a href="https://www.zomato.com/ncr/saket-delhi-restaurants"><div id="insidebox5">
<p>Saket</p>
<div id="belowp">
<P style="font-size:16px;">356 places</p>
<div id="itag">
<i class="fa-solid fa-chevron-right"></i>
</div>
</div>
</div></a>
<a href="https://www.zomato.com/ncr/dlf-cyber-city-restaurants"><div id="insidebox6">
<p>DLF Cyber City</p>
<div id="belowp">
<P style="font-size:16px;">186 places</p>
<div id="itag">
<i class="fa-solid fa-chevron-right"></i>
</div>
</div>
</div></a>
<a href="https://www.zomato.com/ncr/golf-course-road-restaurants"><div id="insidebox7">
<p>Golf Course Road</p>
<div id="belowp">
<P style="font-size:16px;">163 places</p>
<div id="itag">
<i class="fa-solid fa-chevron-right"></i>
</div>
</div>
</div></a>
<a href="https://www.zomato.com/ncr/dlf-phase-4-restaurants"><div id="insidebox8">
<p>DLF Phase 4</p>
<div id="belowp">
<P style="font-size:16px;">240 places</p>
<div id="itag">
<i class="fa-solid fa-chevron-right"></i>
</div>
</div>
</div></a>
<a href="https://www.zomato.com/ncr/delhi-university-gtb-nagar-delhi-restaurants"><div id="insidebox9">
<p>Delhi University-GTB Nagar</p>
<div id="belowp">
<P style="font-size:16px;">197 places</p>
<div id="itag">
<i class="fa-solid fa-chevron-right"></i>
</div>
</div>
</div></a>
</div>
<div id="belowmultipleboxes">
<div id="image6">
<img src="mobilephone.jpg" alt="mobilephone" height="320px" width="300px">
</div>
<div id="imageksidemtext">
<p style="color:1c1c1c; font-size:44px; font-family:verdana,sans-serif; margin-top:50px; font-weight:600; width:500px;">Get the Zomato app</p>
</div>
<div id="headingkneeche">
<p style="font-size:16px; font-family:verdana,sans-serif; position:relative; top:200; right:490; width:500px;">We will send you a link, open it on your phone to download the app</p>
</div>
<div id="inputbox">
<input style="border:none; font-family:verdana,sans-serif; outline:none; font-size:16px; border:2px solid;
border-color:e1d9d1;
border-top-left-radius:5px;
border-bottom-left-radius:5px;
border-top-right-radius:5px;
border-bottom-right-radius:5px; height:50px; width:292px; position:relative; bottom:25;" type="text" placeholder="Phone Number">
<button>Share App Link</button>
<p style="font-size:14px;
color:9c9c9c;
height:21px;
width:450px; font-family:verdana,sans-serif; position:relative; bottom:30;">Download app from</p>
<a href="https://play.google.com/store/apps/details?id=com.application.zomato&hl=en_IN" target="_main"><img style="position:relative; bottom:40;" src="googleplay.jpg" alt="playstore" height="40px" width="137px"></a>
<a href="https://apps.apple.com/in/app/zomato-food-delivery-dining/id434613896" target="_main"><img style="margin-left:20px; margin-bottom:20px; position:relative; bottom:20;" src="ios.jpg" alt="Applestore" height="40px" width="137px"></a>
</div>
</div>
<footer>
<div id="belowdownload">
<div id="img">
<img src="zomatoblack.jpg" width="132px" height="28px">
</div>
<div id="indialogo">
<img src="india.jpg" height="15px" width="22px">
<p>India</p>
</div>
<div id="englishlogo">
<i style="height:18px; width:18px;" class="fa-solid fa-globe"></i>
<p>English</p>
</div>
<div id="lists">
<p style="font-size:14px; font-family:verdana,sans-serif; font-weight:600; margin-left:200px;">ABOUT ZOMATO</p>
<ul>
<li>Who We Are</li>
<li>Blog</li>
<li>Work With Us</li>
<li>Investor Relations</li>
<li>Report Fraud</li>
<li>Press Kit</li>
<li>Contact Us</li>
</ul>
</div>
<div id="lists2">
<p style="font-size:14px; font-family:verdana,sans-serif; font-weight:600; margin-left:200px; color:000000;">ZOMAVERSE</p>
<ul>
<li>Zomato</li>
<li>Blinkit</li>
<li>Feeding India</li>
<li>Hyperpure</li>
<li>Zomato Live</li>
<li>Zomaland</li>
<li>Weather Union</li>
</ul>
</div>
<div id="lists3">
<p style="font-size:14px; font-family:verdana,sans-serif; font-weight:600; margin-left:200px; color:000000;">FOR RESTAURANTS</p>
<ul>
<li>Partner with us</li>
<li>Apps for you</li>
</ul>
</div>
<div id="lists4">
<p style="font-size:14px; font-family:verdana,sans-serif; font-weight:600; margin-left:100px; color:000000;">LEARN MORE</p>
<ul>
<li>Privacy</li>
<li>Security</li>
<li>Terms</li>
<li>Sitemap</li>
</ul>
</div>
<p style="font-size:14px; font-family:verdana,sans-serif; font-weight:600; margin-left:200px; position:relative; right:20; bottom:15; color:000000;">SOCIAL LINKS</p>
<div id="fiveicons">
<i style="height:25px;
width:25px;
border:1px solid black;
border-radius:50%; color:white; background-color:black; display:flex; justify-content:center; align-items:center; margin-left:5px;" class="fa-brands fa-linkedin-in"></i>
<i style="height:25px;
width:25px;
border:1px solid black;
border-radius:50%; color:white; background-color:black; display:flex; justify-content:center; align-items:center; margin-left:5px;" class="fa-brands fa-instagram"></i>
<i style="height:25px;
width:25px;
border:1px solid black;
border-radius:50%; color:white; background-color:black; display:flex; justify-content:center; align-items:center; margin-left:5px;"class="fa-brands fa-twitter"></i>
<i style="height:25px;
width:25px;
border:1px solid black;
border-radius:50%; color:white; background-color:black; display:flex; justify-content:center; align-items:center; margin-left:5px;"class="fa-brands fa-youtube"></i>
<i style="height:25px;
width:25px;
border:1px solid black;
border-radius:50%; color:white; background-color:black; display:flex; justify-content:center; align-items:center; margin-left:5px;"class="fa-brands fa-facebook"></i>
<a href="https://play.google.com/store/apps/details?id=com.application.zomato&hl=en_IN" target="_main"><img style="position:relative; bottom:40; position:relative; top:50; right:148;" src="googleplay.jpg" alt="playstore" height="40px" width="137px"></a>
<a href="https://apps.apple.com/in/app/zomato-food-delivery-dining/id434613896" target="_main"><img style="margin-left:20px; margin-bottom:20px; position:relative; bottom:20; position:relative; top:100; right:305;" src="ios.jpg" alt="Applestore" height="40px" width="137px"></a>
</div>
<div id="belowline">
</div>
<div id="lastptag">
<p>By continuing past this page, you agree to our Terms of Service, Cookie Policy, Privacy Policy and Content Policies. All trademarks are properties of their respective owners. 2008-2024 © Zomato™ Ltd. All rights reserved.</p>
</div>
</div>
</footer>
</body>
</html>
<br>
CSS CODE:
*{
margin:0;
border:border-box;
}
#icon{
margin-top:20px;
color:white;
font-size:14px;
width:50%;
font-weight:600;
font-family:verdana,sans-serif;
}
#icon a{
color:white;
text-decoration:none;
}
#navbar{
height:472.56px;
width:100%;
background-image:url("zomatologo.jpg");
background-size:cover;
color:white;
font-family:helvetica;
display:flex;
justify-content:space-evenly;
align-items:flex-start;
flex-wrap:wrap;
}
#navbar a{
color:white;
text-decoration:none;
font-family:verdana,sans-serif;
font-weight:300;
margin-top:20px;
font-size:18px;
}
#image{
margin-top:130px;
position:absolute;
height:70px;
width:330px;
background-image:url("transparentlogo.jpg");
background-size:cover;
}
#belowimage{
display:flex;
align-items:center;
justify-content:center;
height:50px;
width:766px;
}
#belowimage p{
font-family:verdana,sans-serif;
margin-bottom:35px;
font-size:34px;
margin-top:200px;
}
#border{
display:flex;
height:55px;
width:776.2px;
align-items:center;
border:1px solid white;
background-color:white;
border-top-left-radius:8px;
border-bottom-left-radius:8px;
border-top-right-radius:8px;
border-bottom-right-radius:8px;
}
#locationicon{
color:rgb(255,0,0,0.5);
margin-left:15px;
}
#input{
margin-left:5px;	
}
#arrowdown{
height:12px;
width:12px;
color:black;
margin-bottom:5px;
margin-left:5px;
}
#line{
color:black;
margin-bottom:23px;
margin-left:10px;
margin-top:20px;
color:grey;
}
#searchicon{
color:grey;
margin-left:15px;
}
#aftersearch{
margin-left:10px;
}
#belowheader{
height:300px;
display:flex;
justify-content:center;
}
#box1{
height:250px;
width:354px;
border:2px solid;
border-color:f5f5f5;
border-top-left-radius:10px;
border-bottom-left-radius:10px;
border-top-right-radius:10px;
border-bottom-right-radius:10px;
margin-top:30px;
margin-left:50px;
transition-property:all;
transition-duration:0.25s;
}
#image1{
height:160px;
}
#box1:hover{
transform:scale(1.07);
}
#box2{
height:250px;
width:354px;
border:2px solid;
border-color:f5f5f5;
border-top-left-radius:10px;
border-bottom-left-radius:10px;
border-top-right-radius:10px;
border-bottom-right-radius:10px;
margin-top:30px;
margin-left:50px;
transition-property:all;
transition-duration:0.25s;
}
#box2:hover{
transform:scale(1.07);
}
#image2{
height:160px;
}
#box3{
height:250px;
width:354px;
border:2px solid;
border-color:f5f5f5;
border-top-left-radius:10px;
border-bottom-left-radius:10px;
border-top-right-radius:10px;
border-bottom-right-radius:10px;
margin-top:30px;
margin-left:50px;
transition-property:all;
transition-duration:0.25s;
}
#box3:hover{
transform:scale(1.07);
}
#image3{
height:160px;
}
#belowimage1 p{
font-family:verdana,sans-serif;
margin-top:10px;
margin-left:20px;
}
#belowimage2 p{
font-family:verdana,sans-serif;
margin-top:10px;
margin-left:20px;
}
#belowimage3 p{
font-family:verdana,sans-serif;
margin-top:10px;
margin-left:20px;
}
#belowimages{
height:600px;
}
#uparvaalap{
margin-top:70px;
color:1c1c1c;
font-size:36px;
font-family:verdana,sans-serif;
}
#neechevaalap{
margin-top:10px;
font-size:18px;
font-family:verdana,sans-serif;
color:363636;
}
#belowimages p{
margin-left:200px;
}
#againboxes{
display:flex;
}
#boxone,#boxtwo,#boxthree{
position:relative;
left:180;
top:30;
margin-left:20px;
}
#boxone{
height:320px;
width:275px;
}
#boxtwo{
height:320px;
width:275px;
}
#boxthree{
height:320px;
width:275px;
}
#heading{
margin-top:20px;
text-align:center;
}
#heading2{
margin-top:20px;
text-align:center;
}
#heading3{
margin-top:20px;
text-align:center;
}
#heading,#heading2,#heading3{
font-family:verdana,sans-serif;
font-size:12px;
color:e03546;
}
#multiplesboxes{
height:450px;
}
#ptag{
margin-left:200px;
color:363636;
font-size:36px;
font-family:verdana,sans-serif;
}
#insidebox1{
margin-left:210px;
margin-top:50px;
height:79px;
width:350px;
border:2px solid;
border-color:e1d9d1;
border-top-left-radius:10px;
border-bottom-left-radius:10px;
border-top-right-radius:10px;
border-bottom-right-radius:10px;
}
#multiplesboxes a{
color:1c1c1c;
text-decoration:none;
}
#insidebox1 p{
margin-left:20px;
font-size:20px;
font-family:verdana,sans-serif;
margin-top:10px;
}
#belowp p{
font-size:16px;
font-family:verdana,sans-serif;
color:454545;
}
#itag{
margin-left:320px;
position:relative;
bottom:30;
}
#insidebox2{
margin-left:210px;
margin-top:50px;
height:79px;
width:350px;
border:2px solid;
border-color:e1d9d1;
border-top-left-radius:10px;
border-bottom-left-radius:10px;
border-top-right-radius:10px;
border-bottom-right-radius:10px;
}
#insidebox2 p{
margin-left:20px;
font-size:20px;
font-family:verdana,sans-serif;
margin-top:10px;
}
#belowp p{
font-size:16px;
font-family:verdana,sans-serif;
color:454545;
}
#multiplesboxes{
display:flex;
flex-wrap:wrap;
}
#insidebox3{
margin-left:210px;
margin-top:50px;
height:79px;
width:350px;
border:2px solid;
border-color:e1d9d1;
border-top-left-radius:10px;
border-bottom-left-radius:10px;
border-top-right-radius:10px;
border-bottom-right-radius:10px;
}
#insidebox3 p{
margin-left:20px;
font-size:20px;
font-family:verdana,sans-serif;
margin-top:10px;
}
#belowp p{
font-size:16px;
font-family:verdana,sans-serif;
color:454545;
}
#insidebox1,#insidebox2,#insidebox3{
position:relative;
margin-left:20px;
left:180;
}
#insidebox4{
position:relative;
bottom:70;
right:10;
margin-left:210px;
margin-top:50px;
height:79px;
width:350px;
border:2px solid;
border-color:e1d9d1;
border-top-left-radius:10px;
border-bottom-left-radius:10px;
border-top-right-radius:10px;
border-bottom-right-radius:10px;
}
#insidebox4 p{
margin-left:20px;
font-size:20px;
font-family:verdana,sans-serif;
margin-top:10px;
}
#belowp p{
font-size:16px;
font-family:verdana,sans-serif;
color:454545;
}
#insidebox5{
position:relative;
bottom:70;
right:200;
margin-left:210px;
margin-top:50px;
height:79px;
width:350px;
border:2px solid;
border-color:e1d9d1;
border-top-left-radius:10px;
border-bottom-left-radius:10px;
border-top-right-radius:10px;
border-bottom-right-radius:10px;
}
#insidebox5 p{
margin-left:20px;
font-size:20px;
font-family:verdana,sans-serif;
margin-top:10px;
}
#belowp{
font-size:16px;
font-family:verdana,sans-serif;
color:454545;
}
#insidebox6{
position:relative;
right:180;
bottom:20;
height:79px;
width:350px;
border:2px solid;
border-color:e1d9d1;
border-top-left-radius:10px;
border-bottom-left-radius:10px;
border-top-right-radius:10px;
border-bottom-right-radius:10px;
}
#insidebox6 p{
margin-left:20px;
font-size:20px;
font-family:verdana,sans-serif;
margin-top:10px;
}
#belowp{
font-size:16px;
font-family:verdana,sans-serif;
color:454545;
}
#insidebox7{
position:relative;
bottom:90;
left:200;
height:79px;
width:350px;
border:2px solid;
border-color:e1d9d1;
border-top-left-radius:10px;
border-bottom-left-radius:10px;
border-top-right-radius:10px;
border-bottom-right-radius:10px;
}
#insidebox7 p{
margin-left:20px;
font-size:20px;
font-family:verdana,sans-serif;
margin-top:10px;
}
#belowp{
font-size:16px;
font-family:verdana,sans-serif;
color:454545;
}
#insidebox8{
position:relative;
bottom:90;
left:220;
height:79px;
width:350px;
border:2px solid;
border-color:e1d9d1;
border-top-left-radius:10px;
border-bottom-left-radius:10px;
border-top-right-radius:10px;
border-bottom-right-radius:10px;
}
#insidebox8 p{
margin-left:20px;
font-size:20px;
font-family:verdana,sans-serif;
margin-top:10px;
}
#belowp{
font-size:16px;
font-family:verdana,sans-serif;
color:454545;
}
#insidebox9{
position:relative;
bottom:90;
left:240;
height:79px;
width:350px;
border:2px solid;
border-color:e1d9d1;
border-top-left-radius:10px;
border-bottom-left-radius:10px;
border-top-right-radius:10px;
border-bottom-right-radius:10px;
}
#insidebox9 p{
margin-left:20px;
font-size:20px;
font-family:verdana,sans-serif;
margin-top:10px;
}
#belowp{
font-size:16px;
font-family:verdana,sans-serif;
color:454545;
}
#belowmultipleboxes{
display:flex;
justify-content:flex-start;
height:480px;
background-color:fffbf7;
}
#image6{
margin-top:100px;
margin-left:300px;
position:relative;
bottom:10;
}
#inputbox{
position:relative;
top:300;
right:990;
}
button{
position:relative;
bottom:25;
height:50px;
width:150px;
background-color:ef4f5f;
color:white;
margin-bottom:40px;
font-size:16px;
font-family:verdana,sans-serif;
border:2px solid;
border-top-left-radius:5px;
border-bottom-left-radius:5px;
border-top-right-radius:5px;
border-bottom-right-radius:5px;
}
#belowdownload{
background-color:f8f8f8;
height:480px;
display:flex;
flex-wrap:wrap;
justify-content:flex-start;
}
#indialogo{
display:flex;
justify-content:center;
align-items:center;
border:2px solid;
height:38px;
width:110px;
border-color:e1d9d1;
border-top-left-radius:5px;
border-bottom-left-radius:5px;
border-top-right-radius:5px;
border-bottom-right-radius:5px;
}
#indialogo p{
font-family:verdana,sans-serif;
font-size:18px;
color:1c1c1c;
}
#englishlogo{
display:flex;
justify-content:center;
align-items:center;
border:2px solid;
height:38px;
width:110px;
border-color:e1d9d1;
border-top-left-radius:5px;
border-bottom-left-radius:5px;
border-top-right-radius:5px;
border-bottom-right-radius:5px;
}
#englishlogo p{
font-family:verdana,sans-serif;
font-size:18px;
color:1c1c1c;
}
#img{
width:65%;
}
#englishlogo{
margin-left:25px;
}
#img,#indialogo,#englishlogo{
margin-top:50px;
}
#img{
margin-left:200px;
display:flex;
}
#lists li{
list-style-type:none;
margin-top:10px;
font-size:16px;
color:696969;
margin-left:160px;
}
#lists2 li{
list-style-type:none;
margin-top:10px;
font-size:16px;
color:696969;
margin-left:160px;
}
#lists3 li{
list-style-type:none;
margin-top:10px;
font-size:16px;
color:696969;
margin-left:160px;
}
#lists4 li{
list-style-type:none;
margin-top:10px;
font-size:16px;
color:696969;
margin-left:60px;
}
#fiveicons{
display:flex;
position:relative;
left:1350;
bottom:230;
}
#belowline{
height:0.1px;
width:1300px;
border:1px solid;
border-color:696969;
margin-left:200px;
}
#lastptag{
color:4f4f4f;
font-family:verdana,sans-serif;
font-size:13px;
margin-left:200px;
}


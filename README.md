<!-- it's just html code -->

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <script src="https://kit.fontawesome.com/d7d52fc678.js" crossorigin="anonymous"></script>
  <title>personal</title>
<!-- this is css option -->
  <script>
    body{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif
}
header{
  width: 100%;
  height: 90px;
  position: fixed;
  top: 0;
  background-color: white;
}
header div{
  float: left;
  justify-content: space-between;
  align-items: center;
}
header .logo{
 margin-left: 200px;
 padding: 10px;
 padding-top: 26px;
}
header .nav{
  top: 0;
  right: 0;
  position: absolute;
  margin-right: 200px;
}
header .nav ul{
  list-style: none;
}
header .nav ul li{
  float: left;
  padding: 30px;
}
header .nav ul li a{
  text-decoration: none;
  color: black;
  text-transform: uppercase;
  font-size: 15px;
  font-weight: bold;
}
header .nav ul li a :hover{
  color: blue;
}

/*sECTION oNE sTART*/
section{
  background-color: whitesmoke;
  width: 100%;
  height: 1050px;
  margin: 75px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
section .half1{
  width: 50%;
}
section .half2{
  width: 50%;
}
.half1{
  margin-left: 210px;
  margin-bottom: 150px;
}
.half2{
  padding-right: 100px;
}
half2 img{
  width: 100%;
  height: 50px;
  padding-top: 200px;
}
.half1 h3{
  font-weight: normal;
  color: gray;
}
.half1 h1{
  font-size: 70px;
}
.half1 p{
  color: slategray;
  font-size: 20px;
}
.half1 input{
  padding: 20px 40px;
  background-color: deepskyblue;
  outline: none;
  color: white;
  border: 1px solid;
  font-size: 20px;
}
.half1 input:hover{
  box-shadow: 5px 10px 30px rgba(130, 147, 255, 0.5);
  transition: all 0.5s ease-in 0.1;
  outline: none;
}
/*sECTION oNE eND*/

/*sECTION tWo sTART*/

.section2{
  width: 100%;
  height: 650px;
  margin: 75px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 30px;
}
.section div{
  width: 40%;
  justify-content: space-between;
  align-items: center;
}
.section2 div h3{
  font-weight: normal;
  color: slategrey;
}
.section2 div h1{
  font-size: 50px;
}
.section2 div p{
  color: gray;
  font-size: 20px;
}
.half3 img{
  padding-left: 175px;
}
.half4{
  padding-right: 175px;
}
.half4 input{
  padding: 20px 40px;
  background-color: deepskyblue;
  outline: none;
  color: white;
  border: 1px solid;
  font-size: 20px;
}
.half4 input:hover{
 box-shadow: 5px 10px 30px rgba(130, 147, 255, 0.5);
 transition: all 0.5s ease-in 0.1;
 outline: none;
}
/*sECTION tWO eND*/

/*sECTION tHREE sTART*/
.section3{
  width: 98%;
  height: 900px;
  margin: 0 auto;
  padding: 0 auto;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  padding: 20px;
  margin-left: 75px;
  text-align: center;
}
.services{
  width: 100%;
  margin: 0 auto;
  padding-top: 20px;
}
.half5{
  justify-content: center;
}
.half5 h1{
  font-size: 70px;
  margin-left: 500px;
  line-height: 5px;
}
.half5 p{
  font-size: 20px;
  color: dimgrey;
  margin-left: 525px;
  width: 600px;
}
.ser1, .ser2{
  width: 100%;
  overflow: hidden;
}
.half6 div{
  width: 25%;
  height: 150px;
  float: left;
  margin: 20px;
  justify-content: center;
  align-items: center;
}
.services h1{
  font-size: 35px;
  color: gray;
}
.services p{
  color: grey;
  font-size: 20px;
}
.half6 div:hover{
  background-color: deepskyblue;
}
.half6 div:hover h1{
  color: black;
}
.half6 div:hover p{
  color: white;
}
.half6{
  padding-left: 210px;
}

/*section three end*/

/*section four start*/
.section4{
  width: 100%;
  height: 300px;
  background-color: deepskyblue;
}
.section4 div{
  width: 15%;
  text-align: center;
  position: relative;
  justify-content: space-around;
  gap: 20px;
  padding: 10 0;
  margin: 0 auto;
}
.section4 div h1{
  font-size: 50px;
  color: white;
  line-height: 5px;
}
.section4 div p{
  font-size: 20px;
  color: white;
}
.section4 div:hover h1{
  color: black;
}
.section4 div:hover p{
  color: blue;
}
/*section four emd*/

/*protfolio section start*/
.section5{
  width: 100%;
  height: 1100px;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  text-align: center;
}
.text2{
  margin: 0 auto;
  padding-top: 25px;
}
.text2 h1{
  font-size: 70px;
  color: grey;
  line-height: 0;
}
.text2 p{
  font-size: 24px;
  color: dimgrey;
}

.section5 .imgg1{
  width: 75%;
  height: auto;
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  margin: 0 auto;
}
 .section5 .imgg1 div{
   width: 340px;
   height: 339px;
   padding-bottom: 90px;
   text-align: center;
 }
 .section5 .imgg1 h1{
   font-size: 25px;
   color: dimgray;
 }
 .section .imgg1 p{
   color: grey;
 }
 .section5 figure{
   background: linear-gradient(40deg, #8490ff 40%, #62bdfc 100%);
   width: 340px;
   height: 339px;
   margin: 0;
   padding: 0;
   overflow: hidden;
   border-radius: 3%;
 }
 .section5 figure:hover img{
   opacity: 0.3;
   transition: all .4s ease-in-out;
 }
/*protfolio section end*/

/*pricing section start*/
.section6{
  width: 100%;
  height: 900px;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start
}
.section6 .text3{
  text-align: center;
  padding: 2% 0;
 justify-content: flex-start;
 align-items: flex-start;
 padding-left: 550px;
}
.section6 .text3 h1{
font-size: 60px;
line-height: 0px;
padding-top: 15px;
}
.section6 .text3 p{
  color: grey;
}
.section6 .card{
  width: 75%;
  height: auto;
  display: flex;
  justify-content: space-around;
  margin: 0 auto;
  text-align: center;
}
.section6 .card .card1 h1{
  font-size: 60px;
  color: grey;
}
.section6 .card .card1 h2{
  font-size: 30px;
  color: dimgray;
}
.section6 .card .card1 p{
  font-size: 14px;
  color: grey;
}
.section6 .card .card1 input{
  padding: 20px 40px;
  background-color: deepskyblue;
  outline: none;
  border: 1px solid;
  color: white;
  font-size: 20px;
  border-radius: 10%;
}
.section6 .card .card1 input:hover{
  box-shadow: 5px 10px 30px rgba(130, 147, 255, 0.5);
  transition: all 0.5s ease-in 0.1;
  outline: none;
}
.section6 .card1:hover{
  background-color: navajowhite;
  color: white;
  transition: all 0.25s ease-in;
  border: 1px solid;
  box-shadow: 0 8px 12px 0;
}
/*pricing section end*/

/*footer start*/
footer{
  background-color: dimgray;
  width: 100%;
  height: 400px;
  position: absolute;
  color: white;
  padding-left: 100px;
  padding-right: 100px;
  padding-top: 100px;
}
footer .foot{
  width: 90%;
  height: auto;
  display: flex;
  justify-content: space-around;
  margin: 0 auto;
  margin-top: 120px;
}
footer .foot .foot1 input{
  font-size: 16px;
  outline: none;
  border: none;
  padding: 10px 150px 10px 10px;
}
footer .foot .foot1 button{
  font-size: 18px;
  color: white;
  background-color: #8293ff;
  outline: none;
  border: none;
  cursor: pointer;
  padding: 12px 30px;
}
footer .foot .foot1 button:hover{
 box-shadow: 5px 10px 30px rgba(130, 147, 255, 0.5);
 transition: all 0.5s ease-in 0.1;
 outline: none;
}
/*footer end*/
  </script>
</head>
<body>
  <!-- Header Start-->
  <header>
    <div class="logo">
      <img src="logo.png" alt="personal">
    </div>
    <div class="nav">
      <ul>
        <li><a href="home.html" style="color: blue">Home</a></li>
        <li><a href="contect.html">Contect</a></li>
        <li><a href="#">Portfolio</a></li>
        <li><a href="#">Srevices</a></li>
        <li><a href="#">About</a></li>
      </ul>
    </div>
  </header>
  <!--Header End -->
  
  
  <!-- Section Start -->
  <section class="section1">
    <div class="half1">
      <h3>This is me</h3>
      <h1>ZIAUDDIN SHAHIN</h1>
      <p> "WORKERS BUILD THE FOUNDATION OF OUR WORLD WITH THEIR SWEAT AND DEDICATION."<br><br>
"THE STRENGTH OF A NATION LIES IN THE HANDS OF ITS WORKERS."</p>
      <input type="button" value="DISCOVER NOW">
    </div>
    <div class="half2">
      <img src="baba.png" alt="man">
    </div>
  </section>
  <!-- Section one is end -->
  
  
  
  <!-- Section two start -->
  <section class="section2">
    <div class="half3">
      <img src="baba2.png" alt="personal2" id="baba2">
    </div>
    <div class="half4">
      <h3>ABOUT ME</h3>
      <h1>PERSONAL DETAILS</h1>
      <p>MY NAME IS ZIAUDDIN SHSHIN. I AM 52 YEARS OLD. I KIVE IN BANGLADESH.<br> MY EDUCATIONAL AND OCCUPETIONAL INFORMETION IS, A AM PASS A "BA" AND <br> AT THE -RESERN TIME I AM A CAR DRIVER <br>
      MY PERSONAL INFORMETION IS......</p>
      <input type="button" value="VIEW ALL DETAILS">
    </div>
  </section>
  <!-- Section two is end -->
  
  <!-- Section three start -->
  <section class="section3">
    <div class="half5">
      <h1>MY OFFERED SERVICES</h1>
      <p>OFFERING PERSONALIZED PROGRAMMING TUTORIALS AND RESOURCES, I HELP LEARNERS OF ALL LEVELS MASTER</p>
    </div>
    <div class="services">
      <div class="half6">
        <div>
          <i class="fa-solid fa-code"></i>
          <h1>PROGRAMMING</h1>
          <p>PROFITIONAL PROGRAMMER. EXPART IN WEB DEVELOPMENT, DESIGN FONTEND AND BACKEND.</p>
        </div>
        <div>
          <i class="fa-solid fa-blog"></i>
          <h1>WRITING</h1>
          <p>PROFITIONAL WRITER, EXPART IN WRITING, RETYPING, BLOOGING, ETC</p>
        </div>
        <div>
          <i class="fa-solid fa-hashtag"></i>
          <h1>SEO</h1>
          <p>PROFITIONAL SEO EXPART. EXPART IN KEYWORD RESOURCES, TAGING,</p>
        </div>
        <div>
          <i class="fa-solid fa-envelope-open-text"></i>
         <h1>MARKETING</h1>
         <p>PROFITIONAL MARKETER. AFFILITE MARKETING, FACEBOOK MARKETING.</p>
        </div>
        <div>
          <i class="fa-solid fa-video"></i>
         <h1>CONTENT CREATOR</h1>
         <p>PROFITIONAL CONTENT CREATEOR. EXPART IN YOUTUBING FACEBOOK CONTENT CREATOR.</p>
        </div>
        <div>
          <i class="fa-solid fa-image"></i>
         <h1>PHOTOGRAPHY</h1>
         <p>PROFITIONAL PHOTOGRAPHER. EXPART IN PHOTO EDIT, STYLISH PHOTO PICKER.</p>
        </div>
      </div>
    </div>
  </section>
  <!-- Section three end -->
  <!-- section four start -->
 <section class="section4">
  <div>
    <h1>1000</h1>
    <p><strong>PROJECT COMPLEITED</strong></p>
  </div>
  <div>
    <h1>3000</h1>
    <p><strong>HAPPY CLIENTS</strong></p>
  </div>
  <div>
    <h1>4000</h1>
    <p><strong>CUP'S OF COFFEE</strong></p>
  </div>
  <div>
    <h1>44.55%</h1>
    <p><strong>RATEING</strong></p>
  </div>
 </section>  
  <!-- section four end -->
  <!-- protfolio section start -->
  <section class="section5">
    <div class="text2">
      <h1>OUR LATEST FEATURED SREVICES</h1>
      <p><strong>WHO ARE IN EXTERNELY LOVE WITH ECO FRIENDLY SESTYM</strong></p>
    </div>
    <div class="imgg1">
      <div>
        <figure>
          <img src="p1.jpg">
        </figure>
        <h1><strong>2D VINYL DESIGN</strong></h1>
        <p><strong>VECTOR</strong></p>
      </div>
      <div>
         <figure>
          <img src="p2.jpg">
         </figure>
         <h1><strong>2D VINYL DESIGN</strong></h1>
         <p><strong>VECTOR</strong></p>
      </div>
      <div>
         <figure>
          <img src="p3.jpg">
         </figure>
         <h1><strong>2D VINYL DESIGN</strong></h1>
         <p><strong>VECTOR</strong></p>
      </div>
      <div>
         <figure>
          <img src="p4.jpg">
         </figure>
         <h1><strong>2D VINYL DESIGN</strong></h1>
         <p><strong>VECTOR</strong></p>
      </div>
      <div>
         <figure>
          <img src="p5.jpg">
         </figure>
         <h1><strong>2D VINYL DESIGN</strong></h1>
        <p><strong>VECTOR</strong></p>
      </div>
      <div>
         <figure>
          <img src="p6.jpg">
        </figure>
        <h1><strong>2D VINYL DESIGN</strong></h1>
        <p><strong>VECTOR</strong></p>
      </div>
    </div>
  </section>
  
  <!-- protfolio section end -->
  <!-- pricing section start -->
  <section class="section6">
    <div class="text3">
      <h1><strong>CHOOSE YOUR PLAN</strong></h1>
      <p><strong>WHEN SOMEONE DOSE SOMETHING THAT THEY KNOW THAT THEY SHOULDN'T DO DID THEY</strong></p>
    </div>
  <div class="card">
    <div class="card1">
      <h1>01</h1>
      <h2>ECONOMY</h2>
      <p>FRO THE INDIVIBUALE</p>
      <hr>
      <p>SECURE ONLINE TRANSFER</p>
      <hr>
      <p>UNLIMITED STYLE 9F INTERFACE</p>
      <hr>
      <p>RELIABLE COSTUMER SREVICES</p>
      <hr>
      <h1>104.00$</h1>
      <input type="button" value="BYE NOW">
    </div>
    <div class="card1">
      <h1>02</h1>
      <h2>BUSINESS</h2>
      <p>FRO THE INDIVIBUALE</p>
      <hr>
      <p>SECURE ONLINE TRANSFER</p>
      <hr>
      <p>UNLIMITED STYLE 9F INTERFACE</p>
      <hr>
      <p>RELIABLE COSTUMER SREVICES</p>
      <hr>
      <h1>104.00$</h1>
      <input type="button" value="BYE NOW">
    </div>
    <div class="card1">
      <h1>03</h1>
      <h2>PREMIUM</h2>
      <p>FRO THE INDIVIBUALE</p>
      <hr>
      <p>SECURE ONLINE TRANSFER</p>
      <hr>
      <p>UNLIMITED STYLE 9F INTERFACE</p>
      <hr>
      <p>RELIABLE COSTUMER SREVICES</p>
      <hr>
      <h1>104.00$</h1>
      <input type="button" value="BYE NOW">
    </div>
    <div class="card1">
      <h1>04</h1>
      <h2>EXCLUSIVE</h2>
      <p>FRO THE INDIVIBUALE</p>
      <hr>
      <p>SECURE ONLINE TRANSFER</p>
      <hr>
      <p>UNLIMITED STYLE 9F INTERFACE</p>
      <hr>
      <p>RELIABLE COSTUMER SREVICES</p>
      <hr>
      <h1>104.00$</h1>
      <input type="button" value="BYE NOW">
    </div>
  </div>  
  </section>
  
  
  <!-- pricing section end -->
  
  <!-- footer start -->
  <footer>
    <dev class="foot">
      <div class="foot1">
        <h1>About Me</h1>
        <p>We have tested a number of registry fix and clean utilities and present our <br> top 3 list on our site for your convenience.</p>
        <p>Copyright ©2024 All rights reserved | This template is made with  by Colorlib</p>
      </div>
      <div class="foot1">
        <h1>Newsletter</h1>
        <p>Stay updated with our latest trends</p>
        <input type="text" placeholder="Enter Email Address"
        <button>SEND</button>
      </div>
      <div class="foot1">
        <h1>Follow Me</h1>
        <p>Let us be social</p>
        <i class="fa-brands fa-square-facebook"></i>
        <i class="fa-brands fa-square-x-twitter"></i>
        <i class="fa-brands fa-square-instagram"></i>
        <i class="fa-brands fa-square-youtube"></i>
      </div>
    </dev>
  </footer>
  
  <!-- footer end -->
  
</body>
</html>

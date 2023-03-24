# Starbucks-Website
Starbucks Coffee Company Clone Website 

HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, intial-scale=1.0">
  <title>Starbucks Coffee Company</title>
  <link rel="stylesheet" href="style.css"/>
  <link rel="shortcut icon" href="images/logo.svg" type="image/svg">
</head>
<body>
    
    <!--navigation start-->
    
    <nav>
        <div class="container">
            <div class="nav-left">
                <div class="logo">
                    <a class="logo" href="https://www.starbucks.com/">
                    <img src="images/logo.svg" alt="logo" width="51px" height="51px">
                    </a>
                </div>
                <ul>
                    <li>
                        <a href="https://www.starbucks.com/menu"><strong>MENU</strong></a>
                    </li>
                    <li>
                        <a href="https://www.starbucks.com/rewards"><strong>REWARDS</strong></a>
                    </li>
                    <li>
                        <a href="https://www.starbucks.com/gift"><strong>GIFT CARDS</strong></a>
                    </li>
                </ul>
            </div>
            <div class="nav-right">
                <div class="location">
                    <img src="images/location.png" alt="location">
                    <ul> 
                        <li>
                            <a href="https://www.starbucks.com/store-locator?map=39.635307,-101.337891,5z">Find a store</a>
                        </li>
                    </ul>
                </div>
                <button class="btn btn-primary">Sign in</button>
                <button class="btn btn-secondary">Join now</button>
            </div>
            <div class="menu">
                <img src="images/menu.png" alt="menu" width="50px" height="51px">
            </div>
        </div>
    </nav>
    
    <!--navigation end-->
    <!--main-content-start-->
    
    <div class="box">
        <div class="container">
            <div class="box-text">
                <h1 class="lg">More sips, more trips</h1>
                <p class="p-lg"> 
                    Join Starbucks® Rewards and link your Delta SkyMiles® account by 3/31 to earn 200 Stars, 500 miles—or both!*
                </p>
                <button class="btn btn-primary btn-white">Join + Link</button>
            </div>
            <div class="box-img"> 
                <img src="images/Travel.jpg" alt="1">
            </div>
        </div>
    </div>
    <div class="box box-secondary">
        <div class="container">
            <div class="box-text box-green box-font">
                <h1>Brighten your day</h1>
                <p>
                    Enjoy a cheery Pink Drink, Paradise Drink or Dragon Drink® Starbucks Refreshers® beverage.
                </p>
                <button class="btn btn-primary">Order now</button>
            </div>
            <div class="box-img"> 
                <img src="images/Iced%20drinks.jpg" alt="2">
            </div>
        </div>
    </div>
    <div class="box">
        <div class="container">
            <div class="box-text box-pink box-font">
                <h1>Uplifting anytime</h1>
                <p> 
                    Recharge with a lively Brown Sugar Oatmilk or Toasted Vanilla Oatmilk Shaken Espresso—140 calories or less in a grande.
                </p>
                <button class="btn btn-primary">Order now</button>
            </div>
            <div class="box-img"> 
                <img src="images/Iced%20Coffee.jpg" alt="3">
            </div>
        </div>
    </div>
    <div class="box box-secondary">
        <div class="container">
            <div class="box-text box-yellow box-font">
                <h1>Hearty on the go</h1>
                <p> 
                    Grab a deliciously filling Double-Smoked Bacon, Cheddar &amp; Egg Sandwich or Bacon &amp; Gruyère Egg Bites.
                </p>
                <button class="btn btn-primary">Order now</button>
            </div>
            <div class="box-img"> 
                <img src="images/Food.jpg" alt="4">
            </div>
        </div>
    </div>
    <div class="box">
        <div class="container">
            <div class="box-text box-light">
                <h1 class="lg">Delivery from our place to yours</h1>
                <p class="p-lg"> 
                    Keep doing you, we’re on the way. Place your Starbucks order for delivery—now on DoorDash. See the DoorDash app for availability and restrictions.
                </p>
                <button class="btn btn-primary">Order now</button>
            </div>
            <div class="box-img"> 
                <img src="images/Door%20dash.jpg" alt="5">
            </div>
            
        </div>
    </div>
     <div class="footer-box">
        <div class="container">
            <p> 
                *At participating stores. Some restrictions apply. Linking bonus open to new members only. For full details, visit http://deltastarbucks.com/terms.
            </p>
        </div>
    </div>
    
    <!--main-content-end-->
    <!--footer-starts-->
    
    <footer class="footer-shadow">
        <div class="footer-container">
            <div class="footer">
                <div class="footer-heading footer-1">
                    <h2>About Us</h2>
                    <a href="#">Our Company</a>
                    <a href="#">Our Coffee</a>
                    <a href="#">Stories and News</a>
                    <a href="#">Starbucks Archive</a>
                    <a href="#">Investor Relations</a>
                    <a href="#">Customer Service</a>
                </div>
                <div class="footer-heading footer-2">
                    <h2>Careers</h2>
                    <a href="#">Culture and Values</a>
                    <a href="#">Inclusion, Diversity, and Equity</a>
                    <a href="#">College Achievement Plan</a>
                    <a href="#">Alumni Community</a>
                    <a href="#">U.S. Careers</a>
                    <a href="#">International Careers</a>
                </div>
                <div class="footer-heading footer-3">
                    <h2>Social Impact</h2>
                    <a href="#">People</a>
                    <a href="#">Planet</a>
                    <a href="#">Environmental and Social Impact Reporting</a>
                </div>
                <div class="footer-heading footer-4">
                    <h2>For Business Partners</h2>
                    <a href="#">Landlord Support Center</a>
                    <a href="#">Suppliers</a>
                    <a href="#">Corporate Gift Card Sales</a>
                    <a href="#">Office Foodservice Coffee</a>
                </div>
                <div class="footer-heading footer-5">
                    <h2>Order and Pickup</h2>
                    <a href="#">Order on the App</a>
                    <a href="#">Order on the Web</a>
                    <a href="#">Delivery</a>
                    <a href="#">Order and Pickup Options</a>
                    <a href="#">Explore and Find Coffee for Home</a>
                </div>
            </div>
        </div>
        <!--
        <div class="footer-container">
            <div class="footer-socials">
                <hr class="solid">
                <h2>
                    <img src="images/facebookblk&wht.PNG">
                    <img src="images/instagramblk&wht.PNG">
                    <img src="images/pinterestblk&wht.PNG">
                    <img src="images/twitterblk&wht.PNG">
                    <img src="images/youtubeblk&wht.PNG">
                </h2>
                <h2>
                    <a href="#">Privacy Notice |</a>
                    <a href="#">Terms of Use |</a>
                    <a href="#">Do Not Share My Personal Information |</a>
                    <a href="#">CA Supply Chain Act |</a>
                    <a href="#">Cookie Preferences |</a>
                </h2>
            </div>
        </div>
        -->
    </footer> 
    <span>© 2023 Created By HindCodes</span>
    <!--footer-ends-->
</body>
</html>

CSS

@import url('https://fonts.googleapis.com/css2?family=Kanit:wght@300;400;600&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body { 
    font-family: 'Kanit', sans-serif;
}

.container {
    width: 1300px;
    margin: 0 auto;
}

ul li {
    letter-spacing: 0.1em !important;
    list-style: none;
}

a {
    text-decoration: none;
}

/* nav */

nav {
    box-shadow: 0 1px 3px rgb(0 0 0 / 10%), 0 2px 2px rgb(0 0 0 / 6%), 0 0 2px rgba(0 0 0 / 7%); 
}

nav .container {
    display: flex; 
    align-items: center;
    justify-content: space-between;
    padding: 32px;
    width: 1300px;
    height: 101px;
    
}

.logo {
    display: block;
    cursor: pointer;
}

.nav-left {
    display: flex;
}

.nav-left ul {
    display: flex;
    align-items: center;
    
}

.nav-left ul li{
    margin-left: 20px;
}

.nav-left ul li a {
    text-decoration: uppercase;
    color: #181A18;
    
}

.nav-left ul li a:hover {
    color: #00754a;
}

.nav-right {
    display: flex;
    align-items: center;
    justify-content: center;
}

.nav-right .location {
    display: flex;
    align-items: center;
    margin-right: 40px;
    cursor: pointer;
}

.nav-right .location ul li a:hover {
    color: #00754a;
}

.nav-right .location ul {
     margin-left: 10px;
}

.nav-right .location ul li a{
     text-decoration: uppercase;
     color: #181A18;
}
    
.location img {
    height: 20px;
    
}

.nav-right button {
    margin-left: 20px;
}

.btn {
    padding: 6.4px 16px;
    background-color: transparent;
    border: none;
    cursor: pointer;
    font-size: 16px;
    border-radius: 40px;
    font-family: 'Kanit', sans-serif;
}

.btn-primary {
    border: 1px solid rgba(0, 0, 0, 0.87);
}

.btn-primary:hover {
   background-color: rgba(0,0, 0, 0.06);
}

.btn-secondary {
    background-color: #181a18;
    color: #fff;
}

.btn-secondary:hover {
    background-color: rgba(0, 0, 0, 0.7);
    border-color: rgba(0, 0, 0, 0.7);
}

.menu {
    display: none;
}

/* main-content */

.box {
    margin-top: 32px;
}

.box .container {
    display: flex;
}

.box-text {
    width: 50%;
    padding: 32px 80px;
    background-color: #1e3932;
    color: #fff;
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.box-text h1 {
    font-size: 50px;
}

.box-text p {
    margin-top: 24px;
    margin-bottom: 32px;
    font-size: 24px;
}

.box-img {
    width: 50%;
}

.box-img img{
    height: 100%;
    width: 100%;
    
} 

.lg {
    font-size: 24px !important;
}

.p-lg {
    font-size: 16px !important; 
}

.mt-0 {
    margin-top: 0 !important;
}

.box-secondary .container {
   flex-direction: row-reverse; 
}

.mb-1 {
    margin-bottom: 32px;
}

.box-light {
    background-color: #d4e9e2;
    color: #181a18;
}

.box-font h1 {
    font-weight: normal;
}

.box-green {
    background-color: #a0c292;
    color: #1e3932;
}

.box-pink {
    background-color: #f6bfd9;
    color: #1e3932;
}

.box-yellow {
    background-color: #fff4d4;
    color: #1e3932;
}


.btn-white {
    border-color: #fff;
    color: #fff;
}

.show {
    display: flex;
}

/*footer*/

.footer-shadow {
    box-shadow: 0 -1px 3px rgba(0,0,0,.1), 0 -2px 2px rgba(0,0,0,.06), 0 0 2px rgba(0,0,0,.07);
}

.footer-box {
    background-color: #fff;
    padding: 4rem 0 4rem 0;
    color: black;
    margin-left: 20rem;
}

.footer-container {
    background-color: #fff;
    padding: 4rem 0 2rem 0;
}

.footer {
    height: 40vh;
    background-color: #fff;
    color: black;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    margin: 0;
}

.footer-heading {
    display: flex;
    flex-direction: column;
    margin-right: 4rem;
}

.footer-heading h2 {
    margin-bottom: 2rem;
    font-size: 20px;
}

.footer-heading a {
    font-size: 15px;
    color: rgba(0, 0, 0, 0.58);
    text-decoration: none;
    margin-bottom: 0.5rem;
}

.footer-heading a:hover {
    color: rgba (0, 0, 0, 0.87);
    transition: 0.3s ease-out;
}


/*
hr.solid {
    border-top: 3px solid #bbb;
    margin-bottom: 2rem;
}

.footer-socials {
    background-color: #fff;
    color: black;
    
}

.footer-socials img {
    width: 30px; 
}


.footer-socials a {
    
    margin-top: 10px;
    color: black;
    font-size: 15px;
    font-weight: 100;
    
}

.footer-socials span {
    color: rgba(0, 0, 0, 0.58);
    font-size: 15px;
}
*/

@media (max-width:786px) {
    ul {
        position: absolute;
        margin-left: 20px;
        flex-direction: column;
        top: 100px;
        background-color: #fff;
        color: black;
        width: 80%;
        display: none;
        padding: 20px;
        box-shadow: -2px 9px 17px 10px rgba(0, 0, 0.1, 0.1); 
    }
    li {
        padding: 20px;   
    }
    .menu {
        display: block;
    }
}
   

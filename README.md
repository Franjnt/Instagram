<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagram</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <section class="main">
        <section class="left">
        <img class="phone" src="\\wsl$\Ubuntu\home\franjnt\instagram\lab-css-instagram-clone-master\images\phones.png" alt="mobile-phone">
        </section>
            <section class="instagram">
                
                <div class="brand">
                <img src="\\wsl$\Ubuntu\home\franjnt\instagram\lab-css-instagram-clone-master\images\brand.png" alt="brand">
                   </div>
                   <div class="login-button">
                   <div class="log-in">
                <img src="\\wsl$\Ubuntu\home\franjnt\instagram\lab-css-instagram-clone-master\images\home.png" alt="log in">
            
                <p class="login">Log in</p>
                    </div>
                </div>
            </section>
            <section class="text">
                <div class="capture">
                <img class="frame" src="\\wsl$\Ubuntu\home\franjnt\instagram\lab-css-instagram-clone-master\images\frame.png" alt="frame">
                <h2>Capture and Share<br>the World's Moments</h2>
                <p>Instagram is a fast, beautiful and fun way to share your life with friends and family. Take a picture or video, choose a filter to transform its look and feel, then post to Instagram — it's that easy. You can even share to Facebook, Twitter, Tumblr and more. It's a new way to see the world. Oh yeah, did we mention it's free?</p>
                </div>
                <section class="store">
                <div class="appstore">
                <img class="iphone" src="\\wsl$\Ubuntu\home\franjnt\instagram\lab-css-instagram-clone-master\images\badge-iphone.png" alt="iphone">
                </div>
                <div class="googleplay">
                <img class="android" src="\\wsl$\Ubuntu\home\franjnt\instagram\lab-css-instagram-clone-master\images\badge-android.png" alt="android">
                </div>
                </section>
            </section>
            </section>
    </section>
</body>

<footer>
    <nav>
       <ul class="foot">
           <li><a href="#">About us</a></li>
           <li><a href="#">Support</a></li>
           <li><a href="#">Blog</a></li>
           <li><a href="#">Press</a></li>
           <li><a href="#">Api</a></li>
           <li><a href="#">Jobs</a></li>
           <li><a href="#">Privacy</a></li>
           <li><a href="#">Terms</a></li>
           <li>© 2014 Instagram</li>
       </ul>
</footer>
</html>


/* css*/


*{
    padding: 0;
    margin: 0;
}

body{
    display: flex;
    flex-direction: row;

}

.main{
    display: flex;
}

.instagram{
    display: flex;
    flex-direction: row;
}

.brand{
    ;
    
}

.login-button{

    display: flex;
    flex-direction: row;
    border: 1px;

}

.log-in{
    
}

.login{

}

.text{

}

.capture{

}

h2{
    color: #06365f
}

p{
    font: 200 16px/1.5 "Helvetica Neue", Helvetica, Arial, sans-serif;
    margin: 0;
}

.store{
    display: flex;
    flex-direction: row;
    
}

.appstore{
    
}

.googleplay{

}

.foot{
    display: flex;
    color: red;
    flex-direction: row;
}

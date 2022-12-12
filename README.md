# MYGO
Here is MYGO to help you out for reaching your destination.  it contain all the things during a travel for example description about destination , room availability food etc.
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <title>Travel Website</title>
</head>
<style>
    *{
    margin:0;
    padding:0;
}

.header{
  height:100vh;
  background:linear-gradient(rgba(0,0,0,0.6),rgba(0,0,0,0.6)),url("C:/Users/Vaishnavi/Pictures/Saved Pictures/mygo_pic3.jpg") no-repeat;
  background-size:cover;
  background-position: center;
  background-attachment:fixed;
  padding-top:30px;
  text-align:center;
  color:#fff;
}

.header img{
    width: 170px;
    float: cover;

}

.login-btn{
    width:100px;
    padding: 8px 0;
    outline: none !important;
    border-radius:50px;
    background:transparent;
    color:#fff;
    float:right;
}

.header h1{
    padding-top:260px;
    padding-bottom:0px;
    font-size:55px;
}
.header p{
    margin: 18px 0px;
}

.input-group{
    width:90% !important;
    max-width:500px;
    border-radius:30px;
    background:#fff;
    margin:auto;
    padding:2px;
}
.form-control{
    border: 0 !important;
    border-radius:30px !important;
    margin:2px;
    box-shadow:none !important;
}
.input-group-text{
    width: 100px;
    background-image:linear-gradient(#00ff7e,#1f3d90);
    border:0 !important;
    color:#fff !important;
    padding:0 25px !important;
    border-radius:30px !important;
    box-shadow:none; 
}
/* features */
.features{
    padding: 100px 0;
}

h1{
    text-align:center;
    padding-bottom:30px;
}

.feature-img img{
      width: 100%;

}

.price{
    width:90px;
    height:90px;
    background:#ff5722;
    color:#fff;
    font-weight:600;
    border-radius:50%;
    padding:10px;
    box-shadow:0 0 10px 1px rgba(37,73,214,0.18);
    position:absolute;
    left:10px;
    bottom:-25px;
}
.feature-img{
    position:relative;
}
.rating{
    padding:3px;
    float:right;
    background:#fff;
    bottom:-1px;
    right:0;
    position:absolute;
}

.features .fa{
    font-size:15px;
    color:#ff5722;
}

.feature-details{
    padding:20px;
    text-align:justify;
}
.feature-details h4{
    font-weight:600%;
    margin-top:20px;
}

.feature-details .fa{
    margin-right:5px;

}
.feature-box{
    box-shadow:0 0 10px 1px rgba(37,73,214,0.18);
    margin-bottom:30px;
}

.gallery{
    padding:100px 0;
    background: #efefef;
}

.gallery-box img{
    width:100%;
    border-radius:16px;
    cursor:pointer;
    transition:1s;
}
.gallery-box img:hover{
    transform:scale(1.1);
}

.gallery-box h4{
    display:block;
    color:#fff;
    text-shadow:-2px 2px 2px #000;
    font-weight:600%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
}

.gallery-box{
    position:relative;
    margin-bottom:30px;
}
 
.banner{
    
    background-image:url("C:/Users/Vaishnavi/Pictures/Saved Pictures/cccccccccccccccc.jpg");
    background-position: center;
    background-size:cover;
    background-attachment:fixed;
    padding-top:14%;
    height:80vh;
}

.banner-highlights{
    padding: 70px 0%;
    background:rgba(0,0,0,0.7);
    text-align:center;
    color:#fff;

}
.booking-btn{
    width:120px;
    padding:8px 0;
    outline:none !important;
    border:2px solid #fff;
    border-radius:50px;
    background:transparent;
    color:#fff;
    margin-top:20px;
}

.users-feedback{
    padding:100px 0;
}
.user-review{
    text-align:center;
    box-shadow:0 0 10px 0 rgba(0,0,100,0.2);
    padding-bottom:50px;
}
.user-review p{
    padding: 50px 10px 10px 10px;
}
.users-feedback img{
    width:60px;
    height:60px;
    border-radius:50%;
    position:relative;
    margin: -30px 0 20px 40%;
}
.user-review p::before{
    content: '\201d';
    display:block;
    position:absolute;
    font-size:100px;
    color:#649fed;
    font-family:sans-serif;
    left:44%;
    top:-20px;

}

.footer{
    padding:100px 20px 15px;
    background-image:linear-gradient(#2d557d,#9610fd);
    color:#fff;

}
.footer-logo{
     width:150px;
     margin-top:15px;
     margin-bottom:15px;
}
.footer h4{
    text-align:left;
    margin-top:15px;
    margin-bottom:25px;

}
.footer p{
    font-size:12px;
    text-align:justify;
    padding-right:35px;

}

.footer .row .fa{
    padding-right:20px;
    font-size:15px;

}
.footer hr{
    margin-top:10px;
    background:#efefef;
}

.fa-heart{
    margin:0 5px;
    color:#f44336;
}
.footer .copyright{
    text-align:center;
}
.contact{
    background-color: #f6f5f4;
    height: 833px;
}
.text-center{
    text-align: center;
    padding: 30px;
    font-family: 'ububtu' ,sans-serif;
    font-size: 35px;
}
.form{
    max-width: 500px;
    margin: 42px auto;

}
.form-input{
    margin: 14px 0;
    padding: 5px 3px;
    width: 100%;
    font-size: 19px;
    border: 2px solid gray;
    border-radius: 6px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

</style>

<body>
    <section class="header">
        <div class="container">
            <img src="C:/Users/Vaishnavi/Pictures/Saved Pictures/mygo_pic1.jpg">
            <button type="button" class="login-btn">Login</button>
        </div>
        <h1>Travel Across The India</h1>
        <p>The journey of a thousand miles begins with a single search.</p>
        <div class="input-group">
            <input type="text" class="form-control" placeholder="Search City">
            <div class="input-group-append">
                <button type="button" class="input-group-text btn">Search</button>
            </div>
        </div>
    </section>
    <section class="features">
        <h1>Featured Destinations</h1>
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <div class="feature-box">
                        <div class="feature-img">
                            <img src="C:/Users/Vaishnavi/Pictures/Saved Pictures/mygo_goa.jpg">
                            <div class="price">
                                <p>From 7999.00/-</p>
                            </div>
                            <div class="rating">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star-half-o"></i>
                                <i class="fa fa-star-o"></i>
                            </div>
                        </div>
                        <div class="feature-details">
                            <h4>Goa</h4>
                            <p>Goa with umpteen numbers of pristine beaches is nothing less than a paradise for beach
                                lovers.
                                Along with beaches,it is one of the sought after places for party lovers and adventure
                                seekers.
                                The touch of Portuguese culture and architecturally beautiful historical buildings make
                                this tourist destination even more enchanting.
                                With a culture so unique and an unparalleled natural setting,Goa present a setting which
                                is different from rest of the country.</p>
                        </div>
                        <span><i class="fa fa-map-marker"></i>Goa</span>
                        <span><i class="fa fa-sun-o"></i>2 Days</span>
                        <span><i class="fa fa-moon-o"></i>3 Nights</span>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="feature-box">
                        <div class="feature-img">
                            <img src="C:/Users/Vaishnavi/Pictures/Saved Pictures/mygo_leh.jpg">
                            <div class="price">
                                <p>From 9999.00/-</p>
                            </div>
                            <div class="rating">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star-half-o"></i>
                                <i class="fa fa-star-o"></i>
                            </div>
                        </div>
                        <div class="feature-details">
                            <h4>Leh Ladakh</h4>
                            <p>The barren beauty of Ladakh in India with snow-capped peaks and the clean azure sky has
                                continued to attract the intrepid travelers.
                                Ladakh has become a favorite haunt for trekking and mountaineering enthusiasts.
                                The rugged terrain and the majestic mountains around, make an exotic cocktail for an
                                adventure lover.
                                But before you decide to fly away to the land of Buddhist monasteries and brave
                                people,here's everything that you need to know.</p>
                        </div>
                        <span><i class="fa fa-map-marker"></i>Leh Ladakh</span>
                        <span><i class="fa fa-sun-o"></i>4 Days</span>
                        <span><i class="fa fa-moon-o"></i>3 Nights</span>
                    </div>

                </div>
                <div class="col-md-4">
                    <div class="feature-box">
                        <div class="feature-img">
                            <img src="C:/Users/Vaishnavi/Pictures/Saved Pictures/mygo_ri.jpg">
                            <div class="price">
                                <p>From 15999/-</p>
                            </div>
                            <div class="rating">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star-half-o"></i>
                                <i class="fa fa-star-o"></i>
                            </div>
                        </div>
                        <div class="feature-details">
                            <h4>Rishikesh</h4>
                            <p>Rishikesh is renowned for its mastery in ‘Yoga’ which is located in northern state of
                                Uttarakhand.
                                It was a city with full of ashrams, temples, and also well-known for various adventurous
                                activities such as trekking, rafting, camping, bungee jumping, attracting thousands of
                                visitors every year.
                                Infact, the city is also called as ‘White rafting capital of India’ due to the glorious
                                river ‘Ganges’ that flow rapidly throughout the city. </p>
                        </div>
                        <span><i class="fa fa-map-marker"></i>Rishikesh</span>
                        <span><i class="fa fa-sun-o"></i>4 Days</span>
                        <span><i class="fa fa-moon-o"></i>3 Nights</span>
                    </div>


                </div>
            </div>
        </div>
    </section>
    <section class="contact">
        <h1 class="text-center">Contact us</h1>
        <section>
            <div class="form">
                <input class="form-input" type="text" name="name" id="name" placeholder="enter your name">
                </br>
                <input class="form-input" type="number" name="name" id="phone" placeholder="enter your phone">
                </br>
                <input class="form-input" type="email" name="name" id="email" placeholder="enter your email">
                </br>
                <textarea class="form-input" name="text" id="text" cols="30" rows="10"></textarea>
                </br>
                <button class="btn btn-dark">Submit</button>
                </br>
            </div>
        </section>
        <section class="gallery">
            <h1>Travelling Gallery</h1>
            <div class="container">
                <div class="row">
                    <div class="col-md-3">
                        <div class="gallery-box">
                            <img src="C:/Users/Vaishnavi/Pictures/Saved Pictures/mygo_go.jpg">
                            <h4>Goa</h4>
                        </div>

                    </div>
                    <div class="col-md-3">
                        <div class="gallery-box">
                            <img src="C:/Users/Vaishnavi/Pictures/Saved Pictures/myg0_lehladd.jpg">
                            <h4>Leh Ladahk</h4>
                        </div>

                    </div>

                    <div class="col-md-3">
                        <div class="gallery-box">
                            <img src="C:/Users/Vaishnavi/Pictures/Saved Pictures/mygo_rishikesh.jpg">
                            <h4>Rishikesh</h4>
                        </div>

                    </div>

                </div>

            </div>
            </div>
        </section>
        <section class="banner">
            <div class="banner-highlights">
                <div class="container">
                    <div class="row">
                        <div class="col-md-8">
                            <h2>Get 30% on top destination</h2>
                            <p>Book your tickets before 25th December and avail 30% flat discount.</p>
                        </div>
                        <div class="col-md-4">
                            <button type="button" class="booking-btn">Book Now</button>
                        </div>
                    </div>

                </div>
            </div>
        </section>
        <section class="users-feedback">
            <h1>User Review</h1>
            <div class="container">
                <div class="row">
                    <div class="col-md-4">
                        <div class="user-review">
                            <p>Thank you for your Great service.Absolutely no hassels at all.Would defenitely book
                                through you again.</p>
                            <h5>Katyayani Singh</h5>
                            <small>Leh Ladakh</small>
                            <img src="C:/Users/Vaishnavi/Pictures/Saved Pictures/mygo_6.jpg">
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="user-review">
                            <p>This was my first Time to Rishikesh.I loved every moment and cannot wait to go back
                                again.Awesome Service! Very organised Trip:)</p>
                            <h5>Divya Yadav</h5>
                            <small>Rishikesh</small>
                            <img src="C:/Users/Vaishnavi/Pictures/Saved Pictures/mygo_6.jpg">
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="user-review">
                            <p>Thanks for such a great deal.We will be booking through you guys again!quick responses to
                                question too.



                            </p>
                            <h5>Shaivi </h5>
                            <small>Goa</small>
                            <img src="C:/Users/Vaishnavi/Pictures/Saved Pictures/mygo_6.jpg">
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="footer">
            <div class="container">
                <div class="row">
                    <div class="col-md-3">
                        <img src="C:/Users/Vaishnavi/Pictures/Saved Pictures/mygo_pic1.jpg">
                        <p>Dare to live the life you've always wanted with MYGO</p>
                    </div>
                    <div class="col-md-3">
                        <h4>Features</h4>
                        <p>Deals & Offers</p>
                        <p>Customer Reviews</p>
                        <p>Cancelation Policy</p>
                    </div>
                    <div class="col-md-3">
                        <h4>Quick Contact</h4>
                        <p><i class="fa fa-phone-square"></i>+919888677990</p>
                        <p><i class="fa fa-envelope"></i>MYGO0433@gmail.com</p>
                        <p><i class="fa fa-home"></i>xyz Road,ABC City</p>
                    </div>
                    <div class="col-md-3">
                        <h4>Follow Us on</h4>
                        <p><i class="fa fa-facebook-official"></i>facebook</p>
                        <p><i class="fa fa-youtube-play"></i>youtube</p>
                        <p><i class="fa fa-twitter"></i>Twitter</p>
                    </div>
                </div>
                <hr>
                <p class="copyright">Made with <i class="fa fa-heart"></i></p>
            </div>
        </section>
</body>

</html>

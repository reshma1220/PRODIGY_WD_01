index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    <link
     href="https://cdn.jsdelivr.net/npm/remixicon@4.3.0/fonts/remixicon.css"
     rel="stylesheet"
    />
    <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css"
    />
    <link rel="stylesheet" href="styles.css" />
    <title>Food</title>
</head>
<body>
    <header>
        <nav>
            <div class="nav__header">
                <div class="nav__logo">
                    <a href="#" class="logo">
                        <img src="logo.jpg" alt="logo" />
                    </a>
                </div>
                <div class="nav__menu__btn" id="menu-btn">
                    <i class="ri-menu-line"></i>
                </div>
            </div> 
            <ul class="nav__links" id="nav-links">
                <li><a href="#home">Why Food</a></li>
                <li><a href="#service">Services</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#contact">Contact</a></li> 
                <li>
                    <button class="btn">
                        <span><i class="ri-login-box-line"></i></span>
                        Login 
                    </button>
                </li> 
            </ul> 
            <div class="nav__btns"> 
                <button class="btn">
                    <span><i class="ri-login-box-line"></i></span>
                    Login 
                </button>
        </nav>
        <div class="section__container header__container" id="home">
            <div class="header__image">
                <img src="header.png" alt="header"/>
            </div>
            <div class="header__container">
                <div class="header__tag">
                    More than Faster
                    <img src="delivery bike.jpg" alt="header tag"/>
                </div>  
                <h1>Be the Fastest In Delivering Your
                <span>Food</span></h1>
                <div class="header__btns">
                    <button class="btn">Get Started</button> 
                </div>     
            </div>    
        </div>        
    </header>  
    <section class="section__container service__container" id="Service">
        <p class="section__subheader">WHAT WE SERVE</p>
        <class="section__header"><h2>Your Favourite Food delivery Partner</h2>
        <div class="service__grid">
            <div class="service__card">
              <img src="service-1.jpg" alt="service" />
              <h4>Easy To Order</h4>
              <p>You only need a few steps in ordering food</p>
            </div>  
            <div class="service__card">
                <img src="service-2.jpg" alt="service" />
                <h4>Fastest Delivery</h4>
                <p>Delivery that is always on time even faster</p>
            </div>  
            <div class="service__card">
                <img src="service-3.jpg" alt="service" />
                <h4>Best Quality</h4>
                <p>Not only fast for us quality is also number one</p>
            </div>  
        </div>    
    </section>
    <section class="section__container menu__container" id="menu">
        <p class="section__subheader">OUR MENU</p>
        <h2 class="section__header">Menu That Always Make You Fall In Love</h2>
        <div class="swiper">
            <div class="swiper-wrapper">
                <div class="swiper-slide">
                    <div class="menu__card">
                        <img src="menu1.jpg" alt="menu"/>
                        <div class="menu__card__details">
                            <h4>Italian Red Sauce Pasta</h4>
                            <button class="btn">Order Now</button></a>  
                        </div>
                    </div>
                </div>
           <div class="swiper-slide">
                <div class="menu__card">
                    <img src="menu2.jpg" alt="menu"/>
                    <div class="menu__card__details">
                        <h4>Dum Biryani</h4>
                        <button class="btn">Order Now</button></a>
                    </div>
                </div>
            </div>
            <div class="swiper-slide">
                <div class="menu__card">
                    <img src="menu3.jpg" alt="menu"/>
                    <div class="menu__card__details">
                        <h4>Chicken Nuggets</h4>
                        <button class="btn">Order Now</button></a>
                    </div>
                </div>
            </div>
            <div class="swiper-slide">
                <div class="menu__card">
                    <img src="menu7.jpg" alt="menu"/>
                    <div class="menu__card__details">
                        <h4>Italian Pizza</h4>
                        <button class="btn">Order Now</button></a>
                    </div>
                </div>
            </div>
            <div class="swiper-slide">
                <div class="menu__card">
                    <img src="menu-6.jpg" alt="menu"/>
                    <div class="menu__card__details">
                        <h4>Burrito Wrap</h4>
                        <button class="btn">Order Now</button></a>
                    </div>
                </div>
            </div>
        </div>    
    </section>
    <section class="section__container client__container" id="client">
        <div class="client__image">
            <img src="client.png" alt="client">
        </div>
        <div class ="client__content">
            <p class="section__subheader">WHAT  THEY SAY</p>
            <h2 class="section__header">What Our Customer Say About Us</h2>
            <p class="section__description">
                "Food is simply outstanding! The variety and deliciousness of their
                meals are unparalleled, offering something for every palate. What sets
                Food apart is their exceptional service. The delivery is impressively
                fast, ensuring your food arrives hot and fresh."
            </p>
            <div class="client__details">
                <img src="user.jpg" alt="client" />
                <div>
                  <h4>Theresa Jordan</h4>
                  <h5>Food Enthusiast</h5>
                </div>
            </div>     
            <div class="client__rating">
                <span><i class="ri-star-fill"></i></span>
                <span><i class="ri-star-fill"></i></span>
                <span><i class="ri-star-fill"></i></span>
                <span><i class="ri-star-fill"></i></span>
                <span><i class="ri-star-line"></i></span>
                <span>4.7</span>
            </div> 
        </div> 
    </section>  
    <section class="download_container" id="Contact">
        <div class="section__container">
            <div class="download__image">
                <img src="delivery.jpg" alt="delivery"/>
            </div>
            <div class="download__content"></br>
                <p class="section__subheader">DOWNLOAD APP</p>
                <h2 class="section__header">Get Started With <span>Food</span> Today!</h2>
                <p class="section__description">
                Discover delicious food wherever and whenever you want and get your food
                delivered on time, every time.</p>
            <div class="download__btn">
                <button class="btn">Get The App</button> 
            </div>   
            </div>           
        </div>
    </section>  
    
    <footer>
        <div class="section__container footer__container">
            <div class="footer__col">
                <div class="footer__logo">
                    <a href="#" class="logo">
                        <img src="logo.jpg" alt="logo">
                    </a>
                </div>
                <h3="section__description">
                    Our job is to filling your tummy with </br>delicious food and with fast
                    and</br> free delivery time.</h3>
                <ul class="footer__socials">
                    <li>
                        <a href="#"><i class="ri-instagram-fill"></i></a>
                    </li>
                    <li>
                        <a href="#"><i class="ri-facebook-fill"></i></a>
                        </li>
                    <li>
                        <a href="#"><i class="ri-twitter-fill"></i></a>
                    </li>
                </ul>  
            </div>  
            <div class="footer__col">
                <h4>About</h4>
                <ul class="footer__links">
                  <li><a href="#">About Us</a></li>
                  <li><a href="#">Features</a></li>
                  <li><a href="#">News</a></li>
                  <li><a href="#">Menu</a></li>
                </ul>
            </div>
        <div class="footer__col">
          <h4>Company</h4>
          <ul class="footer__links">
            <li><a href="#">Why Food?</a></li>
            <li><a href="#">Partner With Us</a></li>
            <li><a href="#">FAQ</a></li>
            <li><a href="#">Blog</a></li>
          </ul>
        </div>
        <div class="footer__col">
          <h4>Support</h4>
          <ul class="footer__links">
            <li><a href="#">Account</a></li>
            <li><a href="#">Support Center</a></li>
            <li><a href="#">Feedback</a></li>
            <li><a href="#">Contact Us</a></li>
            <li><a href="#">Accessibility</a></li>
          </ul>
        </div> 
       </div> 
       <div class="footer__bar">
        Copyright © 2024 Food. All rights reserved.
       </div> 
    </footer>      


  

    <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
    <script src="https://unpkg.com/scrollreveal"></script>
    <script src="script.js"></script>  
</body>    
</html>


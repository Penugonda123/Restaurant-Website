<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Resturant Website </title>

   
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

    
    <link rel="stylesheet" href="style.css">

</head>
<body>
    

<header class="header">

    <a href="#" class="logo"> <i class="fas fa-utensils"></i> DJ's RESTAURANT </a>
    
    <nav class="navbar">
        <a href="#home">home</a>
        <a href="#popular">popular</a>
        <a href="#menu">menu</a>
        <a href="#order">order</a>
        <a href="#about">about</a>
      
    </nav>

    <div class="icons">
        <div id="menu-btn" class="fas fa-bars"></div>
        <div id="search-btn" class="fas fa-search"></div>
        <div id="cart-btn" class="fas fa-shopping-cart"></div>
        <div id="login-btn" class="fas fa-user"></div>
    </div>
    
</header>

<section class="search-form-container">

    <form action="">
        <input type="search" name="" placeholder="search here..." id="search-box">
        <label for="search-box" class="fas fa-search"></label>
    </form>

</section>


<section class="shopping-cart-container">

    <div class="products-container">

        <h3 class="title">your products</h3>

        <div class="box-container">

            <div class="box">
                <i class="fas fa-times"></i>
                <img src="image/menu-1.jpg" alt="">
                <div class="content">
                    <h3> burger </h3>
                    <span> quantity : </span>
                    <input type="number" name="" value="1" id="">
                    <br>
                    <span> price : </span>
                    <span class="price"> &#8377 90rs</span>
                </div>
            </div>

            <div class="box">
                <i class="fas fa-times"></i>
                <img src="image/Icecream.jpeg" alt="">
                <div class="content">
                    <h3> Ice Cream ( vanilla )</h3>
                    <span> quantity : </span>
                    <input type="number" name="" value="1" id="">
                    <br>
                    <span> price : </span>
                    <span class="price"> &#8377 80rs</span>
                </div>
            </div>

            <div class="box">
                <i class="fas fa-times"></i>
                <img src="image/sandwich.jfif" alt="">
                <div class="content">
                    <h3> Sandwich </h3>
                    <span> quantity : </span>
                    <input type="number" name="" value="1" id="">
                    <br>
                    <span> price : </span>
                    <span class="price"> &#8377 80rs</span>
                </div>
            </div>

            <div class="box">
                <i class="fas fa-times"></i>
                <img src="image/Frypiece.png" alt="">
                <div class="content">
                    <h3> Fried Chicken </h3>
                    <span> quantity : </span>
                    <input type="number" name="" value="1" id="">
                    <br>
                    <span> price : </span>
                    <span class="price"> &#8377 120rs</span>
                </div>
            </div>

            

        </div>

    </div>

    <div class="cart-total">

        <h3 class="title"> cart total </h3>

        <div class="box">

            <h3 class="subtotal"> subtotal : <span> &#8377 370rs</span> </h3>
            <h3 class="total"> total : <span>  &#8377 370rs</span> </h3>

            <a href="#" class="btn">proceed to checkout</a>

        </div>

    </div>

</section>


<div class="login-form-container">

    <form action="">
        <h3>login form</h3>
        <input type="email" name="" placeholder="Enter your email" id="" class="box">
        <input type="password" name="" placeholder="Enter your password" id="" class="box">
        <div class="remember">
            <input type="checkbox" name="" id="remember-me">
            <label for="remember-me">remember me</label>
        </div>
        <input type="submit" value="login now" class="btn">
        <p>forget password? <a href="#">click here</a></p>
        <p>don't have an account? <a href="#">create one</a></p>
    </form>

</div>


<section class="home" id="home">

    <div class="content">
        <span><b> welcome foodies </b></span>
        <h3>different spices for the different tastes 😋</h3>
        <p> <b> Go through the Menu and Order your favourite food and Get upto 30% Discount TODAY. </b></p>
        <a href="#" class="btn">order now</a>
    </div>

    <div class="image">
        <img src="image/cup biryani.jpg" alt="" class="home-img">

    </div>

</section>


    <div class="heading">
        <span> Food </span>
        <h3> Availbility </h3>
    </div>

<section class="category">

    <a href="#" class="box">
        <img src="image/dosa.jfif" alt="">
        <h3> Breakfast</h3>
    </a>

    <a href="#" class="box">
        <img src="image/pizza.jfif" alt="">
        <h3>pizza</h3>
    </a>

    <a href="#" class="box">
        <img src="image/meals.jfif" alt="">
        <h3> Lunch </h3>
    </a>

    <a href="#" class="box">
        <img src="image/snaks.jfif" alt="">
        <h3> Snaks</h3>
    </a>

    <a href="#" class="box">
        <img src="image/dinner.jfif" alt="">
        <h3>dinner</h3>
    </a>

    <a href="#" class="box">
        <img src="image/drinks.jfif" alt="">
        <h3> Drinks </h3>
    </a>

</section>





<section class="popular" id="popular">

    <div class="heading">
        <span>popular food</span>
        <h3>our special dishes</h3>
    </div>

    <div class="box-container">

        <div class="box">
            <a href="#" class="fas fa-heart"></a>
            <div class="image">
                <img src="image/korrameenu.jpg" alt="">
            </div>
            <div class="content">
                <h3> korrameenu curry </h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                    <span> (82) </span>
                </div>
                <div class="price">&#8377 250rs <span> &#8377 300rs</span></div>
                <a href="#" class="btn">add to cart</a>
            </div>
        </div>

        <div class="box">
            <a href="#" class="fas fa-heart"></a>
            <div class="image">
                <img src="image/masala dosa.jfif" alt="">
            </div>
            <div class="content">
                <h3> masala dosa</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                    <span> (501) </span>
                </div>
                <div class="price">&#8377 60rs   <span>&#8377 80rs</span></div>
                <a href="#" class="btn">add to cart</a>
            </div>
        </div>

        <div class="box">
            <a href="#" class="fas fa-heart"></a>
            <div class="image">
                <img src="image/chicken dum biryani.jfif" alt="">
            </div>
            <div class="content">
                <h3> Chicken Dum biryani </h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                    <span> (234) </span>
                </div>
                <div class="price">&#8377 240rs  <span>&#8377 290rs</span></div>
                <a href="#" class="btn">add to cart</a>
            </div>
        </div>

        <div class="box">
            <a href="#" class="fas fa-heart"></a>
            <div class="image">
                <img src="image/gongura mutton.jfif" alt="">
            </div>
            <div class="content">
                <h3> Gongura Mutton</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                    <span> (196) </span>
                </div>
                <div class="price"> &#8377 200rs  <span> &#8377 230rs</span></div>
                <a href="#" class="btn">add to cart</a>
            </div>
        </div>

        <div class="box">
            <a href="#" class="fas fa-heart"></a>
            <div class="image">
                <img src="image/bamboo.jfif" alt="">
            </div>
            <div class="content">
                <h3> Bamboo Chicken Biryani</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                    <span> (168) </span>
                </div>
                <div class="price"> &#8377 300rs<span> &#8377 340rs</span></div>
                <a href="#" class="btn">add to cart</a>
            </div>
        </div>

       
        
    </div>

</section>



<section class="banner">


    <div class="grid-banner">
        <div class="grid">
            <img src="image/banner-1.png" alt="">
            <div class="content">
                <span>special offer</span>
                <h3>upto 50% off</h3>
                <a href="#" class="btn">order now</a>
            </div>
        </div>
        <div class="grid">
            <img src="image/banner-2.png" alt="">
            <div class="content center">
                <span>special offer</span>
                <h3>upto 25% extra</h3>
                <a href="#" class="btn">order now</a>
            </div>
        </div>
        <div class="grid">        
            <img src="image/banner-3.png" alt="">
            <div class="content">
                <span>limited offer</span>
                <h3>100% cashback</h3>
                <a href="#" class="btn">order now</a>
            </div>
        </div>
    </div>

</section>

<section class="menu" id="menu">

    <div class="heading">
        <span>our menu</span>
        <h3>our top dishes</h3>
        <h3>Breakfast || Lunch || Dinner || Drinks</h3>
    </div>

    <div class="box-container">

        <a href="#" class="box">
            <img src="image/idli.jfif" alt="">
            <div class="content">
                <h3> Idli </h3>
                <div class="price"> &#8377 60rs </div>
            </div>
        
        </a>

        <a href="#" class="box">
            <img src="image/dosa.jfif" alt="">
            <div class="content">
                <h3> Dosa </h3>
                <div class="price"> &#8377 50rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/onion dosa.jfif" alt="">
            <div class="content">
                <h3> Onion Dosa </h3>
                <div class="price"> &#8377  65rs </div>
            </div>
        </a>
    
    
        <a href="#" class="box">
            <img src="image/sambar idli.jfif" alt="">
            <div class="content">
                <h3>Sambar Idli</h3>
                <div class="price">&#8377  80rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/vada.jfif" alt="">
            <div class="content">
                <h3> Vada </h3>
                <div class="price"> &#8377 60rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/sambar vada.jfif" alt="">
            <div class="content">
                <h3>Sambar Vada </h3>
                <div class="price">&#8377  80rs </div>
            </div>
        </a>
        
        <a href="#" class="box">
            <img src="image/chapathi.jfif" alt="">
            <div class="content">
                <h3> Chapathi </h3>
                <div class="price"> &#8377 60rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/puri.jfif" alt="">
            <div class="content">
                <h3> Puri </h3>
                <div class="price">&#8377 60rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/bonda.jfif" alt="">
            <div class="content">
                <h3> Bondaa </h3>
                <div class="price">&#8377 60rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/punukulu.jfif" alt="">
            <div class="content">
                <h3> Punukulu </h3>
                <div class="price"> &#8377 70rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/half meals.jfif" alt="">
            <div class="content">
                <h3> Half Meals </h3>
                <div class="price">&#8377 80rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/full meals.jfif" alt="">
            <div class="content">
                <h3> Full Meals </h3>
                <div class="price"> &#8377 150rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/chicken dum biryani.jfif" alt="">
            <div class="content">
                <h3> Chicken Dum Biryani </h3>
                <div class="price"> &#8377 210rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/fry piece.jfif" alt="">
            <div class="content">
                <h3> Fry Piece Biryani </h3>
                <div class="price"> &#8377 200rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/bamboo.jfif" alt="">
            <div class="content">
                <h3> Bamboo Chicken Biryani</h3>
                <div class="price"> &#8377  220rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/tandoori.jfif" alt="">
            <div class="content">
                <h3> Tandoori Chicken</h3>
                <div class="price"> &#8377 200rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/mutton biryani.jfif" alt="">
            <div class="content">
                <h3> Mutton Biryani</h3>
                <div class="price"> &#8377 230rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/mutton curry.jfif" alt="">
            <div class="content">
                <h3> Mutton Curry</h3>
                <div class="price"> &#8377 200rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/mutton khurma.jfif" alt="">
            <div class="content">
                <h3> Mutton Khurma</h3>
                <div class="price">&#8377 200rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/mutton fry.jfif" alt="">
            <div class="content">
                <h3> Mutton Fry </h3>
                <div class="price"> &#8377 240rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/gongura mutton.jfif" alt="">
            <div class="content">
                <h3> Gongura Mutton</h3>
                <div class="price">&#8377  280rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/gongura chicken.jfif" alt="">
            <div class="content">
                <h3>Gongura Chicken</h3>
                <div class="price"> &#8377 250rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/veg biryani.jfif" alt="">
            <div class="content">
                <h3> Veg Biryani</h3>
                <div class="price">&#8377  150rs </div>
            </div>
        </a>

        
       

        <a href="#" class="box">
            <img src="image/veg pasta.jfif" alt="">
            <div class="content">
                <h3> Veg Pasta </h3>
                <div class="price"> &#8377 120rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/ice creams.jfif" alt="">
            <div class="content">
                <h3> Ice Creams ( All Flavours)</h3>
                <div class="price">&#8377  80rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/cold coffee.jfif" alt="">
            <div class="content">
                <h3> Cold Coffee </h3>
                <div class="price"> &#8377 70rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/hot coffee.jfif" alt="">
            <div class="content">
                <h3> Hot Coffee </h3>
                <div class="price">&#8377 50rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/sweet lassi.jfif" alt="">
            <div class="content">
                <h3> Sweet Lassi </h3>
                <div class="price">&#8377 50rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/salt lassi.jfif" alt="">
            <div class="content">
                <h3> Salt Lassi</h3>
                <div class="price">&#8377 50rs </div>
            </div>
        </a>

        
        <a href="#" class="box">
            <img src="image/special tea.jfif" alt="">
            <div class="content">
                <h3>Special Tea</h3>
                <div class="price"> &#8377 60rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/allam tea.jfif" alt="">
            <div class="content">
                <h3> Allam Tea</h3>
                <div class="price"> &#8377 70rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/badam milk.jfif" alt="">
            <div class="content">
                <h3> Badam Milk</h3>
                <div class="price"> &#8377 90rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/red bull.jfif" alt="">
            <div class="content">
                <h3> Red Bull</h3>
                <div class="price">&#8377 160rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/fruit beer.jfif" alt="">
            <div class="content">
                <h3> Fruit Beer</h3>
                <div class="price"> &#8377 140rs </div>
            </div>
        </a>

        <a href="#" class="box">
            <img src="image/all types of soft.jfif" alt="">
            <div class="content">
                <h3>  All types of Soft Drinks </h3>
                <div class="price"> &#8377 30rs </div>
            </div>
        </a>

        

    </div>

</section>


<section class="order" id="order">

    <div class="heading">
        <span> order now </span>
        <h3>fastest home delivery</h3>
        <span> <u> If we Dont deliver the food within the Delivery Time, you will get your money back along with Food. Delivery Time is <b> 20min - 40min </b> depends on distance.</u></span>
    </div>

    <div class="icons-container">

        <div class="icons">
            <img src="image/icon-1.png" alt="">
            <h3>07:00am to 10:30pm</h3>
        </div>

        <div class="icons">
            <img src="image/icon-2.png" alt="">
            <h3>+91-7993058602</h3>
        </div>

        <div class="icons">
            <img src="image/icon-3.png" alt="">
            <h3> Vishakapatnam - 531055</h3>
        </div>

    </div>

    <form action="">

        <div class="flex">
            <div class="inputBox">
                <span>your name</span>
                <input type="text" placeholder="Customer's name" name="" id="">
            </div>
            <div class="inputBox">
                <span>your Mobile number</span>
                <input type="number" placeholder="Customer's mobile number" name="" id="">
            </div>
        </div>

        <div class="flex">
            <div class="inputBox">
                <span>your order</span>
                <input type="text" placeholder="Food you want" name="" id="">
            </div>
            <div class="inputBox">
                <span>how much</span>
                <input type="number" placeholder= Quantity or orders" name="" id="">
            </div>
        </div>

        <div class="flex">
            <div class="inputBox">
                <span>Anything for us</span>
                <input type="text" placeholder="Your message" name="" id="">
            </div>
            <div class="inputBox">
                <span> You want Your Food Before </span>
                <input type="time">
            </div>
        </div>

        <div class="flex">
            <div class="inputBox">
                <span> Your Delivery Address</span>
                <textarea placeholder="Your address" id="" cols="30" rows="10"></textarea>
            </div>
            
        </div>

        <input type="submit" value="proceed to order" class="btn">

    </form>

</section>

<section class="about" id="about">

    <div class="image">
        <img src="image/thaali.png" alt="">
    </div>

    <div class="content">
        <span>why choose us?</span>
        <h3 class="title">what's make our Resturant Special!</h3>
        <p> <b>We have been Treating Every Customer in a Polite manner and we consider that customer is like a God Who gives us hope to earn big. Here we have been Providing Quality food.</p>
        <a href="#" class="btn">read more</a>
        <div class="icons-container">
            <div class="icons">
                <img src="image/serv-1.png" alt="">
                <h3>fast delivery</h3>
            </div>  
            <div class="icons">
                <img src="image/serv-2.png" alt="">
                <h3>fresh food</h3>
            </div>   
            <div class="icons">
                <img src="image/serv-3.png" alt="">
                <h3>best quality</h3>
            </div>  
                       
        </div>
    </div>

</section>




<

<section class="footer">

    <div class="newsletter">
        <h3>newsletter</h3>
        <form action="">
            <input type="email" name="" placeholder="Enter your email" id="">
            <input type="submit" value="subscribe">
        </form>
    </div>

    <div class="box-container">

        <div class="box">
            <h3>our menu</h3>
            <a href="#"><i class="fas fa-arrow-right"></i> pizza</a>
            <a href="#"><i class="fas fa-arrow-right"></i> burger</a>
            <a href="#"><i class="fas fa-arrow-right"></i> chicken</a>
            <a href="#"><i class="fas fa-arrow-right"></i> pasta</a>
            <a href="#"><i class="fas fa-arrow-right"></i> and more...</a>
        </div>

        <div class="box">
            <h3>quick links</h3>
            <a href="#home"> <i class="fas fa-arrow-right"></i> home </a>
            <a href="#popular"> <i class="fas fa-arrow-right"></i> popular</a>
            <a href="#menu"> <i class="fas fa-arrow-right"></i> menu </a>
            <a href="#order"> <i class="fas fa-arrow-right"></i> order</a>
            <a href="#about"> <i class="fas fa-arrow-right"></i> about</a>
        </div>

        <div class="box">
            <h3>extra links</h3>
            <a href="#"> <i class="fas fa-arrow-right"></i> my order</a>
            <a href="#"> <i class="fas fa-arrow-right"></i> my account</a>
            <a href="#"> <i class="fas fa-arrow-right"></i> my favorite</a>
            <a href="#"> <i class="fas fa-arrow-right"></i> terms of use</a>
            <a href="#"> <i class="fas fa-arrow-right"></i> privary policy</a>
        </div>

        <div class="box">
            <h3>opening hours</h3>
            <p>monday : 7:00am to 10:00pm</p>
            <p>tuesday : 7:00am to 10:00pm</p>
            <p>wednesday : 7:00am to 10:00pm</p>
            <P>Thursday : 7:00am to 10:00pm</P>
            <p>friday : 7:00am to 10:00pm</p>
            <p><b>saturday and sunday Closed</b></p>
        </div>

    </div>

    <div class="bottom">

        <div class="share">
            <a href="#" class="fab fa-facebook-f"></a>
            <a href="#" class="fab fa-twitter"></a>
            <a href="#" class="fab fa-instagram"></a>
            <a href="#" class="fab fa-linkedin"></a>
            <a href="#" class="fab fa-whatsapp"></a>
        </div>

        <div class="credit"> created By <span><b>Jagadeesh Dowluri</b></span> | all rights reserved! </div>
        
    </div>

</section>

<script src="script.js"></script>


</body>
</html>

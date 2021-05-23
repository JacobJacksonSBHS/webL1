CONTACT
<!doctype html>
<head>
    <title>Classic socks</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <nav>
        <div class="links">
            <a href="index.html">Home</a>
            <a href="Shop.html">Shop</a>
            <a href="contact.html">Contact</a>
            <a href="Sizing.html">Sizing</a>
        </div>
        <img class="logo" src="websiteclassiclogo.png" alt="logo">  
    </nav>

    <section >  

    </section>
           <h1>Contact Us</h1>
    <p>Email us - Classicemail@gmail.com<br>
    Call us NZ - 03-211 3003</p>  
</body>

INDEX
<!doctype html>

<head>
    <title>Classic socks</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <nav>
        <div class="links">
            <a href="index.html">Home</a>
            <a href="Shop.html">Shop</a>
            <a href="contact.html">Contact</a>
            <a href="Sizing.html">Sizing</a>
        </div>
        <img class="logo" src="websiteclassiclogo.png" alt="logo">
    </nav>
    <section>
        <div class="info">
            <h1>New Products!<br>Welcome to classic socks please buy the new hoodie because its great
            </h1>
        </div>



        <img class="promo" src="classic%20sock%20hoodie.png" alt="promohoodie">





    </section>
</body>

<!doctype html>

<head>
    <title>Classic socks</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <nav>
        <div class="links">
            <a href="index.html">Home</a>
            <a href="Shop.html">Shop</a>
            <a href="contact.html">Contact</a>
            <a href="Sizing.html">Sizing</a>
        </div>
        <img class="logo" src="websiteclassiclogo.png" alt="logo">
    </nav>
    <section>
        <h1>Welcome To Classic Shop</h1>
        <ul class="shop">
            <li>
                <img class="products" src="classic%20sock%20hoodie.png" alt="Classic Hoodie">
                <h1>Classic Hoodie</h1>
                <p>$99</p>
            </li>
            <li>
                <img class="products" src="white%20glove.png"    alt="classic glove">
                <h1>Classic Gloves</h1>
                <p>$29.9</p>
            </li>
            <li>
                <img class="products" src="sock%20glow.png" alt="Classic Socks">
                <h1>Classic Socks</h1>
                <p>$25</p>
            </li>
            <li>
                <img class="products" src="combat%20vest.png"  alt="combat vest">
                <h1>Classic Combat Vest</h1>
                <p>$149</p>
            </li>
        </ul>
    </section>
</body>

SIZING
<!doctype html>

<head>
    <title>Classic socks</title>
    <link rel="stylesheet" href="styles.css">

    <script>
        function calulate() {
            var data = document.getElementById("neck").value;
            if (data <= 15) {
                document.getElementById("answer").innerHTML = 'You are smaller than the smallest size';
            }
            if (data >= 15 && data < 15.5) {
                document.getElementById("answer").innerHTML = 'Your size is S';
            }
            if (data >= 15.5 && data < 15.75) {
                document.getElementById("answer").innerHTML = 'Your size is M';
            }
            if (data >= 16 && data < 16.5) {
                document.getElementById("answer").innerHTML = 'Your size is L';
            }
            if (data >= 17 && data < 17.5) {
                document.getElementById("answer").innerHTML = 'Your size is XL';
            }
            if (data >= 18 && data < 18.5) {
                document.getElementById("answer").innerHTML = 'Your size is XXL';
            }
            if (data >= 18.5) {
                document.getElementById("answer").innerHTML = 'You are bigger than the biggest size';
            }
        }

    </script>
</head>

<body>
    <nav>
        <div class="links">
            <a href="index.html">Home</a>
            <a href="Shop.html">Shop</a>
            <a href="contact.html">Contact</a>
            <a href="Sizing.html">Sizing</a>
        </div>
        <img class="logo" src="websiteclassiclogo.png" alt="logo">
        <div class="size">
           
            <input type="number" name="size" id="neck">
            <button type="submit" onclick="calulate()">Submit</button>
            <p id='answer'></p>
        </div>
   
    </nav>
     <h1> Neck Size Calculator</h1>
        <p>Please enter your neck circumfrence (inches),<br>
        to get your size in tshirt, hoodie and vest</p>
        <p>Gloves size length - Small 8 inch
                               - large 10 inch
            <br>Sock Sizing
            MEDIUM: Suitable for a Men's (US) Shoe Size 6 - 8.5<br>
            LARGE: Suitable for a Men's (US) Shoe Size 9 - 13 </p>
    <section>

    </section>
</body>
  STYLES
      * {
    margin: 0px;
    padding: 0px;
}

html {
    /*   background: rgb(255,113,41);*/
    background: linear-gradient(0deg, rgba(255, 113, 41, 1) 0%, rgba(47, 47, 43, 1) 77%);
    height: 100vh;
    font-family: 'blanchope';
    color: #ff7129;
    font-size: 25px;

}

nav {
    display: grid;
    grid-template-columns: 1fr 1fr;
    align-items: center;
    color: #2f2f2b;
    font-family: "blanchope";
    font-size: 45px;
    text-shadow:
        -1px -1px 0 #ff7129,
        1px -1px 0 #ff7129,
        -1px 1px 0 #ff7129,
        1px 1px 0 #ff7129;

}

.logo {
    grid-column: 2/3;
    width: 20%;
    justify-self: end;

}


section {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-column: 2/6;
    grid-row: 2/3;
    width: 70%;
    margin: 20px auto;
    background-color: #2f2f2b;
    box-shadow: 1px 1px 2px #ff914d, 0 0 45px #ff914d, 0 0 10px #ff914d;
    color: #ff914d;
    font-family: "blanchope";

}




.promo {
    grid-column: 2/2;

    z-index: 1;
    justify-self: center;
}

a {
    color: #2f2f2b;
}

.info {
    font-family: "blanchope";
    color: #ff7129;
    font-size: 40px;
    border-right: 4px solid #ff914d;
    margin: 15px;
    margin-left: 50px;


}

a:hover {
    color: #ff7129;
}

.products {
  
     

}
li img{
    width: 60%;
    
   
        
}
li {
    list-style: none;
}
.shop{
    grid-column: 1/3;
    display: grid;
    grid-template-columns: 1fr 1fr;

}

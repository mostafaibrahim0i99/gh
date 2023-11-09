<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="css.css">

    <title>Document</title>
    <link rel="stylesheet" media="screen and (max-width: 600px)" href="smallscreen.css">
</head>
<body>
    <div class="nav">
        <a href="#home" id="o"> Gourmet au Catering</a>
        <a href="#Projects" id="n">About</a>
        <a href="#about">Menu</a>
        <a href="#Contaact">Contact</a>
    </div>
    <div class="header" id="home">
        <img src="hamburger.jpg" alt="">
    </div>
    <div class="about" >
        <br>
        <br>
        <br>
        <br>
        <div class="main" id="Projects" >
        
            <div class="imag">
                <img src="tablesetting2.jpg" alt="">

            </div>
            <div class="text">
                <h1>About Catering</h1>
                <h2>Tradition since 1889</h2>
                <p>The Catering was founded in blabla by Mr. Smith in lorem ipsum dolor sit amet, consectetur adipiscing elit consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute iruredolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.We only use seasonal ingredients Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod temporincididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
            </div>
        </div>
    </div>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <div class="about1" id="about">
        <br>
        <br>
        <br>
        <br>
        <div class="main1">
        
            <div class="text1">
                <h1>Our Menu</h1>
                <h3>Bread Basket</h3>
                <p>Assortment of fresh baked fruit breads and muffins 5.50</p>
                <h3>Honey Almond Granola with Fruits</h3>
                <p>Natural cereal of honey toasted oats, raisins, almonds and dates 7.00</p>
                <h3>Belgian Waffle</h3>
                <p>Vanilla flavored batter with malted flour 7.50</p>
                <h3>Scrambled eggs</h3>
                <p>Scrambled eggs, roasted red pepper and garlic, with green onions 7.50</p>
                <h3>Blueberry Pancakes</h3>
                <p>With syrup, butter and lots of berries 8.50</p>
            </div>
            <div class="imag1">
                <img src="tablesetting.jpg" alt="">

            </div>
        </div>
    </div>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <div class="about2">
        <br>
        <br>
        <br>
        <br>
        <div class="main2">
        
            <div class="text2">
                <h1>Contact</h1>
                <p>We offer full-service catering for any event, large or small. We understand your needs and we will cater the food to satisfy the biggerst criteria of them all, both look and taste. Do not hesitate to contact us.</p>
                <h3>Catering Service, 42nd Living St, 43043 New York, NY</h3>
                
                <p>You can also contact us by phone 00553123-2323 or email catering@catering.com, or you can send us a message here:</p>

            </div>

        </div>
    </div>
    <div class="about3" >
        <br>
        <br>
        <br>
        <br>
        <div class="main3" id="Contaact">
        
            <div class="text3">
                <input type="text" placeholder="Name">
                <br>
                <br>
                <input type="number" placeholder="How many people">
                <br>
                <br>
                <input type="date" placeholder="date and timeWWW">
                <br>
                <br>
                <input type="text" placeholder="message/special requirements">
                <br>
                <br>
                <button id="btton">SEND MESSAGE</button>

            </div>

        </div>
    </div>
    <footer>
    <br>
    <br>
    <br>
    <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp">w3.css</a></p>
    </footer>
style{
    *{
    padding: 0;
    margin: 0;
}
.nav{
    width: 100%;
    height: 50px;
    position: fixed;
    background-color:#fff;
    box-shadow: 0 2px 5px 0 rgba(0,0,0,0.16), 0 2px 10px 0 rgba(0,0,0,0.12);
    display: flex;
    z-index: 5;

}
.nav   a{
    text-decoration: none;
    color: #000;
    padding: 14px 24px;
    font-family: "Lato", sans-serif; 
    font-size: 15px;
    text-align: center;
    letter-spacing: 4px;
}




.nav  a:hover{
    background-color: gray;
    padding: 14px 24px;
    text-align: center;
    text-decoration: none;
    color: inherit;
    font-family: "Lato", sans-serif; 

    text-align: center;                                 
    cursor: pointer;
    font-size: 15px;


}

 #o{
    margin-right: 910px;
    padding: 14px 4px;
    font-family: Verdana,sans-serif;
    letter-spacing: 4px

}
.header{
    width: 100%;
    height: 100vh;
}
.header img{
    width: 100%;

}
.about{
    width: 100%;
    height: 100vh;

}
.about  .main{
    height: 100%;
    width: 70%;
    margin: auto;
    display: flex;
}
.about .main .image img{
    width: 100%;
    
    margin-bottom:50px;

}
.about .main .text p{
     margin-left: 50px;
}
.about .main .text h1{
    margin-left: 50px;
}
.about .main .text h2{
    font-family: "Playfair Display";
    letter-spacing: 5px;
    text-align: center!important;
    font-weight: 400;
    margin: 30px 0;

}
.about1{
    width: 100%;
    height: 100vh;

}
.about1  .main1{
    height: 100%;
    width: 70%;
    margin: auto;
    display: flex;
}
.about1 .main1 .image1 img{
    width: 100%;
    
    margin-bottom:50px;

}

.about1 .main1 .text1 h3{
    font-family: "Segoe UI",Arial,sans-serif;
    font-family: "Playfair Display";
    letter-spacing: 5px;

    margin: 10px ;
}
.about1 .main1 .text1 p{
color: #757575!important;
box-sizing: inherit;
margin: 40px;


}
.about .main .text h1{    
    font-size: 36px;
    font-weight: 400;
    margin: 10px 0;
    font-family: "Playfair Display";
    letter-spacing: 5px;
    text-align: center!important;
}
.about1 .main1 .text1 h1{    
    font-size: 36px;
    font-weight: 400;
    margin: 30px ;
    font-family: "Playfair Display";
    letter-spacing: 5px;
    text-align: center!important;
}
.about .main .text p{
    box-sizing: inherit;
    font-size: 18px!important;
}
.about2{
    width: 100%;
    height: 30vh;

}
.about2  .main2{
    height: 100%;
    width: 70%;
    margin: auto;
    display: flex;
}
.about2 .main2 .text2 h3{
    color: #607d8b!important;
    
}
.about2 .main2 .text2 h1{
font-family: "Playfair Display";
letter-spacing: 5px;
font-weight: 400;
margin: 10px 0;
font-size: 36px;
}
.about3 .main3 .text3 input{
    width: 100%;
    height:  50px;
    border: none;
    border-bottom: 1px solid #ccc;
}
#btton{
    color: #000!important;
    background-color: #f1f1f1;
    margin-top: 16px!important;
    margin-bottom: 16px!important;
    font: inherit;
    white-space: nowrap;
    font-family: "Times New Roman", Georgia, Serif;
    height: 50px;
    width: 150px;
    border: none;
}
#btton:hover{
    background-color: gray;
}
.about3{
    width: 100%;
    height: 70vh;

}
.about3  .main3{
    height: 100%;
    width: 70%;
    margin: auto;
    display: flex;
}
.about3  .main3 .text3{
    height: 100%;
    width: 100%;

}
footer{
    width: 100%;
    height: 20vh;
    background-color: #f1f1f1;
    text-align: center;
}
footer p a{
    color: #000;

}
footer p a:hover{
    color: lightgreen;
}
@media only screen and (max-device-width:1129px) {
     #o{
    margin-right: 380px;
    padding: 14px 4px;
    font-family: Verdana,sans-serif;
    letter-spacing: 4px

    }
    .header {
        width: 100%;
        height: auto
    }
    .header img{
        width: 100%;
    
    }
    .about{
        width: 100%;
        height: auto;
        display: block;
    }
    .about  .main{
        width: 70%;
        margin: auto;
        display: block;
        flex-wrap:wrap ;
    }
    .about .main .image img{
        width: 100%;
        
        margin-bottom:50px;
    
    }
    .about .main .text p{
         margin-left: 50px;
    }
    .about .main .text h1{
        margin-left: 50px;
    }
    .about .main .text h2{
        font-family: "Playfair Display";
        letter-spacing: 5px;
        text-align: center!important;
        font-weight: 400;
        margin: 30px 0;
    
    }
    .about .main .text p{
        box-sizing: inherit;
        font-size: 18px!important;
    }
    .about1{
        width: 100%;
        height: auto;
    
    }
    .about1  .main1{
        height: auto;
        width: 70%;
        margin: auto;
        display: block;
        flex-wrap: wrap;
    }
    .about2{
    width: 100%;
    height: auto;

    }
    .about2  .main2{
    height: 100%;
    width: 70%;
    margin: auto;
    display: flex;
    }
    .about2 .main2 .text2 h3{
    color: #607d8b!important;
    
    }
    .about2 .main2 .text2 h1{
    font-family: "Playfair Display";
    letter-spacing: 5px;
    font-weight: 400;
    margin: 10px 0;
    font-size: 36px;
    }
    .about3{
    width: 100%;
    height: auto;

    }
    .about3  .main3{
    height: 100%;
    width: 70%;
    margin: auto;
    display: flex;
    }
    .about3  .main3 .text3{
    height: 100%;
    width: 100%;

    }
    #btton{
        color: #000!important;
        background-color: #f1f1f1;
        margin-top: 16px!important;
        margin-bottom: 16px!important;
        font: inherit;
        white-space: nowrap;
        font-family: "Times New Roman", Georgia, Serif;
        height: 50px;
        width: 150px;
        border: none;
        margin-bottom: 300px;
    }
}
@media only screen and (min-device-width:320px) and (max-device-width:720px) {
     #o{
    margin-right: 370px;
    padding: 14px 4px;
    font-family: Verdana,sans-serif;
    letter-spacing: 4px

    }
    .header {
        width: 100%;
        height: auto
    }
    .header img{
        width: 100%;
    
    }
    .about{
        width: 100%;
        height: auto;
        display: block;
    }
    .about  .main{
        width: 70%;
        margin: auto;
        display: block;
        flex-wrap:wrap ;
    }
    .about .main .image img{
        width: 100%;
        
        margin-bottom:50px;
    
    }
    .about .main .text p{
         margin-left: 50px;
    }
    .about .main .text h1{
        margin-left: 50px;
    }
    .about .main .text h2{
        font-family: "Playfair Display";
        letter-spacing: 5px;
        text-align: center!important;
        font-weight: 400;
        margin: 30px 0;
    
    }
    .about .main .text p{
        box-sizing: inherit;
        font-size: 18px!important;
    }
    .about1{
        width: 100%;
        height: auto;
    
    }
    .about1  .main1{
        height: auto;
        width: 70%;
        margin: auto;
        display: block;
        flex-wrap: wrap;
    }
    .about2{
    width: 100%;
    height: auto;

    }
    .about2  .main2{
    height: 100%;
    width: 70%;
    margin: auto;
    display: flex;
    }
    .about2 .main2 .text2 h3{
    color: #607d8b!important;
    
    }
    .about2 .main2 .text2 h1{
    font-family: "Playfair Display";
    letter-spacing: 5px;
    font-weight: 400;
    margin: 10px 0;
    font-size: 36px;
    }
    .about3{
    width: 100%;
    height: auto;

    }
    .about3  .main3{
    height: 100%;
    width: 70%;
    margin: auto;
    display: flex;
    }
    .about3  .main3 .text3{
    height: 100%;
    width: 100%;

    }
}
}
</body>
</html>

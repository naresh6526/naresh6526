<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Virtual credit Card Design</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <div class="card">
            <div class="card-inner">
                <div class="front">
                    <h1>Bank of India</h1>
                    <div class="row">
                        <img src="images/chip.png" alt="" width="70px">
                        <img src="images/master-logo.png" alt="" width="90px">
                    </div>
                    <div class="row card-number">
                        <p>5244</p>
                        <p>2150</p>
                        <p>5244</p>
                        <p>3425</p>
                    </div>
                    <div class="row card-holder">
                        <p>Card Holder Name</p>
                        <p>Expire Date</p>
                    </div>
                    <div class="row card-name">
                        <p>DHARAVATH NARESH</p>
                        <p>06/29</p>
                    </div>
                    <p class="debit">Debit card</p>
                </div>
                <div class="back">
                    <div class="bar"></div>
                    <div class="row card-cvv">
                        <div>
                            <img src="images/pattern.png" alt="">
                        </div>
                        <p>503</p>
                    </div>
                    <div class="row card-text">
                        <p>Now a global payment technology platform, Mastercard brands prepaid, debit, and credit cards in addition to offering a range of business and finance services globally. At the end of December 2020</p>
                    </div>
                    <div class="row SIGNATURE">
                        <p>CUSTOMER SIGNATURE</p>
                        <img src="images/master-logo.png" alt="" width="80px">
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>


css


@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');

*{
    padding: 0;
    margin: 0;
    font-family: "Josefin Sans", sans-serif;
    box-sizing: border-box;

}

.container{
    min-height: 100vh;
    width: 100%;
    background: #000;
    display: flex;
    align-items: center;
    justify-content: center;
}

.card{
    width: 500px;
    height: 300px;
    color: #ffff;
    cursor: pointer;
    perspective: 1000px;
}

.card-inner{
    width: 100%;
    height:100% ;
    position: relative;
    transition:transform 1s;
    transform-style:preserve-3d ;
}

.front, .back{
    width: 100%;
    height: 100%;
   
    background-color: rgb(95, 137, 160);
    position: absolute;
    top: 0;
    left: 0;
    padding: 20px 30px;
    border-radius: 15px;
    overflow: hidden;
    z-index:1;
    backface-visibility: hidden;

}
.row{
    display: flex;
    align-items: center;
    justify-content: space-between;
 
}
.card-logo{
    width: 200px;
    height: 200px;
}

.map-img{
    width: 100%;
    position: absolute;
    top: 0;
    left: 0;
    opacity: 0.3;
    z-index: -1;
}

.card-number{
    font-family: "Roboto";
    font-size: 30px;
    margin-top: 30px;
}
.debit{
    display: flex;
    justify-content: flex-end;
}
.card-holder{
    font-size: 20px;
    margin-top: 30px;
    min-width: 200px;
}

.card-name{
    font-size:20px;
    margin-top: 15px;
}

.bar{
    background-color: #000;
    margin-left: -30px;
    margin-right: -30px;
    height:57px ;
    margin-top: 20px;
}

.card-cvv{
    margin-top: 20px;

}
.card-cvv div{
    flex: 1;
}
.card-cvv img{
    width: 100%;
    display: block;
    line-height:0 ;

}

.card-cvv p{
    background-color: #fff;
    color: #000;
    font-size: 22px;
    padding: 10px 20px;

}

.card-text{
   margin-top: 15px;
   font-size: 12px;
   font-family: "Roboto";
}

.SIGNATURE{
    margin-top: 10px;
    font-size: 10px;
    font-weight: 500;

}

.back{
    transform:rotateY(180deg);
}

.card:hover .card-inner{
    transform: rotateY(180deg);
}

C:\Users\dell\html css\images

![image](https://github.com/user-attachments/assets/e42dbc26-0120-47f2-8643-b19038453e88)

![image](https://github.com/user-attachments/assets/eb4fb806-39ae-4742-bec4-4fc39c7e25fb)

![image](https://github.com/user-attachments/assets/97a77a11-8d51-4085-b4c8-6bf866697725)

![image](https://github.com/user-attachments/assets/f3e99ca3-dcbd-4b7a-a957-83fe7d381708)








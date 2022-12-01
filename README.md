# Web-development-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Indie+Flower&family=Nanum+Gothic:wght@700&display=swap" rel="stylesheet">
    <title>website</title>
    <style>
        *{
            margin: 0%;
            flex-wrap: wrap;
            
        }
        .marleft{
            margin-top: 30px;
            margin-left:25px;
        }
        .formbox{
           
            flex-wrap: wrap;
            background-color: grey;
            /* height:580px;
            width:350px; */
            position: absolute;
            left: 150px;
            border-radius:20px ;
            top:200px;
            background-color: transparent;
            color:white;
            /* box-shadow: black; */
            width: 350px;
            height: 550px;
            /* background-color:s rgba(41, 39, 39, 0.3); */
            box-shadow: 0 5px 70px black;
            /* text-align: center; */
            /* background-color:rgb(165, 142, 84); */

            
        }
        

            /* width: 350px;
  height: 450px;
  background-color:s rgba(41, 39, 39, 0.3);
  box-shadow: 0 5px 30px black; */
        
    #submit:hover{

        background-color: black;
            color: aliceblue;
            font-weight: 100;
            /* font-weight: 600;
            margin-top: 120px;
            margin-left:120px;
            border-radius:15px;
            height: 60px;
            width:170px */
            
        /* background-color: #fff; */
    }
        ul{
            /* margin-top: ; */
            position: absolute;
            display: grid;
            margin-top:-65px ;
            /* display: inline; */
            margin-left: 30%;
            grid-template-columns: repeat(5,auto);
            padding: 40px;
            /* right:300px; */

        }
        a{
            text-decoration: none;
            color: rgb(7, 3, 0);
            font-weight: bold;
            

        }
        a:hover{
            border: 1px solid white ;
            border-width: 3px;
            /* border-bottom: 3px solid white  ; */
            font-weight: 500;
            background-color: transparent;
            box-shadow: 0px 2px 20px #021e37 ;
            /* border-radius: 20%; */
            
        }
        input:hover{
            font-weight: bold;
            border: 2px solid #021e37;
            box-shadow: 2px 2px 50px #021e37 ;
             
        }
        li{
            /* #337ab7 */
            display: inline;
            padding: 20px;
            text-transform: uppercase;
            font-family: 'Indie Flower', cursive;
            font-size: 25px ;

            
           
        }
        .navbar>img{
            
            /* border: 2px solid red;
            height: 3rem; */
           width:100px;
           height: 60px;
           border-radius:50px;
           margin-top:-4.5px;
           
        }
        .input{
            
            
            height: 50px;
            border-radius: 15px;
            background-color: transparent;
            box-shadow: black;
            background-color:antiquewhite;
            border: none;
            box-shadow: 0 5px 20px rgb(66, 66, 18);
            font-weight: 900;
           
           
            

            
        }
        .input2{

            height: 50px;
            border-radius: 15px;
            background-color:antiquewhite;
            border: none;
            width: 49%;
            margin-top: 19px;
            box-shadow: 0 5px 20px rgb(66, 66, 18);
            
            font-weight: bolder;

        }
        select{
            /* font-family: 'Nanum Gothic', sans-serif; */
            background-color: antiquewhite;
            box-shadow: 0 5px 20px rgb(66, 66, 18);
            margin-left: 7%;
            border-radius:15px;
            height: 50px;
            width:115px
           
            
            /* margin-left: 65%; */
            

            
        }
        select:hover{
            font-weight: 600

        }
        
        .input,.input2:hover{
            font-weight: 700;
            
        }
        .date{
            background-color: antiquewhite;
            border-radius:15px;
            height: 50px;
            margin-left: 7%;
            box-shadow: 0 5px 20px rgb(66, 66, 18);

        }
        #submit{
            background-color: black;
            color: aliceblue;
            font-weight: 600;
            margin-top: 30px;
            margin-left:100px;
            border-radius:15px;
            height: 40px;
            width:150px;
            border: none;
            box-shadow: 0 5px 20px rgb(66, 66, 18);

            

        }
        h1{
            margin-left: 20px;
            
            /* background-color: orange */
            font-family: 'Indie Flower', cursive;
        font-family: 'Nanum Gothic', sans-serif;
            
        }
        h1>span{
            margin-left: 100px;
        }
        .boot{
            margin-top: -30px;
        }
        .headin1{
            text-align: center;
            background-color: white!important;
            color: #337ab7;
            /* border-color: #337ab7 !important;
            color: azure; */

            margin: 0%;
            
            height: 100px;
            font-size:40px;
            font-weight: 700;
            

        }
        .kunal{
            position:absolute;
            top: 10px;
            
        }
        .headin1{
            margin-left: -600px;
            font-family: 'Nanum Gothic', sans-serif;
            color:#2c5476;
            
        }
        .footer1,.footer2,.footer3{
            width: 400px;
           height: 400px;
           background-color: black;
           margin: 2px;
           }
        
            

        
        .mainfooter{
            display: grid;
            /* justify-content: center; */
            margin-top: 100px;
            /* margin-right: */
            grid-template-columns:0.5fr 0.5fr 1fr ;
            margin-left:150px;
        }
        .footup{
            text-align: center;
            
        }

        
    </style>
</head>
<body><div class="cont1">
    <nav class="navbar">
        <h2 class="headin1">Indian Railway Reservation system </h2>
        <img class = 'kunal'src="https://us.123rf.com/450wm/yaydesign/yaydesign2106/yaydesign210600198/yaydesign210600198.jpg?ver=6" alt="">
        
        
        <ul>
            <li><a href="home.html">Home</a></li>
            <li><a href="meals.html">Meals</a></li>
            <li><a href="Holiday.html">Holiday Package</a></li>
            <li><a href="Service.html">Service station</a></li>
            <li><a href="Contactus.html">Contact Us</a></li>
        </ul>

    </div>
    </nav>
    
    <div class="boot">
        
        <img src="https://images.unsplash.com/photo-1601999007938-f584b47324ac?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1935&q=80" width="1535"height="700px" alt="">
        
        <video src="https://youtu.be/E1Oa-eX8Uyo"></video>
    </div>
    
   
   
    <div class="formbox">
    <!-- <div class="form"> -->
        <form action="">
        <h1 class="spa">Book
             Your <br><span>Ticket</span> here..</h1>
<form action="">
<div class="marleft">
    <input class="input"type="text" placeholder="From" >
    <br>
    <input class="input2"type="text" placeholder="To">
</div>
     
     
     <br>
     <br>
     

     <input class="date" type="date">
     <br>
     <br>
     <select name="selct" id="select" value="All classes">

    
        <!-- <optgroup label="All classes"> -->
        <option value="All classes">All classes</option>
        <option value="Phagwara">Phagwara</option>
        <option value="Phagwara">Phagwara</option>
        <option value="Phagwara">Phagwara</option>
        <option value="Phagwara">Phagwara</option>
        <option value="Phagwara">Phagwara</option>
        <option value="Phagwara">Phagwara</option>
        <option value="Phagwara">Phagwara</option>
        
     </select>
     <br>
     <br>
     <br>
     <input id="submit"type="submit" value="Find Trains">
     </form>
    </div>
<div class="footup"><h1>Holiday Packages</h1></div>
<footer class="mainfooter">
    
    <div class="footer1"><img src="https://img.republicworld.com/republic-prod/stories/promolarge/xhdpi/whzmbaslkninfxwv_1568293856.jpeg" width="400px" height="400px" alt=""></div>
    <div class="footer2"><img src="https://img.republicworld.com/republic-prod/stories/promolarge/xhdpi/whzmbaslkninfxwv_1568293856.jpeg"
        width="400px" height="400px" alt=""></div>
    <div class="footer3"><img src="https://img.republicworld.com/republic-prod/stories/promolarge/xhdpi/whzmbaslkninfxwv_1568293856.jpeg"
        width="400px" height="400px" alt=""></div>
</footer>
     
</body>
</html>

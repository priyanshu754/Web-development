# Web-development
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sanjeev - Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
        }
        body {
            background-color: #000021; /* Dark blue color */
            color: white;
            font-family: 'Poppins', sans-serif;
        }
        nav{
            display:flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(18, 18, 62);
        }
         nav ul{
            display: flex;
            justify-content: center;
         }  
         nav ul li {
            list-style: none;
            margin: 0 23px;
         }
        nav ul li a{
           text-decoration: none;
           color: white;
        }

        
        nav ul li a:hover{
        color: lavender;
        font-size: 1.04rem;
        }
main hr{
    border: 0;
    background: #9c97f1;
    height: 1.2px;
    margin: 60px 84px;
}
        .left{
            font-size: 1.5rem;
        }
        .firstSection{
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 130px 0; 

        }
        .firstSection >div{
          width: 30%;  
        }
        


        .leftSection{
            font-size:2.5rem ; 
         
        }
        .rightSection img{
            width: 80%;
        }
       
      
      .purple{
        color: rgb(155, 85, 221);
      }
      .text-gray{
        color: gray;
      }
      #element{
         color:rgb(155, 85, 221);
      }
      .secondSection{
        max-width:80vw;
        margin: auto;
        height:80vh ;
      }
      .secondSection h1{
        font-size: 1.9rem;
      }
      .secondSection .box{
        width: 77vw;
        background: white;
        height: 2px;
        margin: 56px 0;
        display: flex;
      }
      .secondSection .vertical{
        height:93px  ;
        width: 1px;
        background-color: white;
        margin: 0 140px;
      }
.image-top{
    width: 40px;
    position: relative;
    top: -40px;
    left: -9px;
}
      .vertical-title{
          position: relative;
          top: 75px;
          width: 150px;
          font-size: 14px;
      }
      .vertical-desc{
   position: relative;
   top: 86px;
   color: gray;
   width: 150px;
   font-size: 9px;


}

    </style>
</head>

<body>
    <header>
        <nav>
            <div class="left">Sanjeev's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="/">About</a></li>
                    <li><a href="/">Services</a></li>
                    <li><a href="/">Projects</a></li>
                    <li><a href="/">Contact Me</a></li>
                </ul>
            </div>
        </nav>
    </header>
 <main> 
    <section class="firstSection">
        <div class="leftSection"> 
            Hi, My Name is <span class="purple"> sanjeev</span>
            <div>and I am a Passionate </div>
        <!-- <div>  Web Developer </div>-->
            <span id="element"></span>
        </div> 
        <div class="rightSection">
            <img src="bg.png.webp" alt="error">
        </div>
    </section>
<hr>
    <section class="secondSection">
        <span class="text-gray">What i have done so far</span>
        <h1>Work Experience </h1>
        <div class="box">
          <div class="vertical">
            <img class="image-top"  src="bg.png.webp" alt="error" >
            <div class="vertical-title">
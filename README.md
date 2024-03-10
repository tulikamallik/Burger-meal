# Burger-meal
{
    margin: 0;
    padding: 0;
    font-family:  'Trebuchet MS','lucinda Sans Unicode','lucinda Grande','Lucinda Sans','Arial', sans-serif;
    box-sizing: border-box;
}
html,body{
   width: 100%;
   height: 100;
}
#main{
   width: 100%;
   min-height:100vh ;
}
.top{
   width: 100%;
   min-height: 60vh;
   background-image: url(https://th.bing.com/th/id/OIP.38brhG9oI6rtMgaIJmRYLwHaE7?rs=1&pid=ImgDetMain);
   background-size: cover;
   background-position: center;


}
.top .overlay{
   width:100% ;
   min-height: inherit;
   background-image: url(https://th.bing.com/th/id/OIP.cmw97_UvZNt5ObDvet85eAHaJl?rs=1&pid=ImgDetMain);
   background-size: cover;
   background-position: center;
}
.text{
   display: flex;
   justify-content:space-between ;
   align-items: center;
   position: absolute;
   width: 100%;
   padding:0 10vh;
   color: white;
   bottom: 5%;
}
.text h1{
   font-height: 600;
   font-size: 4vw;
   text-decoration-color: white;
}
.text .image{
   background-image: url(https://i.pinimg.com/564x/a8/e4/67/a8e46738ce2fe13e83c3e3f548214405.jpg);
   background-size: cover;
   background-position: center;
   height: 300px;
   width: 220 px;

}
.rtext{
   display: flex;
   width: 25%;
   align-items: center;
   justify-content: space-between;

}
.rtext p{
   font-size: 12px;
}

.bottom{
   display: flex;
   width: 100%;
   min-height: 40vh;
}
.b1{
   width: 30%;
   min-height: inherit;
   background-image: url(https://th.bing.com/th/id/OIP.Wsd31ToL1mhVHPP0m5W6ewHaFj?rs=1&pid=ImgDetMain);
   background-size: cover;
   background-position: center;
}
.b1 h1{
   text-align: center;
   padding: 30px;
}
.b1 p{
     color: white;
     text-align: center;
     padding: 15px;
}
.b2{
    width: 30%;
    min-height: inherit;
    display:flex ;
    flex-direction: column;
}
.b2 up{
     width: 100%;
     min-height: 20vh; 
     background-image: url(https://th.bing.com/th/id/OIP.uEFP1s8Fc_jYbD2Nxxg-BAHaEo?rs=1&pid=ImgDetMain);
     background-size: cover;
     background-position: center;
}
.b2 .up h1{
   text-align: center;
   padding: 30px;
}
.b2.up p{
   color: white;
   text-align: center;
   padding: 15px;
} 
.b2.down{
   width:20vh ;
   min-height: 20vh;
   background-image: url(https://wallpapercave.com/wp/wp4889244.jpg);
   background-size:cover ;
   background-position: center;

}
.b2.down.overlay{
   position: relative;
   width: 100%;
   min-height: 20vh;
   background-color: rgba(255, 255, 255, 0.342);

}
.b3{  
     width: 40%;
     min-height: inherit;
     background-image: url(https://wallpapercave.com/wp/wp4889244.jpg));
     background-size: cover;
     background-position: center;

}
.b3 .overlay{
   justify-content: right;
   position: relative;
   margin-left: 50%;
   width: 50%;
   height: 100%;
   padding: 4vw 3vh;
}
.b3 .overlay p{
   padding: 1.2vh;
}
@media(max-width:700px){
   .rtext{
       flex-direction: column;
   }
   .b3 .overlay{
       width: 100%;
       margin-left: initial;
   }
}
@media(max-width:500px){
   .text{
       flex-direction: column;
         align-items: flex-start;
      }
      .text h1{
       font-size: 5vh;
      }
      .text .image{
       height: 200px;
       width:140px;
       margin-top: 20px;;
      }
      .rtext{
       flex-direction: column;
       align-items: flex-start;
      }
      .rtext p{
       margin:10px
      }
      .rtext p{
       margin-top: 10px;
      }
      .icons{
       margin-top: 10px;
      }
      .bottom{
       flex-direction: column;
       align-items: flex-start;
      }
      .b1{
        width: 100%;
        height: 30vh;
      }
      .b2{
       width: 100%;
      }
      .b2 .up{
         min-height: 40vh;
      }
      
      .b3{
       width: 100%;
       min-height: 30vh;
       background-position: left;
      }

}

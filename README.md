# Animation-code-in-css
Wishing  you  all  engineers in happy engineers day ... wishing with create greeting animation using css animation  style and  his attributes . 

<!doctype html>
<html>
 <head>
<style>
@keyframes box{
  0%{
    width: 300px;
    height: 500px;
    left: 0px;
     }
  30%{
       width: 300px;
       height: 400px;
       background-color: red;
       
     }
     
  40%{
    width: 800px;
    height: 300px;
    background-color: green;  
    
  }
  50%{
       height: 400px;
       width: 600px;
       background-color: orange;
     
              
     }
  
  60%{
       height: 400px;
       width: 600px;
       background-color: pink;
       left : 100px; 
              
     }
     
     70%{
       height: 400px;
       width: 700px;
       background-color: aqua;
    ; 
              
     }
     
   80%{
     
     height: 800px;
     width: 2000px;
     background-color: aquamarine;
      }
   
     
   90%{
     
     height: 600px; 
     width: 1500px; 
     background-color : yellow;
       }
  100%{
       width: 1000px;
       height: 400px;
       background-color: black;
       
     }
}

div{
  height: 300px;
  width: 300px;
  position: Absolute;  
  background-color: blue;
  animation-name: box;
  animation-duration: 2s;
  animation-delay: 2s;
  animation-timing-function : infinite;
  animation-iteration-count: 20;
  animation-direction : alternate-reverse;  
}

</style >
</head>
 <body> 
  <div> 
   <h1><i>HAPPY ENGINEERING DAY TO All Engineers 🥳🥳🥳<br> from : Prajakta Yadav <br> <br> </i> 
    <center> 
     <i>🎈🎈🎈🎈🎈🎈🎈🎊🎊🎊🎊🎊🎊🎊🎈🎈🎈🎈🎈🎈🎈</i> 
    </center></h1> 
  </div> 
 </body>
</html>

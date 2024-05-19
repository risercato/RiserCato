<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Jaro:opsz@6..72&family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&display=swap');
      @import url('https://fonts.googleapis.com/css2?family=Jaro:opsz@6..72&family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&family=Satisfy&display=swap');
      
      
      #but{
        font-family: jaro;
        padding: 20px;
        margin: 2%;
        margin-top: 20px;
        margin-bottom: 20px;
        padding-left: 30px;
        padding-right: 30px;
        color: rgb(255, 255, 255);
        background-color: #156;
        border: none;
        border-radius: 5px 10px 10px 10px;
        font-size: 20px;
        text-shadow: #1566;
        animation-name: test2;
        animation-duration: 3S;
        
       
        }
        @keyframes test2 {
          from {
            filter: blur(100px);
            color: #156;
          }
          to {
            filter: blur(0px);
            color: aliceblue;
          }
        }
      
      #elem{
        background-color: black;
        border-radius: 10px;
        animation-name: test;
        animation-duration: 5s;}

        @keyframes test {
          from {
            background-color : #156 ;
          }
          to {
            background-color : black ;
          }
        
        }
        #spa{
          margin-left: 10px;
          padding: 6px;
          margin-left: 10px;
          margin-top: 10px;
          padding: 10px;

        }
        #grt{
          background-color: blanchedalmond;
          padding: 10px;
          font-family: Satisfy;
          border-radius: 10px 10px 0px 0px;
          padding: 10px;
          animation-name: riser;
          animation-duration: 2s;
          
        }
        @keyframes riser {
          from{
            scale: 0%;
          }
          to {
            scale: 100%;
          }
          
        }
      
    </style>
</head>
<body bgcolor="#156" >
  <div id="elem" >
    
    <center>
      <button id="but" >Riser</button>
      <button id="but" >zahra</button>
      <button id="but" >FZ</button>
    </center>
  </div>
  <div>
    <div id="">
      <h1 id="grt" >
        <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@24,400,0,0" />
        
            <span class="material-symbols-outlined" id="spa" >
            done_all
            </span>
        
        RiserCato
      </h1>
    </div>
    
    <p id="grt">popopopopopopopopopopopoop</p>
  </div>
  
</body>
</html>

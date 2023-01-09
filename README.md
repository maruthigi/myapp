<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="project.css">
    
    <title>Document</title>
</head>
<body class="border">
   <section>
    <div class="container">
        <div class="logo">BAZAR</div>
        <div><input type="text" name="" id="search" placeholder="search here" onkeyup="fil()" ></div>
        <div class="menu">
            <ul>
                <li>mens</li>
                <li>womens</li>
                <li>kids</li>
                <li>beauty</li>
            </ul>
        </div>
        <div class="toggle">Menu</div>
        <div class="login">Login</div>
        <div class="bucket">Cart</div>
      
    </div>
   </section>
   <div id="span"></div>
   <section1>
    <div class="maru">
    <div class="bazar1">
      <h2 class="bazar">MARUTHI@bazar</h2>
    </div>

   
  <section2>
    <div class="title">SING IN</div>
    <form  onsubmit="ar()">
        <input type="text" name="user1" id="user1" class="revanth" placeholder="username">
        <br>
        <input type="password" name="password" id="password1" class="revanth" placeholder="password">
        <br>
        <input type="submit" name="login" id="login1" value="login">
        <br>
        <input type="checkbox" name="box" id="box">remember your password
    </form>
  </section2>
 
  
    <div class="container3">
      <div class="card1">
        
        <div>
        <img src="./shirt11.jpg" alt="" width="100%">
        </div>
        <div>
        <h2 id="ti">besan</h2>  
        <p>2000</p>
        <button id="button">add-cart</button>
        </div>

        </div>
        <div class="card1">
          <img src="./shirt11.jpg" alt="" width="100%">
          <h2 id="ti">dark</h2>  
          <p>2000</p>
          <button id="button">add-cart</button>
          </div>

          <div class="card1">
            <div>
            <img src="./shirt11.jpg" alt="" width="100%">
            </div>
            <div>
            <h2 id="ti">jeans</h2>  
            <p>2000</p>
            <button id="button">add-cart</button>
            </div>

            </div>

            <div class="card1">
              <div>
              <img src="./shirt11.jpg" alt="" width="100%">
              </div>
              <div>
              <h2 id="ti">pants</h2>  
              <p>2000</p>
              <button id="button">add-cart</button>
              </div>

              </div>

              
              <div class="card1">
                <div>
                <img src="./shirt11.jpg" alt="" width="100%">
              </div>
              <div>
                <h2 id="ti">color</h2>  
                <p>2000</p>
                <button id="button">add-cart</button>
                </div>

                </div>

      </div>
        </div>
  
  <section4>
    <div class="cart">
      <h3 id="cart1">your cart is empty please add some items</h3>
     
     

    </div>
  </section4>
 <!----- <section5>
    <div class="nag">
      <div class="nag1">Delivery-Details</div>
    <form  onsubmit="karthik2()">
      <label for="">name</label>
      <input type="text" name="name1" id="fullname1" required>
      <br>
      <label for="">mobile</label>
      <input type="tel" name="city1" id="fullcity1" required>
      <br>
     
      <label for="">delivery address</label>
      <textarea name="daddress1" id="fulldaddress1" cols="30" rows="10" required></textarea>
      <br>
      <input type="submit" name="" id="submit" value="submit">


    </form>
    </div>
  </section5>
  <section6>
    <div class="import">
      <table>
        <thead>
          <tr>
            <th>name</th>
            <th>mobile</th>
            <th>address</th>
          </tr>
        </thead>
        <tbody>

        </tbody>
      </table>

    </div>
  </section6>--->
   <script src="project.js"> </script>
   
    
  
    
</body>
</html>
*{
    padding: 0px;
   margin: 0px;
   box-sizing: border-box;
   font-family: sans-serif;
}
section{
    background-color: rgb(41, 40, 40);
    box-shadow: 0px 2px 5px 0px;
}
.container{
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    color: white;
    font-weight: 600;
    align-items: center;

}
.menu ul{
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.menu ul li{
    list-style: none;
}
.toggle{
   margin-left: 50px;
   display: none;
}
.logo{
    font-size: larger;
    font-weight: 900;
   
}
.login{
    cursor: pointer;
    margin-left: 80px;
}
#button{
    background-color: ghostwhite;
    border: 1px solid black;
    border-radius: 5px;
    outline: none;
    font-weight: 800;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    cursor: pointer;
    color: black;
}
#buy{
    background-color: rgb(163, 244, 224);
    border: 1px solid black;
    border-radius: 5px;
    outline: none;
    font-weight: 800;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    cursor: pointer;
    color: black;
    margin-left: 20px;

}
.galary{
    width: 100%;
    height: 300px;
    background-color: rgba(0, 0, 0, 0.011);
}
#slider{
    margin-top: 25px;
    width: 100%;
    height: 300px;
  border: 1px solid black;
  border-radius: 3px;
}
.maru{
    display: grid;
    grid-template-columns: auto auto;
   
}
.bazar{
    font-weight: 900;
    color: rgb(29, 36, 36);
    font-size: larger;
   
   text-align: center;
   margin-top: 50px;
   margin-left: 20px;
 


}
.bazar1{
    background-color: rgb(188, 246, 129);
}
section1{
   
    position: absolute;
    top: 20%;
    left: 50%;
    background-color: rgba(255, 255, 255, 0.667);
    animation-name: drop;
    animation-duration: 1s;
    display: none;

}
.super{
    display: block;
}
@keyframes drop {
    0%{
        opacity: 0.2;
        transform: translate(0,-150%);
    }
    50%{
        opacity: 0.2;
        transform: translate(0,-30%);
    }
    100%{
        opacity: 0.5;
        transform:none;
    }
    
}
.head{
    text-align: center;
                                                            /* login form styles here*/
    border-radius: 5px;
    box-shadow: 1px 0px 0px 0px;
}
strong{
    font-weight: 900;
   font-style: normal;
  
   color: rgb(28, 23, 23);
   margin: 10px;
   width: 100%;
}
input{
    margin: 0px;
    border: 1px solid black;
    outline: none;
    border-radius: 5px;

}

   

   

section2 {
    position: absolute;
    left: 50%;
    top: 20%;
    background-color: white;
    box-shadow: 0px 2px 1px 0px;
    width: 350px;
    text-align: center;
   display: none;
    animation-name: logi;
    animation-duration: 1s;
    border: 1px solid black;
    outline: none;
    border-radius: 5px ;

}
.nag input{
    display: flexbox;
    flex-direction: column;
    margin: 10px;
    padding: 10px;
}
.nag {
   display: flexbox;
   flex-direction: column;
   margin-top: 20px;
   position: absolute;
   top: 20%;
   left: 50%;
  
    
    background-color: rgba(235, 222, 222, 0.861);
    height: 400px;
    width: 30%;
    border: 1px solid black;
    outline: none;
    border-radius: 5px;
    box-shadow: 1px 2px 1px 3px white;
}
.import{
    background-color: rgb(231, 200, 163);
    width: 50%;
    height: 300px;
}
.nag1{
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-weight: 900;
    font-size: larger;
    margin: 15px;
    text-align: center;
    background-color: aliceblue;

}
.raj{
    display: block;
}
.revanth{
    border: 1px solid black;
    outline: none;
    border-radius: 3px ;
    box-shadow: 1px 0.5px 1px 1px white;
    background-color: rgb(244, 134, 134);
}
@keyframes logi {
    0%{
        opacity: 0.5;
        transform: translate(0,-150%);
    }
    0%{
        opacity: 0.9;
        transform: translate(0,-50%);
    }
    100%{
        opacity: 0.3;
        transform: none;
    }
    
}
.title{
    color: black;
    font-weight: 700;
    font-style: normal;
    margin: 5px;

}
section2 input{
    margin: 5px;
    border: 1px solid black;
    border-radius: 5px;
    outline: none;
}
#login1{
    background-color: rgb(142, 225, 16);
    width: 100px;
    border-radius: 5px;
    font-family: sans-serif;
    font-weight: 600;
}
#spa1{
    color: rgb(67, 131, 67);
}
a{
    text-decoration: none;
    color: black;
}
#submit{
    background-color: rgb(70, 240, 96);
    border-radius: 5px;
    border: 1px solid black;
    outline: none;
    color: white;
    font-weight: 700;
    width: 100px;
}
@media (max-width:760px){
    .toggle{
        display: block;
        cursor: pointer;
    }
    .menu {
        display: none;
       
    }
  
   
   
    .container{
        flex-direction: column;
        align-items: flex-start;

    }
    .akka{
        width: 200px;

    }
    .menu ul{
        flex-direction: column;
       width: 100%;
        background-color: rgba(0, 0, 255, 0.075);
       margin-top: 30px;
        margin-left: 0px;
       position: absolute;
       top: 5%;
       left: -40%;
       color: black;
       }
       .menu ul li{
        text-align: center;
      margin: 10px;
       width: 100%;
       float: left;

        
       }
       .menu.active{
        display: flex;
       }

}
section3{
    width: 100%;
    height: 100vh;
    background-color: white;
}
.we3{
    position: absolute;
  
   border: 1px solid black;
   outline: none;
   border-radius: 5px;
    color: rgb(35, 31, 31);
}

.we1{
    border: 1px solid black;
    background-color: white;
    color: black;
  padding: 5px;
  padding-left: 10px;
  background-color: white;
  border: 1px solid black;
  outline: none;
  border-radius: 5px;
 padding: 6px;
 margin-left: 0px;
 

    
    
}
.we{
    border: 1px solid black;
    background-color: white;
    color: black;
  padding: 5px;
  padding-left: 10px;
  background-color: white;
  border: 1px solid black;
  outline: none;
  border-radius: 5px;
 
 padding-top: 20px;
 
  
 
   

}
.we{
   
    border: 1px solid black;
    background-color: white;
    color: black;
  padding: 5px;
  padding-left: 10px;
  background-color: white;
  border: 1px solid black;
  outline: none;
  border-radius: 5px;
  

}
.butr{
    width: 100px;
    background-color: rgb(176, 247, 70);
    border: 1px solid black;
    outline: none;
    border-radius: 5px;
   
   
}
.card1 img{
    height: 200px;
    
}

#span{
    position: absolute;
    left: 80%;
    top: 0%;
    color: white;
}
.cart{
    margin-left: 100px;
background-color: rgb(236, 200, 200);
border: none;
overflow-y: scroll;

width: 60%;
height: 50vh;
position: absolute;
top: -100%;
}


.cart.active{
    top: 50px;
}
.bucket{
    cursor: pointer;
}

  

.container3{
    margin-left: 150px;
    display: grid;
    grid-template-columns: auto auto auto ;
    grid-gap: 60px;
    margin-top: 60px;
    margin-right: 50px;
}
.card{
    border: 1px solid rgb(239, 231, 231);
    border-radius: 5px;
    outline: none;
    box-shadow: 5px 10px 10px 5px white;
    width: 200px;


}
    

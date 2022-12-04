# login-page-for-groceries
#using html
<DOCTYPE html>
    <html>
        <head>
            <h1>
                GROSO
            </h1>
       
        <link rel="stylesheet" href="style.css">
        </head>
            <body background="C:\Users\SHAIK YASEEN BASHA\Pictures\Screenshots\front.jpeg">
        <div class="loginbox">
            <img src="C:\Users\SHAIK YASEEN BASHA\Pictures\Screenshots\avatar.jpeg" class="avatar">
            <h2>Login Here</h2>
            <form>
                <p>Username</p>
                <input type="text" name="" placeholder="Enter username">
                <p>Password</p>
                <input type="password" name="" placeholder="Enter password">
                <a href="file:///C:/Users/SHAIK%20YASEEN%20BASHA/Documents/p2.html"> <h3>Login</h3>
                </a>
                <a href="#">Lost your password</a><br>
                <a herf="#">Dont have account?</a>
            </form>
           
        </div>
            

        </body> 
    </html>
    #code for css
    h1{font-style: initial;
    text-align: center;
    background-color:aqua;
    background-position: center;
    border:solid;
    border-radius: 100px;
    width: 10cm;
    margin-left: 15cm;
    
  }
 
  body{
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: cover;
  }
  .loginbox{
    width: 320px;
    height: 500px;
    background:black;
    color: white;
    top: 50%;
    left: 50%;
    position: absolute;
    transform: translate(-50%,-50%);
    box-sizing: border-box;
    padding: 80px 50px;
    
  }
  .avatar{
    width: 100px;
    height: 100px;
    border-radius: 50%;
    position: relative;
    top: -50px;
    left: calc(50% - 50px);
  }
  .h2{
    margin: 0;
    padding:0 0 20px;
    text-align: center;
    font-size: 22px;

  }
  .loginbox p{
    margin: 0;
    padding: 0;
    font-weight: bold;

  }
  .loginbox input{
    width: 100%;
    margin-bottom: 20px;

  }
  .loginbox input[type="text"],input[type="password"]
  {
    border: none;
    border-bottom: 1px solid white;
    background: transparent;
    outline: none;
    height: 40px;
    color: white;
    font-size: 16px;

  }
  h3
  {
    border: none;
    outline: none;
    height: 40px;
    background: red;
    color: whitesmoke;
    font-size: 20px;
    border-radius: 20px;
    text-align: center;
    
  }
  .loginbox input[type="submit"]:hover{
    cursor: pointer;
    background:black;
    color:blue;

  }
  .loginbox a{
    text-decoration: none;
    font-size: 12px;
    line-height: 20px;
    color: darkgreen;
  }
  .loginbox a:hover{
    color:blueviolet;
  }


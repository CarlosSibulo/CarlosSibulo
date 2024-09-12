<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic HTML CSS Login Form</title>
    <link rel="stylesheet" href="/css/styles.css">
</head>
<body>
    <body>
        <div class="login">
            <div class="login-screen">
                <div class="app-title">
                    <h1>Welcome</h1>
                </div>
    
                <div class="login-form">
                    <div class="control-group">
                    <input type="text" class="login-field" value="" placeholder="username" id="login-name">
                    <label class="login-field-icon fui-user" for="login-name"></label>
                    </div>
    
                    <div class="control-group">
                    <input type="password" class="login-field" value="" placeholder="password" id="login-pass">
                    <label class="login-field-icon fui-lock" for="login-pass"></label>
                    </div>
    
                    <a class="btn btn-primary btn-large btn-block" href="#">Login</a>
                    <a class="login-link" href="#">Lost your password?</a>
                </div>
            </div>
        </div>
    </body>
</body>
</html>            
* {
  box-sizing: border-box;
  }
  
  *:focus {
    outline: none;
  }
  body {
  font-family: Arial;
  background-color: #AD7657;
  padding: 50px;
  display: flex;
  justify-content: center;
  align-items: center;
  }
  .login {
  margin: 20px auto;
  width: 300px;
  }
  .login-screen {
  background-color: #BA8940;
  padding: 20px;
  border-radius: 10px
  }
  
  .app-title {
  text-align: center;
  color: #B89847;
  }
  
  .login-form {
  text-align: center;
  }
  .control-group {
  margin-bottom: 10px;
  }
  
  input {
  text-align: center;
  background-color: #C18832;
  border: 2px solid transparent;
  border-radius: 10px;
  font-size: 16px;
  font-weight: 200;
  padding: 10px 0;
  width: 250px;
  transition: border .5s;
  }
  
  input:focus {
  border: 2px solid #C7A651;
  box-shadow: none;
  }
  
  .btn {
    border: 2px solid transparent;
    background: #EABF29;
    color: #EC9443;
    font-size: 16px;
    line-height: 25px;
    padding: 10px 0;
    text-decoration: none;
    text-shadow: none;
    border-radius: 10px;
    box-shadow: none;
    transition: 0.25s;
    display: block;
    width: 250px;
    margin: 0 auto;
    border: 2px solid transparent;
    background: #EC9443;
    color: #F9C87E;
  }
  
  .btn:hover {
    background-color: #EC9443;
  }
  
  .login-link {
    font-size: 12px;
    color: #F9C87E;
    display: block;
    margin-top: 12px;
  }                                         
  /* Replace with your JS Code 
(Leave empty if not needed) */

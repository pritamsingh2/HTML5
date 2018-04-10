<!DOCTYPE html>
<html lang="en">
<head>
  <title>Login Form</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<style type="text/css">
   

  .row {
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
  margin: 0 40px;
}

.row-25 {
  -ms-flex: 25%; /* IE10 */
  flex: 25%;
}

.col-25 {
  -ms-flex: 25%; /* IE10 */
  flex: 25%;
}

.row-75 {
  -ms-flex: 75%; /* IE10 */
  flex: 75%;
}

.row-25,
.row-75,
.col-25,
.col-75 {
  padding: 0 16px;
}
  
.inputs{
margin-bottom: 20px;
display: table;
}
.go{
width:75px;
padding: 5px;
border:1px solid #ccc;
border-radius: 5px;
background-color:black ;
color: white;
}
.login{
background-color: lightgray;
  padding: 5px 5px 5px 5px;
  border: 1px solid lightgrey;
  border-radius: 3px;
}


    </style>
</head>
<body>
<form class="login">
<div class="row-25">



<div class="row">
 <div class="col-xs-3"></div>
 <div class="col-xs-3">Email ID</div>
 <div class="col-xs-3">Password</div>
</div>
<div class="row">

<div class="col-xs-3">
 <label>Already Registered?</label>
 
 </div>
 
 <div class="col-xs-3">
<input type="text"  id="email" name="email" style="width: 300px;" />

</div>

<div class="col-xs-3">
<input type="password"    name="psw" >

 </div>
 <div class="col-sm-3">
        
      <button type="submit" class="go" >GO</button>
      </div>
</div>

	  </div>
</form>
<br>

<div style="width: 100%; height: 10px; border-bottom: 1px solid black; text-align: center">
      <span style="font-size: 15px; background-color: #F3F5F6; ">
        OR
      </span>
    </div>
 <br>
 <br>
 
 <form>
<div class="row-75">


<div class="row">
<div class="col-xs-3"><label>Register As*</label></div>
</div>
<div class="row">
<div class="col-xs-3">
	<select class="inputs" style="width: 220px; background-color:lightgray;">
	<option >Select member type</option>
	<option value="0"></option>
	</select>
	</div>
	</div>
	<div class="row">
	<div class="col-xs-3"><label >Email ID*</label></div>
	</div>
	<div class="row">
	<div class="col-xs-3">
	<input class="inputs" type="email" style="height: 20px; width: 220px; background-color:lightgray;"  placeholder="***@***.com" name="emailId" />
	</div>
	</div>
	<div class="row">
	<div class="col-xs-2"><label>Password*</label></div>
	
	<div class="col-xs-2">
	<label >Confirm Password*</label>
	</div>
	</div>
	<div class="row">
	<div class="col-xs-2">
	<input class="inputs" style="display: table; width: 150px; height: 20px;margin-bottom: 8px;background-color:lightgray;" type="password" placeholder="" />
	</div>
	<div class="col-xs-2">
	<input class="inputs" style="display:table;width: 150px; height: 20px;margin-bottom: 8px;background-color:lightgray;" type="password" placeholder="" required="required"/>
	</div>
	</div>
	<div class="row">
	<div class="col-xs-2">
	<label>Full name*</label>
	</div>
	</div>
	<div class="row">
	<div class="col-xs-2">
	<input  type="text" style="display:table;width: 150px; height: 20px;margin-bottom: 8px;background-color:lightgray;"  placeholder="First Name" />
	</div>
	<div class="col-xs-2">
	<input  type="text" style="display:table;width: 150px; height: 20px;margin-bottom: 8px;background-color:lightgray;"  placeholder="Middle Name" />
	</div>
	<div class="col-xs-2">
	<input  type="text" style="display:table;width: 150px; height: 20px;margin-bottom: 8px;background-color:lightgray;"  placeholder="Last Name" />
	</div>
	</div>
	<div class="row">
	<div class="col-xs-2">
	<label>Display Name</label>
	</div>
	<div class="col-xs-2">
	<label>Mobile Number*</label>
	</div>
	<div class="col-xs-2">
	<label>Gender*</label>
	</div>
	</div>
	<div class="row">
	<div class="col-xs-2">
	<input  type="text" style="display:table;width: 150px; height: 20px;margin-bottom: 8px;background-color:lightgray;"  />
	</div>
	<div class="col-xs-2">
	<input  type="text" style="display:table;width: 150px; height: 20px;margin-bottom: 8px;background-color:lightgray;"  />
	</div>
	<div class="col-xs-2">
	<select class="inputs" style="width: 150px;margin-bottom: 8px; background-color:lightgray;">
	</select>
	</div>
	</div>
	<div class="row">
	<div class="col-xs-2">
	<label>Captcha*</label>
	</div>
	<div class="col-xs-2">
	<label>Enter the code here</label>
	</div>
	</div>
	<div class="row">
	<div class="col-xs-2">	<input class="inputs" type="text" id= "mainCaptcha"  readonly="true" style="display:table;width: 150px; height: 40px;margin-bottom: 8px;" /> </div>
	<div class="col-xs-2"><input  type="text" style="display:table;width: 150px; height: 20px;margin-bottom: 8px;background-color:lightgray;"  /></div>
	</div>
	<div class="row">
	<div class="col-xs-5">
		<input type="checkbox" id="check" name="check" value="check" style="margin-right: 5px;margin-bottom: 20px;"/><label>I have read,understood and accepted the rules for membership.
	</label> 
	</div>
	</div>
	<div style="display: table; float: right" >
	<input type="button" class="cancel" value="Cancel" onclick="cancel()">
	<button type="submit" class="register"  onclick="ValidCaptcha(); password();">Register</button>
	</div>
	</form>
	</body>
	<script type="text/javascript">
	function Captcha(){
                     var alpha = new Array('A','B','C','D','E','F','G','H','I','J','K','L','M','N','O','P','Q','R','S','T','U','V','W','X','Y','Z','a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z');
                     var i;
                     for (i=0;i<6;i++){
                       var a = alpha[Math.floor(Math.random() * alpha.length)];
                       var b = alpha[Math.floor(Math.random() * alpha.length)];
                       var c = alpha[Math.floor(Math.random() * alpha.length)];
                       var d = alpha[Math.floor(Math.random() * alpha.length)];
                       var e = alpha[Math.floor(Math.random() * alpha.length)];
                       var f = alpha[Math.floor(Math.random() * alpha.length)];
                       var g = alpha[Math.floor(Math.random() * alpha.length)];
                      }
                    var code = a + ' ' + b + ' ' + ' ' + c + ' ' + d + ' ' + e + ' '+ f + ' ' + g;
                    document.getElementById("mainCaptcha").value = code
                  }
				  function ValidCaptcha(){
                      var string1 = removeSpaces(document.getElementById('mainCaptcha').value);
                      var string2 = removeSpaces(document.getElementById('txtInput').value);
                      if (string1 == string2){
                    	  checkbox();
                    	  
                        return true;
                      }
                      else{ 
                    	  alert("Enter Valid Captcha!");
                    	  Captcha();
                    	 
                        return false;
                      }
                  }
	</script>
</html>

this reposiory is a front web page devlopment for sex engine and cycle to control the robot arm
1-interface robot arm.html
2-control the arm.css robot

<!DOCTYPE html>
<html>
<head>
<title> interface for robotic arms     </title>
<style>
body{
 background-color:lightCyan;
 padding:10px;
 border-style:solid;
 border-color:gray;
 }
 
div{
text-align:center;
border-color:black;

P.center{
text-align:center;
}
#main-Unorder-List{
	color:rgb(171, 59, 171);
	font-weight:bold;
}
.order-list{
text-decoration:none;
font-weight:bold;
color:#000000;
font-style:cycle;
}


.engine1{
   margin-top:40px;
  text-align:center;
	color:black;
	}
	

.engine2{
    margin-top:40px;
  text-align:center;
	color:black;
	}
	.engine3{
   margin-top:40px;
  text-align:center;
	color:black;
	}

.engine4{
   margin-top:40px;
  text-align:center;
	color:black;
	}
	
	.engine5{
    margin-top:40px;
  text-align:center;
	color:black;
	}
	.engine6{
   margin-top:40px;
  text-align:center;
	color:black;
	}
</style>


</head>

<body>
<h1> <p>interface for robotic arms</h1> </p>
<h2> <p> welcom  </h2> </p>
<img width= 300px src = "https://hanady8.files.wordpress.com/2019/02/img_5750-1.jpg">
<div class =" engine1">
<input type ="rang" min="0"
max="180"value="0"id="number">
  </h> <cycle id="engine1"></cycle> 
        </div>
	<div class="engine1"> <h>engine1
        <input type="range" min="0" max="180" value="0" id="engine1">
           </h> <label> <cycle id="engine1"></cycle></label> </div>

<div class="engine2"> <h>engine2
        <input type="range" min="0" max="180" value="0" id="engine2">
          </h> <label> <cycle id="engine2"></cycle></label> </div>
		  
		   <div class="engine3"> <h> engine3
            <input type="range" min="0" max="180" value="0" id="engine3">
            </h> <cycle id="engine3"></cycle> 
        </div>
 
 
  <div class="engine4"> <h> engine4
        <input type="range" min="0" max="180" value="0" id="engine4">
            </h> <cycle  id="engine4"></cycle > 
        </div>
		
		 <div class="engine5"> <h> engine5
            <input type="range" min="0" max="180" value="0" id="engine5">
            </h> <cycle id="engine5"></cycle> 
			
			<div class="engine6"> <h>engine6
        <input type="range" min="0" max="180" value="0" id="engine6">
            </h><cycle id="engine6"></cycle> 
           
       
        </div> 
        </div>
		<script>
		<form>
		

        </script>
        <div class="container">
        <button class="but-1">Sava</button>
            <button class="but-2">Running</button>
        </div>
        </form>
	
		
</body>
 
  
  
  
  /script>
</html>

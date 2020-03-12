<!DOCTYPE html>
<html>
<head>
    <title>Viewer Page</title>
</head>
<style>
   #body {
    height: 100%;
	width: 100%;
	padding: 0px;
	margin: 0px;
	background-color: #c0c0c0;
   }
   
   #_osn{
   float: left; 
   position: relative;
   }
   
   #_block{
   transition: background-color 0.5s ease; 
   margin-top: 10%; 
   width: 800px; 
   height: 500px; 
   background-color: #6441A4; 
   float: left; 
   position: relative; 
   left: -50%;
   }
   
   #_head{
	height: 20%;
	width: 100%;
	background-color: #ab274f;
	text-align: center;
   }
   
   #_head_content{
   padding-top: 5%;
   }
   
   #_body{
   	height: 60%;
	width: 100%;
	background-color: #ab343a;
   }
   
   #_body_textarea{
   autocomplete: off;
   maxlength: 150;
   width: 90%;
   height: 90%;
   resize: none;
   text-align: center;
   }
   
   #_buttonBlock{ 
	height: 20%;
	width: 100%;  
	background-color: #b03f35;	
   }
   
</style>
<body style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"  id="body">
    <div id="app" class="full-height"></div>
    <script src="https://extension-files.twitch.tv/helper/v1/twitch-ext.min.js"></script>
    <script src="https://code.jquery.com/jquery-3.3.1.min.js"
            integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8="
            crossorigin="anonymous"></script>
    <!--<script src="viewer.js" type="text/javascript"></script>-->
    
	<div id="_osn" style="left: 50%">
        <div id="_block">

			<div id="_head">
				<div id="_head_content">
				Соглашение со стримером
				</div>
			</div>
			
			<div id="_body">
			<textarea name="comment" cols="50" rows="5" id="_body_textarea" disabled>123</textarea>
			</div>
			
			<div id="_buttonBlock">
			3
			</div>
			
        </div>
    </div>
	
</body>
</html>

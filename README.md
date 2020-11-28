<html>
<head></head>
<body>
	  <form id="1"action="doStuff.php" method="post" ><br><br>
	  <p><h1 align="center" class="animated"><span><b><strong><i>Design Mix</i></strong></b></span></h1></p><br><br>
	<label><i><strong><h3 align="center">**This app is completely based on IS456:2000 and IS10262:1982**</h3></strong></i></label>

		<label><h4>Test included:</h4></label>
		<label>1. If Portland Pozzolona Cement is used, strength achieved by them in 28 days should be known.</label></br>
		<label>2. Grading of Fine aggregeate.</label></br>
		<label>3. Water reduced by 1% of Superplasticizer should be known.</label></br>
		<label>4. Some of the Test are described below.</label><br><br>



	  <label>Enter the Grade of Concrete:</label>
	  <select name="grade">
	  		<option value="30">30</option>
		   <option value="10">10</option>
		   <option value="15">15</option>
		   <option value="20">20</option>
		   <option value="25">25</option>
		   <option value="35">35</option>
		   <option value="40">40</option>
		   <option value="45">45</option>
		   <option value="50">50</option>
		   <option value="55">55</option>
		   </select>
	   <label>N/mm<sup>2</sup></label><br><br>

	   
	   
	   
	   <label>Enter the Grade of Cement:</label>
	  <select name="gradec">
	  <optgroup label="Ordinary Portland Cement:">
	  		<option value="OPC 33">OPC 33</option>
		   <option value="OPC 43">OPC 43</option>
		   <option value="OPC 53">OPC 53</option>
		  </optgroup>
		  <optgroup label="For Portland Pozzolana Cement:(Since there is no grade. Please select the strength achieved by cement in 28 days in MPa)">
		  <option value="ab">31.9-36.8</option>
		  <option value="bb">36.8-41.7</option>
		  <option value="cb">41.7-46.6</option>
		  <option value="db">46.6-51.5</option>
		  <option value="eb">51.5-56.4</option>
		  <option value="fb">56.4-61.3</option>
		  
		  
		  
		  
		  
		  
		  </optgroup>
	   </select><br><br>
	   
	   
	   
	   	<label>Enter the Type of Concrete:</label>
	   <select name="type of concrete">
		   <option value="Plain Cement Concrete">Plain Cement Concrete</option>
		   <option value="Reinforced Cement pConcrete">Reinforced Cement Concrete</option>
			</select><br><br>
		
		<label>Exposure Condition:</label>
		<select name="Exposure Condition">
			<option value="Mild">Mild</option>
			<option value="Moderate">Moderate</option>
			<option value="Severe">Severe</option>
			<option value="Very Severe">Very Severe</option>
			<option value="Extreme">Extreme</option>
		</select><br><br>
		
		<label>Size of Aggregate:</label>
		<select name="Size of Aggregate">
			<option value="20">20</option>
			<option value="10">10</option>
			<option value="40">40</option>
		</select>
		<label>mm</label><br><br>
		
		
		<label><i>Take 1kg of Fine Aggregate and Sieve Analysis is done. Note the percentage of Aggregate passing through the 600 micron sieve and Select the option below:</i></label><br><br>
		
		<label>Enter the Passing percent through IS Sieve 300 micron:</label>
		<select name="zone">
			<option value="15-34">15-34</option>
			<option value="35-59">35-59</option>
			<option value="60-79">60-79</option>
			<option value="80-100">80-100</option>
		</select>
		<label>%</label><br><br>
		
		
		<label>Slump Value Needed:</label>
		<select name="Slump Needed">
			<option value="100">100</option>
			<option value="10">10</option>
			<option value="25">25</option>
			<option value="50">50</option>
			<option value="75">75</option>
			<option value="125">125</option>
			<option value="150">150</option>
			<option value="175">175</option>
			<option value="200">200</option>
		</select>
		<label>mm</label><br><br>
		
		<label>Superplasticizer Used?</label>
		<select name="Superplasticizer Used?">
			<option value="No">No</option>
			<option value="Yes">Yes</option>
		</select><br><br>
		
		
		<label>% Superplasticizer Used</br>(Trail ie, 1% and 2%):</label>
		<select name=n>
			<option value="1">1</option>
			<option value="2">2</option>
		</select><br><br>
		
		
		
		
		<label>% of Water Reduced by 1% of Superplasticizer(Please avoid if no Superplastizer used):</label>
		<input type="number" id="%1spw"style="width: 100px;height: 40px" placeholder="Enter here..." default="0"/>
		<label>%</label><br><br>
		


		<label>Type of Cement ( Make sure that the Grade and Type of cement matches ) :</label>
		<select name="type of cement">
			<option value="opc">Ordinary Portland Cement</option>
			<option value="ppc">Portland Pozzolana Cement</option>
		</select><br><br>
		
		
		<label>Methof of Placing of Concrete:</label>
		<select name="method of placing">
			<option value="pumping">Pumping Method</option>
			<option value="non-pumping">Non-Pumping Method</option>
		</select><br><br>
		
		
		<hr width="40%"/><br><br>
		
		
		
		
		<label><h2><u><i>Aggregates:</i></u></h2></label>
		
		<label><i>Take 1kg of Air Dried Aggregate and Calculate the following Results</i><//i></label><br><br>



		<label><i>Take some quantity of Water and Soak the Aggregates in the Water and Enter the Details Below</i></label><br><br>

		
		
		<label><h3><u><i>Coarse Aggregate:</i></u></h3></label>

		<label>Weight of Water(before soaking of aggregates):</label>
		<input type="number" id="wowc" style="width: 100px;height: 40px" placeholder="Enter here..." required/>

		<label>kg</label><br />
		
		
		<label>Weight of Water with Aggregates(After Soaking of Aggregates for "Atleast 24 hours"):</label>
		<input type="number" id="dwwc" style="width: 100px;height: 40px" placeholder="Enter here..."/>

		<label>kg</label><br />


		<label>Surface Saturated Dry Weight of Coarse Aggreate(wet condition):</label>
		<input type="number" id="ssdc"style="width: 100px;height: 40px" placeholder="Enter here..."/>

		<label>kg</label><br />
		
		
		<label>Oven Dried Weight of Coarse Aggregate(Completely Dried)</label>
		
		<input type="number" id="odwc"style="width: 100px;height: 40px" placeholder="Enter here..."/>

		<label>kg</label><br />
		
		
		<hr width="30%"/><br><br>
		
		
		
		<label><h3><u><i>Fine Aggregate:</i></u></h3></label>
		
		<label>Weight of Water(before soaking of aggregates):</label>
		
		
		<input type="number" id="wowf" style="width: 100px;height: 40px" placeholder="Enter here..."/>

		<label>kg</label><br />
		
		
		<label>Weight of Water with Aggregates(After Soaking of Aggregates for "Atleast 24 hours"):</label>
		<input type="number" id="dwwf" style="width: 100px;height: 40px" placeholder="Enter here..."/>

		<label>kg</label><br />


		<label>Surface Saturated Dry Weight of Coarse Aggreate(wet condition):</label>
		<input type="number" id="ssdf"style="width: 100px;height: 40px" placeholder="Enter here..."/>

		<label>kg</label><br />
		
		
		<label>Oven Dried Weight of Coarse Aggregate(Completely Dried)</label>
		
		<input type="number" id="odwf"style="width: 100px;height: 40px" placeholder="Enter here..."/>

		<label>kg</label><br><br>
		
		
		<input type = "button" onclick = "myfunc()" value = "Submit"><br><br>



		

		
		<br>
			Result : <br>
			
			
			<label>Ratio of Cement:Fine Aggregate:Coarse Aggregate:</label></br>
			<input type="text" id="txtresult1" name="TextBox3" style="width: 50px;height: 40px" >
			<label>:</label>
			
			<input type="text" id="txtresult2" name="TextBox3" style="width: 50px;height: 40px" >
			<label>:</label>
			
			<input type="text" id="txtresult3" name="TextBox3" style="width: 50px;height: 40px" >
			<br><br>
			<label >Water Cement Ratio:</label>
			<input type="text" id="txtresult4" name="TextBox3" style="width: 100px;height: 40px" >
			
			<br><br>
			
			
			<input type="reset" value="Reset">

 
		</form>
		<hr width="50%"/><br><br>
		<form>
		
		<label><h4>*This section is only for Superplasticizer*</h4></label><br><br>
		
		<label><i>If the samples are made with 1% and 2% superplasticizer and slump values are noted, Select the below Option</i></label><br><br>
		
	  <label>
	  <input class= "messageCheckbox"type="checkbox" id="action" 		value="after" style="vertical-align: middle; margin:5px" name="choice[]" />After<br><br>
		</label>
		
		
		<p><h2><b></b><strong><u><i>After Sample Making</i></u></strong></b></h2></p><br><br>
		
		
		<label>Slump Obtained by 1% of Superplasticizer:</label>
		<input type="number" id="Slump Obtained by 1%" style="width: 100px;height: 40px" placeholder="Enter here..." />
		<label>mm</label><br><br>
		<label>Slump Obtained by 2% of Superplasticizer:</label>
		<input type="number" id="Slump Obtained by 2%" style="width: 100px;height: 40px" placeholder="Enter here..." />
		<label>mm</label><br><br>
		
		
		
		
		
		
		<input type = "button" onclick = "myfunc()" value = "Submit"><br><br>
		<input type="reset" value="Reset">
		<hr width="50%"/><br><br>
		<br>
		</form>
		<form>
			Result : <br>
			
			
			<label>% of Superplasticizer for given slump:</label>
			<input type="text" id="txtresult5" name="TextBox4" style="width: 50px;height: 40px" ><br><br>

			<label>
	  <input type="radio" id="actiona" 		value="done" style="vertical-align: middle; margin:5px" name="choice[]" />Done<br><br>
		</label>
			
			<label>Slump Obtained :</label>
		<input type="number" id="Slump Obtained" style="width: 100px;height: 40px" placeholder="Enter here..." />
		<label>mm</label><br><br>
		
		<label>% of Superplasticizer Used :</label>
		<input type="number" id="spusedfind" style="width: 100px;height: 40px" placeholder="Enter here..." />
		<label>%</label><br><br>
		
		<input type = "button" onclick = "myfunc()" value = "Submit"><br><br>
		<input type="reset" value="Reset">
		<hr width="75%"/><br><br>

		</form>
    <style>
﻿:root {
	
	/* F O N T S */
	--title-font: "Quicksand", sans-serif;
	--main-font: "Open Sans", sans-serif;

	/* T H E M E C O L O R */
	--black: #0B0C10;
	--basic: #1F2833;
	--pale: #C5C6C7;
	--theme-teal: #66FCF1;
	--theme-cyan: #45A29E; 

}

* {
	font-family: var(--main-font), sans-serif;
	box-sizing: border-box;
}

body {
	margin-left: 15px;
}

p {
	margin: 5px;
	text-align: justify;
}

h1,h2, h3, h4, h5, h6 {
	font-family: var(--title-font);
	margin: 20px 5px;
}



a, span {
	text-decoration: none;
	font-family: inherit;
	color: inherit;
}

button {
	background: var(--theme-cyan);
	border: 2px solid var(--theme-cyan);
	padding: 8px 16px;
	font-family: var(--title-font);
	font-weight: bold;
	letter-spacing: 1px;
	color: #FFF;
	transition: background-color 0.2s ease-out;
}

button:hover {
	background-color: rgba(0, 0, 0, 0.2);
}

/***

Filename: index.css
Author: SPICEAPPLE
Last Modified: 12/4/2019

Desription: Basic styles, layout, and transitions for the main page.

***/

body {
	background: url("https://images.pexels.com/photos/1129253/pexels-photo-1129253.jpeg?auto=compress&cs=tinysrgb&h=5184&w=3456");
	height: 100%;
	font-size: 14px;
	color: #FFF;
}

/***************/
/* H E A D E R */
/***************/

header {
	display: flex;
	margin-top: 20px;
}

/* Title */

header h3 {
	margin-left: 5vw;
	font-size: 25px;
	letter-spacing: 4px;
}

/* Navigation */

header nav {
	margin-left: auto;
	margin-right: 5vw;
}

header ul {
	display: flex;
	list-style-type: none;
	margin: 20px 0;
	padding: 0;
}

header ul li a {
	display: block;
	width: 25px;
	height: 25px;
	margin: 0 10px;
}

header ul li a svg {
	width: 100%;
	height: 100%;
}

/***********/
/* M A I N */
/***********/

main {
	height: 100%;
	display: flex;
}

/* Side Banner */

main .side-banner {
	padding: 70px 35px;
}

main .side-banner p {
	font-family: var(--title-font);
	font-size: 18px;
}

main .side-banner p:first-of-type {
	font-size: 20px;
	font-weight: bold;
}

main .side-banner p:first-of-type span {
	display: block;
	font-size: 60px;
	font-weight: bold;
	color: var(--theme-teal);
	transform: translateY(-10px);
}

main .side-banner button {
	margin: 12px 0;
}

/* Main Content */

main .main-container {
	margin: 35px 70px 35px 10px;
}

/* Content Title */

main .main-container .title-wrapper {
	display: flex;
	background: var(--theme-cyan);
	padding: 5px 20px;
}

main .main-container .title-wrapper h3 {
	margin: 10px 5px;
	font-size: 20px;
	font-weight: normal;
	letter-spacing: 2px;
}

main .main-container .title-wrapper a {
	display: none; /*********/
	height: 25px;
	width: 25px;
	margin: 10px 0;
	margin-left: auto;
}

main .main-container .title-wrapper a svg {
	height: 100%;
	width: 100%;
}

/* Content */

main .content-wrapper {
	display: grid;
	grid-template-columns: 1fr 1fr;
	gap: 20px;
	background: rgba(0, 0, 0, 0.4);
	padding: 15px 20px;
}

/***************/
/* F O O T E R */
/***************/

footer {
	display: grid;
	grid-template-columns: 1fr 1fr;
	background: var(--basic);
	margin-top: 70px;
	padding: 35px 180px;
}

/* Footer Container */

footer .footer-container h2 {
	font-size: 40px;
}

footer .footer-container h3 {
	font-size: 25px;
}

footer .footer-container img {
	display: block;
	margin: 20px auto;
	border-radius: 50%;
	width: 40%;
}

footer .footer-container p {
	margin: 10px 0;
	font-family: var(--title-font);
}

footer .footer-container .social-box {
	display: flex;
}

footer .footer-container .social-box * {
	background: #FFF;
	width: 15%;
	margin: 10px;
	border: 2px solid;
	border-radius: 50%;
}

/***************************/
/* M E D I A Q U E R I E S */
/***************************/

@media (max-width: 1000px) {

	main .main-container {
		margin: 30px;
	}

	main .content-wrapper {
		grid-template-columns: 1fr;
		gap: 10px;
	}

}

@media (max-width: 780px) {

	main .side-banner p:first-of-type span {
		font-size: 40px;
		font-weight: bold;
	}
	main {
		flex-direction: column;
	}

	main .main-container {
		margin: 5vw 10vw;
	}

	main .content-wrapper {
		grid-template-columns: 1fr;
		gap: 10px;
	}

	footer {
		display: grid;
		grid-template-columns: 1fr;
		grid-template-rows: 1fr 1fr;
		background: var(--basic);
		padding: 35px 70px;
	}

}
.animated {
  font-family: 'charm', cursive;
  margin: 0;
  padding: 0;
  font-size: 4rem;
  background: url('https://i.ibb.co/89Cf3dm/text-bg.png');
  background-clip: text;
  -webkit-background-clip: text;
  color: transparent;
  animation: moveBg 90s linear infinite;
  -webkit-animation: moveBg 90s linear infinite;
}
    </style>

			<script>
﻿alert("ACKNOWLEDGEMENT:This app is Entirely based on IS456:2000 and IS10262:1982.")

function myfunc() {
	event.preventDefault()
   var par=document.getElementsByName('grade')[0];
   var index=par.selectedIndex
   var fck =parseInt(par.options[index].value);
   if (fck==10){
	   var s=3.5;
   }else if (fck==15){
	   var s=3.5;
   }else if (fck==20){
	   var s=4;
   }else if (fck==25){
	   var s=4;
   }else if (fck==30){
	   var s=5;
   }else if (fck==35){
	   var s=5;
   }else if (fck==40){
	   var s=5;
   }else if (fck==45){
	   var s=5;
   }else if (fck==50){
	   var s=5;
   }else if (fck==55){
	   var s=5;
   }
   console.log(fck+1.65*s);
   
   
   var pblr=document.getElementsByName('gradec')[0];
   		var index=pblr.selectedIndex
   		var fckc =(pblr.options[index].text);
   		console.log(fckc);
   
   var puur=document.getElementsByName('type of cement')[0];
   var index=puur.selectedIndex
   var tcement =(puur.options[index].text);
   
   if (tcement=="Ordinary Portland Cement"){
   		if (fckc=="OPC 33" && fck==10){
	   		var wcrc=.70;
   		}else if (fckc=="OPC 33" && fck==15){
	   		var wcrc=.575;
   		}else if (fckc=="OPC 33" && fck==20){
	   		var wcrc=.50;
   		}else if (fckc=="OPC 33" && fck==25){
	   			var wcrc=.425;
   		}else if (fckc=="OPC 33" && fck==30){
	   			var wcrc=.37;
	   	}else if(fckc=="OPC 33" && fck>30){
	   			alert("For The given Grade OPC 33 grade cement is inefficient. Please go for higher Grade of Cement");
	   	}
	   	else if (fckc=="OPC 43" && fck==10){
	   			alert("For M10 grade Concrete OPC 33 grade is recommended. Please change the Grade of Cement to OPC 33");
   		}else if (fckc=="OPC 43" && fck==15){
	   			var wcrc=.65;
   		}else if (fckc=="OPC 43" && fck==20){
	   			var wcrc=.58;
   		}else if (fckc=="OPC 43" && fck==25){
	   			var wcrc=.50;
   		}else if (fckc=="OPC 43" && fck==30){
	   			var wcrc=.45;
   		}else if (fckc=="OPC 43" && fck==35){
	   			var wcrc=.40;
   		}else if (fckc=="OPC 43" && fck==40){
	   			var wcrc=.36;
   		}else if(fckc=="OPC 43" && fck>40){
   				alert("For The given Grade OPC 43 grade cement is inefficient. Please go for higher Grade of Cement");
   		}else if (fckc=="OPC 53" && fck==10){
	   			alert("For M10 grade Concrete OPC 33 grade is recommended. Please change the Grade of Cement to OPC 33");
   		}else if (fckc=="OPC 53" && fck==15){
	   			alert("For M15 grade Concrete OPC 53 grade is not recommended. Please go for less Grade of Cement");
   		}else if (fckc=="OPC 53" && fck==20){
	   			var wcrc=.635;
   		}else if (fckc=="OPC 53" && fck==25){
	   			var wcrc=.575;
   		}else if (fckc=="OPC 53" && fck==30){
	   			var wcrc=.515;
   		}else if (fckc=="OPC 53" && fck==35){
	   			var wcrc=.47;
   		}else if (fckc=="OPC 53" && fck==40){
	   			var wcrc=.425;
   		}else if (fckc=="OPC 53" && fck==45){
	   			var wcrc=.39;
   		}else if (fckc=="OPC 53" && fck==50){
	   			var wcrc=.355;
   		}else if (fckc=="OPC 53" && fck==55){
	   			var wcrc=.32;
   		}
   		console.log(fckc);
   
   }else if (tcement=="Portland Pozzolana Cement"){
		if (fckc=="31.9-36.8" && fck==10){
	   		var wcrc=.70;
   		}else if (fckc=="31.9-36.8" && fck==15){
	   		var wcrc=.575;
   		}else if (fckc=="31.9-36.8" && fck==20){
	   		var wcrc=.50;
   		}else if (fckc=="31.9-36.8" && fck==25){
	   			var wcrc=.425;
   		}else if (fckc=="31.9-36.8" && fck==30){
	   			var wcrc=.37;
	   	}else if(fckc=="31.9-36.8" && fck>30){
	   			alert("For The given Grade of PPC for the given strength is inefficient. Please go for higher Grade of Cement");
	   	}else if (fckc=="36.8-41.7" && fck==10){
	   		alert("For M10 grade Concrete lower PPC grade is recommended. Please change the Grade of Cement to lower grade of PPC");
   		}else if (fckc=="36.8-41.7" && fck==15){
	   		var wcrc=.61;
   		}else if (fckc=="36.8-41.7" && fck==20){
	   		var wcrc=.535;
   		}else if (fckc=="36.8-41.7" && fck==25){
	   			var wcrc=.46;
   		}else if (fckc=="36.8-41.7" && fck==30){
	   			var wcrc=.41;
	   	}else if (fckc=="36.8-41.7" && fck==35){
	   			var wcrc=.36;
	   	}else if(fckc=="36.8-41.7" && fck>35){
	   			alert("For The given Grade of PPC for the given strength is inefficient. Please go for higher Grade of Cement");
	   	}
	   	
	   	
	   	//////////////
	   	
	   	
	   	
	   	
	   	else if (fckc=="41.7-46.6" && fck==10){
	   			alert("For M10 grade Concrete lower PPC grade is recommended. Please change the Grade of Cement to lower grade of PPC");
   		}else if (fckc=="41.7-46.6" && fck==15){
	   			var wcrc=.65;
   		}else if (fckc=="41.7-46.6" && fck==20){
	   			var wcrc=.58;
   		}else if (fckc=="41.7-46.6" && fck==25){
	   			var wcrc=.50;
   		}else if (fckc=="41.7-46.6" && fck==30){
	   			var wcrc=.45;
   		}else if (fckc=="41.7-46.6" && fck==35){
	   			var wcrc=.40;
   		}else if (fckc=="41.7-46.6" && fck==40){
	   			var wcrc=.36;
   		}else if(fckc=="41.7-46.6" && fck>40){
   				alert("For The given Grade PPC cement is inefficient. Please go for higher Grade of Cement");
   		}
   		
   		
   		////////////{}
   		
   		else if (fckc=="46.6-51.5" && fck==10){
	   			alert("For M10 grade Concrete lower PPC grade is recommended. Please change the Grade of Cement to lower grade of PPC");
   		}else if (fckc=="46.6-51.5" && fck==15){
	   			alert("For M15 grade Concrete lower PPC grade is recommended. Please change the Grade of Cement to lower grade of PPC");
   		}else if (fckc=="46.6-51.5" && fck==20){
	   			var wcrc=.61;
   		}else if (fckc=="46.6-51.5" && fck==25){
	   			var wcrc=.55;
   		}else if (fckc=="46.6-51.5" && fck==30){
	   			var wcrc=.485;
   		}else if (fckc=="46.6-51.5" && fck==35){
	   			var wcrc=.43;
   		}else if (fckc=="46.6-51.5" && fck==40){
	   			var wcrc=.385;
   		}else if (fckc=="46.6-51.5" && fck==45){
	   			var wcrc=.36;
   		}else if(fckc=="46.6-51.5" && fck>45){
   				alert("For The given Grade PPC cement is inefficient. Please go for higher Grade of Cement");
   		}
   		
   		
   		
   		
   		
   		
   		
   		
   		
   		
   		
   		
   		
   		else if (fckc=="51.5-56.4" && fck==10){
	   			alert("For M10 grade Concrete lower PPC grade is recommended. Please change the Grade of Cement to lower grade of PPC");
   		}else if (fckc=="51.5-56.4" && fck==15){
	   			alert("For M15 grade Concrete lower PPC grade is recommended. Please change the Grade of Cement to lower grade of PPC");
   		}else if (fckc=="51.5-56.4" && fck==20){
	   			var wcrc=.635;
   		}else if (fckc=="51.5-56.4" && fck==25){
	   			var wcrc=.575;
   		}else if (fckc=="51.5-56.4" && fck==30){
	   			var wcrc=.515;
   		}else if (fckc=="51.5-56.4" && fck==35){
	   			var wcrc=.47;
   		}else if (fckc=="51.5-56.4" && fck==40){
	   			var wcrc=.425;
   		}else if (fckc=="51.5-56.4" && fck==45){
	   			var wcrc=.39;
   		}else if (fckc=="51.5-56.4" && fck==50){
	   			var wcrc=.355;
   		}else if (fckc=="51.5-56.4" && fck==55){
	   			var wcrc=.32;
   		}
   		
   		////////////
   		else if (fckc=="56.4-61.3" && fck==10){
	   			alert("For M10 grade Concrete lower PPC grade is recommended. Please change the Grade of Cement to lower grade of PPC");
   		}else if (fckc=="56.4-61.3" && fck==15){
	   			alert("For M15 grade Concrete lower PPC grade is recommended. Please change the Grade of Cement to lower grade of PPC");
   		}else if (fckc=="56.4-61.3" && fck==20){
	   			alert("For M20 grade Concrete lower PPC grade is recommended. Please change the Grade of Cement to lower grade of PPC");
   		}else if (fckc=="56.4-61.3" && fck==25){
	   			var wcrc=.595;
   		}else if (fckc=="56.4-61.3" && fck==30){
	   			var wcrc=.54;
   		}else if (fckc=="56.4-61.3" && fck==35){
	   			var wcrc=.49;
   		}else if (fckc=="56.4-61.3" && fck==40){
	   			var wcrc=.45;
   		}else if (fckc=="56.4-61.3" && fck==45){
	   			var wcrc=.42;
   		}else if (fckc=="56.4-61.3" && fck==50){
	   			var wcrc=.375;
   		}else if (fckc=="56.4-61.3" && fck==55){
	   			var wcrc=.34;
   		}
   		///////////
  
	}
	
   console.log(fckc);
   console.log(wcrc);
   
   
   
   
   
   var per=document.getElementsByName('type of concrete')[0];
   var index=per.selectedIndex
   var tof =(per.options[index].text);
   if (tof=="Plain Cement Concrete"){
	   var toc="pcc"
   }else if(tof="Reinforced Cement Concrete"){
   		var toc="rcc"
   }
   console.log(toc);
   
   
   
   
   
   
   
   var pir=document.getElementsByName('Exposure Condition')[0];
   var index=pir.selectedIndex
   var exp =(pir.options[index].text);
   if (exp=="Mild"){
	   var expsr="mild";
   }else if (exp=="Moderate"){
	   var expsr="moderate";
   }else if (exp=="Severe"){
	   var expsr="severe";
   }else if (exp=="Very Severe"){
	   var expsr="very severe";
   }else if (exp=="Extreme"){
	   var expsr="extreme";
   }
   console.log(expsr);
   
   
   
   
   
   
   if (toc=="pcc"){
	   if (expsr=="mild"){
		   var micc=0;
		   var maw=.60;
		   var mcc=220;
	   }else if (expsr=="moderate"){
		   var micc=15;
		   var maw=.60;
		   var mcc=240;
	   }else if (expsr=="severe"){
		   var micc=20;
		   var maw=.50;
		   var mcc=250;
	   }else if (expsr=="very severe"){
		   var micc=20;
		   var maw=.45;
		   var mcc=260;
	   }else if (expsr=="extreme"){
		   var micc=25;
		   var maw=.40;
		   var mcc=280;
	   }
   }
   if (toc=="rcc"){
	   if (expsr=="mild"){
		   var micc=20;
		   var maw=.55;
		   var mcc=300;
	   }else if (expsr=="moderate"){
		   var micc=25;
		   var maw=.50;
		   var mcc=300;
	   }else if (expsr=="severe"){
		   var micc=30;
		   var maw=.45;
		   var mcc=320;
	   }else if (expsr=="very severe"){
		   var micc=35;
		   var maw=.45;
		   var mcc=340;
	   }else if (expsr=="extreme"){
		   var micc=40;
		   var maw=.40;
		   var mcc=360;
	   }
   }
   console.log(micc);
   console.log(maw);
   console.log(mcc);
   
   
   if (wcrc<maw){
	   var maw=wcrc;
   }else{
	   var maw=maw;
   }
   
   
   
   
   if (micc>=fck){
	   alert("The given Grade is Less than the Minimum Grade. Please Change the Grade before proceeding or the Design may fail")
   }
   
   
   
   
   
   
   
   
   var por=document.getElementsByName('Size of Aggregate')[0];
   var index=por.selectedIndex
   var sag =parseInt(por.options[index].value);
   
   if (sag==10){
	   var wc=208;
	   var mcc=mcc+40;
	   var p=950;
   }else if (sag==20){
   		var wc=186;
   		var p=980;
   }else if (sag==40){
	   var wc=165;
	   var mcc=mcc-30;
	   var p=990;
   }
   console.log(wc);
   console.log(mcc);
   
   
   
   
   
   
   
   
   var pur=document.getElementsByName('zone')[0];
   var index=pur.selectedIndex
   var z =(pur.options[index].value);
	
	
	
	
	
	if (sag==10){
		if (z=="15-34"){
			var cfa=.44;
		}else if (z=="35-59"){
			var cfa=.46;
		}else if (z=="60-79"){
			var cfa=.48;
		}else if (z=="80-100"){
			var cfa=.50;
		}
	}else if (sag==20){
		if (z=="15-34"){
			var cfa=.60;
		}else if (z=="35-59"){
			var cfa=.62;
		}else if (z=="60-79"){
			var cfa=.64;
		}else if (z=="80-100"){
			var cfa=.66;
		}
	}if (sag==40){
		if (z=="15-34"){
			var cfa=.69;
		}else if (z=="35-59"){
			var cfa=.71;
		}else if (z=="60-79"){
			var cfa=.73;
		}else if (z=="80-100"){
			var cfa=.75;
		}
	}
	console.log(cfa);
	
	
	
	
	
	
	
	
	var paar=document.getElementsByName('Slump Needed')[0];
   var index=paar.selectedIndex
   var slmp = parseInt(paar.options[index].value);
	var c1t=((slmp-50)/25)*3;
	console.log(c1t);
	
	
	
	
	
	var peer=document.getElementsByName('Superplasticizer Used?')[0];
   var index=peer.selectedIndex
   var spu =(peer.options[index].text);
   if (spu=="Yes"){
	   const piir= 	document.getElementById('%1spw').value;
		var c2t= parseFloat(piir);
		console.log(c2t);
		
		
		var paer=document.getElementsByName('n')[0];
   var index=paer.selectedIndex
   var n = parseInt(paer.options[index].value);
	
	
		if (c2t<0|| c2t>100){
			alert("% Water reduced by 1% of Superplasticizer should be between 0 to 100. Please Change it before proceeding");
document.getElementById("%1spw").defaultValue = "0";

		}
   }else if(spu=="No"){
	   var c2t= 0;
	   var n=0;
   }
   var spcon= n*c2t;
   console.log(spcon);
   
   
   
   
   
   
   
   
   var watercontentba= wc+(c1t*wc/100);
   console.log(watercontentba);
   
   
   var watercontent= watercontentba+(-spcon*watercontentba/100);
   console.log(watercontent);
   
   
   var cementcontent = watercontent/maw;
   console.log(cementcontent)
   
   
   if (cementcontent>=mcc){
	   var fcementcontent = cementcontent;
   }else{
	   var fcementcontent = mcc;
   }
   console.log(fcementcontent);
   
   
   
   
  	var puur=document.getElementsByName('type of cement')[0];
   var index=puur.selectedIndex
   var tcement =(puur.options[index].text);
   
   
   
   
   if (tcement=="Ordinary Portland Cement"){
	   var spc=3.15;
	   var finalcementcontent= fcementcontent;
	   var flyashcontent= 0;
	   var cementy=fcementcontent;
   }else if (tcement=="Portland Pozzolana Cement"){
	   var spc=2.9;
	   var cementy = fcementcontent+fcementcontent/10;
		var finalcementcontent=cementy*.7;
		var flyashcontent=cementy*.3;
   }
   console.log(spc);
   console.log(finalcementcontent);
   console.log(flyashcontent);
   console.log(cementy);
   
   
   var spf=2.2;
   console.log(spf);
   
   var spsp=1.145;
   console.log(spsp);
   
   
   const paaar= 	document.getElementById('wowc').value;
	var wowc= parseFloat(paaar);
	console.log(wowc);
   if (paaar.length == 0){
		 alert("Weight of Water for testing Coarse Aggregate is must. Please Enter it");
   
   }
   
   const peeer= 	document.getElementById('dwwc').value;
	var dwwc= parseFloat(peeer);
	console.log(dwwc);
   if (peeer.length == 0){
		 alert("Weight of Water with Aggregate for testing Coarse Aggregate is must. Please Enter it");
   
   }
   
   var dc= dwwc-wowc;
   console.log(dc);
   
   
   if (dc<0){
	   alert("Weight of Water with Aggregate cannot be smaller than the Weight of Aggregate. please change it in Coarse Aggregate section before proceeding or the Design may be wasted")
   }
   
   
   
   const piiir= 	document.getElementById('ssdc').value;
	var ssdc= parseFloat(piiir);
	console.log(ssdc);
   if (piiir.length == 0){
		 alert("Saturated Surface Dry Weight for testing Coarse Aggregate is must. Please Enter it");
   
   }
   
   
   const pooor= 	document.getElementById('odwc').value;
	var odwc= parseFloat(pooor);
	console.log(odwc);
   if (pooor.length == 0){
		 alert("Oven Dry Weight for testing Coarse Aggregate is must. Please Enter it");
   
   }
   
   
   const puuur= 	document.getElementById('wowf').value;
	var wowf= parseFloat(puuur);
	console.log(wowf);
   if (puuur.length == 0){
		 alert("Weight of Water for testing Fine Aggregate is must. Please Enter it");
   
   }
   
   const paaaar= 	document.getElementById('dwwf').value;
	var dwwf= parseFloat(paaaar);
	console.log(dwwf);
   if (paaaar.length == 0){
		 alert("Weight of Water with Aggregate for testing Fine Aggregate is must. Please Enter it");
   
   }
   
   var df= dwwf-wowf;
   console.log(df);
   
   
   if (df<0){
	   alert("Weight of Water with Aggregate cannot be smaller than the Weight of Aggregate. please change it in Fine Aggregate section before proceeding or the Design may be wasted")
   }
   
   
   
   const peeeer= 	document.getElementById('ssdf').value;
	var ssdf= parseFloat(peeeer);
	console.log(ssdf);
   if (peeeer.length == 0){
		 alert("Saturated Surface Dry Weight for testing Fine Aggregate is must. Please Enter it");
   
   }
   
   
   const piiiir= 	document.getElementById('odwf').value;
	var odwf= parseFloat(piiiir);
	console.log(odwf);
   if (piiiir.length == 0){
		 alert("Oven Dry Weight for testing Fine Aggregate is must. Please Enter it");
   
   }
   
   
   
   var spca= odwc/(ssdc-dc);
   console.log(spca);
   
   var spfa= odwf/(ssdf-df);
   console.log(spfa);
   
   var wr = (.5-maw)*20;
   var cfa = cfa+(cfa*wr/100);
   console.log(cfa);
   
   
   
   
   var poooor=document.getElementsByName('method of placing')[0];
   var index=poooor.selectedIndex
   var tom =(poooor.options[index].text);
   if (tom=="Pumping Method"){
	   var cfa= cfa-(cfa/10);
   }else if (tom=="Non-Pumping Method"){
	   var cfa=cfa;
   }
   
   
   
   
   
   var ca=(p-watercontent-(finalcementcontent/spc)-(flyashcontent/spf)-(n/100*watercontent)/spsp)*spca*cfa;
	console.log(ca);
   
   var fa=(p-watercontent-(finalcementcontent/spc)-(flyashcontent/spf)-(n/100*watercontent)/spsp)*spca*(1-cfa);
	console.log(fa);
   
   
   var Mcc= (1-odwc)/odwc;
   console.log(Mcc);
   
   var Mcf= (1-odwf)/odwf;
   console.log(Mcf);
   
   var Ac = (ssdc-odwc)/odwc;
   console.log(Ac);
   
   var Af= (ssdf-odwf)/odwf;
   console.log(Af);
   
   var fca= (ca+ca*Mcc);
   console.log(fca);
   
   var ffa= (fa+fa*Mcf);
   console.log(ffa);
   
   var fwatercontent = watercontent-((ca*(Mcc-Ac))+(fa*(Mcf-Af)));
   console.log(fwatercontent);
   
   
   var cementr=cementy/cementy;
   var ffar= (ffa/cementy).toFixed(2);
   var fcar=(fca/cementy).toFixed(2);
   var wcr=(fwatercontent/cementy).toFixed(2);
   
  
   var c=console.log(cementr);
   var f=console.log(ffar);
   var cc=console.log(fcar);
   var w=console.log(wcr);
	var result = console.log("Ratio:"+cementr+":"+ffar+":"+fcar+":"+wcr);
   	document.getElementById("txtresult1").value= cementr;
   
   document.getElementById("txtresult2").value= ffar;

	document.getElementById("txtresult3").value= fcar;

	document.getElementById("txtresult4").value= wcr;


	

	








	

	

	




	/////////////////////////////
	////////////////////////////
	////////////////
	
	
	
	
	
	var checkBox=document.getElementById("action");
	
	
	
 	console.log(slmp);
 	
   
   
   
   if (checkBox.checked == true){
   		var aft="ok";
   
   }else{ 
	   var aft="no";
   }
   
   if (aft=="ok"){
   
	if (n!=0){
	const puuuur= 	document.getElementById('Slump Obtained by 1%').value;
	var slump1= parseFloat(puuuur);
	console.log(slump1);
   if (puuuur.length == 0){
		 alert("Slump Obtained by 1% is must for calculation of % of superplasiticer. Please Enter it");
   
   }
   
   
   
   const paaaaar= 	document.getElementById('Slump Obtained by 2%').value;
	var slump2= parseFloat(paaaaar);
	console.log(slump2);
   if (puuuur.length == 0){
		 alert("Slump Obtained by 2% is must for calculation of % of superplasiticer. Please Enter it");
   
   }
   
   
   var slmpa= slump1-10;
   var slmpb= slump1+10;
   var slmpc= slump2-10;
   var slmpd= slump2+10;
   console.log(slmpa);
   console.log(slmpb);
   console.log(slmpc);
   console.log(slmpd);
   
   
	if (slmpa<=slmp && slmp<=slmpb){
		var n=1;
	}else if (slmpc<=slmp && slmp<=slmpd){
		var n=2;
	}
	else{
		var spv=(slmp-slump2)/(slump2-slump1);
		var n=2+spv;
	}
	console.log(n);
	
	
	var spcon= n*c2t;
   console.log(spcon);
	
	
	var watercontentba= wc+(c1t*wc/100);
   console.log(watercontentba);
   
   
   var watercontent= watercontentba+(-spcon*watercontentba/100);
   console.log(watercontent);
   
   
   
   
   var cementcontent = watercontent/maw;
   console.log(cementcontent)
   
   
   if (cementcontent>=mcc){
	   var fcementcontent = cementcontent;
   }else{
	   var fcementcontent = mcc;
   }
   console.log(fcementcontent);
	
	
	if (tcement=="Ordinary Portland Cement"){
	   var spc=3.15;
	   var finalcementcontent= fcementcontent;
	   var flyashcontent= 0;
	   var cementy=fcementcontent;
   }else if (tcement=="Portland Pozzolana Cement"){
	   var spc=2.9;
	   var cementy = fcementcontent+fcementcontent/10;
		var finalcementcontent=cementy*.7;
		var flyashcontent=cementy*.3;
   }
   console.log(spc);
   console.log(finalcementcontent);
   console.log(flyashcontent);
   console.log(cementy);
	
	var ca=(p-watercontent-(finalcementcontent/spc)-(flyashcontent/spf)-(n/100*watercontent)/spsp)*spca*cfa;
	console.log(ca);
   
   var fa=(p-watercontent-(finalcementcontent/spc)-(flyashcontent/spf)-(n/100*watercontent)/spsp)*spca*(1-cfa);
	console.log(fa);
	
	
	var fca= (ca+ca*Mcc);
   console.log(fca);
   
   var ffa= (fa+fa*Mcf);
   console.log(ffa);
   
   var fwatercontent = watercontent-((ca*(Mcc-Ac))+(fa*(Mcf-Af)));
   console.log(fwatercontent);
	
	var cementr=cementy/cementy;
   var ffar= (ffa/cementy).toFixed(2);
   var fcar=(fca/cementy).toFixed(2);
   var wcr=(fwatercontent/cementy).toFixed(2);
   
  
   var c=console.log(cementr);
   var f=console.log(ffar);
   var cc=console.log(fcar);
   var w=console.log(wcr);
	var result = console.log("Ratio:"+cementr+":"+ffar+":"+fcar+":"+wcr);
   	document.getElementById("txtresult1").value= cementr;
   
   document.getElementById("txtresult2").value= ffar;

	document.getElementById("txtresult3").value= fcar;

	document.getElementById("txtresult4").value= wcr;
	
	document.getElementById("txtresult5").value= n;
	
	
	///////////////////////
	///////////////////
	//////////////////
	
	
	
 	console.log(slmp);
 	
   
 	
   if (document.getElementById('actiona').checked) {
  var ball = document.getElementById('actiona').value;
}
   
   console.log(ball);
   if (ball=="done"){
   		var last="done";
   
   }else{
	   var last="doneilla";
   }
   
   
   
   
   
   
   
   
   
   

   if (last=="done"){
	   
	   
	   const pdr= 	document.getElementById('Slump Obtained').value;
	var slump3= parseFloat(pdr);
	console.log(slump3);
   if (pdr.length == 0){
		 alert("Slump Obtained is must for calculation of % of superplasiticer. Please Enter it");
   
   }
	   
	   
		const ballj=document.getElementById('spusedfind').value;
		var n= parseFloat(ballj);
		
		var slmpe= slump3-10;
   		var slmpf= slump3+10;
	   
	   
	   	if (slmpe<=slmp && slmp<=slmpf){
		var n=n;
	}
	else{
		
		
		var spv=(slmp-slump3)*(2-n)/(slump2-slump3);
		var n=n+spv;
	}
	console.log(n);
	   
	   
	   var spcon= n*c2t;
   console.log(spcon);
	
	
	var watercontentba= wc+(c1t*wc/100);
   console.log(watercontentba);
   
   
   var watercontent= watercontentba+(-spcon*watercontentba/100);
   console.log(watercontent);
   
   
   
   
   var cementcontent = watercontent/maw;
   console.log(cementcontent)
   
   
   if (cementcontent>=mcc){
	   var fcementcontent = cementcontent;
   }else{
	   var fcementcontent = mcc;
   }
   console.log(fcementcontent);
	
	
	if (tcement=="Ordinary Portland Cement"){
	   var spc=3.15;
	   var finalcementcontent= fcementcontent;
	   var flyashcontent= 0;
	   var cementy=fcementcontent;
   }else if (tcement=="Portland Pozzolana Cement"){
	   var spc=2.9;
	   var cementy = fcementcontent+fcementcontent/10;
		var finalcementcontent=cementy*.7;
		var flyashcontent=cementy*.3;
   }
   console.log(spc);
   console.log(finalcementcontent);
   console.log(flyashcontent);
   console.log(cementy);
   
   
   console.log(p);
   console.log(spf);
   console.log(spca);
   console.log(cfa);
	
	var ca=(p-watercontent-(finalcementcontent/spc)-(flyashcontent/spf)-(n/100*watercontent)/spsp)*spca*cfa;
	console.log(ca);
   
   var fa=(p-watercontent-(finalcementcontent/spc)-(flyashcontent/spf)-(n/100*watercontent)/spsp)*spca*(1-cfa);
	console.log(fa);
	
	
	var fca= (ca+ca*Mcc);
   console.log(fca);
   
   var ffa= (fa+fa*Mcf);
   console.log(ffa);
   
   var fwatercontent = watercontent-((ca*(Mcc-Ac))+(fa*(Mcf-Af)));
   console.log(fwatercontent);
	
	var cementr=cementy/cementy;
   var ffar= (ffa/cementy).toFixed(2);
   var fcar=(fca/cementy).toFixed(2);
   var wcr=(fwatercontent/cementy).toFixed(2);
   
  
   var c=console.log(cementr);
   var f=console.log(ffar);
   var cc=console.log(fcar);
   var w=console.log(wcr);
	var result = console.log("Ratio:"+cementr+":"+ffar+":"+fcar+":"+wcr);
   	document.getElementById("txtresult1").value= cementr;
   
   document.getElementById("txtresult2").value= ffar;

	document.getElementById("txtresult3").value= fcar;

	document.getElementById("txtresult4").value= wcr;
	
	document.getElementById("txtresult5").value= n;

   document.getElementById("txtresult5").value= n;
	   
   }else if (last="doneilla"){
	   
   }
   
   
   
   
   
  

	
	}
	
	
	
	}else if(aft=="no"){
		
	}
	

		
	
}
</script>
</body>
</html>

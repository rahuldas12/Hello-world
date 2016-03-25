

<html>
<head>
<title>Hello</title>

<style>

body 
	{  
    background-image:url("swingmation-wip.gif");
    background-repeat:no-repeat;
    background-top:0px;
    background-size:300px;
    background-attachment:fixed;
    background-position: 25% 75%;
    background-position:center;
}

*	{	
	margin:0px;
	padding:0px;
	}
			
				

body
	{
	font-family:verdona;
	background-color:#E6E6E6;
	padding:0px

	}

h1	{                     /* editing  Heding menu  line*/
	color:#585858;
	font-family:Chiller;
	text-align:center;
	border-bottom:2px solid #009;
	margin-bottom:8px;    /* menu up and down section */
	}

header {
	position: fixed;
	width: 100%; /* this ensures the header is fully as wide as the display window */
	background-color: #0FF;
	margin: -50px; /* this negative margin negates the 50px padding on the body of the page */
	padding-bottom: 30px;
	}

section {
	clear: both;
	margin-top:150px; /* this ensures the readable content clears the fixed header so user can see all */
	}
	
ul#navmenu {
	
	width:645px;
	margin:0px auto;
	}
	
ul#navmenu, ul.sub1, ul.sub2	{
	list-style-type: none;
	font-size:10pt;
	}
                             /*new menu letter change*/
ul#navmenu li {
	width:125px;
	text-align:center;
	position:relative;
	float:left; 
	margin-right:3px;
	font-size:150%;
	font-family:Gabriola;
	}
							/*menu background color*/
ul#navmenu a {
	text-decoration:none;
	display:block;
	width:125px;
	height:25px;
	line-height:25px;
	background-color:white;
	border:1px solid white;
	border-radios:5px;
	}
	
ul#navmenu .sub li {
	}
						/* horizential hover menu button height and weight */
ul#navmenu .sub1 a {
	margin-top:5px;
	}
	
ul#navmenu .sub2 a {
	margin-left:10px; 
	}
	
ul#navmenu li:hover> a {
	background-color:#E6E6E6;
	}
	
ul#navmenu li:hover a:hover {
	backround-color:#BDBDBD;
	}
	
ul#navmenu ul.sub1 {
	display:none;
	position:absolute;
	top:26px;
	left:0px;
  }
						/* horzentail menu down menu section */
ul#navmenu ul.sub2 {
	display:block;
	position:absolute;
	top:32px;
	left:120px;
 }

ul#navmenu li:hover .sub1 {
	display:block;
	}

ul#navmenu .sub1 li:hover .sub2 {
	display:none;
        
        }

.darrow { 
         font-size:13pt;
         position:absolute;
         top:6px;
         right:0px;
         }

.rarrow {
        font-size:13pt;
         position:absolute;
         top:6px;
         right:0px;
		 
         }
		


</style>

</head>
<body>

 <h1>Welcome To My World</h1>

<ul id="navmenu">
	<li><a href="#">Home</a></li>
	<li><a href="#">Poem</a><span class="darrow">&#9660;</span>

	 <ul class="sub1">
	<li><a href="#">hyperlink 2.1</a></li>
	<li><a href="#">hyperlink 2.2</a></li>
	<li><a href="#">hyperlink 2.3</a>

	</ul>

	</li>
	<li><a href="#">Technology</a><span class="rarrow">&#9660;</span></li>
	<li><a href="#">Story</a><span class="rarrow">&#9660;</span>

	<ul class="sub1">

	<li><a href="#">Facebook</a></li>
	<li><a href="#">instagram</a><span class="darrow">&#9654;</span></li>
 	
	<ul class="sub2">
	<li><a href="#">Friends</a></li>
	<li><a href="#">About</a></li>

	</ul>

	</li>
	</ul>
	</li>

	<li><a href="#">Contract</a><span class="rarrow">&#9660;</span></li>
</ul>


</body>
</html>

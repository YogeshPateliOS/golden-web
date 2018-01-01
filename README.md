# golden-web
golden web

/*css*/

*{box-sizing: border-box;}

body{
	padding: 0;
	margin: 0;
}
.row, .container-fluid{
	padding-left: 0;
	padding-right: 0;
	margin-left: 0!important;
	
}
.bg{
background:url(../images/bg2.jpg) no-repeat center ;
background-attachment: scroll;
background-size: 100% 100%;
height: 700px;
width: 100%;
}
.bg-color{
	background-color: rgba(0,0,0,0.6);
	height: 100%;
}
.header{
	padding-top: 50px;
}
.header_top img{
	padding-top: 14px;
}

.navbar-dark .navbar-nav .nav-link {
    color: rgba(255,255,255,1);
    font-size: 14px;
}


.detail{
	margin-top: 200px;
	text-align: center;
}
.detail h2{
	font-size: 40px;
	font-family:"DroidSerif" ;
	font-style: italic;
	color:white;
}
.detail h1{
	font-size: 75px;
	font-family:"arial" ;
	font-weight: bold;
	font-style: normal;
	color:white;
}
.btn{
	font-size: 18px;
	color: white;
	background-color: #fed136;
	height: 65px;
	width: 240px;
}
.navbar-nav{
	padding-left: 200px;
}
.navbar-dark .navbar-toggler {
    color: rgba(255,255,255,.5);
    border-color: black;
}
.navbar-toggler {
    padding: .25rem .75rem;
    font-size: 1.25rem;
    line-height: 1;
    background: 0 0;
    border: 1px solid transparent;
    border-radius: .25rem;
}


/*services*/
.content_part{
	width: 70%;
}
.services{
	margin-top: 120px;
	text-align: center;
}
.services h1{
	font-size: 40px;
	font-family: "Montserrat", halvetica,arial;
	font-weight: bold;

}
.services > p{
	padding-top: 20px;
	font-size: 16px;
	font-family:"DroidSerif" ;
	font-style: italic;
	color: #9b9b9b;
}
.part1 p{
	padding-top: 20px;
	font-size: 14px;
	font-family:"RobotoSlab" ;
	font-style: normal;
	color: #9b9b9b;
	text-align: center;
}


.part1{
	padding-right: 35px;
}
.part1 h6{
	padding-top: 25px;
	font-size:18px ;
	font-family:"Montserrat", halvetica,arial; ;
	font-weight: bold;
}


.service1{
	margin-top: 80px;
}

/*count_part*/
.count_bg{
	background: url("../images/map_bg.jpg") no-repeat;
	background-attachment: scroll;
	background-size: 100% 100%;
	height: 300px;
	width: 100%;
	padding-right: 0;
	
}
.user{
	color: white;
	text-align: center;
	padding-top: 40px;

}
.user > span{
	font-size: 50px;
	padding-top:45px;
}
.user h2{
	padding-top: 25px;
}




.fullBackground {
  background-position: center center;
  background-attachment: scroll;
  background-size: 100% 100%;
  position: relative;
  top: 10px;
  right: 0;
  left: 0;
	width: 100%;
  height: 700px;
}

.head {
  font-size: 30pt;
  text-transform: uppercase;
  color: #fff;
  position: absolute;
  top:2500px ;
  left: 50%;
  transform: translate(-50%, -50%);
  color: red;
}

.head:after {
  content:"\A";
  width:10px;
  height:10px;
  border-radius:50%;
  background: #00bbeb;
  display: inline-block;
  
}






@media only screen and (max-width: 467px){
	
	.bg{
		height: 700px;
	}
	.header_top img{
	text-align: center;
	}

	
}
@media only screen and (max-width: 767px){

.header_top{
	width:50%;
	text-align: center;
}
.nav1{
	width:50%;
	background: black;
}

.count_bg{
		height: 700px;
	}

.detail{
	margin-top: 20px;
}
.user{
	padding-top: 3px!important;
}
.user > span{
	padding-top: 8px;
}
.user h2{
	padding-top: 2px;
}

@media only screen and (min-width: 567px) { 
.count_bg{
	height:310px;
}
.user > span{
	padding-top: 10px;

}
.navbar-nav{
	padding-left: 0;
}
}

@media only screen and (min-width: 768px) { 

.navbar-nav{
	
}

//Html link

<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width,initial-scale=1.0">
	<title>golden_web</title>
  <link rel="stylesheet" type="text/css" href="css/font-awesome.css">
  <link rel="stylesheet" type="text/css" href="css/font-awesome.min.css">
	<link rel="stylesheet" href="css/bootstrap.min.css">
  <script src="js/jquery-3.2.1.js"></script>
  <link rel="stylesheet" type="text/css" href="css/style.css">
  <script src="js/popper.min.js"></script>
  <script src="js/bootstrap.min.js"></script>
  <script src="js/jquery.min.js"></script>
 
</head>

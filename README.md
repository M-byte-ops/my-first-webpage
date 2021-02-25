<!doctype html>
<html>
<head>
<title>My First Webpage</title>
<style>

#nav{
background-color: purple;
height: 35px;
font-size: 25px;
font-weight: bold;
font:Tahoma;
}

#nav ul{
padding: 0;
margin: 0;
text-align: center;
}

#nav ul li{
display: inline;
padding: 20px;
vertical-align: middle;
}

#nav a{
padding: 8px 8px 8px 8px;
color: white;
vertical-align: middle;
}

#nav ul li a:hover{
background-color: black;
color: white;
}

#txt{
background-image: url(sea.jpg);
}

#form{
background-image: url(tourist.jpg);
}

h1, h2, h3{
color: black;
background-color:pink;
padding: 15px 15px 15px 15px;
font-family: verdana;
font-size: 25px;
font-weight: dark;
border: black 2px solid;
border-radius: 20px;
}

p.text{
font-size:25px;
text-align:center;
}


ol{
font-size:20px;
}


form{
background: linear-gradient(to top right, blue, pink, yellow);
border: black 2px solid;
border-radius:10px;
padding: 10px;
margin: 20px;
height:450;
overflow: scroll;
}

#footer{
background-image: url(color.jpg);
margin: 10px;
height:60px;
border-radius:10px;
color:black;
text-align: center;
padding: 15px;
font-size: 100%;
}

</style> 
</head>

<div id="nav">
<ul>
   <li><a href="">Home</a></li>
   <li><a href="">Links</a></li>
   <li><a href="">Forums</a></li>
   <li><a href="">Contacts</a></li>
</ul>
</div>

<body>

<div id="txt">

<h1> A to Z tours and travels</h1>
<p class="text"><img src="image.jpg" width="500" height="200"></p>
<P class="text 1"><b>Welcome to our tours and travels website.</b> 
<br>
<br>
<b<Live with no excuses and Travel with no regrets</b>
<br>
<b>We assure you a safe and happy journey with full memories</b>
<br>
<b>Your safety our first priority!!!</b>
</P>

<h2>Facilities we provide for your journey</h2>

<ol>
    <li> flight/train/bus tickets</li>
<br>
    <li> cab facility to your desired location</li>
<br>
    <li> hotel rooms with complementary breakfast</li>
<br>
    <li> tickets for tourist hotspot incase needed</li>
<br>
</ol>

<br>
<br>

</div>


<div id="form">

<h3>Give us your details</h3>
<form action=""method"">

<label for="First name">First name:</label>
<input type="text" id="First name" name="">
<br>
<br>

<label for="Last name">Last name:</label>
<input type="text" id="Last name" name="">
<br>

<br>
<br>
Gender:
<br>
<input type="checkbox" name="">male &nbsp &nbsp <input type="checkbox" name="">female &nbsp &nbsp <input type="checkbox" name="">transgender



<p>Are u willing to accept our services?</p>
yes:
<input type="radio" name="yes or no" value="">
no:
<input type="radio" name="yes or no" value="">
<br>
<br>

Enter the place you want to travel to:
<br>
<br>
<label for="Place">Place:</label>
<input type="text" id="Place" name="">
<br>
<br>

<label for="number of persons">number of persons:</label>
<input type="number" id="number of persons">
<br>
<br>

Enter the day you want to travel:
<input type="date" name="day">
<br>
<br>
number of days: <input type="number" name="numdays">
<br>
<br>
comments:
<br>
<br>
<textarea rows="15" cols="80"></textarea>
</br>
<input type="submit" value="submit">
</form>
</div>

<div id="footer">
&copy; 2014 Historyden.com 
<br>
All Rights Reserved
<br>
<B>Location: 54, abc road, xyz area, Coimbatore-12</B>
<br>
<B>Contact:9876543210</B>
</div>

</body>
</html>

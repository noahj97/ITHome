<html>
<head>
<title>CSS Template</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

header {
  background-color: gold;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: black;
}



article {
  float: left;
  padding: 20px;
  width: 70%;
  background-color: white;
  height: 300px;
}


section::after {
  content: "Created on the 15-12-21";
  display: table;
  clear: both;
}


footer {
  background-color: Gold;
  padding: 10px;
  text-align: center;
  color: black;}


</style>
</head>
<body>

<header>
<h2>Noah Etherington Home</h2>
</header>

<section>

  
<article>
<h1>Link Hub: Follow the links for more infomation</h1>
<p>
<a href="url">My Infomation</a>
</p>
<p>
<a href="url">Questions and Tests</a>
</p>
<p>
<a href="url">IT Project</a>
</p>  

</article>
</section>

<footer>
<p>"Fun Fact: Life goal is to summit all Abel mountains."</p>
</footer>

</body>
</html>

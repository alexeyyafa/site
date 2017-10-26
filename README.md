<!DOCTYPE html>
<html>
<head>
<title>welcome</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<meta charset="UTF-8">
<style>
* {
    box-sizing: border-box;
}
body {
    background-color: #F0FFFF;
    margin: 0;
}
ul {  
    padding: 0;
    overflow: hidden;
    background: linear-gradient(to right, #c5f0fa, #FFE4E1);
}
li {
    text-align: center;
}
li a {
    color: DodgerBlue;
    display: block;
    text-align: center;
    padding: 16px;
    text-decoration: none;
    margin: auto;
    width: 10%;
}
li a:hover {
    background: linear-gradient(to right, #c5f0fa , #FFE4E1);
}
details {
	text-align:center;
}
h1 {
    color: DodgerBlue;
}
iframe {
	max-width: 100%;
    height: auto;
}
</style>
</head>
<body>

<ul>
  <li><h1>Welcome</h1></li>
  <li><a href="https://www.google.com/" target="_blank">
<img src="http://media.idownloadblog.com/wp-content/uploads/2015/10/Google-app-icon-small.png" alt="google" style="width:50px;height:50px;"></a></li>
  <li><a href="https://www.instagram.com/alexey_yafa/" target="_blank"><img src="https://icon-icons.com/icons2/836/PNG/128/Instagram_icon-icons.com_66804.png" alt="instagram" style="width:50px;height:50px;"></a></li>
  <li><iframe width="400" src="https://www.youtube.com/embed/e5QYvSmMu_k">
</iframe></li>
</ul>

<details>
<summary style="text-align:center">Опрос:</summary>
<form action="#">
 <fieldset>
<legend>Как вам сайт?</legend>
  <input type="radio" name="value" value="идеальный"> Идеальный<br />
  <input type="radio" name="value" value="норм"> Норм<br />
  <input type="radio" name="value" value="не норм"> Не норм<br />
  <input type="submit" value="жмяк">
  </fieldset>
</form> 
</details>
</body>
</html>

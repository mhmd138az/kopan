<html lang="fa">
<head>
    <link rel="stylesheet" href="style.css">
<title>محمد</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
    * {
    box-sizing: border-box;
    }
    body {
    font-family: Arial, Helvetica, sans-serif;
    margin: 0;
    }
    .header {
    padding: 0.1px;
    text-align: center;
    background:#67408e;
    color: rgb(255, 255, 255);
    }
    .header h1 {
    font-size: 40px;
    }
    .navbar {
    overflow: hidden;
    background-color: #333;
    position: sticky;
    position: -webkit-sticky;
    top: 0;
    }
    .navbar a {
    float: left;
    display: block;
    color: rgb(255, 253, 256);
    text-align:center;
    padding: 3px 8px;
    text-decoration: none;
    }
    .navbar a.right {
    float: right;
    }
    .navbar a:hover {
    background-color: #13d9ef;
    color: rgb(0, 0, 0);
    }
    .navbar a.active {
    background-color: #666;
    color: rgb(255, 255, 255);
    }
    .row {
    display: -ms-flexbox; /* IE10 */
    display: flex;
    -ms-flex-wrap: wrap; /* IE10 */
    flex-wrap: wrap;
    }
    .side {
    -ms-flex: 30%; /* IE10 */
    flex: 30%;
    background-color: #e9e8d9;
    padding: 20px;
    }
    .main {
    -ms-flex: 70%; /* IE10 */
    flex: 70%;
    background-color:  rgb(194, 190, 157);
    padding: 20px;
    }
    .fakeimg {
    background-color: #934c4c;
    width: 100%;
    padding: 20px;
    }
    .footer {
    padding: 20px;
    text-align: center;
    background: #48515f;
    }
    @media screen and (max-width: 700px) {
    .row {
    flex-direction: column;
    }
    }
    @media screen and (max-width: 400px) {
    .navbar a {
    float: none;
    width: 100%;
    }
    }
    *{
    box-sizing: border-box;
    }
    .container{
    width: 300px;
    }
    input,select,textarea{
    width: 100%;
    margin: 0 0 10px 0;
    padding: 10px;
    }
    .btn1{
    background-color: green;
    color: #ffffff;
    }
    ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #281740;
    }
    li {
    float: left;
    }
    li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    }
    li a:hover {
    background-color: #0eccf6;
    }
    #search{
    width: 100%;
    height: 100%;
    position: fixed;
    top: 0;
    right: 0;
    background-color: rgba(0, 0, 0, 0.8);
display: none;
justify-content: center;
align-items: center;
}
#search:target{
    display: flex;
}
#search form{
    width: 100%;
    max-width: 300px;
    display: flex;
    flex-direction: column;
    gap: 1em;
}
#search input{
    width: 100%;
    border: none;
    padding: 0.5em 1em;
    border-radius: 0.5em;
}
#search div{
    display: flex;
    gap: 1em;
    justify-content:center;
}
#search a,
#search button{
    border:none;
    padding: 0,25em 1em;
    border-radius: 0,25em;
    color:black;
    font-weight: bold;
    cursor: pointer;
}
#search a{
    background-color: crimson;
}
#search button{
    background-color:chartreuse;
}
</style>
</head>
<body>
<div class="header">
<h1>نام سایت</h1>

<form action="">

<h2> <form id="form">
</form>
<p style="font-weight: bold">توضیح کوتاه درباره سایت</p>
<a href="#search">جستجو</a>
<div id="search">
    <form action="">
        <input type="text" placeholder="دنبال چه چیزی هستید؟">
        <div>
            <a href="">بستن</a>
            <botton></botton>
        </div>
    </form>
</div>
<body>
<ul>
<li><a class="active" href="#">خانه</a></li>
<li><a href="">تصاویر</a></li>
<li><a href="https://rubika.ir/alierza7086">ارتباط با ما</a></li>
</ul>

</body>
    
 <div class="row">
    <div class="side">
    <h5></h5>
    <div class="fakeimg" style="height:200px;"></div>
    <p>توضیحات</p>
    <h3>موضوع عکس</h3>
    <p>توضیحات</p>
    <div class="fakeimg" style="height:60px;">تصاویر</div><br> <a href="https://uploadkon.ir/" target="_blank" title="https://uploadkon.ir/"><img src="https://uploadkon.ir/uploads/4db919_24IMG-20240905-172137-615.jpg" border="0" alt="https://uploadkon.ir/uploads/4db919_24IMG-20240905-172137-615.jpg" /></a>
    <div class="fakeimg" style="height:60px;">تصویر</div><br>
    </div>
    <div class="main">
    <h2>موضوع تصویر</h2>
    <h5>تابستان۱۴۰۳</h5>
    <div class="fakeimg" style="height:200px;">تصاویر</div>  
    <p>توضیحات</p>
    <p><br>
    <h2>موضوع تصویر</h2>
    <h5>تابستان ۱۴۰۳</h5>
    <div class="fakeimg" style="height:200px;">تصاویر</div> <a href="https://uploadkon.ir/" target="_blank" title="https://uploadkon.ir/"><img src="https://uploadkon.ir/uploads/964519_24IMG-20240905-172126-172.jpg" border="0" alt="https://uploadkon.ir/uploads/964519_24IMG-20240905-172126-172.jpg" /></a>
  <div></div>
    <div class="footer">
    <h1>تماس با ما</h1>
    <h3>شماره تماس : 09178537782</h3>
    <h3>ایتا : @Mhmd1386az</h3>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">

</head>
<body>
<h2>ارتباط با ما</h2>
<div class="container">
<h3><form action="/action_page.php" method="post">
<label for="fname"></label>
<input type="text" id="fname" name="firstname" placeholder="نام">
<label for="lname"></label>
<input type="text" id="lname" name="lastname" placeholder="نام خانوادگی">
<label for="city"></label>
<select id=" city " name=" city ">
<option value="shiraz"> shiraz </option>
<option value="tehran"> tehran </option>
<option value="ahvaz"> ahvaz </option>
</select>
<label for="subject"></label>
<textarea id="subject" name="subject" placeholder="موضوع" style="height:150px"></textarea>
<input class="btn1" type="submit" value="ارسال">
</form>

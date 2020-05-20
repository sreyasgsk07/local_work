<!DOCTYPE html>
<html lang="en">
<head>
<title>GSK5 </title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Style the body */
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}

/* Header/logo Title */
.header {
  padding: 80px;
  text-align: center;
  background: #1abc9c;
  color: white;
}

/* Increase the font size of the heading */
.header h1 {
  font-size: 40px;
}

/* Style the top navigation bar */
.navbar {
  overflow: hidden;
  background-color: #333;
}

/* Style the navigation bar links */
.navbar a {
  float: left;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

/* Right-aligned link */
.navbar a.right {
  float: right;
}

/* Change color on hover */
.navbar a:hover {
  background-color: #ddd;
  color: black;
}

/* Column container */
.row, .mob_img_txt1_class, .mob_img_txt2_class, .comp_img_txt1_class, .comp_img_txt2_class, .hdst_img_txt1_class, .hdst_img_txt2_class, .tv_img_txt1_class, .tv_img_txt2_class, .wtch_img_txt1_class, .wtch_img_txt2_class {  
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
}

/* Create two unequal columns that sits next to each other */
/* Sidebar/left column */
.side {
  -ms-flex: 20%; /* IE10 */
  flex: 20%;
  background-color: #f1f1f1;
  padding: 20px;
}

/* Main column */
.main {   
  -ms-flex: 80%; /* IE10 */
  flex: 80%;
  background-color: white;
  padding: 20px;
}

/* Fake image, just for this example */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
}

/* Mobile img and text 1 */
.mob_img_txt1_class {   
  -ms-flex: 100%; /* IE10 */
  flex: 100%;
  background-color: white;
  align-items:flex-start;
  padding: 20px;
}

/* Mobile img and text 2 */
.mob_img_txt2_class {   
  -ms-flex: 100%; /* IE10 */
  flex: 100%;
  background-color: white;
  align-items:flex-start;
  padding: 20px;
}

/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 730px) {
  .row {   
    flex-direction: column;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 635px) {
  .navbar a {
    float: none;
    width: 100%;
  }
}


/* Responsive layout -  */
@media screen and (max-width: 500px) {
  .mob_img_txt1_class, .mob_img_txt2_class {
    float: none;
    width: 100%;
    flex-direction: column;
	align-items:center;
  }
}


</style>
</head>


<body>

<div class="notice">
<marquee attribute_name = "notice_value">
   ***Due to COVID-19 pandemic, delivery may delay for 2-3 days***
</marquee>
</div>

<div class="header">
  <h1>GSK5</h1>
  <p>You order We deliver</p>
</div>

<div class="navbar">
  <a href="#mobiles_id">Mobiles</a>
  <a href="#computers_id">Computers</a>
  <a href="#headsets_id">Headsets</a>
  <a href="#televisions_id">Televisions</a>
  <a href="#watches_id">Watches</a>
  <a href="#more_products_id" class="right">More</a>
</div>

<div class="row">

  <div class="side">
  
    <h3>BEST SELLING</h3>
        <input type="checkbox" id="checkbox_mobile" name="checkbox_mobile" value="Mobiles">
  		<label for="checkbox_mobile"> Mobiles</label><br>
  		<input type="checkbox" id="checkbox_computer" name="checkbox_computer" value="Computers">
 		<label for="checkbox_computer"> Computers</label><br>
  		<input type="checkbox" id="checkbox_headset" name="checkbox_headset" value="Headsets">
 		<label for="checkbox_headset"> Headsets</label><br>
        <input type="checkbox" id="checkbox_tv" name="checkbox_tv" value="Televisions">
 		<label for="checkbox_tv"> Televisions</label><br>
  		<input type="checkbox" id="checkbox_watches" name="checkbox_watches" value="Watches">
 		<label for="checkbox_watches"> Watches</label><br><br>
  		  
  </div>
  
  <div class="main">
  
   <div class="mobiles_class" id="mobiles_id" >
     <h2>MOBILES</h2>
     <div class="mob_class" id="mob_id" style="height:900px;">
      <div class="mob_img_txt1_class" id="mob_img_txt1_id" style="height:400px;">
       <img src="data:image/jpeg;base64,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" alt="Oneplus 7t pro" width="200" height="280">
       
        <div class="mob_txt1_class" id="mob_txt1_id" style="height:40px;">
        <p>Oneplus 7t pro</p>
        <p>M.R.P: Rs.53,999/-</p>
        <p>GSK PRICE: Rs.45,999/-</p>
        </div> 
       </div>
       
       <div class="mob_img_txt2_class" id="mob_img_txt2_id" style="height:400px;">
        <img src="data:image/jpeg;base64,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" alt="Apple iPhone 11 Pro Max" width="200" height="300">
     
     	<div class="mob_txt2_class" id="mob_txt2_id" style="height:40px;">
     	<p>Apple iPhone 11 Pro Max</p>
     	<p>M.R.P: Rs.1,09,900/-</p>
        <p>GSK PRICE: Rs.1,04,999/-</p>
        </div>
       </div>
     
     </div>
    
   </div> 
   
    <br>
    
    <div class="computers_class" id="computers_id">
    <h2>COMPUTERS</h2>
    <div class="comp_class" id="comp_id" style="height:900px;">
      <div class="comp_img_txt1_class" id="comp_img_txt1_id" style="height:400px;">
       <img src="" alt="comp1" width="200" height="300">
       
        <p>comp1</p>
        <p>M.R.P: Rs.53,999/-</p>
        <p>GSK PRICE: Rs.45,999/-</p>
       </div>
       
       <div class="comp_img_txt2_class" id="comp_img_txt2_id" style="height:400px;">
        <img src="" alt="comp2" width="200" height="300">
     
     	<p>comp2</p>
     	<p>M.R.P: Rs.1,09,900/-</p>
        <p>GSK PRICE: Rs.1,04,999/-</p>
       </div>
     
     </div>
    
    </div>
    
    <br>
    
    <div class="headsets_class" id="headsets_id" >
    <h2>HEADSETS</h2>
    <div class="hdst_class" id="hdst_id" style="height:900px;">
      <div class="hdst_img_txt1_class" id="hdst_img_txt1_id" style="height:400px;">
       <img src="" alt="hd1" width="200" height="300">
       
        <p>hd1</p>
        <p>M.R.P: Rs.53,999/-</p>
        <p>GSK PRICE: Rs.45,999/-</p>
       </div>
       
       <div class="hdst_img_txt2_class" id="hdst_img_txt2_id" style="height:400px;">
        <img src="" alt="hd2" width="200" height="300">
     
     	<p>hd2</p>
     	<p>M.R.P: Rs.1,09,900/-</p>
        <p>GSK PRICE: Rs.1,04,999/-</p>
       </div>
     
     </div>
    
    </div>
    
    <br>
    <div class="televisions_class" id="televisions_id">
    <h2>TELEVISIONS</h2>
    <div class="tv_class" id="tv_id" style="height:900px;">
      <div class="tv_img_txt1_class" id="tv_img_txt1_id" style="height:400px;">
       <img src="" alt="tv1" width="200" height="300">
       
        <p>tv1</p>
        <p>M.R.P: Rs.53,999/-</p>
        <p>GSK PRICE: Rs.45,999/-</p>
       </div>
       
       <div class="tv_img_txt2_class" id="tv_img_txt2_id" style="height:400px;">
        <img src="" alt="tv2" width="200" height="300">
     
     	<p>tv2</p>
     	<p>M.R.P: Rs.1,09,900/-</p>
        <p>GSK PRICE: Rs.1,04,999/-</p>
       </div>
     
     </div>
    
    </div>
    
    <br>
    <div class="watches_class" id="watches_id">
    <h2>WATCHES</h2>
    <div class="wtch_class" id="wtch_id" style="height:900px;">
      <div class="wtch_img_txt1_class" id="wtch_img_txt1_id" style="height:400px;">
       <img src="" alt="wtch1" width="200" height="300">
       
        <p>wtch1</p>
        <p>M.R.P: Rs.53,999/-</p>
        <p>GSK PRICE: Rs.45,999/-</p>
       </div>
       
       <div class="wtch_img_txt2_class" id="wtch_img_txt2_id" style="height:400px;">
        <img src="" alt="wtch2" width="200" height="300">
     
     	<p>wtch2</p>
     	<p>M.R.P: Rs.1,09,900/-</p>
        <p>GSK PRICE: Rs.1,04,999/-</p>
       </div>
     
     </div>
    
    </div>
    
    <br>
    <div class="more_products_class" id="more_products_id" >
    <h2>MORE PRODUCTS COMMING SOON.....</h2>    
    </div>
    
    
  </div>
</div>

<div class="footer">
  <p>Available at:<p>
  <p>Hyderabad<p>
  <p>Warangal<p>
  <p>Chennai<p>
  <p>Bangalore<p>
  <p>Thiruvananthapuram<p>
</div>

</body>
</html>


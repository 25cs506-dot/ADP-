# ADP
<!DOCTYPE html> 
<html> 
<head> 
<title>Student Registration Form</title> 
<style> 
* { 
box-sizing:border-box; 
} 
body, html { 
background:rgb(144, 238, 180); 
} 
.main-panel { 
width: 100%; 
max-width:550px; 
margin: 50px auto; 
background: rgb(255, 254, 235); 
padding:20px 10px 50px 20px; 
border-radius:5px; 
} 
h1 { 
font-size: 45px; 
text-align: center;
margin:5px; 
} 
.row { 
display:flex; 
justify-content: center; 
} 
.form-group { 
margin-top:20px; 
padding: 10px; 
flex-direction: column; 
display: flex; 
width: 100%; 
} 
input, select { 
width:100%; 
padding:10px; 
height:40px; 
border:1px solid rgba(1, 1, 2, 0.204); border-radius:5px; 
font-size: 16px; 
margin-top:5px; 
} 
input[type="radio"], input[type="checkbox"] { width: 17px; 
height:17px; 
margin-left:5px; 
position:relative;
top:2px; 
} 
button { 
border:none; 
width:50%; 
height:42px; 
font-size:16px; 
cursor:pointer; 
margin-top:40px; 
border-radius:5px; 
background: rgb(38, 255, 0); 
color: rgba(255, 255, 255, 0.771); } 
/* Mobile Version */ 
@media screen and (max-width: 600px) { .row { 
flex-wrap: wrap; 
} 
} 
</style> 
</head> 
<body>  
<div class="main-panel"> 
<h1>Student Registration Form </h1> <div class="row">
<div class="form-group"> <label>Student Name</label> <input type="text" /> 
</div> 
</div> 
<div class="row"> 
<div class="form-group"> <label>Mobile Number</label> <input type="text" /> 
</div> 
<div class="form-group"> <label>Email Id</label> 
<input type="text" /> 
</div> 
</div> 
<div class="row"> 
<div class="form-group"> <label>Father Name</label> <input type="text" /> 
</div> 
<div class="form-group"> <label>Mother Name</label> <input type="text" /> 
</div> 
</div> 
<div class="row"> 
<div class="form-group"> <label>Course</label>
<div> 
<select> 
<option>Html</option> 
<option>Css</option> 
<option>Java</option> 
<option>Python</option> 
<option>JavaScript</option> </select> 
</div> 
</div> 
<div class="form-group"> 
<label>Date Of Birth</label> <input type="date" /> 
</div> 
</div> 
<div class="row"> 
<div class="form-group"> 
<label>Gender</label> 
<div> 
<input type="radio" name="g" /> Male 
<input type="radio" name="g" /> Female </div> 
</div> 
</div> 
<div class="row"> 
<div class="form-group">
<label>Select Branch</label> 
<div> 
<input type="checkbox" /> 
CSE 
<input type="checkbox" /> 
IT 
<input type="checkbox" /> 
ECE 
<input type="checkbox" /> 
AIDS 
<input type="checkbox" /> 
Civil </div> 
</div> 
</div> 
<div class="row"> 
<div class="form-group"> 
<label>Address</label> 
<textarea style="height:110px;"></textarea> </div> 
</div> 
<div class="row"> 
<button type="submit">Submit</button> </div> 
</div> 
</body> 
</html>

# Registration-form
 <title>FORM</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="regform">REGISTRATION FORM</div>
    <div class="content">
        <form action="">
            <div id="name">
                <h2>Name</h2>
                <label class="firstlabel">first name</label>
                <input type="text" id="firstname" name="firstname">
                <label class="lastlabel">last name</label>
                <input type="text" id="lastname" name="lastname">
            </div>
            <h2>Company</h2>
            <input type="text" id="company" name="company">
            <h2>Email</h2>
            <input type="email" id="email" name="email">
            <h2>Phone</h2>
            <label class="areacode">Area code</label>
            <input type="text" id="code" name="areacode">
            <label class="phonenumber">phone number</label>
            <input type="tel" id="phone" name="phonenumber">
            <h2>Subject</h2>
            <select name="subject" id="subject">
                <option disabled="disabled" selected="selected">--choose option</option>
                <option value="subject 1">mathematics</option>
                <option value="subject 2">english</option>
                <option value="subject 3">yoruba</option>
            </select>
            <h3 id="question">Are you a beginner?</h2>
            <label class="yes">YES</label>
            <input type="radio" id="YES" name="question" value="YES">
            <label class="no">NO</label>
            <input type="radio" id="NO" name="question" value="NO">
            <button type="submit">Register</button>
        </form>
  </div>
    </body>
    
    *{
    margin: 0px;
    padding: 0px;
}
body{
    background-image: url(d.jpg);
    background-position: center;
    background-size: cover;
    font-family: sans-serif;
    margin-top: 40px;
}
.regform{
    width: 500px;
    background-color: rgb(83, 236, 147);
    margin: auto;
    color: rgb(8, 23, 66);
    padding-left: 270px;
    border-radius: 5px;
    font-style: italic;
    font-weight: 700;
    font-size: larger;
}
.content{
    background-color: rgb(105, 139, 211);
    width: 780px;
    margin: auto;
}
form{
    padding: 10px;
}
#name{
    width: 100%;
    height: 100px;
}
h2{
    margin-left: 25px;
    margin-top: 30px;
    color: white;
    width: 100px;
font-size: 18px;
font-weight: 600;
}
#firstname{
    position: relative;
    left: 200px;
    bottom: 25px;
    line-height: 30px;
    font-size: 16px;
    color: #555;
    border-radius: 5px;
}
#lastname{
    position: relative;
    left: 150px;
    bottom: 25px;
    line-height: 30px;
    font-size: 16px;
    color: #555;
    border-radius: 5px;
}
.firstlabel{
    position: relative;
    left: 300px;
    text-transform: capitalize;
    font-size: 14px;
    color: antiquewhite;
}
.lastlabel{
    position: relative;
    left: 250px;
    text-transform: capitalize;
    font-size: 14px;
    color: antiquewhite;
}
 #company{
     position: relative;
     left: 270px;
     bottom: 25px;
     line-height: 30px;
     width: 450px;
     font-size: 16px;
     border-radius: 5px;
     color: #555;
 }
 #email{
     position: relative;
     left: 270px;
     bottom: 25px;
     line-height: 30px;
     width: 450px;
     font-size: 16px;
     border-radius: 5px;
     color: #555;
 }
 #code{
    position: relative;
    left: 200px;
    bottom: 25px;
    line-height: 30px;
    font-size: 16px;
    color: #555;
    border-radius: 5px;   
    width: 100px;
 }
 #phone{
    position: relative;
    left: 130px;
    bottom: 25px;
    line-height: 30px;
    font-size: 16px;
    color: #555;
    border-radius: 5px;
    
 }
 .areacode{
    position: relative;
    left: 290px;
    text-transform: capitalize;
    font-size: 14px;
    color: antiquewhite;   
 }
 .phonenumber{
    position: relative;
    left: 250px;
    text-transform: capitalize;
    font-size: 14px;
    color: antiquewhite;   
 }
 #subject{
    position: relative;
    left: 270px;
    bottom: 25px;
    line-height: 30px;
    width: 450px;
    height: 30px;
    font-size: 16px;
    border-radius: 5px;
    color: #555;
    outline: none;
    overflow: hidden;
 }
 #subject option{
    font-size: 20px;

 }
 #question{
     margin-left: 25px;
     color: white;
     font-size: 18px;
 }
 .yes{
     margin-left: 25px;
     margin-top: 30px;
     color: white;
     font-size: 18px;
     display: inline-flex;
 }
 .no{
     margin-left: 200px;
     margin-top: 30px;
     color: white;
     font-size: 18px;
     display: inline-flex;
 }
button{
    background-color: rgb(231, 198, 127);
    display: block;
    border: 2px solid rgb(17, 17, 0);
    margin: 20px;
    outline: none;
    padding: 15px;
    width: 300px;
    margin-left: 30px;
    border-radius: 10px;
    cursor: pointer;
}
button:hover{
    background-color: blue;
}

  

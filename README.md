# Registration-form
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
  

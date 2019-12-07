# Loginpage
A simple HTML Login Page
# Code for the login 

<!DOCTYPE html>
<html>
  <head>
    <title>CPN-SignUp</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.11.2/css/all.min.css"
    />
   <link rel="icon" href="./jpg/cpn1.png">
  <link rel="stylesheet" href="./style1.css">
   
  </head>
  <body>
    <h1>HTML Form Project</h1>
    <br />
    <form action="" method="GET">
      <fieldset>
        <legend><b>CPN SignUp</b></legend>
        <br />

        <label for="username">Enter Your Username:</label>
        <br />
        <i class="fas fa-user" 
          ></i> &nbsp; <input type="text" name="username" id="username" placeholder="Your Username" required />
        <br />
        <br />
        <label for="pass">Enter the Password:(at least 6 characters)</label>
        <br />
        <i class="fas fa-key"></i>
        &nbsp;
          <input
            type="password"
            name="password"
            id="pass"
            placeholder="Your Password"
            required
            minlength="6"
        />
        <br />
        <br />
        <label for="date">Date of Birth:</label>
        <br />
        
        <i class="fas fa-calendar-week"></i>
        &nbsp;
          <input type="date" name="date" id="date" required />
      
        <br />
        <br />
        <label for="country">Select Your Country:</label>
        <br />
        <i class="fas fa-globe-asia"></i>
        &nbsp;
          <select name="country" id="country" required>
            <option value="Afghanistan">Afganistan</option>
            <option value="Bangladesh">Bangladesh</option>
            <option value="Bhutan">Bhutan</option>
            <option value="India">India</option>
            <option value="Maldives">Maldives</option>
            <option value="Nepal">Nepal</option>
            <option value="Pakistan">Pakistan</option>
            <option value="Sri Lanka">Sri Lanka</option>
          </select>
       
        <br />
        <br />
        <i class="fas fa-book-reader"></i>
        &nbsp;
        <label for="course">Which Course are you seeking for?</label>
        <br />
        <br />

        <input type="radio" name="course" id="course" required />Coding
        <i class="fas fa-laptop-code"></i>
        <br />
        <input type="radio" name="course" id="course" />Networking
        <i class="fas fa-wifi"></i>
        <br />
        <input type="radio" name="course" id="course" />Mobile Application
        Development <i class="fas fa-mobile"></i>
        <br />
        <input type="radio" name="course" id="course" /> File & Data Management <i class="fas fa-save"></i>
        <br />
        <input type="radio" name="course" id="course" />Basic Satellite
        Communication <i class="fas fa-satellite-dish"></i>
        <br />
        <br />
        <i class="fas fa-laptop"></i>
        &nbsp;
        <label for="exp">Do you have any experiences in the field of Computer Training?</label>
        <br>
        <input type="radio" name="yes-no" id="exp" required>Yes
        <input type="radio" name="yes-no" id="exp"> No
        <br>
        <br>
        <label for="gender">Choose your Gender:</label> <br />
        <input type="radio" name="gender" id="gender" required /><i
          class="fas fa-male"
        ></i>
        <br />
        <input type="radio" name="gender" id="gender" /><i
          class="fas fa-female"
        >
        </i>
        <br />
        <br />
        <label for="lang">Which Language are you familiar with?(You can choose multiple)</label>
        <br>
        <input type="checkbox" name="Java" id="lang">Java <i class="fab fa-java"></i> 
        <br>
        <input type="checkbox" name="Javascript" id="lang">Javascript <i class="fab fa-js"></i>
        <br>
        <input type="checkbox" name="HTML" id="lang">HTML <i class="fab fa-html5"></i>
        <br>
        <input type="checkbox" name="Python" id="lang">Python <i class="fab fa-python"></i>
        <br>
        <input type="checkbox" name="CSS" id="lang">CSS <i class="fab fa-css3 alt"></i>
        <br>
        <input type="checkbox" name="Swift" id="lang">Swift <i class="fab fa-swift"></i>
        <br>
        <br>
        <input type="reset" value="Clear" />
        <input type="submit" value="SignUp" style="padding-left: 4px;background-color: green;" />
        <br>
        <br>
        By clicking Sign Up, you agree to our <a href="">Terms</a>,<a href=""> Data Policy</a> and <a href=""> Cookies Policy</a>. You may receive SMS Notifications from us
        and can opt out any time. <br>
        <h6 style="text-align: center;">Copyright &copy; 2019 CPN All Rights Reserved</h6>
      </fieldset>
    </form>
  </body>
</html>

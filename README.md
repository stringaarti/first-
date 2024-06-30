<!DOCTYPE html>
<html lang="en">
 <head>
 <meta charset="UTF-8" />
 <meta
 name="viewport"
 content="width=device-width, initial-scale=1.0"
 />
 <title>Registration Form</title>
 <link rel="stylesheet" type="text/css" href="css/style.css">
<script src="include/validation.js"></script>
 </head>
 <body>
 <div class="main">
 <h2>Registration Form</h2>
 <form name="frm" action="">
 <label for="first">Full Name:</label>
 <input 
 type="text"
 id="name"
 name="name"/>
 <label for="email">Email:</label>
 <input
 type="email"
 id="email"
 name="email"/>
<label for="mobile">Contact:</label>
 <input
 type="text"
 id="mobile"
 name="mobile"
 maxlength="10"/>
 <label for="password">Password:</label>
 <input
 type="password"
 id="password"
 name="password"/>
 <label for="repassword">Re-type Password:</label>
 <input
 type="password"
 id="repassword"
 name="repassword"/>
<label for="gender">Gender:</label>
 <input
 type="radio"
 id="rdgen"
 name="rdgen"
 />Male
<input
 type="radio"
 id="rdgen"
 name="rdgen"
 />Female
 <label for="edu">Education:</label>
 <select
 id="edu"
 name="edu">
<option>
 - Select education -
 </option>
 <option value="SSC or less">
 SSC or less
 </option>
 <option value="HSC">
 HSC
 </option>
 <option value="Graduation">
 Graduation
 </option>
<option value="Post Graduation">
 Post Graduation
 </option>
<option value="Other">
 Other
 </option>
 </select>
 <button type="submit" onClick="return check()">
 Submit
 </button>
 </form>
 </div>
 </body>
</html>

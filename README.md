# This HTML page simulates a phishing login page used for cybersecurity awareness demonstration.


<!DOCTYPE html>
<html>
<head>
<title>Account Login</title>
<style>
body{
font-family: Arial;
background:#f2f2f2;
text-align:center;
margin-top:100px;
}

form{
background:white;
padding:30px;
border-radius:10px;
display:inline-block;
}

input{
display:block;
margin:10px;
padding:10px;
width:200px;
}

button{
padding:10px 20px;
}
</style>
</head>

<body>

<h2>Account Verification</h2>

<form>
<input type="text" placeholder="Email">
<input type="password" placeholder="Password">
<button>Login</button>
</form>

</body>
</html>






# password checking code 





import re

password = input("Enter password: ")

if len(password) < 8:
    print("Weak Password")

elif not re.search("[A-Z]", password):
    print("Add uppercase letter")

elif not re.search("[0-9]", password):
    print("Add numbers")

else:
    print("Strong Password")




# Cyber Security Phishing Awareness Project

This project demonstrates how phishing attacks work and how users can protect themselves from social engineering attacks.

Features:
- Phishing login page simulation
- URL phishing detection script
- Password strength checker
- Email validation program

Technologies Used:
- HTML
- CSS
- Python
- Cybersecurity Concepts

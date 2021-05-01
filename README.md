# OTP Playground
This is a simple web application written in Python meant to demonstrate how OTP (One time password) works.  

Prepare your Google Authenticator or Authy app and have fun!
![screenshot](./img/otp.png)
## How to use it
Clone the repo, modify the user.json user database to your like and ...
```
python3 -m venv env
source env/bin/activate
pip install -U pip
pip install -r requirements.txt --no-cache
./app.py
```
Go to:  http://127.0.0.1:5000  
Login and scan the QR code with your Google Authenticator or Authy app...

**...refresh the page to see the new OTP**

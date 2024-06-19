<h4>User Authentication API</h4>
<h6>This API allows complete user authentication like : </h6>
<ul>
  <li>Register user</li>
  <li>OTP verification</li>
  <li>Login Api</li>
  <li>Change password</li>
  <li>Reset password through email</li>
  <li>logout</li>
</ul>


Getting Started
To use the API, you can follow these steps:

Clone the repository: https://github.com/DhanushpathiPrakash/User_Authentication.git

Install the required dependencies: pip install -r requirements.txt

Run the development server: python manage.py runserver

<b>API Endpoints</b><br>
api/ register/ [name='register']<br>
api/ verify/ [name='verify']<br>
api/ login/ [name='login']<br>
api/ profile/ [name='profile']<br>
api/ changepassword/ [name='changepassword']<br>
api/ send-reset-password-email/ [name='send_reset_password_email']<br>
api/ reset-password/<uid>/<token>/ [name='reset_password']<br>
api/ logout/ [name='logout']<br>

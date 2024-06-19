<h4>User Authentication API</h4>4>

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

API Endpoints
api/ register/ [name='register']
api/ verify/ [name='verify']
api/ login/ [name='login']
api/ profile/ [name='profile']
api/ changepassword/ [name='changepassword']
api/ send-reset-password-email/ [name='send_reset_password_email']
api/ reset-password/<uid>/<token>/ [name='reset_password']
api/ logout/ [name='logout']

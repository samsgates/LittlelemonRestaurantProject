Review Note:
Please enter your database details, create users and tokens either manually or using APIs as explained in previous Coursera modules, and then use the corresponding API where token authorization is needed.

Important: Don’t forget to adjust system-specific details, such as port or IP, if you’re using different settings than those listed below.

(Some APIs require authorization. You'll be able to identify this through the response.)

API URL:
http://127.0.0.1:8000/restaurant/menu/       
http://127.0.0.1:8000/restaurant/menu/2/     (CHANGE ID)
http://127.0.0.1:8000/restaurant/api-token-auth/ (POST METHOD)
http://127.0.0.1:8000/restaurant/booking/ 



AUTH USER:
http://127.0.0.1:8000/auth/users/   (USER REGISTRATION THROUGH POST METHOD)
http://127.0.0.1:8000/auth/users/me/
http://127.0.0.1:8000/auth/users/confirm/
http://127.0.0.1:8000/auth/users/resend_activation/
http://127.0.0.1:8000/auth/users/set_password/
http://127.0.0.1:8000/auth/users/reset_password/
http://127.0.0.1:8000/auth/users/reset_password_confirm/
http://127.0.0.1:8000/auth/users/set_username/
http://127.0.0.1:8000/auth/users/reset_username/
http://127.0.0.1:8000/auth/users/reset_username_confirm/

TOKEN:
http://127.0.0.1:8000/auth/token/login/


# logs-a-lot
WordPress frontend user login, reset password, register page, all using theme pages.

On plugin activation 5 login pages are created

* Login Page - Sign In
* Redirect after login - Your Account
* Register Page - Register
* Forgot Password Page - Forgot Your Password?
* Choose New password Page - Pick a New Password

Control redirection of non-admins via _redirect_after_login()_ function by default set to go to 'My Account' page, this currently has a redundant shortcode 'member-account'

## Google Captcha#
Dont forget once active to add recapcha keys https://www.google.com/recaptcha/admin#list in the general settings in Dashboard



_ref - https://code.tutsplus.com/tutorials/build-a-custom-wordpress-user-flow-part-1-replace-the-login-page--cms-23627_

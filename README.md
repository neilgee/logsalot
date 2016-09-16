# logsalot
WordPress Frontend user login, reset password, register pages all customized.

On plugin activation 5 login pages are created

* Login Page - Sign In
* Redirect after login - Your Account
* Register Page - Register
* Forgot Password Page - Forgot Your Password?
* Choose New password Page - Pick a New Password

Control redirection of non-admins via _redirect_after_login()_ function by default set to go to 'My Account' page, this currently has a redundant shortcode 'member-account'

_ref - https://code.tutsplus.com/tutorials/build-a-custom-wordpress-user-flow-part-1-replace-the-login-page--cms-23627_

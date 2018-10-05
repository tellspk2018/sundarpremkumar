# sundarpremkumar
Sundarpremkumar's work in progress items

Am sharing some of my interesting work here. 

Catch me at my [linked-in profile](https://www.linkedin.com/in/sundarpremkumar-s). 
[Like my blog](https://tellspk.wordpress.com). 
[Or do you dig tumblr rather](https://sundarpremkumar.tumblr.com)?

There are quite a few posts to include captcha in cakephp, they are a bit out dated as of now.

reCaptcha seems to be the most adopted verification method. Using it for cakephp requires only a few steps.

- Copy the most recent reCaptcha file from Google code to app/vendors/recaptcha/recaptchalib.php.
- Add the following component to your app\controllers\component\captcha.php

In your controller include the captcha as a component. Sample action to check captcha is given too.

Sample view to be placed in check_captcha.ctp

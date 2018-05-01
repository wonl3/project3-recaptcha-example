## CS 122B Project 3 reCAPTCHA example

This example shows how frontend and backend are separated by implementing a star list page and a single star page with movie list.

### To run this example: 
1. clone this repository using `git clone https://github.com/UCI-Chenli-teaching/project3-recaptcha-example.git`
2. open Eclipse -> File -> import -> under "Maven" -> "Existing Maven Projects" -> Click "Finish".
3. For "Root Directory", click "Browse" and select this repository's folder. Click "Finish".
4. If you haven't done so, get a [reCAPTCHA](https://www.google.com/recaptcha/intro/android.html) from Google. get reCAPTCHA -> choose reCAPTCHA v2 -> enter your AWS IP and localhost -> Register
5. In `src/RecaptchaConstants.java`, replace `SECRET_KEY ="YOUR_SECRET_KEY";` with your own reCAPTCHA secret key.
6. In `WebContent/index.html`, replace `data-sitekey="YOUR_SITE_KEY"` with your own reCAPTCHA site key.
7. In `src/FormRecaptcha.java`, change your mysql username and password.
8. You can run this project on Tomcat now.

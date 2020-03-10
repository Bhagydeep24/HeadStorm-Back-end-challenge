# HeadStorm-Back-end-challenge
Here is the solution of 1st front end coding challenge for Headstorm

Site link:https://www.headstorm.com/challenge/

Github Link:https://github.com/Headstorm/Interview/blob/master/challenges/README.md

##### Question

___
Back End Challenge
Create a REST API using any language or web framework you prefer, which performs the following functionality:

<!-- UL -->

* Provides a POST endpoint at /data where a user submits a JSON formatted list of 500 random numbers. The list has to be exactly 500 numbers, if there are more or less than 500 an error must be returned. Similarly, if something other than a list of numbers is submitted, an error must be returned.
* Provides a GET endpoint at /data which provides the same JSON formatted list of 500 numbers that are sorted from lowest to highest.

**BONUS:**

<!-- UL -->

* Provides a PATCH endpoint at /data which allows insertion of a single number into the list which gets placed in the proper order.
___

So I have create a page(index.php) website which includes both home and contact form. I have created my own css i.e main.css
and the webpage is responsive. For the form I have created a validation.js file to check validation based on class which is invoked before submission of the form 
to check the requirements based on the form elements. It checks every element is valid or not. To add validation such as require simply
add required class to the element and same goes to verify valid email string or not. I have also used 3rd person scroll.js it is to
add scrolling animation when clicked on contact link in the navigation bar. Lastly as per the challenge  requirement integrated Google reCaptcha V3. All the form details submitted is visible in console along with captcha message it will be success or error based on the condition if score <= 0.5 and if returns true after validing secret and response key. For more info regarding recaptcha v3 visit the [site](https://developers.google.com/recaptcha/docs/v3) and it shows green success popup or red error popup if submission had issue.

### Solution Screenshots of the work:

![](ScreenShots/ss1.png)

![](ScreenShots/ss2.png)

![](ScreenShots/ss3.png)

![](ScreenShots/ss4.png)

![](ScreenShots/ss5.png)

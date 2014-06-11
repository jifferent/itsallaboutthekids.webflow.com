Code implementation: 
There are three folders under the github repository, css, images and js. and there is also a index.html:
Index.html is the main page, where they can change the layout of the main page.
Logo:
	          At line 30 of index.html
<img class="logo" src="images/logo-header.png" width="25" alt="530e4fc7f4a216ca3c0000e1_logo-header.png">
          <div class="app-name">Logo</div>
This is the place where you can change the image of of the logo
put the logo image under image folder
change the src=”images/yourLogoPictureName.png”
change the Logo at line 31 to the name you want.(ex: itsallaboutthekids.org)
Credit card section:
	The credit card section is between line 38 to 58.  The part need API(application programming interface) support from Click & Pledge, you may change entire section, or hand this over to Click & Pledge and let them to implement.
App Store Section :
	Between line 65 and 72.
	If you want to change the text of the advertise, is it at line 65
<h2 class="price-text">Get it now for $1.99 on the app store!</h2>
	The app web link is at line 68
<a class="w-inline-block button app-button" href="http://www.apple.com" target="_blank">
	To change the image of app
<img src="images/appstore.png" width="114" alt="52af8cf8aae9d4d567000057_appstore.png">
1. Put the image under image folder
2. Change the img  src=”images/yourLogoPictureName.png”
3. Change the size of the image, width=”int”.
The section also can be other information, like currently news of its all about the kids news.
E-mail:
	change default email section are lines between 78 - 79
<a class="w-inline-block social-button" href="mailto:support@webflow.com?subject=Hello!" target="_blank">
	If you want to change the email address just change “support@webflow.com” to your email address.
	Also your can change the default subject of the email by change the “subject=Hello!”, and only change the “Hello” part. (ex: Supporter E-mail)

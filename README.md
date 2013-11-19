Login-Script
============

This is a fairly simple JavaScript Login Script / built with JavaScript, CSS and HTML.  You can add this login to any page you like on your website.

1. Make sure to point custom.js to the server side script that processes the username and password. Change this line in custom.js

		xmlHttp.open("GET", "http://www.yourwebsite.com/log_user.php?e="+email+"&p="+password, true);

2. To call the login script

		var loginbox1 = new LoginBox;

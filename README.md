### A CodeIgniter skeleton application based on twitter bootstrap 2 and html5boilerplate 3.
---------------------------------------------------
	VERSION 1.1.0

* Codeigniter 2.1.0
* bootstrap 2.0.1
* html5boilerplate 3.0.2

* view rendering handled by a smart MY_Controller.
* jQuery 1.7.1
* underscore.js 1.3.1
* nav_helper
* .htacces tip for remove index.php
* basejs view always include in page. (usefull to access via js some server side information e.g. base_url())

USAGE
-------------------
1. edit .htaccess file in order to match your server config (see line 5 in the file);
	if you have http://localhost/site you nedd to set RewriteBase /site/
2. set up yor defaults value in application/config/development/custom.php
3. take a look to home controller to understand how does rendering works.
4. create your template: i've set up an header, footer, nav, and main for example purpose. Skeleton.php contains the scaffolding page.

MY_Controller is made for my page basic template, feel free to improve it. Send a pull request, or contact me.
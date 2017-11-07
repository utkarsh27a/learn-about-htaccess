Why we use htaccess file?
 We can use additional functions and features of apache web server with htacces, but htaccess majorly use for URL Rewriting.

Then the next question ocurs that why we Rewrite URLs?
 We Rewrite URLs to make it SEO frindly, to make it Clean URL.

Who uses htaccess?
 Laravel, Zend, CodeIgniter, Yii
 Wordpress, Joomla, Drupal , OpenCart, Magento

How can we use .htaccess?
 Its simple, enable mod_rewrite in your apache configurations and make .htaccess file in your project. Then write some rules for rewriting your urls.

Lesson 1
  Allow / Deny Listing if not index file in dir
  Options +Indexes

Lesson 2
  Allow / Deny Specific files for listing
  IndexIgnore *.php

Lesson 3
  Deny some file for listing and open
  <FilesMatch "\.(txt|jpg)$">
    order allow,deny
    deny from all
  </FilesMatch>

Lesson 4
  Change default index file
  DirectoryIndex home.php

Lesson 5
  Change default index file
  Redirect /u /users

Lesson 6
URL Rewriting

Lesson 7
Protect Dir with basic auth

# webfun
This is the base of all the codeigniter projects.
1. Twitter Bootstrap 3.1.1 in root/bootstrap/bootstrap3.1.1
2. Application/views/header.php
3. Application/views/footer.php
4. .htaccess file in root to remove index.php file
5. spark in root/tools
6. Application/core/My_Folder
7. Common language file. Application/language/english/en_admin_lang.php
8. My_Controller in Application/core/My_Controller
9. Change $autoload['libraries'] = array(); to $autoload['libraries'] = array('database', 'session'); 
10. In main index.php file change define('ENVIRONMENT', 'development'); to define('ENVIRONMENT', 'production'); for security purposes.

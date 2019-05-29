Project: NextGen

Task:Replicate the following blocks from this website: https://nextgendistribution.com.au/ using Drupal 8.
1. Home Page Main Slider Block
2. Our Services Block

Environment Used : XAMPP (xampp-win32-7.2.11-0-VC15-installer)

Drupal Version Installed: 8.7.2
To install Drupal on your localhost, follow the following steps
1. Download the drupal instance 'drupal8exp' in 'htdocs' folder
2. Unzip the drupal instance (if required). The database is in root directory of 'drupal8exp' folder with name 'db'.
3. Import the drupal8exp_final.sql file in phpmyadmin on localhost.
4. Change the database details in settings.php file under 'sites/default' folder of 'drupal8exp' (if required).
5. Run instance from your localhost with url 'http://localhost/drupal8exp'

Theme Name: Basic
Module Used:paragraph,slick paragraph,slick carousel and all related module required to use these module.

Task completed:
1. Create a homepage with paragraph type.
2. Created a paragraph to integrate on homepage.
3. Home Page Slider Task steps followed:
	a. Created a content type 'Home Banner'
	b. Created a view with name 'Slider' and used view slideshow for home banner
	c. Used View in Paragraph by View Reference field to show slider on homepage
4. Service Slider Steps followed: 
	a. Created a bundle paragraph (paragraphtype > servicecarousel > slides) for carousel slider.
	b. Aadd it on homepage. 
	c. Used slick paragraph module to show services in carousel.




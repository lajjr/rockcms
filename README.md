<a href='http://www.pledgie.com/campaigns/21192'><img alt='Click here to lend your support to: Rock CMS and make a donation at www.pledgie.com !' src='http://www.pledgie.com/campaigns/21192.png?skin_name=chrome' border='0' /></a>

Rock CMS
========

Rock CMS will be a new type of Content Management System. You download a script and use the script to get the program. 
During the download the script gets all the need files and installs automatically.

The script will be like this.

script create config -defaults domain.cfg

(-defaults can be blue, red, crossover, bootstrap, biz1, biz2, ecomm1 etc.)

eg: script config biz1 mydomain.cfg (This will make a site based on biz1)

Defaults adds a default template and make everything work.

The file name must be the name of the site.

eg: domain.com = domain.cfg

It asks questions on the database, domain, and admin information.

creates the configuration file and downloads all files frameworks templates needed.


CRM Module
==========
Customer Relations Management

Will be an added feature to add CRM 



Forums Module
=============

Forums Module for forums, and follows theme in setup.

eg:

script create biz1 crmmod forummod --red 

The biz1 follows a template but with options red follows red template. Also if you pick blue same.


Biz 1(2-6)
==========

The biz template is special it sets up a Business with the following added extras setup.
This requires a SSL 

# Store
* Products
* Store
* Payment Gatways

# Contact
* Address
* Phone

# Policies
* Privacy
* Shipping
* Returns


WorkingForumBundle
==================

[![Join the chat at https://gitter.im/WorkingForumBundle/Lobby](https://badges.gitter.im/WorkingForumBundle/Lobby.svg)](https://gitter.im/WorkingForumBundle/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Build Status](https://travis-ci.org/Yosimitso/WorkingForumBundle.svg?branch=master)](https://travis-ci.org/Yosimitso/WorkingForumBundle) [![Latest Stable Version](https://poser.pugx.org/yosimitso/workingforumbundle/v/stable)](https://packagist.org/packages/yosimitso/workingforumbundle) [![Total Downloads](https://poser.pugx.org/yosimitso/workingforumbundle/downloads)](https://packagist.org/packages/yosimitso/workingforumbundle) [![License](https://poser.pugx.org/yosimitso/workingforumbundle/license)](https://packagist.org/packages/yosimitso/workingforumbundle)

V3 is coming
===============
Among new features : lighter, new design, Flex recipes, Webpack, important refactoring, some URLs rewritted, better unit tests

ENGLISH
=================  
A forum bundle for Symfony 3/4, easy to use with a lot of features  
This bundle work with your user bundle with no extra configuration (which can extend FOSUserBundle)  
The bundle was made to be customizable and overridable to fit your application  

Demo
-------------
Try it here - https://demoworkingforum.charlymartins.fr


Features
------------------
- Support multi language
- Responsive design (mobile, tablet, desktop)
- Post editor using markdown with smiley, quote and instant preview
- Threads status : resolved, closed, pinned, moved from a moderator
- Enclosed files with post (files upload system)
- Vote system for posts
- Moderator role as ROLE_MODERATOR (and default admin roles)
- Reporting system for thread
- Auto-lock system for old thread
- Automatic breadcrumb, messages counters, pagination
- Allow or not the anonymous to read forums
- Database safety : no HTML stored, only markdown
- Search system
- Backend administration
- Antiflood system
- Email notification on new posts


Setup
------------------
See SETUP-SF3.md or SETUP-SF4-FLEX if you use Symfony 4 with Flex structure


Configuration
-----------------
Refer to CONFIGURATION.md

Contribute
----------------
About a fix : 
Make a PR !

About a feature :
please open an issue, to talk about it and share the work

To launch tests, go to the bundle's directory and execute 
````
composer install
vendor/phpunit/phpunit/phpunit
````




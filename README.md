Apache-Site-Template
====================

Simple, flexible templating system for Apache sites with SSI.

## Features
Sorta like a CMS, but very file based, and template driven.

## Requirements
* Apache
* SSI enabled

## Setup

Edit you Apache configuration file (httpd.conf, or httpd-vhosts.conf, or a .htaccess file) so that server side includes are allowed.

    AddType text/html .shtml
    AddOutputFilter INCLUDES .shtml
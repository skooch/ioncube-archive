
                     ionCube PHP Encoder 9.0
                     -----------------------

Thank you for installing this evaluation of the ionCube PHP Encoder.

Please take a moment to review the information here before exploring the
product further.

Product Layout
==============

The product directory is structured as follows:

README.txt              - This file!

ioncube_encoder.sh      - Generic launch script for the Encoder. 
			  Run with -h for guidance.


Inside "bin" - Encoders

ioncube_encoder4_9.0    - The PHP Encoder for PHP 4 based scripts.

ioncube_encoder5_9.0    - The PHP Encoder for PHP 4 and 5 based scripts.
                          PHP 5.0.3 or newer is required to run files from
                          this Encoder.

ioncube_encoder53_9.0   - The PHP Encoder for PHP 4, 5 and 5.3 based scripts.
                          PHP 5.3 or newer is required to run files from this
                          Encoder.
 
ioncube_encoder54_9.0   - The PHP Encoder for PHP 4, 5, 5.3 and 5.4 based scripts.
                          PHP 5.4 or newer is required to run files from this
                          Encoder.

ioncube_encoder55_9.0   - The PHP Encoder for PHP 4, 5, 5.3, 5.4 and
			  5.5 based scripts.
                          PHP 5.5 or newer is required to run files from this
                          Encoder.

ioncube_encoder56_9.0   - The PHP Encoder for PHP 4, 5, 5.3, 5.4, 5.5
                          and 5.6 based scripts. PHP 5.6 or newer is
                          required to run files from this Encoder.

... plus older version 8.3 and version 7 Encoders.

make_license            - Program to create license files for your PHP scripts
                          if required (Pro and Cerberus editions only).


Inside "docs" - Documentation. 

LICENSE.txt             - Your End User License Agreement.

README-COMPAT.txt       - Information on program compatibility with different
                          FreeBSD versions (FreeBSD version only).

RELEASE-NOTES.txt       - Information about changes in this release.

USER-GUIDE.pdf          - The detailed user guide. Recommended reading, with
                          full details of how to get started.

loader-wizard/          - The ionCube Loader Wizard script for assisting with
                          installing the ionCube Loader on a target server
                          (required for running encoded files). 

loader-wizard/loader-wizard.php
                        - The Loader Wizard script. Note that a more recent
                          version may be available from:

                            http://www.ioncube.com/lw

                          On most servers, the Wizard will automatically
                          detect and indicate if a new version is available.

loader-wizard/README.txt
                        - Wizard documentation.


Using Encoded Files - the ionCube Loader
========================================

A free component called the ionCube Loader is provided to process encoded
files. Loaders are available for many platforms, and with ionCube technology a
widely used industry standard, many hosting servers have the Loader component
installed by default. Where it is not pre-installed then depending on the 
web server configuration, a user can either easily install it themselves, or
otherwise server administrators / hosting providers would usually do this
if required.

Two tools are provided to assist with Loader installation from 
http://loaders.ioncube.com. A Windows program called the Loader Installer is 
recommended, which can deploy a Loader to a remote server using FTP or sFTP
and make the necessary changes to a php.ini file. An alternative is a PHP script
called the Loader Wizard. The Wizard will indicate which Loader package and file
are required to be installed, and advise on the PHP configuration changes.

Loaders can be downloaded from http://loaders.ioncube.com

To get a Loader setup for yourself, use the Loader Installer or simply install
the Loader Wizard script (loader-wizard.php) onto a target web server, 
point your browser to the script and follow the instructions. 


What Next?
==========

The User Guide PDF will guide you gently into the product with some simple
examples, and then covers all the available Encoder options in detail.
Other topics such as license file creation and an API in the Loader are
also covered in later chapters. For a quick reminder when using the Encoder,
running it with the --help option will give a summary of all available options.

We hope you enjoy using and evaluating the product, and we can be contacted
via our Support Helpdesk if you need assistance at http://support.ioncube.com

Copyright (c) 2002-2015 ionCube Ltd.

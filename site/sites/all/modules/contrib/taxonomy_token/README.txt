/* $Id: README.txt,v 1.1.2.2 2010/12/10 19:28:41 rsevero Exp $ */

-- SUMMARY --

The Taxonomy Token module allows the user to set vocabularies for which there
will be created specific tokens. It's main use is together with the Pathauto
module.

For a full description of the module, visit the project page:
  http://drupal.org/project/taxonomy_token

To submit bug reports and feature suggestions, or to track changes:
  http://drupal.org/project/issues/taxonomy_token


-- REQUIREMENTS --

* Taxonomy

* Token


-- INSTALLATION --

* Install as usual, see http://drupal.org/node/70151 for further information.


-- CONFIGURATION --

* Upon install all existing vocabularies will be set to get single term specific
  tokens.

* Users with the 'administer taxonomy' permission can go to Administer >> 
  Content Management >> Taxonomy >> Tokens <admin/content/taxonomy/token> to set
  the type of tokens that should be created for each vocabulary. There is also
  the option of not creating any specific tokens for selected vocabularies.


-- UPGRADING --

* You have to reconfigure Taxonomy Token after upgrading to version 6.x-1.0-RC3
  as configuration settings changed format because of the implementation of
  optional generation of bottom term tokens.

* In version 6.x.1.3 the settings page changed from the previous
  <admin/settings/taxonomy_token> location to <admin/content/taxonomy/token>.


-- TROUBLESHOOTING --

Empty.


-- FAQ --

Q: Empty

A: Empty.


-- CONTACT --

Maintainer:
* Rodrigo Severo (rsevero) - http://drupal.org/user/496564

This project is sponsored by:
* Fábrica de Idéias
  Drupal based site development in Brazil. Visit http://www.fabricadeideias.com
  for more information.

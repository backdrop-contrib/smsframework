SMS Framework
=============
Description
-----------

Provides a pluggable API for Backdrop to interact with SMS messages. 

- sms.module - the core API module
- sms_user.module - provides integration with Backdrop users
- sms_blast.module - for sending a batch of messages (PORT IN PROGRESS)
- sms_valid.module - provides extensible validation functionality (PORT IN PROGRESS)
- sms_track.module - records sms inbound and outbound traffic for tracking purposes (PORT IN PROGRESS)
- sms_sendtophone.module - input filter and node links for sending snippets of text via sms (PORT IN PROGRESS)
- sms_actions.module - integrates sms with the actions module (PORT IN PROGRESS)
- sms_devel.module - integrates sms with devel module (PORT IN PROGRESS)


Installation
-----------
1. Drop into your modules directory
2. Enable the modules you want to use from admin/build/modules
3. Set and configure your default gateway at admin/smsframework/gateways
4. Check out the settings pages at admin/smsframework

Documentation
-----------
TBD

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.


Maintainers
-----------
Ported to Backdrop by https://github.com/docwilmot
Seeking maintainers

Credits
-------
Drupal Maintainers

http://drupal.org/u/almaudoh
http://drupal.org/u/batje
http://drupal.org/u/ekes
http://drupal.org/u/mcpuddin
http://drupal.org/u/univate

Drupal credits

Will White of Development Seed (http://drupal.org/user/32237)
Tylor Sherman of Raincity Studios (http://drupal.org/user/143420)
Email Address Validator
=======================



## Usage:
    var eav = require('/lib/emailaddressvalidator');
    eav.emailAddressValidator('name@host.com'); // => true
    eav.emailAddressValidator('namehost.com'); // => false



## Based on...
This RegExp is based on Michael Rushtons RegExp and is officially used by PHP in "filter_var()". 
See: http://svn.php.net/viewvc/php/php-src/trunk/ext/filter/logical_filters.c?view=markup


==Usage== 
 * var eav = require('/lib/emailaddressvalidator');
 * eav.emailAddressValidator('name@host.com'); // Returns: true


==Base==
This RegExp is based on Michael Rushtons RegExp an is officially used by PHP in "filter_var()". 
( http://svn.php.net/viewvc/php/php-src/trunk/ext/filter/logical_filters.c?view=markup )
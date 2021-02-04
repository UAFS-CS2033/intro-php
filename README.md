# Introduction to PHP
PHP is a server-side scripting language.  PHP code blocks are inserted into HTML files to provide server-side processing of data received from the client. The web server processes the php file from top to bottom. PHP code blocks are executed at the point they are inserted in the page, and the output from the php block is sent to the HTTP Response. All other HTML elements outside the PHP code blocks are sent to the HTTP Response as normal.

PHP is a fairly easy language to learn for the Java programmer.  

### Variables
Whiel Java has static typing and variable types must be specified, PHP has dynamic variables without a specified type.  All variables in PHP must start with a **$**.

### If Statements and Loops
Branching and Looping instructions follow the same syntax as in Java.

### Strings
The String concatenation operator in PHP is a **.** instead of a **+**.

### Structured vs. Object Oriented
Code in PHP can be structured with functions and no objects, or objects and classes can be used(Newer).

PHP works with the data(*name-value pairs*) in the **HTTP GET or POST Request** sent from the browser(*client*) to the web server(*server*). To insert a block of PHP code in a Page, use the following format:

```php
<?php

?>
```
Code inside the PHP block will be executed and the output from the code block will be insrted in the HTML page being returned.  The server returns HTML to the browser.


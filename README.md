# PHP Dynamics Online CRM 2011 SOAP Class

This class is to enable you to connect to Microsoft Dynamics 2011 online cloud hosted CRM service with PHP via SOAP.
Updated for compatibility with the latest changes from Microsoft.  Works with online orgs still using LiveID authentication.  Does not work with Office365 authentication.

## Usage

You need to pass four parameters to the class:

- Your Live Email address
- Your Live password
- Your CRM url
- The debug level [optional]

```php
$dynamicsClient = new dynamicsClient('email','password','orgname.crm4.dynamics.com',1);
```

If the debug mode is set to 1 then all requests and reponse data will be printed.

Originally created by Ben Speakman
Modified by Matt Barnes
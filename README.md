# Cirrus PowerShell Toolkit

Version: 1.0.0<br />
Date: June 9, 2015<br />
Author: Johan Cyprich<br />
Author Email: jcyprich@live.com<br />
Author URL: www.cyprich.com<br />
License: The MIT License (MIT)

## SUMMARY

PowerShell function to send mail with an option for authentication. If you do not want to authentication, leave $sAuthUserName and $AuthPassword as empty strings.

## FUNCTIONS

<b>function SendMail</b> ([string] $sHost, [string] $sFrom, [string] $sTo, [string] $sSubject, [string] $sMessage, [string] $sAuthUserName, [string] $sAuthPassword)

<b>$sHost</b> - Host name of mail server.<br />
<b>$sFrom</b> - E-mail address of mail sender.<br />
<b>$sTo</b> - E-mail address of mail recipient.<br />
<b>$sSubject</b> - Subject title of message.<br />
<b>$sMessage</b> - Message sent to recipient.<br />
<b>$sAuthUserName</b> - User name for authentication.<br />
<b>$sAuthPassword</b> - Password for authentication.

Returns True if mail was sent successfully, False otherwise.

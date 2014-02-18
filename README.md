Virtual Host Snippet
================

## Summary
Easy Set virtual host

## Install

#### Git Clone
Clone this repository in to the Sublime Text "Packages" directory, which is located where ever the
"Preferences" -> "Browse Packages" option in sublime takes you.

```<VirtualHost *:80>
	ServerName      domain.com
	ServerAlias     www.domain.com
	DocumentRoot    /var/www/html/domain.com

	CustomLog       /var/log/httpd/domain.com-access.log common
	ErrorLog        /var/log/httpd/domain.com-error.log
</VirtualHost>```
## Usage

Type vhost and press tab

---

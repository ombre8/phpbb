# Openshift 3 source to image deployment for PHPBB

[![phpBB](https://www.phpbb.com/theme/images/logos/blue/160x52.png)](http://www.phpbb.com)

## ABOUT

phpBB is a free open-source bulletin board written in PHP. This script enables you to deploy phpBB on a Openshift 3 Plattform. You can set a Version by defining an Environement Variable called 'BRANCH'. The Database creation is not automated, do the Setup by hand on first install. As soon the Database is filled, you should define the Database Environement Variables. The Setup will be skipped, if they are defined.

## Variables
 - `BRANCH` Defines the Branch of the phpbb Repo should be used.
 - `MYSQL_SERVICE_HOST` Database host, on OSE 3 usualy localhost
 - `MYSQL_SERVICE_PORT` Database port
 - `MYSQL_DATABASE` Database Name **If this Variable is defined, the Setup will be skipped, a allredy setup Database is expected**
 - `MYSQL_USER` Database Username
 - `MYSQL_PASSWORD` Database Passwort

## LICENSE

[GNU General Public License v2](http://opensource.org/licenses/gpl-2.0.php)

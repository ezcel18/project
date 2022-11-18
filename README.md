# FS (Facility Scheduler)

The rSchoolToday Facilities Scheduler is the most comprehensive scheduling system available. It provides real-time views of all activities in all buildings and locations within your school or District.

Facilities Scheduler shares data in real-time with the rSchoolToday Athletic Scheduler, School Web Calendars, and Maintenance Requests to provide effortless scheduling and automated conflict-checking across your whole organization.

This program is cost-effective and a HUGE time saver!

## Requirements

1. PHP 5.6
2. NGINX/ Apache2
3. MySQL

## Development Installation (local env)
#### CURRENT 2022
1. git clone the repo provided: "/host/project_name.git" will create "/local_path/project_name"
2. create virtual host: "\bin\apache\apacheX.X.X\conf\extra\httpd-vhosts.conf"
3. copy-paste old repo/svn_trunk the following folders: from`/tmp`, `/maintenance`, `/clients` to `/local_path/project_name`
4. on `/clients` folder: duplicate the `default` folder and rename it that corresponds to vhost ServerName: ex. /local_path/project_name/clients/`fs-local`
5. update hosts file -> windows: C:\Windows\System32\drivers\etc


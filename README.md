Garmin Connect Onebox
=====================

Garmin connect onebox for embeding garmin courses

Install in Discourse 1.0

```sh
cd /var/discourse
./launcher ssh app
cd /var/www/discourse
rake plugin:install repo='https://github.com/mrloop/garmin_connect_onebox.git'
exit
./launcher restart app
./launcher ssh app
cd /var/www/discourse
rake posts:refresh_oneboxes
```

Example at http://elgin.cc/t/sun-19th-oct-14-spey-moor/77

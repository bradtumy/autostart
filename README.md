# autostart
/etc/init.d scripts to autostart the IAM services

**Usage**

Copy to /etc/init.d:

**OpenAM**
* $ sudo chmod 755 /etc/init.d/openam
* $ sudo chkconfig --add openam
* $ sudo chkconfig openam on

Verify:
* $ chkconfig --list will show services

**OpenDJ**
* $ sudo chmod 755 /etc/init.d/opendj
* $ sudo chkconfig --add opendj
* $ sudo chkconfig opendj on

Verify:
* $ chkconfig --list will show services

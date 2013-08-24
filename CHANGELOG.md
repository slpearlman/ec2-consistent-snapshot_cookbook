# ec2-consistent-snapshot_cookbook

## 0.1.0

New:

* added chefspec
* added minitest
* added foodcritic
* added strainer
* added berkshelf
* added test kitchen
* enabled support for ubuntu 12.04
* enabled support for centos 6.4

Fixes

* fixed meta data to be correct by giving it a name
* only install xfs if an attribute is set
* changed all hardcoded values to attributes

Chnages

* renamed LWRP to same as cookbook 
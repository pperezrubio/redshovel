RedShovel
=========

*Digging up the dirt from your redmine.*


Install 
-------

Currently the only version is the development version.  To install it
using pip follow these instructions.

```sh
pip install git+git://github.com/NeCTAR-RC/redshovel.git@master
```

Usage
-----

Example usage:

```sh
rs-issue -u http://localhost/redmine/ -a xxxxxxxxxxxxxxxxxxxxxxxxxxxx
-vv --project-id rc-support --tracker-id 3 
+------+---------+----------------+----------+------------------------------------------------------------------------------------+-----------------------+
|  ID  | Tracker |     Status     | Priority |                                       Title                                        |      Assigned To       |
+------+---------+----------------+----------+------------------------------------------------------------------------------------+-----------------------+
| 1309 | Support |  In Progress   |  Normal  |                 Issues with creating bananas from in sputnik                       |                       |
| 1306 | Support |      New       |  Normal  |
Snapshot is a success                          |      Kam Orrison      |
+------+---------+----------------+----------+------------------------------------------------------------------------------------+-----------------------+
```


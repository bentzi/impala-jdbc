impala-jdbc
===========

The codebase is taken from Hive JDBC 0.13.1. 

This is an attempt to strip most of the Hive code to the bare minimum.
The aim is to have an Impala specific JDBC driver / or a simpler Hive2 JDBC codebase to work with.

By forking, the development of the driver can go faster than the release cycle of Hive.


This is the first working version. 
Kerberos support has been removed for now.


See related JIRA Tickets  :
   * [HIVE-1625](https://issues.apache.org/jira/browse/HIVE-1625)
   * [HIVE-3625](https://issues.apache.org/jira/browse/HIVE-3625)
   * [HIVE-4806](https://issues.apache.org/jira/browse/HIVE-4806)
   * [HIVE-7676](https://issues.apache.org/jira/browse/HIVE-7676)
   * [IMPALA-1099](https://issues.cloudera.org/browse/IMPALA-1099)

Java-FlyFF
==========
FlyFF (Fly for Fun) server emulator in Java.

Contributions
=============
We LOVE contributions, just submit a pull request and we'll check it out.


License Information
===================
    Copyright (C) 2014 Jon Huang <project54_jon@live.com>

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

Project Information
===================
Java-Flyff is a FlyFF server emulation programmed in Java and Scala.
Our primary objective is to produce stable and scalable environment
for FlyFF similar to the FlyFF program environment done in C++. However,
our main difference resides in the libraries we use, cross platform support,
and multiple database support. Primarily for Java-Flyff, we will use MySQL
for managing the data. However, we will not limit the user from using other
available database drivers.

Runtime Requirements
====================
Java-FlyFF requires a JVM compliant with the Java SE 7.0. The Sun JVM can be 
acquired [here](http://java.sun.com/javase/downloads/index.jsp).

You will also need to reference a few libraries:
* [Apache MINA 2.0.7](http://mina.apache.org/downloads-mina.html)
* [MySQL Connector/J](http://dev.mysql.com/downloads/connector/j/)
* [Apache DBCP 2.0.1](http://commons.apache.org/proper/commons-dbcp/download_dbcp.cgi)
* [Apache Pool 2.2](http://commons.apache.org/proper/commons-pool/download_pool.cgi)
* [Apache DBUtils 1.6](http://commons.apache.org/proper/commons-dbutils/download_dbutils.cgi)
* [Apache Logging 1.2](http://commons.apache.org/proper/commons-logging/download_logging.cgi)
* [Apache Lang 3.3.2](http://commons.apache.org/proper/commons-lang/download_lang.cgi)
* [Joda-Time 2.4](https://github.com/JodaOrg/joda-time/releases)
* [slf4j 1.7.7](http://www.slf4j.org/download.html)

Libraries to be referenced in the near future:
* [JacORB 1.5](http://www.jacorb.org/download.html)
* [Google Guava 17.0](https://code.google.com/p/guava-libraries/downloads/list)
* [Apache Daemon 1.0.15](http://commons.apache.org/proper/commons-daemon/download_daemon.cgi)

Finally you will also need the FlyFF data files.

For storage purposes Java-FlyFF requires a database backend which is accessible 
using a JDBC driver. Since other DBMS have not been tested with Java-FlyFF, we 
recommend [MySQL](http://dev.mysql.com).

N.B. We have not included the libraries due to licensing concerns. However, we have
provided links for downloading such libraries for your convenience.
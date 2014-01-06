Memcached Java Client
=========

MyCache.java is the example to cache key value paris (including Java Beans) into memcached, using Java APIs.

Memcached Installation
----

Installation

```sh
apt-get install memcached
```

Change the configuration to accept remote access

```sh
vim /etc/memcached.conf
```

Replace the 127.0.0.1 to 0.0.0.0


Restart the service

```sh
/etc/init.d/memcached restart
```

Memcached Client Library
----

```xml
      <dependency>
          <groupId>com.whalin</groupId>
          <artifactId>Memcached-Java-Client</artifactId>
          <version>3.0.2</version>
      </dependency>
```
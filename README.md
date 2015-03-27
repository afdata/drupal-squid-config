# drupal-squid-config
A sample configuration of squid 3.X for Drupal reverse proxy solution


## Installation of squid on centos / redhat enterprise linux

```
yum install squid
```

## Squid configuration - squid.conf

```
/etc/squid/squid.conf
```

## Squid start and stop daemon configuration in redhat - squid.sysconfig

please edit the **SQUID_SHUTDOWN_TIMEOUT** of the maximum response time of the web service.
The option **SQUID_CONF**, is the defintion where the squid config are stored on server.

```
/etc/sysconfig/squid
```

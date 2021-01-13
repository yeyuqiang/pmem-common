# PMem Common

PMem Common package includes native libraries and JNI interface for Intel Optane PMem.

## Online Documentation

You can find the all the PMem Common documents on the [project web page](https://oap-project.github.io/pmem-common/).

## Prerequisites

Below libraries need to be installed in the machine

- [Memkind](http://memkind.github.io/memkind/)

- [Vmemcache](https://github.com/pmem/vmemcache)

## Building

```
mvn clean package -Ppersistent-memory,vmemcache
```

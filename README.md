# pdnsd-china-list

Convert [dnsmasq-china-list](https://github.com/felixonmars/dnsmasq-china-list) into pdnsd format.

### How to use

You can run the following command to get `reject` line.
``` bash
$ ./nxdomain-dnsmasq2pdnsd ./dnsmasq-china-list/bogus-nxdomain.china.conf
```

Also you can run the following command to get `exclude` line.
``` bash
$ ./domains-dnsmasq2pdnsd ./dnsmasq-china-list/accelerated-domains.china.conf
```

The `pdnsd.conf.sample` is for reference if you don't know how to fill in `reject` line and `exclude` line.

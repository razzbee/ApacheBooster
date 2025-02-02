####This project is no longer supported and will not update in the future. If you want to use both varnish and nginx on cPanel, you can either install unixy varnish http://unixy.net/varnish/ or the active forked version of apachebooster https://github.com/breezylinuz/ApacheBooster.git.

ApacheBooster
=============

ApacheBooster is a integration of nginx and varnish, this Plugin will reduce the server load spike and memory usage. Also the plugin will provide the maximum performance of your websites.

####Varnish

Varnish Cache is a web application accelerator also known as a caching HTTP reverse proxy. You install it in front of any server that speaks HTTP and configure it to cache the contents. Varnish Cache is really, really fast. It typically speeds up delivery with a factor of 300 – 1000x, depending on your architecture. A high level overview of what Varnish does can be seen in the video attached to this web. Varnish performs really, really well. It is usually bound by the speed of the network, effectivly turning performance into a non-issue. We’ve seen Varnish delivering 20 Gbps on regular off-the-shelf hardware.

####Nginx

Nginx is known for its high performance, stability, rich feature set, simple configuration, and low resource consumption.

Unlike traditional servers, Nginx doesn’t rely on threads to handle requests. Instead it uses a much more scalable event-driven (asynchronous) architecture. This architecture uses small, but more importantly, predictable amounts of memory under load.


## Installation/Upgrade instructions

1. Clone the installation folder onto your CPanel server:
```bash
$> git clone https://github.com/Prajithp/ApacheBooster.git
              OR
$> wget https://github.com/Prajithp/ApacheBooster/archive/master.zip -O ApacheBooster.zip
$> unzip ApacheBooster.zip
```

2. Change the working directory to cloned or extracted folder:
```bash
$> cd ApacheBooster/apachebooster
              OR
$> cd ApacheBooster-master/apachebooster
```

3. Execute installation script and wait for it to finish:
```bash
$> sh install.sh
```

## Uninstallation instructions:

```bash
1. Clone the ApacheBooster files onto your server.
2. Change the working directory to cloned folder.
3  execute uninstall script.
  $> sh uninstall
```

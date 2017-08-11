---
layout: post
title: A Wordpress shell
---

At [The Mighty](https://themighty.com) my work involves dealing with wordpress extensively. Having a php shell with access to the full wordpress libraries was something I was looking for. I tried couple of php cli hacks before I stumbled on [WP CLI](http://wp-cli.org). Now getting a php cli with wordpress is as simple as

```
$ wp shell
```

As a side note -- I created a simple docker container to run [wordpress with few extras, here.](https://hub.docker.com/r/csandeep/centos-php7-apache-wordpress-latest/)

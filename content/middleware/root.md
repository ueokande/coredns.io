+++
title = "root"
description = "*root* simply specifies the root of where CoreDNS finds (e.g.) zone files. "
weight = 21
tags = [  "middleware" , "root" ]
categories = [ "middleware" ]
date = "2017-07-24T15:25:40+00:00"
+++

The default root is the current working directory of CoreDNS. A relative root path is relative to
the current working directory.

## Syntax

~~~ txt
root PATH
~~~

**PATH** is the directory to set as CoreDNS' root.

## Examples

Serve zone data (when the *file* middleware is used) from `/etc/coredns/zones`:

~~~ txt
root /etc/coredns/zones
~~~

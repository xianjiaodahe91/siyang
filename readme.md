Nginx Module for Google
=======================

[![Build Status](https://travis-ci.org/cuber/ngx_http_google_filter_module.svg?branch=dev)](https://travis-ci.org/cuber/ngx_http_google_filter_module)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/cuber/ngx_http_google_filter_module?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

#### Description ####
`ngx_http_google_filter_module` is a filter module which makes google mirror much easier to deploy.    
Regular expressions, uri locations and other complex configurations have been built-in already.    
The native nginx module ensure the efficiency of handling cookies, gstatic scoures and redirections.   
Let's see how `easy` it is to setup a google mirror.
```nginx
location / {
  google on;
}
```
> _What? Are you kidding me?_   
> _Yes, it's just that simple!_

This is my Practice
==========================

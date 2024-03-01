---
layout: post
title: Spring Boot How to Guide - 3.Embedded Web Servers
description: Any Feedbacks Are Welcomed.
date: 9999-09-18 09:09:09 +0900
tags: Spring-Boot
---

#### [source link](https://docs.spring.io/spring-boot/docs/current/reference/html/howto.html#howto.webserver)

> Spring Boot ships by default with Tomcat 10.1.x which supports `h2c` and `h2` out of the box. [(In Docs)](https://docs.spring.io/spring-boot/docs/current/reference/html/howto.html#howto.webserver.use-another:~:text=Spring%20Boot%20ships%20by%20default%20with%20Tomcat%2010.1.x%20which%20supports%20h2c%20and%20h2%20out%20of%20the%20box.%20Alternatively%2C%20you%20can%20use%20libtcnative%20for%20h2%20support%20if%20the%20library%20and%20its%20dependencies%20are%20installed%20on%20the%20host%20operating%20system.)

Each Spring Boot web application includes an **embedded web server**. This feature leads to how to *change* the embedded server and how to *configure* the embedded server. Setting an embedded server is essential for testing during the development.

This section answers those questions.

##

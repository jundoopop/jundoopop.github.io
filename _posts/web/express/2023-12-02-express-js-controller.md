---
layout: post
title: Discussing About Controller
description: Example With Express.js
date: 2123-12-02 08:08:08 +0900
tags: node.js
---

#### Routes receive HTTP Request, and controllers get them and response to HTML.

##### 1. Express / Node Introduction in MDN Web Docs

This document introduces about key elements in Express.js and Node.js.
Especially, I focused on the part of Express.js:

This is a list of mechanisms mdn shows.

- Write handlers for requests with different HTTP verbs at different URL paths (routes).

  - _[This is a reference by which I tried to explain about.](https://expressjs.com/en/guide/routing.html) -> Express.js Guide_
  - _Route in Express.js defines how to response to client's request. There are several request methods of HTTP; GET, POST, PUT, etc._
  - _Code from Express.js document: for explaination of routing:_

  ```javascript
  // GET method route
  app.get("/", (req, res) => {
    res.send("GET request to the homepage");
  });
  // POST method route
  app.post("/", (req, res) => {
    res.send("POST request to the homepage");
  });
  ```

- Integrate with "view" rendering engines in order to generate responses by inserting data into templates.
- Set common web application settings like the port to use for connecting, and the location of templates that are used for rendering the response.
- Add additional request processing "middleware" at any point within the request handling pipeline.

![Structure of Backend Project](image.png)

```

```

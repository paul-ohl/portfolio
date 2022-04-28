---
title: "Webserv"
date: 2022-03-22
draft: false
toc: false
description: "A HTTP web server, guess nginx wasn't good enough"
images:
  - https://images.unsplash.com/photo-1558494949-ef010cbdcc31?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop
tags:
  - C/C++
  - Web
  - Teamwork
imagecredit: 'Photo by Taylor Vick on Unsplash'
---

## A ~~home~~ school made web server

It is a [school project](https://42.fr/) where we had to create a web server
that could work with the HTTP standard.

We were three members on this project, which taught me a lot about team work,
and git. We coordinated the team using mainly
[Notion](https://www.notion.so/pohl/webserv-adb495c3ae2b42f1a0fd9f41344e9b7e).

## There were four major parts to this project:
- Working with sockets: The communication with the client uses linux sockets,
which we had to learn how to use.
- Parsing: The web server needed two parsers: one for the configuration file,
and one for the input we received from the client.
- Error management: a big part of selecting pages in a server is... not finding
them, so we had to create a very solid error management system to always *fail
gracefully*. C++'s try-catch blocks came in very handy!
- External programs: The server had to handle CGIs (running external programs
using input from the client) so we had to setup a way for our program to launch
external programs, and use their ouput as the response to send to the client.

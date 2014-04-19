---
layout: post
title: "Hello, World!"
date: 2014-04-18 02:20:50 +0530
comments: true
author: Sankalp Agrawal
categories:
- Java
- Ruby
---

This is just a test post to see how it works, how the blog looks like, links, code snippets and all.

Let's do a simple [Hello World Program](http://en.wikipedia.org/wiki/Hello_world_program) for that.

``` java Print Hello, World! in Java
public class HelloWorld {
    public static void main(String [] args) {
        System.out.println("Hello, World!");
    }
}
```

Just the final steps...

``` ruby Fire up Git Bash
# Go to the directory where octopress is
cd c:/github/blog # for me
rake generate # Generate to the proper format
rake preview # Check how it looks like by visiting localhost:4000/blog in Chrome
rake deploy # Add, Commit, Push to the repo
```

Looks nice!

Ok then, that's all for now!

Watch out for better posts coming up. ;)
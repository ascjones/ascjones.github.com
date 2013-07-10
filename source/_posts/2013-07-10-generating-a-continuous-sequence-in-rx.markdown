---
layout: post
title: "Generating a continuous sequence in Rx"
date: 2013-07-10 21:12
comments: true
categories: [.NET, Rx]
---

Previously when I wanted to create an 'infinite' observable sequence I was using something like the following:

``` c#
if (x == 1) 
{
	x = 2;
}
```



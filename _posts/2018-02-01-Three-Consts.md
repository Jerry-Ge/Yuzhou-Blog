---
layout: post
title: The Three Const Keywords in C++
date: 2018-02-01 08:45:20
categories: c++ reference
tags: [C++, keywords, Const]
description: What's the use of three different const keywords in C++
image: 
---

>Consider the following block of code

	template<class K, class V>
	V const& Map<K,V>::get(const K& key) const
	{...}

### The first const means:
You can not modify the returned value V

### The second const means:
You can not modify the input argument key

## The third const means:
This member function "get" never modifies data members in an objectss
s
---
### More

For more questions or any cooperations, please contact me at yuzhou@yuzhoulab.com! 

---

### Love & Peace !!!

---
title: "Abstract Class"
date: 2022-09-17T00:27:27+06:00
draft: false
description: "Desc Text."
tags: ["abstract-class"]
---

an abstract class cannot be instantiated.
an abstract class may contain abstract methods and accessors.
it is not possible to modify an abstract class with the sealed modifier because the two modifiers have opposite meanings. 
the sealed modifier prevents a class from being inherited and the abstract modifier requires a class to be inherited.
a non-abstract class derived from an abstract class must include actual implementations of all inherited abstract methods and accessors.
an abstract class must provide implementation for all interface members.
an abstract class that implements an interface might map the interface methods onto abstract methods.
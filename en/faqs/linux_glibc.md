
---
title: What's the lowest glibc version that the Agora RTM SDK requires on Linux Java and Linux C++?
description: 
platform: Linux CPP,Linux Java
updatedAt: Tue Oct 15 2019 15:48:29 GMT+0800 (CST)
---
# What's the lowest glibc version that the Agora RTM SDK requires on Linux Java and Linux C++?
The lowest glibc version that the Agora RTM SDK requires on Linux Java and Linux C++ is v2.14. If your glibc version is lower, the .so library will fail to load and the following error message will occur: 

- version 'GLIBC_2.14' not found.
- "NoClassDefFoundError". 

Upgrade your glibc version to fix this issue. 

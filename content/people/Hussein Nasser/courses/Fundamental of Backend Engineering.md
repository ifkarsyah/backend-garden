---
title: Fundamentals of Backend Engineering
---
Detail:
- URL: https://www.udemy.com/course/fundamentals-of-backend-communications-and-protocols/?couponCode=HT817IDMT81324
- Author: 
- TLDR: Understand backend communication design patterns, protocols, execution and proxying.


## Description

Backend engineering is an art. During my 18 years career working with and building backend applications, I discovered that certain communication design patterns keep emerging. There are only handful of ways clients communicate with backend applications, although they might be more, I believe the **patterns** I discuss in this course are the most common. Examples of these patterns are request-response, publish-subscribe, short and long and push.

Based on these communication design patterns, engineers may use a number of protocols for concrete communication. While core transport vehicles are limited to either TCP or UDP, tons of industry specific protocols are built on top of these two to address certain problems and use cases. Examples of these high level protocols are HTTP/1.1, HTTP/2, HTTP/3, gRPC, WebRTC and many more. Other transport protocols like QUIC was built on top of UDP to bring HTTP/2 streaming down at the transport level. Each protocol has its pros and cons and fits certain use cases. In the course, I discuss the top common protocols and provide examples and demos where applicable.

Before the client can send a request, it has to establish a connection to the backend. Understanding how the connection is established, and what parts of connection establishment is done at kernel and what parts are done at the backend application process is critical. How the connection is then accepted by the backend application and how it can accept connections as fast as possible so the kernel queue doesn’t get full otherwise clients can no longer connect.

After the connection is established the client sends the request, but what happens exactly in the backend application to read the request? What exactly is a request? Understanding the cost of parsing a request based on the protocol makes the engineer appreciate the work done and equip her with better tools to troubleshoot performance problems or bugs.

Once the request reaches the backend, the application has to execute the request. The backend has a buffet of design choices when it comes to the style of execution it can choose. Understanding the difference between a process and a thread, multi-process, multi-threaded and the correlation to the number of CPU cores or hardware threads is crucial to pick the right execution pattern. One does not have to stick with these patterns but can invent new ones that suits their needs.

This course is designed for engineers who have built backend applications, it is an intermediate — advance level course, certain programming and networking knowledge is required so I recommend taking my fundamentals of network engineering course before taking this course if you don’t have the networking skills. I hope you enjoy this course, and thank you so much for considering it.
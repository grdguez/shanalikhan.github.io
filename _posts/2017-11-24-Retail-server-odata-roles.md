---
layout: post
title: Allowed Roles for Retail Server OData Controllers
description : Complete details on which you can see the roles allowed for Retail Server OData Controllers.
---

The Retail Server is a wrapper over commerce runtime. Retail Server uses a web API and OData to support thin clients both in the store and online on tablets and phones. The commerce runtime communicates with Retail Headquarters through Commerce Data Exchange services.

Retail Server supports Service to Service authentication which makes it possible to have services capable of communicating with Retail Server without a need of a user in front of a screen to provide credentials at some point in time. This enables scenarios when you need to create processes to periodically contact Retail Server to perform different kind of tasks, for instance, synchronizing customers, orders, publishing products for eCommerce functionality and so on.

To use the Retail Server OData Controllers you must be authorized by some roles. If you are not Authroized by the required roles, Retail Server throw exception as:

> Retail Proxy Exception : User is not authorized.

But you can check what type of roles each of the Retail Server Controller Action requires in the following way.

**Open Retail Server SDK from Machine.**

Navigate to Retail Server in Azure Machine. The controllers are present in the Retail Server Library and you need to decompile the assembly. I personally prefer [JetBrains dotPeek](https://www.jetbrains.com/decompiler/)

![Retail Server](http://shanalikhan.github.io/img/rs-odata-role1.PNG)

**Open Assembly in Decompiler**

The Controllers are present in 'ODataControllers' Namespace.

![Retail Server Controllers](http://shanalikhan.github.io/img/rs-odata-role2.PNG)

**Open Controller and See Authorized Roles**

![Retail Server Controllers Roles](http://shanalikhan.github.io/img/rs-odata-role3.PNG)
![Retail Server Controllers Roles](http://shanalikhan.github.io/img/rs-odata-role4.PNG)

If you are connected through any application custom application, you must have application mode enabled as i discussed in my previous [post](http://shanalikhan.github.io/2017/08/31/enable-application-mode-dynamics-retail-server.html) and you will be able to call the actions that allows application role.


Feel free to ask questions!
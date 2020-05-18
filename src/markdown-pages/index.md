---
title: 'Introduction'
page: 1
nextpage: '/get-started'
prevpage: null
---

### Introduction

Crypt Oauth 2.0 service is a web service to provide Authentication to Server Side Applications using Oauth2.0 Protocol. Before OAuth, a common pattern for granting access to your account to a third-party application was to simply give it your password and allow it to act as you. We commonly saw this with Twitter apps which would ask for your Twitter password in order to give you some stats on your account, or would ask to be able to tweet something from your account in exchange for something of value.

This pattern of applications obtaining user passwords obviously has a number of problems. Since the application would need to log in to the service as the user, these applications would often store users’ passwords in plain text, making them a target for harvesting passwords. Once the application has the user’s password, it has complete access to the user’s account, including having access to capabilities such as changing the user’s password! Another problem was that after giving an app your password, the only way you’d be able to revoke that access was by changing your password, something that users are typically reluctant to do.

CryPt Oauth2.0 provides user the right to give access to there credentials to client applications.Our service provide access token to client application (if user have granted the access).The client application provide that token in subsequent request to get access to users resources.The expire time is associated with token so that client applications get access for resources only for short period of time. Our service also provide the right to user for revoking access from client applications.

[click here to contribute to this page](https://github.com/sharvan-sharma/CryPt-docs/tree/master/src/markdown-pages/index.md)

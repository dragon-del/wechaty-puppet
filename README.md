# WECHATY PUPPET

[![NPM Version](https://badge.fury.io/js/wechaty-puppet.svg)](https://badge.fury.io/js/wechaty-puppet)
[![TypeScript](https://img.shields.io/badge/%3C%2F%3E-TypeScript-blue.svg)](https://www.typescriptlang.org/)
[![Linux/Mac Build Status](https://travis-ci.com/Chatie/wechaty-puppet.svg?branch=master)](https://travis-ci.com/Chatie/wechaty-puppet)

![chatie puppet](https://chatie.io/wechaty-puppet/images/puppet-logo.jpg)

> Picture Credit: [https://www.shareicon.net](https://www.shareicon.net/puppet-marionette-puppeteer-puppet-variant-marionette-variant-665400)

Abstract(Base) Class of Wechaty Puppet Framework.

This module is part of the [Wechaty](https://github.com/chatie/wechaty) SDK.

Learn more at:

1. Wiki: <https://github.com/Chatie/wechaty/wiki/Puppet>
1. Issue: <https://github.com/Chatie/wechaty/issues/1167>

## EXAMPLE

PuppetMock: <https://github.com/chatie/wechaty-puppet-mock>

The above puppet is for mocking, and also could be a good starter if you want to implement a new puppet for yourself.

### Implementations

* [PuppetWechat4u](https://github.com/chatie/wechaty-puppet-wechat4u) Web API via HTTP, by Huan LI
* [PuppetPuppeteer](https://github.com/chatie/wechaty-puppet-puppeteer) Web API via Browser, by Huan LI
* [PuppetPadchat](https://github.com/lijiarui/wechaty-puppet-padchat) iPad API via Protocol Server, by Rui LI
* [PuppetHostie](https://github.com/chatie/wechaty-puppet-hostie) gRPC Proxy via Chatie.io(PaaS - Puppets as a Service), by Huan LI

## DEPENDENCIES

### Peer Depedence

`FileBox` (npm module `file-box`) must be a `peerDependencies`, becasue all the Wechaty Framework need to check `instanceof FileBox`, we must be sure all `FileBox` is the same version.
`MemoryCard` (npm module `memory-card`) must be a `peerDependencies`, becasue all the Wechaty Framework need to check `instanceof MemoryCard`, we must be sure all `MemoryCard` is the same version.

## Resources

### Pure Function

* [Functional Programming Concepts: Pure Functions](https://hackernoon.com/functional-programming-concepts-pure-functions-cafa2983f757)
* [What Are Pure Functions And Why Use Them?](https://medium.com/@jamesjefferyuk/javascript-what-are-pure-functions-4d4d5392d49c)
* [Master the JavaScript Interview: What is a Pure Function?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-pure-function-d1c076bec976)

## AUTHOR

[Huan LI](http://linkedin.com/in/zixia) \<zixia@zixia.net\>

<a href="https://stackexchange.com/users/265499">
  <img src="https://stackexchange.com/users/flair/265499.png" width="208" height="58" alt="profile for zixia on Stack Exchange, a network of free, community-driven Q&amp;A sites" title="profile for zixia on Stack Exchange, a network of free, community-driven Q&amp;A sites">
</a>

## COPYRIGHT & LICENSE

* Code & Docs © 2018 Huan LI \<zixia@zixia.net\>
* Code released under the Apache-2.0 License
* Docs released under Creative Commons
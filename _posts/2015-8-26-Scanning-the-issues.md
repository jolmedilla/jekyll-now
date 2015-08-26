---
layout: post
title: Scanning the issues: Communications of the ACM and IEEE Software, August 2015
---

I have scanned August issues of Communications of the ACM and IEEE Software and I have found a couple of interesting articles that I would like to share with you:

## [Testing Web Applications with State objects](http://cacm.acm.org/magazines/2015/8/189845-testing-web-applications-with-state-objects/fulltext)

This is an iteresting practical article that describes a method to specify and build tests for web applications using Martin Fowler's Page Objects on top of Selenium WebDriver. The beauty of it is that a complete web site can be described, from a testing perspective, as a state machine in which all pages are stateful and the transition between pages are state transitions. Page Objects and State Objects help to abstract from the underlying Selenium WebDriver API into a more domain meaningful voabulary so that the tests can be easily understood by all stakeholders.

---
layout: post
tag: code, book
title: Design Patterns
author: 怡安
---

我覺得要學好 Object Oriented Programming (OOP)，最好的方式就是學 Design Pattern。Design Patterns 最經典的書是 [Design Patterns: Elements of Reusable Object-Oriented Software](https://www.oreilly.com/library/view/design-patterns-elements/0201633612/)，是第一本關於 Design Patterns 的書。不過我覺得這本書不適合拿來入門，我讀的是 [Head First Design Patterns](https://www.oreilly.com/library/view/head-first-design/0596007124/)，這本書對於每個 Design pattern 都有舉很生活化的例子，而且也會告訴我們如果沒有用 Design Pattern 會造成像是 highly coupled 的維護上的困難。

有一章是介紹很經典的 MVC 框架，如果用 Design Pattern 的觀點來看的話就會很好理解，Model - Observer, View - Composite, Control - Strategy 使得三者的分工很明確，Observer 讓 model 不用 depend on viewer 和 controllers，Strategy 讓 controller 只關注把 user input 轉成 model 的 action，Composite 讓 view 有一種樹狀的結構。這是這本書最為精彩的部分。

當然每種 Design Patterns 帶來的好處也會有相對的壞處，通常是讓整個系統更加的複雜，還有 class 的數量變很多。所以這本書也強調不是一定要用 Design Patterns，如果有更簡單的解法就用簡單的解法，更重要的是學會運用 OO 的 Design Principles ，在以前沒遇過的問題時，也能想出好的解決方法。

## OO Basics
* Abstraction
* Encapsulation
* Polymorphism
* Inheritance

## OO Principles
* Encapsulate what varies.
* Favor composition over inheritance.
* Strive for loosely coupled designs between objects that interact.
* Classes should be open for extension but closed for modification.
* Depend on abstractions. Do not depend on concrete classes.
* Only talk to your friends.
* Don't call us, we'll call you.
* A class should have only one reason to change.
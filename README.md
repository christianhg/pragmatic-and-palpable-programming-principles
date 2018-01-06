# Pragmatic and Palpable Programming Principles

> Disclaimer: I don't know what I'm doing.

[Separation of Concerns](https://en.wikipedia.org/wiki/Separation_of_concerns) (SoC) is valuable but too vague.<sup><a href="#fn1">[1]</a></sup> [Don't Repeat Yourself](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) (DRY) is flat out harmful.<sup><a href="#fn2">[2]</a></sup> This resource sets out to define a set of easy-to-grasp and easy-to-follow principles for programmers.

Each entry deserves their own chapter in an important book<sup><a href="#fn3">[3]</a></sup>, but for now an annotated list must do:

* **Economize code.**
  <br>Writing code is often easier than removing it again. Coding in the blind or copy/pasting from documentation or other learning material can be a powerful way to get going, but at the same time it can introduce excessive amounts of code. Every time you've gotten a feature or function to work, experiment with taking it apart again by removing code that might be unnecessary. Ensure that every single line of code matters and that you undestand why.

* **Communicate clearly.**
  <br>Spend those extra five minutes to craft an even better commit message. Take pride in doing spellcheck and ensuring a consistent (and short) line length to highten the legibility. Commits are the primary way programmers communicate: treat it as such. Use the commit summary mainly to describe **why** the change was needed. This ensures that programmers - you or others, now or in the future - are in the know.

* **Be honest.**
  <br>If you don't know why a change is needed, why a bug went away or how a feature of mashed together spaghetti code came to life, do everything you can to find out. If you fail to reach an understanding, throw the work away.

* **Write tests.**
  <br>Tests can help you design your program, ensure that it works, and protect it from getting broken later.

* **Embrace constraints.**
  <br>The less features an API offers to its consumer, the easier it is to learn and work with. A function with a single parameter is simpler to use than one with three.

* **Be declarative.**
  <br>Knowing **how** a piece of code works is often not an important factor. On the other hand, knowing **what** a piece of code does is.

* **Skepticize conditionals.**
  <br>If the cost of every conditional is assessed before it is added, the result will be a simpler codebase with fewer branches and breeding grounds for bugs.

* **Favor functions.**
  <br>Always choose the least powerful abstraction that can get the job done.

* ...

---

<a id="fn1">[1]</a> Clearly there exists different interpretations of what a "concern" is. [Insert rant about SoC]

<a id="fn2">[2]</a> DRY is too easy to take too literally. [Insert rant about DRY]

<a id="fn3">[3]</a> They probably already have.

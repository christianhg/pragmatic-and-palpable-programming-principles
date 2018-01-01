# Pragmatic and Palpable Programming Principles

> Disclaimer: I don't know what I'm doing.

[Separation of Concerns](https://en.wikipedia.org/wiki/Separation_of_concerns) (SoC) is valuable but too vague.<sup><a href="#fn1">[1]</a></sup> [Don't Repeat Yourself](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) (DRY) is flat out harmful.<sup><a href="#fn2">[2]</a></sup> This resource sets out to define a set of easy-to-grasp and easy-to-follow principles for programmers.

Each entry deserves their own chapter in an important book<sup><a href="#fn3">[3]</a></sup>, but for now an annotated list must do:

* **Write tests.**
  <br>Tests can help you design your program, ensure that it works, and protect it from getting broken later.

* **Embrace constraints.**
  <br>The less features an API offers to its consumer, the easier it is to learn and work with. A function with a single parameter is simpler to use than one with three.

* **Strive for declarative code.**
  <br>Knowing **how** a piece of code works is often not an important factor. On the other hand, knowing **what** a piece of code does is.

* ...

---

<a id="fn1">[1]</a> Clearly there exists different interpretations of what a "concern" is. [Insert rant about SoC]

<a id="fn2">[2]</a> DRY is too easy to take too literally. [Insert rant about DRY]

<a id="fn3">[3]</a> They probably already have.

Here are some of my personal recommendations 💻

## Programming 👨🏼‍💻

````
Linux kernel coding style
=========================

This is a short document describing the preferred coding style for the
linux kernel.  Coding style is very personal, and I won't **force** my
views on anybody, but this is what goes for anything that I have to be
able to maintain, and I'd prefer it for most other things too.  Please
at least consider the points made here.

First off, I'd suggest printing out a copy of the GNU coding standards,
and NOT read it.  Burn them, it's a great symbolic gesture.

Anyway, here goes:
````

- [Coding Style](https://www.kernel.org/doc/Documentation/process/coding-style.rst)

---

## Software engineering 👩🏼‍🍳

````
Semantic Versioning 2.0.0
=========================

In the world of software management there exists a dreaded place
called “dependency hell.” The bigger your system grows and the more
packages you integrate into your software, the more likely you are to
find yourself, one day, in this pit of despair.
````

-[Semantic Versioning](https://semver.org/)

---

````
In the modern era, software is commonly delivered as a service: called
web apps, or software-as-a-service. The twelve-factor app is a
methodology for building software-as-a-service apps that:

  - Use declarative formats for setup automation, to minimize time and
  cost for new developers joining the project;
  - Have a clean contract with the underlying operating system,
  offering maximum portability between execution environments;
  - Are suitable for deployment on modern cloud platforms, obviating
  the need for servers and systems administration;
  - Minimize divergence between development and production, enabling
  continuous deployment for maximum agility;
  - And can scale up without significant changes to tooling,
  architecture, or development practices.

The twelve-factor methodology can be applied to apps written in any
programming language, and which use any combination of backing
services (database, queue, memory cache, etc).
````

-[The twelve-factor app](https://12factor.net/)
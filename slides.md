# Framework-agnostic code

Stefano Torresi ([@storresi](https://twitter.com/storresi))

---

# Disclaimer

Opinionated content ahead,
take with a grain of salt.

---

# To framework or not to framework?

This is _not_ the question, forget about Shakespeare.

---

# Everything is a trade-off

**Pro:** frameworks let you get started quickly.  
**Con:** fast prototyping leads to sloppy design.

---

# Everything is a trade-off

**Pro:** abstractions help solving common problems.  
**Con:** leaky abstractions are problems on their own.

---

# Everything is a trade-off

**Pro:** third-party code is not your responsibility  
**Con:** third-party code is not under your control

---

# _In medio stat virtus_

---

# The web is simple

`f(Request): Response`

---

# The UNIX philosophy

_Do one thing and do it well._

---

# The UNIX philosophy

Easy is complex, simple is hard.

---

### PHP Standards Recommendations

- Made by php-fig.org.
- Compensate shortcomings of the PHP Stdlib.
- Provide implementation-agnostic conventions.

---

# Examples

- PSR-3: Logging
- PSR-4: Autoloading
- PSR-7,15,17,18: HTTP
- PSR-11: DI containers

---

# Demo time

_Talk is cheap, show me [the code](https://github.com/stefanotorresi/frameworkless-php-boilerplate)._
Linus Torvalds

---

# Conclusions

- Understand the costs of big third-party bundles
- Learn how decoupled small libraries can interact together
- Keep It Stupid Simple

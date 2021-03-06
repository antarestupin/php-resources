---
title: "How to Write Standardized PHP Code?"
updated: "October 8, 2016"
permalink: "/faq/coding-standards/"
---

For PHP there are many standards or coding style recommendations that you should
look into when writing code. It simplifies collaboration on the code and makes
it more readable once you get used to one style.

One of the most adopted standards recommendation in PHP is [PHP FIG](http://php-fig.org)
which recommends coding style via two PSRs (PHP Standard Recommendation):

* [PSR-1](http://www.php-fig.org/psr/psr-1/) - Basic coding standard
* [PSR-2](http://www.php-fig.org/psr/psr-2/) - Coding style guide

Many open source projects also extend above PSRs with their own coding style guides:

* [Symfony](http://symfony.com/doc/current/contributing/code/standards.html)

Many advanced PHP IDEs and editors offer also code refactoring through their
plugins and extensions. With predefined common code styles such as PSR-1 and PSR-2
refactoring code, automatic code generation, autocomplete and similar nice features
can be solved very nicely and consistently.

More you will write code, more you will understand the importance in using common
style guide. Specially when working with source code control such as Git, coworkers,
or just to be consistent in general.

## See Also

* [Core PHP language specification](https://github.com/php/php-langspec)
* [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) - Tokenizes PHP,
  JavaScript and CSS files and detects violations of a defined set of coding
  standards.
* [PHP Coding Standards Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) - Tool
  that fixes coding standards in your code.
* [PHP-FIG: Extended Coding Style Guide proposal](https://github.com/php-fig/fig-standards/blob/master/proposed/extended-coding-style-guide.md)

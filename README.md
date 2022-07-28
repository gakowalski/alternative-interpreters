# Alternative Interpreters

## PHP

### Alternative interpreters and compilers

* [php-wasm](https://github.com/seanmorris/php-wasm) - Run PHP right in the browser. Live demo included.
* [HippyVM](https://github.com/hippyvm/hippyvm) - an implementation of the PHP language using RPython/PyPy technology
* [KPHP](https://vkcom.github.io/kphp/) - compiles a limited subset of PHP to a native binary running faster than PHP
* [php.js](http://phpjs.hertzen.com/) -  reads PHP code and transforms it into JavaScript code and then runs
* ❤️ [PH7](https://ph7.symisc.net/) - An Embedded Implementation of PHP 5 with a lot of PHP 7+ and C++-like improvements, see its [distinctive features](https://ph7.symisc.net/features.html)
* [PHPPHP](https://github.com/ircmaxell/PHPPHP) - PHP interpreter written in PHP, low performance - for much faster one see: Recki-CT
* [pipp](https://github.com/bschmalhofer/pipp) - an implementation of the language PHP that runs on Parrot
* [pyhp](https://github.com/juokaz/pyhp) - incomplete implementation of the PHP language using the RPython technology (for complete implementation see: HippyVM)
* [pyhp.js](https://github.com/juokaz/pyhp.js) - PyHP interpreter translated into JavaScript using emscripten, resulting javascript file is asm.js which can be loaded in any browser or ran with Node.js
* [Quercus](https://www.caucho.com/resin-3.1/doc/quercus.xtp) - Java implementation of the PHP language
* [Recki Compiler Toolkit for PHP](https://github.com/google/recki-ct) - quote from [1]: "a compiler written entirely in PHP and only targets a subset of the PHP specification. It intentionally limits itself to a more static subset so that it is faster. This means that it does not support things like references, variable-variables and global variables. Recki-CT compiles PHP down to machine code but unlike HHVM and HippyVM, which use Just in Time compilation to compile PHP, it uses Ahead of Time compilation which caches an intermediary representation that can be compiled at run-time. Therefore, more aggressive optimisations can be applied and more efficient code can be generated. Based on trivial benchmarks, Recki-CT proves to be extremely fast."

Old stuff: https://stackoverflow.com/a/1408499/925196

### Transpilers ###

(empty)

### Trans-compilers from other languages to PHP

* [Blueberry](https://github.com/gosukiwi/Blueberry) - a script language with clean syntax, inspired from Ruby, CoffeeScript, and Python which compiles to PHP
* [Haxe](https://haxe.org/) - high-level strictly-typed programming language with a fast optimizing cross-compiler which also compiles to PHP
* [Phabel](https://github.com/phabelio/phabel) - allows native usage of PHP 8+ features and especially syntax in projects and libraries, while allowing maintainers to publish a version targeting lower versions of php
* [Pharen](https://github.com/scriptor/pharen) - compiles a Lisp-inspired language to PHP
* [Phel](https://phel-lang.org/) - dialect of Lisp that compiles to PHP
* [Pratphall](http://cretz.github.io/pratphall/) - an optionally-typed language that compiles to readable PHP
* [Salty](https://github.com/egonschiele/salty) - a language that compiles to PHP, JavaScript, and JSX; Haskell-inspired
* [Snowscript](https://github.com/runekaagaard/snowscript) - a language that compiles to PHP; its syntax is inspired by Python, Lua, Coffescript, Go and Scala and strives to be DRY, clean and easy to read as well as write
* [THT](https://tht.dev/) - a clean re-design of PHP, making it more secure and easier to use

### Preprocessors

* [Pre](https://preprocess.io/) - compiles new syntax to work in new and old versions of PHP

### Other

* [AerScript](https://github.com/sc0ttj/AerScript) - general-purpose, object-oriented scripting programming language based on PH7 (alternative PHP interpreter)

### Languages derived from PHP

* [Hack](https://hacklang.org/) - PHP-like new language with gradual typing, generics and new container types (vector, map, set, pair) executed on HipHop Virtual Machine (HHVM) [2]

### Research papers

#### References

* [1] KHAN, Sher Ali; MAFFEIS, Sergio. A Comparative Study of PHP Dialects. 2015.
* [2] ADAMS, Keith, et al. The hiphop virtual machine. In: Proceedings of the 2014 ACM International Conference on Object Oriented Programming Systems Languages & Applications. 2014. p. 777-790.
* [3] OTTONI, Guilherme. HHVM JIT: A Profile-guided, Region-based Compiler for PHP and Hack. In: Proceedings of the 39th ACM SIGPLAN Conference on Programming Language Design and Implementation. 2018. p. 151-165.

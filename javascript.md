# Alternative Interpreters

## JavaScript

### JS interpreters written in JS

Reasons:
* bypassing disabled `eval` and `Function`
* running code in sandbox
* controlling execution time

Some benchmarks:


name | description | last commit
--- | --- | ---
[engine262](https://github.com/engine262/engine262) | An implementation of ECMA-262 in JavaScript | 2022
[eval.js](https://github.com/marten-de-vries/evaljs) | drop in alternative for window.eval(), supossedly supports ES6, 104 kB minified, 16 kB gzipped | 2016
[eval5](https://github.com/bplok20010/eval5) | supports ES5, 131 kB minified, 34 kB gzipped | 2022
[JS-Interpreter](https://github.com/NeilFraser/JS-Interpreter) | execute arbitrary JavaScript code line by line in isolation and safety | 2022
[MetaES](https://github.com/metaes/metaes) | a JavaScript metacircular interpreter | 2022
[narcissus](https://github.com/mozilla/narcissus) | original proof-of-concept meta-circular evaluator written by JavaScript creator, Brendan Eich, using the SpiderMonkey engine | 2012
[sablejs](https://github.com/sablejs/sablejs) | the fastest interpreter written in JS, covers ~95% test262 es5-tests cases, supports ES 5.1, 216 kB minified, 29 kB gzipped | 2022
[sval](https://github.com/Siubaak/sval) |supporting ES5~10 full features, 148 kB minified, 40 kB gzipped | 2020

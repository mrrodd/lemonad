lemonad
=======

a functional programming library built on, and extending, [Underscore.js](http://underscorejs.org) -- inspired by the [Clojure](http://www.clojure.org) core and contrib libraries.

![lemonad](https://raw.github.com/fogus/lemonad/master/docs/logo.png)

currently available functions:

```javascript
[ '$',
  'CAS',
  'CASProtocol',
  'L',
  'Hole',
  'RefProtocol',
  'VERSION',
  'WatchableProtocol',
  'accessor',
  'actions',
  'addWatch',
  'assoc',
  'best',
  'butLast',
  'cat',
  'compareAndSwap',
  'complement',
  'compose',
  'conjoin',
  'cons',
  'constantly',
  'ctor',
  'curry',  
  'curry2',
  'curry3',
  'curry4',  
  'dec',
  'decreasing',
  'decreasingOrEq',
  'def',
  'disjoin',
  'dropWhile',
  'everyPred',
  'existy',
  'explode',
  'fnull',
  'frequencies',
  'gt',
  'implode',
  'inc',
  'increasing',
  'increasingOrEq',
  'interleave',
  'interpose',
  'into',
  'invokeAll',
  'isAssociative',
  'isEven',
  'isIndexed',
  'isOdd',
  'isNeg',
  'isPos',
  'isReference',
  'isSeq',
  'isInst',
  'isZero',
  'iterateUntil',
  'juxt',
  'k',
  'keep',
  'keepIndexed',
  'lt',
  'mapcat',
  'maxKey',
  'meth',
  'nth',
  'partial$',
  'partial1',
  'partial2',
  'pipeline',
  'plucker',
  'pour',
  'reductions',
  'remove',
  'removeWatch',
  'repeat',
  'repeatedly',
  'second',
  'setValue',
  'snapshot',
  'someFun',
  'splitAt',
  'splitWith',
  'swap',
  't',
  'takeSkipping',
  'takeWhile',
  'thrush',
  'truthy',
  'update' ]
```

Influences / References
-----------------------

* [Clojure and ClojureScript](http://www.clojuredocs.org)
* [Inheritance Patterns in JavaScript](http://bolinfest.com/javascript/inheritance.php) by Michael Bolin
* [Underscore.js](http://underscorejs.org/)
* [Functional JavaScript](http://osteele.com/sources/javascript/functional/) by Oliver Steele
* Functional JavaScript (the book)

Todo
-----

* Promises
* The rest of the things
  - cycle, ...
* Moar monadology
* Logic vars?
* Unification?
* Other things that I can't think of right now
* Generators?
* Futures?
* Laziness?
* Badass memoize
* Some data generators?
* merges
* partitions
* walking
* rel alg
* `into` for objects
* make sure that anything that works for array also works for `arguments`
* Make sure I say, *sequence* on input and *array* on output
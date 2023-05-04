---
layout: default
---

<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->

<h1 id="function-equaltext">Function equalText <a href="#function-equaltext" title="Permalink">#</a></h1>

Check equality of two strings. Comparison is case sensitive.

For matrices, the function is evaluated element wise.


<h2 id="syntax">Syntax <a href="#syntax" title="Permalink">#</a></h2>

```js
math.equalText(x, y)
```

<h3 id="parameters">Parameters <a href="#parameters" title="Permalink">#</a></h3>

Parameter | Type | Description
--------- | ---- | -----------
`x` | string &#124; Array &#124; DenseMatrix | First string to compare
`y` | string &#124; Array &#124; DenseMatrix | Second string to compare

<h3 id="returns">Returns <a href="#returns" title="Permalink">#</a></h3>

Type | Description
---- | -----------
number &#124; Array &#124; DenseMatrix | Returns true if the values are equal, and false if not.


<h3 id="throws">Throws <a href="#throws" title="Permalink">#</a></h3>

Type | Description
---- | -----------


<h2 id="examples">Examples <a href="#examples" title="Permalink">#</a></h2>

```js
math.equalText('Hello', 'Hello')     // returns true
math.equalText('a', 'A')             // returns false
math.equal('2e3', '2000')            // returns true
math.equalText('2e3', '2000')        // returns false

math.equalText('B', ['A', 'B', 'C']) // returns [false, true, false]
```


<h2 id="see-also">See also <a href="#see-also" title="Permalink">#</a></h2>

[equal](equal.html),
[compareText](compareText.html),
[compare](compare.html),
[compareNatural](compareNatural.html)
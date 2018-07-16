---
title: Math Support
date: 2018-07-16
tags: MathJax
use_math: true
---

You can enable math support through `use_math: true` front matter which enable the MathJax.js rendering.

After enable math support, use `$$ ... $$` displaying math equation.

<div>
<strong><em>For inline mode</em></strong>
<div style="margin-left:1em;">
    type your equation in line with other text
</div>
<strong><em>For display mode:</em></strong>
<div style="margin-left:1em;">
    type your equation such that there is a blank line <em>before</em> your beginning <code>$$</code> and there is a blank line <em>after</em> your ending <code>$$</code>
</div>
</div>

<br>
As an example, the following *code*:
```
The Pythagoras' theorem state that the square of the hypotenuse (the side opposite the right angle) is equal to the sum of the squares of the other two sides. The theorem can be written as an equation relating the lengths of the sides $$a$$, $$b$$ and
$$c$$, often called the "Pythagorean equation":

$$a^2 + b^2 = c^2$$

where $$c$$ represents the length of the hypotenuse and $$a$$ and $$b$$ the lengths of the triangle's other two sides. `[source: wikipedia]`

This also implies that for any square with side length $$x$$, the length of its diagonal is $$\sqrt{2}x$$.

**_Proof:_**
Let the length of diagonal be $$d$$. Apply Pythagoras theorem on the right angle triangle that has the diagonal as hypotenuse, and side of square as the other two side, we have:

$$
\begin{align*}
x^2 + x^2 &= d^2 \\
d^2 &= 2x^2 \\
d &= \sqrt{2}x \tag*{$\blacksquare$}
\end{align*}
$$

```
<br>
*produces*:
<hr>

The Pythagoras' theorem state that the square of the hypotenuse (the side opposite the right angle) is equal to the sum of the squares of the other two sides. The theorem can be written as an equation relating the lengths of the sides $$a$$, $$b$$ and
$$c$$, often called the "Pythagorean equation":

$$a^2 + b^2 = c^2$$

where $$c$$ represents the length of the hypotenuse and $$a$$ and $$b$$ the lengths of the triangle's other two sides. `[source: wikipedia]`

This also implies that for any square with side length $$x$$, the length of its diagonal is $$\sqrt{2}x$$.

**_Proof:_** Let the length of diagonal be $$d$$. Apply Pythagoras theorem on the right angle triangle that has the diagonal as hypotenuse, and side of square as the other two side, we have:

$$
\begin{align*}
x^2 + x^2 &= d^2 \\
d^2 &= 2x^2 \\
d &= \sqrt{2}x \tag*{$\blacksquare$}
\end{align*}
$$

<hr>

**_Reference_**
- <https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-qu%E2%80%8C%E2%80%8Bick-reference> (MathJax cheatsheet)
- <https://cdn.rawgit.com/mathjax/MathJax/2.7.1/test/sample-eqnum.html> (some MathJax example)
- <https://www.mathjax.org/#demo> (test your equation at here)
- <https://kramdown.gettalong.org/syntax.html#math-blocks> (Kramdown rendering of `$$...$$` to math mode)

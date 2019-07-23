---
layout: page
mathjax: true

---

<br>

## Table of Contents
 - [Derivatives and Integrals](#derivatives)
 - [Chain rule and product rule](#chain)

<br>

## Derivatives and Integrals
How to calculate the area of a circle?  
 * The area of a circle can be approximated to the aggregated areas of many rectangles ($2\pi rdr$, perimeter $2\pi r$ as the length*width $dr$)

 * ![Area](../src/image/calculus-area.png)
 [Area 6:45](https://www.youtube.comwatch?v=WUvTyaaNkzM&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr&index=1)

<br>

## Chain rule and product rule
 - For Sum rule: The derivative of a sum is the sum of derivatives
   * $\frac{d}{dx}(g(x)+h(x)) = \frac{dg}{dx} + \frac{dh}{dx}$
   * e.g. $\frac{d}{dx}(sin(x)+x^2 = cos(x) + 2x$
   * ![Sum rule](../src/image/sum-rule.png)
[Sum rule, 3:05](https://www.youtube.com/watch?v=YG15m2VwSjA&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr&index=4)
 - Product rule: try to use area for visualization
   * Numerically: Left d(Right) + Right d(Left)
   * $f(x) = g(x)h(x)$
   * $df = g(x)dh + h(x)dg$
   * $\frac{df}{dx} = g(x)\frac{dh}{dx} + h(x)\frac{dg}{dx}$

   * ![Product rule](../src/image/product-rule.png)
   [Product rule, 7:20](https://www.youtube.com/watch?v=YG15m2VwSjA&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr&index=4)
 - Function composition
   * Chain Rule: $\frac{d}{dx}g(h(x)) = \frac{dg}{dg}(h(x))\frac{dh}{dx}(x)$
   * ![Chain rule](../src/image/chain-rule.png)
      [Chain rule, 11:37](https://www.youtube.com/watch?v=YG15m2VwSjA&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr&index=4)

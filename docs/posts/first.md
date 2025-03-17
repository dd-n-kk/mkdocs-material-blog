---
date:
  created: 2025-01-01
  updated: 2025-01-01

authors:
- MY_NAME

categories:
- Miscellany

tags:
- Material for MkDocs
---

# My first post

<!-- more -->


## Python Markdown

- Admonition:

    !!! note

        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla.
        Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa,
        nec semper lorem quam in massa.

- Caret:
    - ^Superscript^
    - ^^Underline^^

- Tilde:
    - ~Subscript~
    - ~~Crossed-out~~

- Mark:
    - ==Marked==

- Footnoted[^1]
  [^1]: Lorem ipsum dolor sit amet, consectetur adipiscing elit.


## KaTeX

- $\displaystyle e^{i\theta} = \cos{\theta} + i\sin{\theta}$

- $$f(x) = \frac{1}{σ\sqrt{2π}}\exp\left(-\frac{1}{2}\left(\frac{x-μ}{σ}\right)^2\right)$$


## Code

- Inline: `#!py lambda seq: {str(x): x for x in seq}`

- Block:
  ```py
  def foo(x: int | None = None) -> int:
      return x or 0  # Comment
  ```

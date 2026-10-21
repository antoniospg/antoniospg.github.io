---
title: Post title
description: One-line summary shown on the home page.
tags: []
# math: false   # MathJax is on for all posts; set false to skip loading it
---

Intro paragraph. Inline math goes between double dollars inside a sentence: $$E = mc^2$$.

Display math is double dollars on their own lines, with blank lines around:

$$
\nabla \cdot \mathbf{u} = 0
$$

Multi-line equations use `aligned` (plain `\\` line breaks don't work outside an environment):

$$
\begin{aligned}
a &= b + c \\
d &= e + f
\end{aligned}
$$

Numbered equations use `equation` plus `\label`, and `\eqref{eq:euler}` refers back to them:

$$
\begin{equation}
e^{i\pi} + 1 = 0 \label{eq:euler}
\end{equation}
$$

Images go in `assets/posts/<post-slug>/`:

![alt text](/assets/posts/post-slug/image.png)

**Figure 1:** Caption.
{: .caption}

```cpp
int main() { return 0; }
```

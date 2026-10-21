# antoniospg.github.io

My blog, built with Jekyll on GitHub Pages, at https://antoniospg.github.io.

## Writing a post

1. Copy `_drafts/post-template.md` to `_posts/YYYY-MM-DD-slug.md`.
2. Put the post's images in `assets/posts/slug/`.
3. Commit and push to `main`. GitHub Pages rebuilds the site within a minute or two.

The post's URL is `/YYYY/slug/`.

## Math

MathJax 3 is loaded on every post (set `math: true` in the front matter to use it on other pages).
kramdown handles the delimiters:

- Inline: `$$x^2$$` inside a sentence
- Display: `$$ ... $$` on its own lines, with blank lines around it
- Multi-line: wrap the lines in `\begin{aligned} ... \end{aligned}`
- Numbered: `\begin{equation} ... \label{eq:x} \end{equation}`, then reference with `\eqref{eq:x}`

## Local preview

Needs Ruby 3.x (`brew install ruby`).

```sh
bundle install
bundle exec jekyll serve --drafts   # http://localhost:4000
```

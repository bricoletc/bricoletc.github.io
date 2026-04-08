This repo holds my mini-website. Published at https://bricoletc.github.io.

For the Markdown source, see [index.md](index.md).

## Credit

All boilerplate code (CSS, HTML) was copied, and the LICENCE file carried over from, https://github.com/elipapa/markdown-cv by Eliseo Papa.

## Rendering 

Two options:

### I. Use Github Pages to publish it online

1. Push to `gh-branches`

### II. Build it locally and print a PDF

1. To [install jekyll](https://jekyllrb.com/docs/installation/), run `gem install bundler jekyll` from the command line.
3. [Clone](https://help.github.com/en/articles/cloning-a-repository) your fork of markdown-cv to your local machine.
3. Type `jekyll serve` to render your CV at http://localhost:4000.
4. You can edit the `index.md` file and see the changes live in your browser.
5. To print a PDF, press <kbd>⌘</kbd> + <kbd>p</kbd>. Print and web CSS media queries should take care of the styling.

## Styling

The included CSS will render your CV in two styles:
s
1. `kjhealy` the original default, inspired by [kjhealy's vita
template](https://github.com/kjhealy/kjh-vita).
2. `davewhipp` is a tweaked version of `kjhealy`, with bigger fonts and dates
  right aligned.

To change the default style, simply change the variable in the
`_config.yml` file.

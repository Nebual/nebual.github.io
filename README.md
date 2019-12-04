**Jekyll** is a static site generator that's perfect for GitHub hosted blogs
([Jekyll Repository](https://github.com/jekyll/jekyll)).
**Jekyll Now** reduces boilerplate.

## Editing Posts
Adding/changing a Markdown file in _posts/, or editing any file in this repo,
will trigger Github Pages to rebuild the static site.

> There are 3 different ways that you can make changes:
> 1. Edit files within the repository in the browser at GitHub.com
> 2. Use a third party GitHub content editor, like
[Prose by Development Seed](http://prose.io).
> 3. Clone down your repository and make updates locally,
then push them to your GitHub repository.

## Local Development

1. Install ruby `sudo apt install ruby`
2. Install Jekyll and plugins `sudo gem install github-pages`
3. Clone this repo
4. `jekyll serve` builds and watches for changes, viewable at http://127.0.0.1:4000/
5. Pushes to `master` will cause GitHub Pages to auto rebuild and publish.
n
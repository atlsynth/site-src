This project is based on [Hugo](https://gohugo.io/).

1. Install g: https://github.com/stefanmaric/g
2. Install Go: `g install latest`
3. Install Hugo: `go install github.com/gohugoio/hugo@latest`
4. Install Git submodules: `git submodule init && git submodule update`

To view the site while writing: `hugo server -D`
To build the site into the `public` directory: `hugo`

The theme used is [Ananke](https://themes.gohugo.io/gohugo-theme-ananke/).

## Adding New Content

1. Create a new feature branch: `git checkout -b my-new-feature`
1. Make your content changes. Use https://gohugo.io/content-management/ as
reference
1. Create a commit: `git add --all && git commit -m 'I added some stuff'`
1. Push the feature branch to GitHub: `git push -u origin my-new-feature`
1. Open a PR on the GitHub website. When the PR is merged, the site will
automatically be built and published

While working on your new content, use `hugo server -D` to view your work
locally.

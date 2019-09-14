This project is based on [Hugo](https://gohugo.io/).

1. Install gvm: https://github.com/moovweb/gvm
2. Install Go: `gvm install go1.9 -B`
3. Install Hugo: `go get -v github.com/gohugoio/hugo`

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

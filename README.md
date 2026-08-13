# About

Website for SIGma meetings.

## Getting Started

```console
git clone git@github.com:SIGma-UIUC/website --recurse-submodules
```

## Editing

- `content/` - markdown files for the index
- `static/meetings/` - pdfs for the slides
- `meetings/` - repository for any source files

Use `hugo` to compile these into `.html` for the static site.

Each edit needs two commits:

1. committing the built `.html` files in the `public/` directory.
2. committing the source `.md` files in the `content/` directory (and bump the gitlink for `public/`)

### Preview

In the `public/` directory, a simple http server is sufficient to preview the site.

```console
python3 -m http.server
```

## Resources

[Create and host a blog with Hugo and GitHub Pages in less than 30 minutes](https://www.mytechramblings.com/posts/create-a-website-with-hugo-and-gh/)

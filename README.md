# jack-lukomski.github.io

Personal site, built by GitHub Pages with Jekyll.

## Writing a post

1. Create `_posts/YYYY-MM-DD-title.md` with front matter:

   ```
   ---
   layout: post
   title: My post title
   ---
   ```

2. Write the post in Markdown below the front matter.
3. Commit and push. GitHub Pages rebuilds the site in about a minute.

Work-in-progress posts go in `_drafts/` and are not published.
See `_drafts/example-post.md` for a template.

## Previewing locally

Needs Ruby 3.3 to match GitHub Pages (macOS system Ruby is too old, and Ruby 4 is too new):

```
brew install ruby@3.3
export PATH="$(brew --prefix ruby@3.3)/bin:$PATH"
bundle install
bundle exec jekyll serve --drafts
```

Then open http://localhost:4000. `--drafts` also shows posts in `_drafts/`.

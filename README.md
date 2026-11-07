# Recipes – cooking.jchellmuth.com

Small Jekyll site (Minima theme), moved from `jchellmuth.github.io/recipes/_posts/` in November 2026.
Each post keeps its old `permalink`, so a recipe formerly at `jchellmuth.com/pulled-pork/` is now at
`cooking.jchellmuth.com/pulled-pork/`. All pages are `noindex`.

Add a recipe: new file `_posts/YYYY-MM-DD-title.md` (copy the header of an existing one).

Local preview: `bundle install && bundle exec jekyll serve` → http://localhost:4000

Hosting: GitHub Pages (Settings → Pages → Deploy from branch `main`, folder `/`), custom domain `cooking.jchellmuth.com`
(DNS: CNAME `cooking` → `jchellmuth.github.io`).

---
layout: post
title: Running Jekyll Locally
---

If I want to use Jekyll's built-in development server which will allow me to preview what the generated site will look like in my browser locally, I can run:

```
$ jekyll serve
# => A development server will run at http://localhost:4000/
# Auto-regeneration: enabled. Use `--no-watch` to disable.
```

As of version 2.4, the `serve` comamnd will watch for changes automatically. To disable this, you can use `jekyll serve --no-watch`, which preserves the old behavior.

Run `jekyll serve --options` for options, and this goes for any command.

In the blog post [here](https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/), I won't need to run `jekyll serve --watch` anymore. He should update that post.

My local dev server is located [here](http://127.0.0.1:4000/). 

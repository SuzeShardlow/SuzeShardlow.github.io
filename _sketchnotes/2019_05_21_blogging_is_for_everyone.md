---
layout: coding_project
name: suze.dev
sub_headline: A personal portfolio site built using Jekyll and GitHub Pages.
github: SuzeShardlow.github.io
live_app:
image: /images/coding_projects/personal_website/suze_dev_on_macbook.jpg
comments: true
---

I have had my own website, on and off, since the mid-1990s.  I coded all of them by hand and, on most of them, I had a blog or some kind of journal.

When I started building full-stack web applications, I was between websites so I published a one-pager using [GitHub Pages](https://pages.github.com/) to display my work.  As my tech career developed, I needed to be able to feature other things alongside my coding, like my [public speaking](/public_speaking).  I also wanted to start writing again.

Because I was going to be adding blog functionality, I needed a new look and feel.  I also needed some way of being able to handle lots of groups of pages which were all based on the same layouts.

After doing a bit of research, I decided to use a static site generator.  This would enable me to use [DRY principles](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself), saving me having to copy the same markup across every HTML page on the site.  [Jekyll](https://jekyllrb.com/) seemed to be the obvious choice, because it powers GitHub Pages, meaning I could build on my existing repo.

Jekyll uses [Liquid](https://shopify.github.io/liquid/) for templating, allowing me to create reusable layouts.  I was already accustomed to doing this, having used [EJS](https://ejs.co/) a few times in my previous coding projects, so Liquid was quite easy to pick up.

I now have a website which showcases all my work and is a breeze to scale up.  I create all my content using Markdown.  Everything sits on GitHub, which means I can write and publish a blog post on the fly (for example on a train journey), using my phone.

More recently, I have set up a Jekyll/GitHub Pages site from scratch for a friend.

I also teach a [Jekyll with GitHub Pages workshop](/talks).  I ran the first one of these in San Diego, California.  After creating their websites from scratch in my 90-minute workshop, three people had their blogs up and running with their own articles within 24 hours.  A couple of weeks later, one of them was promoted to a cyber security role she had been aiming for after the hiring manager read her blog.

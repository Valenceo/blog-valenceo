---
layout: post
title: Stop wasting time fussing with your mediocre blogging software
---

### Set up and host a static site (like this one) with Github Pages
#### For free!

So, you know `git` and are comfortable over on [github.com](https://github.com)? You say you have your own domain and something to say? Then, suffer no longer!

1. Choose a [Jekyll](http://jekyllrb.com) theme, such as [Poole](http://github.com/poole) or even consider straight-up copying [mine]({{ site.github.repo }}). You'll replace the lame content later.
2. If you've chosen wisely, fork your theme into a new repo on github. Name and describe it appropriately, to find it later and avoid misunderstandings.
3. Modify any personalized parts of `_config.yml`, the `\_posts` directory, and nuke `CNAME` (if it exists).
4. A few changes to settings are necessary: (go to the Settings gear)
  * Down in GitHub Pages:
    1. Source -> Master Branch -> Save
    2. Custom Domain -> (enter yours) -> Save
5. With your DNS registrar, enter a CNAME record for your custom domain entry to (your-github-username).github.io
6. When you `git pull` in your local repo, you'll see a new file, `CNAME` appear.

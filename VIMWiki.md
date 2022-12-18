# VimWiki

this is the vim plugin to generate a personal wiki, and i'm using
to generate my tech wiki.


to make the automation i'm using git [[hooks]] to build the html before push.

command to be added on git hooks:

```sh
nvim ./README.md +VimwikiAll2HTML +q
```

to publish the the webpages i'm using [[GitHub-Pages]].

---
title: 'Setting up your Node.js app on a VPS: The big picture concepts'
date: 2016-01-09 22:15:28
tags: vps, node, hosting
---

This is a host.

The plight of the junior-ish front-end dev. One thing I find difficult about spending most of my time on the front-end is that when I need to switch gears to do a side project -- say flexbox in 5 (which I did awhile ago), even though I know it's going to be a front-end heavy app, I'm going to have to go through a lot of server config to get there. It's an interesting dillemma because you can be pretty damn competent on the front-end. True story, after working on a small for-fun project locally for several weeks, I ended up paying a freelance sysadmin from Pakistan to configure my VPS, DNS, and Node.app for me, so I could take it from there. I tend to be a do-it-yourself type with almost everything, but the terror (that is the word for it) I felt sudoing around my vps praying I didn't blow something up was too much to bear. For some reason, I started afresh and figured out how to get myself up to speed, and know enough to not be afraid of breaking shit. I think the most important thing was understanding exactly how everything worked.

So this post is going to be a 'big picture' post. That means this isn't a tutorial. It's tutorial prep. It may help alleviate some of the fear of pasting in one wrong character into the terminal, or asking yourself 'how important is it that use the library this tutorial recommends'.

I'm going give you the big picture, say a thing or two about common libraries, and refer you to resources that will help you better than I can.

Metaphor. You are at a restaurant.

## The players

There are a lot of things to keep in mind. Lots of concepts to piece together. The ones we're going to cover here are, specifically how these all fit together:
- VPS
- Hosting
- Web Servers (like Apache or Nginx)
- DNS and TCP/IP
- Node Js Apps
- Process Managers

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)

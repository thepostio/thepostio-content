---
title: What is The Post?
date: 2020-09-22
excerpt: A free blogging plateform? An open-source project? Both?
cover: martin-sepion-wapz7nr-jEc-unsplash.jpg
---
*A free blogging plateform? An open-source project? Both?*

# It's all of that!
First, it's a **blogging plateform**. A place where you can publish your own articles for **free**  and where you keep full ownership and access to your content. This notion of **ownership** is fundamental and is technically achieved by using *GitHub* under the hood. If your article in on your *GitHub* repo (following a certain structure), then it's going to show up here. If you remove it from your repo, then it's no longer going to show up. This is a *one-to-one mapping*.   

You can read more about how to setup everything and publish on **The Post** in [this article](https://thepost.io/thepostio/getting-started).

# Why does ownership matter?
Have you ever created content on a website that suddenly disapeared? I hope not, but it happned to me. Not long ago, I was still using Tictail (a website comparable to Etsy or Gumroad) to sell posters I was designing on my spare time. Later, they got acquired by Shopify, then shutdown because that was the new owner's plan since the begining. I lost my data, my customers and the ability to sell on on Tictail.   

The same may happen to a blogging plateform. Recently, Medium added a [metered paywall](https://help.medium.com/hc/en-us/articles/360017581433-About-the-metered-paywall) and now readers have to pay to access some content. Not all is bad in this story. Apparently,some of the most popular writers can get some money out of publishing, but honnestly, having a subscription for everything is starting to sum-up at the end of the month. This is definitelly not the phylosophy behind The Post. 

On the other side of the spectrum, you have [Ghost](https://ghost.org/pricing/), where authors have to pay at least $29 to put content out there. There are many great features and I personnaly think Ghost is a great project, but if you are paying such money for blogging, it basically means it's your job (as an independant or as part of a larger organization) and not a hobby . 

## Are there other ways to own our content?
Yes, fortunatelly! You can still deploy a Ghost or Wordpress instance yourself but it takes some knowledge and you need to have/rent your own server, deal with its configuration, most likely buy a domain, etc.

Another option is to use GitHub Pages to host your static blog. It's still one of my favorite solution in terms content ownership and ease of use — as a software engineer.  
Whether you are using [Jekyll](https://jekyllrb.com/), [Hugo](https://gohugo.io/), [11ty](https://www.11ty.dev/) or a more custom project with [Gatsby](https://www.gatsbyjs.com/blog/) under the hood, it still takes some rather advanced knowledge to build your static website properly, especially that if you have such a blog, you will want to tweak it, because you can, and then, hours are quickly spent!

# What does *The Post* proposes then?
The Post suggests that you just:
- fork [a repo](https://github.com/thepostio/thepostio-content)
- add your own article files there (Markdown with Yaml front matter)
- hardly any config
- **no** build
- **no** blog engine to install or run
- just `git commit` and `git push`
- then it shows up here!
- you get a friendly URL to share
- you get SEO support
- you get Facebook and Twitter metadata support to generate nice *cards*
- **for free**

# What's the catch?
Actually I don't see any! **The Post** is a project made on my spare time and it hardly costs any money to run. It was designed to scale pretty well, we'll see on the long run, but if it ever shuts down, you won't lose your data!

[— @jonathanlurie](https://twitter.com/jonathanlurie)
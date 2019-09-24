---
- id: blog-post_guess-who-is-back
- author: BruNex
- layout: post
- title: recur blogging
- date: 15/12/2012 18:54
- comments: false
## tags
  - personal
  - clojure
  - blogging
  - blog-engine
---

# Back bloggin (or not)

Hi, Long time no see :)

TL;DR It's 2017, I  living in London, I still work as a software developer with Clojure and ClojureScript, I'm back at brunex.name with a `new` engine and this post is in english.

I've been away from brunex.name,  in the meanwhile I've re-written all the blog engine and stuff.

The big change and why it took so long (beside that I'm a pro procrastinator), is the fact that I changed stack (again), yes I'm now a `clojure/clojurescript` developer, so I took the opportunity to re-write the blog as a way of learning.

With this re-write I wanted to create something meaningful that lasts the `test of time`, that I could be changing and improving `forever` without ever need to worry too much  (very modest requirements).

Inspired by all the `static blog generators`  I ended up creating my own twist,  decoupled the content that makes a blog from everything else, so the content can live by is own.
I used github as my immutable `database` , it is markdown all the way with some metadata (still experimenting with the best way to do this), and because it is a git repo you can see the log as a the full history as a real `blog meaning` google this!!!

My hope here is to solve the `content` problem  `forever` unless someone is predicting github death in a near future, I never need to worry about this anymore it will be online and accessible with all the history.

Half of the puzzle is solved!

The other half  `the blog engine` is plugged to the content repository via a git hook, this part will take care of everything else `http/server` `html/css` `Clojure/ClojureScript` it will be the technical part of my blog, and here I expect to be experimenting `alot`.

Also released it open-source (meaning that you can checkit forkit hackit ) here.

A big cheers up also to  Bruno for the new design (It looks awesome).

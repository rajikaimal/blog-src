---
title: inq CLI - learn in public
date: "2020-04-19T22:24:03.284Z"
description: ""
---

Recently I stumbled upon [swyx's learn in public](https://www.swyx.io/writing/learn-in-public/) blog post. The idea is to keep track of what we're learning daily with some kind of a medium. It can be notes, blog posts, youtube streams or twitch. Any medium which can keep track of the progress. To be fair, we tend to forget certain things we learn quite easily with time. Going through the learning process takes some time and it's good if we have some pointers to remind what we learned before, thus acting as a tracking index. As swyx mentions in his post, most devs are learning in private. There's nothing wrong with that. But learning in public can have many advantages. For an example, if we're sharing our experience the experts can join in the converstion to provide useful comments and their thoughts on certain matters.

I often thought about ideas presented by #LearnInPublic movement before finding out that people are actually doing that as a practise. As a result of my ideas on how to share my learnings daily, I wanted to create an easy to use tool. I'm a fan of CLIs and I often choose CLIs over GUIs. Eventually I decided to create a very simple note taking CLI tool. At the same time I wanted to learn go lang. So thought of writing the CLI with go. The idea is to keep track of the notes using git and pushing the notes to a git repository. I'm a huge VIM fan and I configured the tool to use VIM by default. (Current option includes VIM only)

That's how [inq](https://github.com/rajikaimal/inq) was born. The idea is very simple and probably some one must've already created a similar tool. But I wanted to put my go lang skills into practice and do certain features according my preferences. A command line based note taker, which defaults to VIM when taking down notes with the ability to version control notes. Plus you can take notes based on the date and topic. The current version was tested only on MacOs. (Should work on linux based systems hopefully) Here's a quick demo of how you can inq to #LearnInPublic. Cheers! 🤞

Check out the repository - https://github.com/rajikaimal/inq

<iframe width="560" height="315" src="https://www.youtube.com/embed/ft3TSMckUJM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---
title: Why Learning VIM is Worth It 
date: "2020-04-06T22:12:03.284Z"
description: ""
---

The first text editor I have used must be Notepad/Notepad++. For proper coding lessons I had some experience with VI, which at the time, I had no idea what was happening. I immediately decided to use Sublime Text, which was the hottest text editor at the time. Sublime Text was great in terms of the overall experience. Very decent startup time, awesome plugin eco system, and loads of themes made it great for me. I used Sublime as the primary editor for every project. (PHP, Node.js, Angular.js)

Time went by and, GitHub introduced electron and along with that Atom text editor. Atom was bundled with features that provided great developer experience. Soon everyone started shifting to Atom. Since it's based on Electron, JavaScript developers started getting onboard with plugin development and soon this created a massive plugin ecosystem.

Eventually we started experiencing an issue which was inevitable with the technology it was made with compared to native implementations. The startup time for massive projects was not good at all. And it had performance issues with certain features. Main cultript was Electron. Compared to Atom, Sublime was ..., very sublime! for me at least ;). Sublime experience was great compared to Atom. I guess I went back to sublime for a while, until Microsoft released the next gen text editor.

VSCode is the perfect combination of Sublime and Atom. Even though VSCode has better performance compared to Atom, it's based on Electron as well. I'm not quite sure how this implementation has better performance. But VSCode is great in terms of the performance and the feature set.

I continued using VSCode as it had major support from the community around it. As the time went by I wanted give VIM a shot. I saw devs using the cool navigation and quick editing features it had. Particularly videos from [thoughtbot](https://youtube.com/watch?v=wlR5gYd6um0) displayed the great features. [George Hotz's](https://www.youtube.com/channel/UCwgKmJM4ZJQRJ-U5NjvR2dg) streams are always a great treat for any dev. And his primary editor is VIM. Seeing how efficient he is with VIM, I wanted to give it a shot for real work. Before this I've been switching between Code and VIM regularly.

It was not a complete switch to VIM at first. And I believe for anybody who has been using a regular editor for years, it's really hard to switch to VIM and adopt entirely and use it for the day job. It took me around ~2 years to make this transition. It was very very  slow, due to the fact that I didn't switch back to VIM for months. But eventually I started getting the hang of the navigation moves and the command combinations. It should be well highlighted that you should forget everything that you know about text editor/IDEs to use VIM as it has a separate modes (normal, insert, visual, record) and the VIM language itself.

While familiarizing with the movements, I slowly started editing my [vimrc](https://github.com/rajikaimal/vimrc), which the configuration file for VIM (I used [Vundle](https://github.com/VundleVim/Vundle.vim) as my package manager). I use VIM for JavaScript, Go and Rust development. For each language you can find plugins. [VimAwesome](https://vimawesome.com) is a search for VIM plugins.

Transition from VSCode to VIM was not smooth at all. I still use VSCode in my day job as  my primary text editor with the VIM plugin (Using VIM on Windows was a massive set back, that's why I still use VSCode on Windows). And the VIM configuration is far from perfect and I guess you never end up with a VIM config which is satisfactory ;) 

The major reason why people switch from conventional editors to VIM is productivity. VIM language and it's combinations
makes is really easy to do text editing without touching the mouse. It was really worth investing the time to learn VIM as it increased the editing productivity when compared to the conventional editors. 

If you're on the border line of thinking of a transition, a complete transition won't do it. You have to make a very slow transition. It might differ for different individuals and the amount of time you have to invest in such a huge transition, specially if you have a day job which requries using other editors/IDEs.

Here's me struggling with VIM and Go, enjoy!

<iframe width="560" height="315" src="https://www.youtube.com/embed/V3Vp0xTOXr4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

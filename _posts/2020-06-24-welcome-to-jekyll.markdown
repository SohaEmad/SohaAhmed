---
layout: post
title:  "Create your Blog Using Jekyll"
date:   2020-06-25 22:20:45 +0100
categories: jekyll update
---

![write](/images/write.jpeg)

jekyll looks like a cool tool specially with all the plugines you could find in different editors such as atom and VSCode.
the idea of start your own blog is the idea that visit each software developper over and over during his software devlopping journy, some got the gift of talk and explain what the have done and other just can't but one shared element none got the time. I am writing this post 2 am after long day of work just to prove to my self I can take this step. 

the basic idea is recently with this pandimic thing going own the appreciation of time and help other grow for many of us so why not to share what we know and make another software developper easier even if with the smallest peice of information. 


 my trial to start my own blog:

 why Jekyll? 
 well was a recommendation from a friend and then when I started to explorer there was plenty of other tools that could be more efficient and I am planning to try one or two just to see if I can get more option but until now Jekyll seems like a good option with a good community support it but still need more good documentation specially for people who are prand new for Ruby 


 my journy 

 I started with Atom with https://atom.io/packages/jekyll plugin which kept failing to build my site, I call back I solved this problem on my win machine but then when I wanted to continue the work on my Mac the problem poped up again so no. 

 I moved to VScode which have the cool plugin jekyll Run https://marketplace.visualstudio.com/items?itemName=Dedsec727.jekyll-run do the job no problems but still I am into CLI so if you like CLI follow me. 




if you already got Ruby setuped on your device  jumb to the following step if you don't have it 

use the instruction in the folllowing link should be striaght forward and easy https://jekyllrb.com/docs/installation/macos/


 setup jekyll can be found on the site 
 https://jekyllrb.com/

 ```bash  gem install bundler jekyll
  jekyll new my-awesome-site
  cd my-awesome-site
  bundle exec jekyll serve 
 #=> Now browse to http://localhost:4000 
 ```
let's explain what just happen 

first line is the setup and then 
```bash
 jekyll new my-awesome-site
 ``` 
 is to create your first jekyll project so replace my-awesome-site with any name of your choice 

yah you got your project if you want use jekyll run plugin to see your intial workspace jsut click green run button in vs code or use 
```bash 
cd you-project-name 
bundle exec jekyll serve 
```
jekyll include sites and posts 

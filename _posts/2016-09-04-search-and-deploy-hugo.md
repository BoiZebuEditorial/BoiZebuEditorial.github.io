--- 
layout: post
title: Surge & Deploy: Googling Hugo
author: Colin Brayton
---

The time has come, the Walrus said, to drop my attempts to make [Hugo](http://gohugo.io/) work for me on GitHub pages. I have googled every proposed solution there is to google, but the workflow suggested always requires more `git` savvy than I have as yet. 

Dropping it for the time being, at least. 

I need to spend more time actually **writing** in one of all these writing spaces I keep creating. Pick one and rebuild a readership.

Imagine William S. Burroughs as a typewriter repairman too busy with his day job to write [The Naked Lunch](https://en.wikipedia.org/wiki/Naked_Lunch). Not that I compare myself with Bill (Lee the Agent) Lee, but the fact is I am much more of a writer of words, cheap words, than a coder. A living must be made.

Take the case of my [Paraguayan Progress Reports](https://github.com/gringolalia/gringolalia) -- a neat little captain's log with the aptly named [ghostwriter](http://themes.gohugo.io/ghostwriter/) theme -- to replace the [HubPress blog](http://bretonio.github.io) I began using for the blogging of my technical and Web design endeavors.

[HubPress is still a little funky](https://bretonio.github.io/2016/08/31/The-App-Ate-My-Homework.html).

But googling and googling and git command sequence cut and pasting up the wazoo and I still cannot get my Hugo site to live on GitHub project pages -- which should be easier than org and personal pages, but I can accomplish neither.

### A Sudden Urge To Surge 

[Netlify](http://goldsmith-squares-77682.netlify.com/) and [Surge](http://surge.sh) actually do serve this site up live, but without rendering the theme. Just raw HTML. [Urgh!](https://en.wikipedia.org/wiki/Urgh!_A_Music_War) 

But soft! What stylesheet is rendered on yon URL? It is my [Paraguayan Progress Reports](https://gringolalia.surge.sh/) and [ghostwriter](http://themes.gohugo.io/ghostwriter/) is its theme!  

![Merge to Surge](https://raw.githubusercontent.com/bretonio/bretonio.github.io/master/images/surgetogringolalia.png)


[Callooh! Callay!](http://www.jabberwocky.com/carroll/jabber/jabberwocky.html)

Having finally gotten [Node.js](https://wiki.archlinux.org/index.php/Node.js_) and `NPM` working in Arch Linux, more or less -- I still cannot get [middleman](https://middlemanapp.com/) to work after installing it -- all I needed to do was `npm install --global surge` and `surge` in my project directory. 

Designate `public` as the build directory, change the randomly generated domain name -- `somatic-cheesebread` or something -- to `gringolalia` and then navigate to `https://gringolalia.surge.sh`. 

What puzzles me is why my [PPR](https://gringolalia.surge.sh/2016/09/03/search-and-deploy/) will not deploy properly to my local Apache server. 

As in `cp -r public /srv/http/hugo` and then fiddle with `chown` and `chmod`. 

### Wherever Hugo, I Go

So that settles that. 

It ain't pretty but it loads up in my browser and I can e-mail the URL to you and that is something. 

There is still hope that the [very simple advice](http://mariarivas.me/tutorial/hugo/) given by Maria Rivas will bear fruit. 

Meanwhile I can at least continue to develop and present Hugo projects fairly easily as I start moving into the area of [theme adaptations and authoring](https://gohugo.io/tutorials/creating-a-new-theme/).  

This is something I would like to get reasonably good at over the next year.

In my spare time from writing my money laundering novel set in Paraguay and Uruguay, of course. Inspired by [Narcos](http://www.vox.com/2016/9/4/12774246/narcos-review-season-2-netflix), whose second season we just took in during two marathon Netflix sessions.

I am after all something of a connoisseur of [typography](https://en.wikipedia.org/wiki/Typography) and layout. I studied medieval paleography and incunabula for my doctorate. 

![A Gutenberg-inspired font](images/gutenbergo.png)

I was reading [Tufte](https://www.edwardtufte.com/tufte/) when the youth of today were still on Doctor Suess. I used to copyedit [Jakob Nielsen](https://www.nngroup.com)'s usability column in the late, lamented *Internet World*. The [Penton](http://www.penton.com/) publication, not the [Swedish mag](http://internetworld.idg.se/) of the same title.

Yes, all of this is a little off my established career path, but then there is little English-language editorial work in Sambodia. Unlike New York where I always found work. 

(Get back. Get back. Get back to where you once belonged.)

And so here I am, planning to create a portfolio of sites under this root server named after the *bairros* of São Paulo. Itaim-Bibi. Paraísopolis. Vila-Madda. Anhangambaú. Brooklin Novo. Avenida Berrini. Marginal Tietê. Hugo will not entirely do go.

But the surge solution will serve for now.

---
layout: post
title: Sweating the Específicos
tags: ["CSS", "Ruby", "Jekyll", "WordPress", "design", "responsive", "Urubu", "work", "film", "television", "Netflix", "typography", "Brazil", "Material-Docs"]
---

![Ruby Thursday](https://raw.githubusercontent.com/bretonio/bretonio.github.io/master/images/resolvingrubyscaled.png)

> O gênio, o crime e a loucura, provêm, por igual, de uma anormalidade; representam, de diferentes maneiras, uma inadaptabilidade ao meio.
> 
> -- <cite>**Fernando de Pessoa**</cite>

Above: The moment when I resolved the endless nightmare that was my Ruby environment. Or partially resolved it. There is a certain amount of rigamarole still required when installing gems. I wrote about it [in Portuguese](http://bretonio.gitlab.io/gringolalia/2016/10/06/ruby-terca-feira/)	. 

And **an update**: I was able to build the stylesheet changes I wanted, discussed below, at last.

The thing is that I cannot update this writing space without issuing `jekyll build` before pushing. Or rather `bundle  exec jekyll build`. It is a [Rubygem](https://rubygems.org/) and as such is heir to all the ills a gem is heir to.

Very complex posting workflow is not something a WordPress Ghost or Typepad user normally has to worry about, for example.

First thought best thought. That is what Allen Ginsberg used to teach us. 

He clearly never had to sort through all the command line operations required to push his content out into the world. 

But now see here, my stated aim after deciding to abandon the [Sousaphone](https://tupiwire.wordpress.com/) after an entire decade has been to reserve this space for less frequent more finished writing that is more about life in general -- my life in Sambodia with Neuza and the too many crazy dogs -- but lately life in general has degenerated once again into a never-ending series of nettlesome specifics inevitably connected with the infernal machine.

Creating this post in Jekyll, for example, all I can think of is how much the treatment of the `<blockquote></blockquote>` element in the stylesheets of this book of hours bother me.

It seems to me the stylesheet that comes with the theme treats the blockquote more as a version of what we in the publishing business call a "pull quote" -- a quote pulled from the text and featured as a sort of teaser or thematic summary. 

The editorials in the reliably reactionary [Estado de S. Paulo](http://www.estadao.com.br/) follow this pattern reliably: feature a conclusion with a certain impact on its own in order to generate interest in following the often specious argument that led up to it. 

In the case of this post, on the other hand, the existing blockquote style used for the words of Fernando Pessoa is actually quite fitting for what that quotation really is: an [epigraph](http://www.merriam-webster.com/dictionary/epigraph). From the Greek: Something written above or at the beginning of some other writing. 

A blockquote, on the other hand, is a subordinated element: you set it apart as separate from your own text to which you are subordinating it. It is a hypograph, I guess you might say.

The style I like -- and there are hundreds of fancy CSS solutions out there -- is simply a double-indented paragraph in the same font, or perhaps a smidge smaller and lighter, with a nice horizontal border on the left. A [rubricated](https://en.wikipedia.org/wiki/Rubrication) border, perhaps.

I will now spend a good 30 minutes to an hour tweaking the stylesheet `uno.css` to try and create this effect. Doubtless I will break something.

There, all done. Got nowhere after commenting out the '<blockquote>' entry and pasting in another. 

I had forgotten that comments in CSS use the `/* <comment> */` convention. 

At first Jekyll will not build the change. It just outputs the old CSS into the `_site` directory.

I had no difficulty editing styles for the tags and other elements. What gives? I think it was that I used `jekyll build` instead of `bundle exec jekyll build`. Who knows? 

I could now introduce a special tag `blockquote class = "epigraph" but I would not be able to invoke it in Markdown.`

But let us leave that for another time. 

![](https://raw.githubusercontent.com/bretonio/bretonio.github.io/master/images/urubualulascaled.png)

## Paraguayan Progress

Progress! Paraguayan Progress! 

After ruling out [Jekyll Docs](), [Material Docs for Hugo]() and [Mkdocs]() I finally settled on a platform called [Urubu]() -- Brazilian for vulture -- for a project called *Admiráveis Engenhos Novos*. 

The Brave New Engines of the Internet. 

> In times of war, urubu is chicken.

In this project briefly document and review [static](https://www.staticgen.com/) Web site [generators](https://staticsitegenerators.net/) and [similar contraptions](http://yeoman.io/) that facilitate the work of Web developers. 

I do it in Portuguese, there is the selling point.

This is a second try at what I originally called [Projeto Samboja](http://project-sambodia.surge.sh/). 

You have no idea how much time I wasted trying to remove <previous> and <next> navigation from the top navbar before learning from the Mkdocs developer that there was no way to do so but that the next version would provide a way. 

![](https://raw.githubusercontent.com/bretonio/bretonio.github.io/master/images/admiraveisscaled.png)  

The Urubu design, like Mkdocs, is as you can see responsive, which means that on a small screen or reduced browser window the navbar dropdown collapses into the famous hamburger icon. You can read me on your phone! I will have to remember to write shorter sentences and paragraphs.

Mkdocs has this feature as well and probably would have served the purpose in a pinch, but I wanted more space on the top navbar for all my categories: Engenhos-Generators, Andaimes-Frameworks, Clichês-Boilerplates and Ferramentas-Tools as well as a Sobre-About menu. And I wanted to remove <previous><next> navigation. My reference site is strictly random access.

## With The Cross of Catharism Going on Before

And what by the way I have been asked is that logotype of yours? 

![](https://raw.githubusercontent.com/bretonio/bretonio.github.io/master/images/200px-Cathar_cross.svg.png).

A recondite little joke. 

This is the symbol of the [Catahar movement](https://en.wikipedia.org/wiki/Catharism), subject of the 20-year [Albigensian Crusade](https://en.wikipedia.org/wiki/Albigensian_Crusade). 

They were early 13th-Century [Cartesian dualists](https://en.wikipedia.org/wiki/Dualism_(philosophy_of_mind)) before their time and an expression of cultural transference from East to West.

> The idea of two Gods or principles, one being good and the other evil, was central to Cathar beliefs. The good God was the God of the New Testament and the creator of the spiritual realm, contrasted with the evil Old Testament God—the creator of the physical world whom many Cathars, and particularly their persecutors, identified as Satan. All visible matter, including the human body, was created by this evil god; matter was therefore tainted with sin.

A [friend of mine](http://www.luizfernandofontesteixeira.com.br/) is a connoiseur of heresies and the Cathars came most readily to mind when the subject came up for conversation.

While I remain grateful to C.S. Peirce and his student Umberto Eco for [liberating me from the clutches of Cartesianism for good and all](http://www.peirce.org/writings/p27.html), there is an admittedly revolutionary potential in this way of thinking. Reducing oneself to [the body without organs](https://en.wikipedia.org/wiki/Body_without_organs) is a revolutionary act.

Life. Suffering. Cause of suffering: desire.

## The Return of Netflix and Cooking With Gas

![](https://raw.githubusercontent.com/bretonio/bretonio.github.io/master/images/bootabsolutebeginscaled.png)

First it was [spies](https://en.wikipedia.org/wiki/The_Americans_(2013_TV_series)). Then it was [terrorists](https://en.wikipedia.org/wiki/Homeland_(TV_series)). Somewhere in between was [Escobar](https://en.wikipedia.org/wiki/Narcos) with Wagner Moura and his peculiar accent. 

We spend our evenings now hooking up the laptop to the big screen and tuning into Neflix which, however, recently stopped accepting our Itaú bank card to pay for credits. 

So have have to schlep over to the Pão de Açucar supermarket to buy the cards. Which is a pain. 

To tide us over in recent days: An excellent copy of the complete *Hard Day's Night" and the [sequel](https://en.wikipedia.org/wiki/Brancaleone_at_the_Crusades) to [the Incredible Army of Brancaleone](https://en.wikipedia.org/wiki/L%27armata_Brancaleone) from 1966 and 1970 respectively. 

The youth of today. All you have to do is mention something culture from the dark ages of your own youth and they already googled it up and are digging it. Alex for example. Remarkable expert on the old Disney **Silly Symphonies**.	

We also finally managed to afford a *botijão* of cooking gas after being reduced to dining on microwaved ovos pochês a la ranchero. Our clients are very funky about how long it takes them to pay.

And yes, we have neither hot running water nor gas in a pipe. The shower heater is a dangerous-looking contraption with bare wires exposed but it has not killed us yet. The house dates back to the architectural experimentations of a Dutch sculptor who built it as a studio.

The electrical transformers on our street only explode whenever it rains.

The rainy season is upon us. 

AES Eletropaulo.

Third World infrastructure.

First World rates.

## I Am Curious, Yellow

Next I would like to build a nice and fairly original Web site out of [Nanoc](http://nanoc.ws/), or perhaps [Yellow](https://developers.datenstrom.se/), and incorporating say [an Ubuntu typographic style from Google Fonts](https://fonts.google.:4000com/?query=ubuntu&selection.family=Ubuntu) and [Bootswatch](https://www.bootstrapcdn.com/bootswatch/) elements.

[Yellow](https://github.com/datenstrom/yellow/search?utf8=%E2%9C%93&q=footer) is a flat file CMS that offers a simple static site generation script as follows,

```
php yellow.php build <folder>
```

But I have not gotten it to work yet. All the links in the plain HTML files refer back to the original folder where you ran the generator. 

But now, checking my e-mail I see that Mark explains,

> As a static site generator you need to configure the server settings, otherwise the website will not work properly. These server settings depend on where the website **will be** running. Here are three examples configurations ...

Will be. Important, that. And sure enough if I edit `system/conf/config.ini` and write

```
	ServerScheme: http
        ServerName: localhost
        ServerBase: /amarillo
```

I can then move to the root of the site to be converted and run the `build` command on the folder `amarillo`.

```
sudo cp -r amarillo /var/www/html/
```

and oba oba! My site tests out and is ready to deploy. 

Or almost. All its links are relative to its own root folder. The only thing wrong is that the <edit this page> link that is displayed is broken. That will have to be edited out of the original. Oh and so will the search function. These PHP files are editable in `system/themes/snippets`
	
I would also like to make a nice landing page for *Admiráveis Engenhos* with the jumbotron element. 

I would also like to finally learn [enough emacs to use its Markdown previewer](http://jblevins.org/projects/markdown-mode/).

[So little time so much to know](https://en.wikipedia.org/wiki/Jeremy_Hillary_Boob).

![](https://raw.githubusercontent.com/bretonio/bretonio.github.io/master/images/emacsmarkdown.png)

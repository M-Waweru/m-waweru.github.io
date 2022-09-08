---
layout: post
title: My story as a Gephi user and contributor
permalink: /story-gephi-user-contributor/
published: false
date_readable:               Sept 08, 2022
last_modified_at_readable:   Sept 08, 2022
---

*My journey as a Gephi user and contributor*

<div align="center">
   <img src="https://upload.wikimedia.org/wikipedia/commons/0/04/Gephi-logo.png" title="The Gephi logo" width="300px"/>
</div>  

# Quick background on Gephi

Two-line summary if you don't know Gephi. Born around 2007, [Gephi](https://gephi.org) is the leading software for the visualization and exploration of networks.
It is open source and free. It is used by analysts, professors, journalists, students. It useful to find patterns and connecting the dots in rich and unstructured datasets, for instance: finding communities, people with key roles in a crowd, identifying connections between items or products, etc.

<div align="center">
   <img src="https://user-images.githubusercontent.com/1244100/189077290-65d51016-df16-4b8c-a154-0cf64ee01eb9.png" title="A screenshot of Gephi" width="500px"/>
</div>                                                                                                                                  

**Gephi has been downloaded [millions of times](https://seinecle.github.io/gephi-tutorials/generated-html/history-en.html#_a_cumulative_downloads) since its creation**, and the original paper describing Gephi has been cited by close to **[10,000 academic publications from a huge variety of scientific fields](https://scholar.google.fr/citations?view_op=view_citation&hl=fr&user=fEDLILQAAAAJ&citation_for_view=fEDLILQAAAAJ:u5HHmVD_uO8C)**.

The Gephi Code retreat is a one-week event organized by the founding members of Gephi to accelerate the development of the software and help the community of Gephi enthusiasts meet and cohere. That is the second year such a retreat is organized, after a first edition in Copenhagen.


## Being a historian, discovering Gephi in 2010

Gephi is the reason I transitioned from being a historian of science to a social scientist using computational (data-intensive) approaches.
As a post-doc at the [KNAW](https://www.knaw.nl/en) in the Netherlands in 2008, Gephi had just appeared (there was also [GUESS](http://graphexploration.cond.org/) that I used as well).

I realized that to explore and find insights in networks of neuroeconomists (that was my interest at the time), scrolling through big tables in Excel was going to be difficult:

An author in column A, the co-author in column B.
How do you make sense of 10,000 of rows like that?

Relations between authors in column A and their co-authors in column B describe a network.
Networks can be analyzed in formal ways with a body of knowledge called "network analysis" or "social network analysis" (SNA). Researchers in SNA have developed methods to compute metrics on networks, or to generate different types of networks, with dedicated software like [UCINET](https://sites.google.com/site/ucinetsoftware/) or R packages like [igraph](https://igraph.org/).

My need was different though: I needed to "make sense" of the network, in a global and generalist sense. Things like:

- do we see clearly split sub-groups in the network or is it a compact hairball?
- are two famous neuroeconomists "neighbors" in the network or are they far apart?
- is the oldest research lab in the field of neuroeconomics at the periphery or at the center of the network?
- where are European neuroeconmists, relative to their American peers?
- are psychologists scattered in the network or grouped in one region?
- how are positioned the neuroeconomists who tend to publish on addiction? And those working on animal studies?
- etc...

I needed a way to ask all these questions and get a broad sense of whether they were relevant. Also, exploring the data would hopefully reveal other patterns of interest that I had not tought of. To do this, I did not need an analytical tool to test hypotheses, I needed a way to explore my data.

Being completely new to the field of social network analysis, my first impulse was to explore the network **visually**. In 2010, I found Gephi, which was already so much advanced compared to the classic viz solutions such as [Pajek](http://mrvar.fdv.uni-lj.si/pajek/) or UCINET's [NetDraw](https://sites.google.com/site/netdrawsoftware/download). By the way, it is pretty common for historians to have a similar epiphany with the visualization of networks, and Gephi is a pretty popular tool in the digital humanities.

(see two publications [1](https://www.nature.com/articles/nrn3354) [2](https://www.frontiersin.org/articles/10.3389/fnhum.2016.00336/full) of my research project on neuroeconomics that used Gephi and [VOSviewer](https://www.vosviewer.com/), another very good network viz tool).

## Gephi's killer features

The basic workflow in Gephi is super effective at delivering insights.
Each step is a simple one-click operation!

1. **get the big picture**: apply a layout to immediately get a sense of the size, patterns of relations, core / periphery structure... that characterize the network ([source](http://www.martingrandjean.ch/connected-world-air-traffic-network/)):

<div align="center">
   <img src="http://www.martingrandjean.ch/wp-content/uploads/2016/05/Airports-network.gif" title="airport network animation with Gephi by Martin Grandjean" width="300px"/>
</div>   


2. **detect communities** (in one-click): quickly see how a crowd divides in sub-groups, based on the pattern of connections between the members of the group

3. **find central nodes**: which member of the group has the most connections? Who is placed "in the middle of the network"?

4. **explore attributes**: Gephi can handle the attributes attached to the members of the network. Not just their name, but any textual or numerical attribute you have stored on them. Occupation, gender, city, year of birth... 

5. **zoom on sub-regions**: what if we filter out all the network except for one group of nodes and their relations: can we identify local communities within this subnetwork? Who are the central actors within this region?

==The killer feature of Gephi is that these 4 operations have an intuitive, **illustrated** expression in Gephi:==

1. The layout (with Force Atlas) deploys / unfolds progressively, showing how the connection micro-patterns progressively moulds the final, global result 
2. Visualize different communities by painting them in different colors
3. Visualize the importance of each node by resizing them according to their centrality
4. Visualize attributes by switching on the display of labels attached to the nodes, or by painting the nodes in colors representing categories ("blue nodes for professors, "red nodes for post-docs").
5. Explore subregions by hiding the parts of the network you want to ignore - just apply a filter in one click 

## From enthusiastic user to first steps as a contributor

In the course of using Gephi, I started asking a lot of questions on the [now defunct Gephi forum](https://forum-gephi.org/). The community of users is now the most active in a [private Facebook group](https://www.facebook.com/groups/gephi) with close to 10,000 members (join!), where I continue being active.

Even with the help I received on the forum ([Sébastien Heymann](https://www.linkedin.com/in/heymann) did a lot here!), I was frustrated by the absence of basic functions I needed. Like: paint a node in green if it has the text "green" stored in one of its attributes. How to get these functions I needed?

Gephi is a free and open source product, developed by a very small team of volunteers on their free time. That they could create Gephi and take the time to answer all my questions felt already huge. I had heard of "open source software" but the scale and impact of Gephi made me realize that there was nothing that justified for me to stay on the sidelines and complain - if I want something, I could at least make an effort and try to contribute?

The first thing I did was contribute to helping fellow users on the forum. I was an intensive user of Gephi, so there was plenty of cases when people were stuck on issues that could be solved by simply explaining where to click in Gephi and that sorts of things. It was relatively low effort but it felt already good to give back and also receive thank you messages from the users I helped (it should be noted that the Gephi community is really super nice btw - I can't remember that we ever encountered a troll on the forum or the FB group!)

## Starting developping Gephi plugins

To contribute to new functions for Gephi, that was a step beyond and that felt really out of reach.
[Almost since its inception](https://seinecle.github.io/gephi-tutorials/generated-html/history-en.html#_b_version_0_7_2010), Gephi came with a [system of plugins](https://gephi.org/plugins/#/) that anyone can develop. But as I am not a computer scientist, this sounded too hard. I had an experience in VBA (the programming language for Excel) as an real amateur, but Gephi is developed in Java and that felt like another league. Java even necessitates to install a software to use it.  I had tried to download and install it (it is called NetBeans, there are others too). Being a real newbie I felt utterly lost: what are the menus and windows in this software *even supposed to do*? I had no clue.

But using Gephi for my research projects, the question of developing features I needed was really nagging. if I just need, you know, a plugin to change the colors of my nodes - surely it can't be *that* hard to create?

[After some inquiries in 2010](https://forum-gephi.org/viewtopic.php?f=5&t=229&sid=e5005ceb2af5bf315d56e8a5cc303f12), in the end, in 2011, I jumped in this strange world of Java, [buying a book for complete beginners](https://www.amazon.fr/Java-Beginners-Guide-Herbert-Schildt-dp-1260463559/dp/1260463559/) and learning how the thing works.
By the way besides a book, everything is free: the software to code ([NetBeans](https://netbeans.apache.org)), and the Java language itself. Not costly to try!

I got hooked when I realized Java was a zillion time faster than Excel. With Excel, I was literally waiting for half an hour to apply operations on my rows, to end up freezing and crashing Excel. With Java that became a 10 seconds operation!

I used Java first to create custom gexf files (custom made networks!!) and finally [some plugins for Gephi](https://gephi.org/plugins/#/browse/search/levallois).

My coding style was horrendous. I remember showing my code Francesco Ficarola (I believe), the developer of a Java library that helps create gexf files. I think he said that his eyes burnt. But with time, things improve!

Another big help in learning how to program was Stackoverflow.
This is THE Q&A website for programming issues, and browsing back to the first question I asked on it, you see it really shows that I was [transitioning from Excel to Java](https://stackoverflow.com/revisions/7200090/1)!

## Using Gephi programmatically - the additional benefits

Knowing how to program came with exponential benefits, beyond Gephi, and right away. Java is a versatile language which enabled me to easily [analyze text](https://aclanthology.org/S13-2068/), create [web apps](https://nocodefunctions.com), [desktop apps](https://github.com/seinecle/Gaze), publish courses [in fancy formats](https://seinecle.github.io/mk99/), [grade large groups of students without going mad](https://github.com/emlyon/GradingPicsOnBrightspace), [teach a course on how to create mobile apps](https://seinecle.github.io/codapps/), [create silly personal projects](https://github.com/seinecle/lescalanquessontellesouvertes), and more.

I wrote [tutorials for Gephi](https://seinecle.github.io/gephi-tutorials/), and I continued using Gephi in most of my research projects to this day (on [collusion in European markets](https://onlinelibrary.wiley.com/doi/full/10.1111/jcms.12232), [dynamic inter-banking financial networks](https://www.risk.net/journal-of-network-theory-in-finance/2462066/dynamic-visualization-of-large-financial-networks), and new ways to identify [communities on Twitter](https://management-aims.com/index.php/mgmt/article/download/4245/10254?inline=1).



# If you'd like to see the Gephi week or what I'm doing

- Check the [Twitch stream of the Gephi week](https://www.twitch.tv/datalgo) - I'll try to say hi this afternoon (Paris time)
- Get fresh news from the [Gephi Twitter account](https://twitter.com/Gephi) and also from [Datalgo](https://twitter.com/nicolasbchb)
- Here are the [Gephi plugins I have developed over the years](https://gephi.org/plugins/#/browse/search/levallois)

I have written [tutorials for Gephi](https://seinecle.github.io/gephi-tutorials/).
I also build [nocode functions](https://nocodefunctions.com) 🔎 that can also serve the needs of the community of Gephi users. It is [fully open source](https://github.com/seinecle/nocodefunctions).
Try it and give some feedback, I would appreciate it!

* my email: [admin@clementlevallois.net](mailto:admin@clementlevallois.net) 📧
* or on Twitter: [@seinecle](https://twitter.com/seinecle) 📱
* you can also read [the other articles of this blog](https://nocodefunctions.com/blog) 👓, where I write about my journey as a social scientist and app developer.
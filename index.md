---
layout: default
title: 'Home'
---

<style>
    .l-box {
        padding: 2em;
        }
</style>

<div class="pure-g">
<div class="pure-u-1-2" >

<div class="vh">
<div class="l-box">
<!-- pure-img makes image scalable-->

<!-- <img class="pure-img" src="website_nw.png" size="300px"> -->

<iframe src="{{ "assets/network/network.html" | absolute_url }}" width="300px" height="300px" frameBorder="0" style=" border-width:0 ">
</iframe>



</div>
</div>

</div>

<div class="pure-u-1-2" >

<div class="vh">

<p>I study factors that promote and maintain biodiversity from a community, metacommunity and macroecological perspective. My research has mostly focused on running water ecosystems, but my interests are question focused, not system specific. I am currently a postdoctoral scholar at <a href="http://oregonstate.edu/">Oregon State University</a> in Corvallis, OR, USA. I'm based in the <a href="http://ib.oregonstate.edu/">Department of Integrative Biology</a>, and I'm on the editorial boards of <a href="http://onlinelibrary.wiley.com/journal/10.1111/(ISSN)1365-2427">Freshwater Biology</a> and <a href="https://peerj.com/">PeerJ</a>. You can read more about <a href="/about">me</a> (including contact details), my <a href="/research">research</a>, and my <a href="/publications">publications</a> on this website. Also find my <a href="/blog">blog here</a> and hear me talk about my recent research <a href="https://youtu.be/mqnuv6YZBSM" target="_blank"> here</a>.
</p>

</div>
</div>
</div>

<hr style="height: 1px; color:#d5d5d5; border:none; background-color:#d5d5d5;" />

## Latest news

<!-- TEMPLATE:  <span style="color:#999">DATE</span> » **TITLE**-->

<span style="color:#999">14 May 2018</span> » **Paper accepted in PeerJ.** Happy to have just had a paper accepted for publication in *PeerJ* looking at latitudinal variation in metacommunity structure in New Zealand stream invertebrates. More details soon. 

<span style="color:#999">12 May 2018</span> » **Off to NCEAS in Santa Barbara.** I'm heading to NCEAS (National Center for Ecological Analysis and Synthesis) in Santa Barbara for an exciting week of discussions on long-term metacommunity synthesis. 

<span style="color:#999">22 Apr 2018</span> » **Special issue on river network metacommunities.** I recently edited a special issue in Freshwater Biology with Florian Altermatt and Jani Heino on metacommunities in river networks. You can find the special issue [here](https://onlinelibrary.wiley.com/toc/13652427/63/1), our editorial [here](http://dx.doi.org/10.1111/fwb.13045), and our review of dispersal in river networks [here](http://dx.doi.org/10.1111/fwb.13037). You can find pdfs [here](publications). 

<span style="color:#999">21 Apr 2018</span> » **Redesign of site = more news.** I've just redesigned my site to enable easier dissemination of news, so expect a lot more updates from now on. Also, I'm moving any blog posts back here to keep it all centralised. 

<span style="color:#999">10 Apr 2018</span> » **New paper.** We just published a paper in [Science of the Total Environment](http://dx.doi.org/10.1016/j.scitotenv.2017.11.242) showing that preceding year climatic conditions outweigh long-term climatic trends on stream invertebrate communities in Europe. 

<span style="color:#999">10 Feb 2018</span> » **New paper on EBVs.** We've just published a paper on linking essential biodiversity variables (EBVs) and ecological integrity for the next generation of site-based long-term ecological monitoring at [Science of the Total Environment](http://dx.doi.org/10.1016/j.scitotenv.2017.08.111). I hope this thinking gets implemented in LTER. This is something I started back when I worked at Senckenberg in Germany so it's great to see it out! Thanks to co-leads, Peter and Stefan, as well as all co-authors. 

<span style="color:#999">24 Jan 2018</span> » **New paper in Nature Ecology and Evolution.** Very excited to have a new paper out in [Nature Ecology and Evolution](http://dx.doi.org/10.1038/s41559-017-0379-0) on ecological networks in uncertain futures. Find a short overview [here](blog/2018/01/24/New-Paper-In-NEE) and a full 'behind the paper' writeup [here](https://natureecoevocommunity.nature.com/users/70479-jonathan-tonkin/posts/22255-networks-degrade-when-river-flows-depart-from-natural). Thanks to my coauthors Dave, Dave, Julian and Lindsay! PDF [here](publications). 

<span style="color:#999">24 Jan 2018</span> » **New paper in Ecology Letters recommended on f1000.** We recently published a paper in [Ecology Letters](http://dx.doi.org/10.1111/ele.12866) where we develop a model to explore the countervailing effects of disturbance on population dynamics. In this paper, we derived a novel form of the logistic growth equation that permits time-varying carrying capacity and growth rate. Find the f1000 recommendation [here](https://f1000.com/prime/732394087). Thanks Laura, Dave and Patrick! PDF [here](publications). 

<span style="color:#999">23 Jun 2017</span> » **Joining Freshwater Biology Editorial Board.** I'm very excited to announce that I have recently joined the Editorial Board of [Freshwater Biology](http://onlinelibrary.wiley.com/journal/10.1111/(ISSN)1365-2427). I've always thought of Freshwater Biology as the flagship freshwater specific journal, so I'm super excited and honoured by the opportunity to be a part of the team there.

<span style="color:#999">12 Jun 2017</span> » **Featured on the SFS Making Waves podcast.** I was recently featured on the Society for Freshwater Science's [Making Waves](http://www.freshwater-science.org/Education-and-Outreach/Media/Podcast.cfm) podcast. This was a really great opportunity to share some recent research of ours, including our paper on seasonality and some of our recent population modeling work. You can find the podcast [here](https://youtu.be/mqnuv6YZBSM).

<span style="color:#999">26 Apr 2017</span> » **New paper in Ecology.** We have a new paper out in [Ecology](http://dx.doi.org/10.1002/ecy.1761). This deals with the role of seasonality and predictability in environmental fluctuations on temporal species diversity. We show that understanding the role of seasonality in regulating biodiversity is not complete without and understanding of its predictability. We developed a framework for examining these aspects by combining wavelets and information theory. Thanks to my excellent co-authors (Mike, Nuria, Blanca, and Dave) for making this a great experience. I will write a brief blog post on this soon. PDF [here](publications).

Older news [here](news).  


## Latest blogs

<ul class="posts">
<!-- the below show's the latest 3 posts and adds a bit of text (first 20 words) from post as well as the title-->
	  {% for post in site.posts limit:3 %}
	    <li><span style="color: #999;" >{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a> »
	    {{ post.content | strip_html | truncatewords:20}}
	    <a href="{{ post.url }}">Read more...</a></li>
	    <br>
	  {% endfor %}
	</ul>


## Featured papers

<div class="pure-g">
	
	<div class="pure-u-1-4">

<script type="text/javascript" src="https://d1bxh8uas1mnw7.cloudfront.net/assets/embed.js"></script><div class="altmetric-embed" data-badge-type="medium-donut" data-altmetric-id="29523449"></div>
<br>
	</div>
	
	<div class="pure-u-3-4">
			
<p>Tonkin, J. D., J. D. Olden, D. M. Merritt, L. V. Reynolds, and D. A. Lytle. 2017. Flow regime alteration degrades ecological networks in riparian ecosystems. <a href="http://dx.doi.org/10.1038/s41559-017-0379-0" target="_blank">Nature Ecology & Evolution</a> DOI:10.1038/s41559-017-0379-0.</p>
<br>
	</div>
<br>	
	
</div>

<div class="pure-g">
	
	<div class="pure-u-1-4">

<script type="text/javascript" src="https://d1bxh8uas1mnw7.cloudfront.net/assets/embed.js"></script><div class="altmetric-embed" data-badge-type="medium-donut" data-altmetric-id="16029019"></div>
<br>
	</div>
	
	<div class="pure-u-3-4">
			
<p>Tonkin, J. D., M. T. Bogan, N. Bonada, B. Rios-Touma, and D. A. Lytle. 2017. Seasonality and predictability shape temporal species diversity. <a href="http://dx.doi.org/10.1002/ecy.1761" target="_blank">Ecology</a> DOI:10.1002/ecy.1761. <a href="http://jdtonkin.github.io/publications/2017_Tonkin_etal_Ecology.pdf"><i class="fa fa-fw fa-file-pdf-o"></i></a></p>
<br>
	</div>
<br>	
	
</div>


## Special isue on river networks 

<style>
    .l-box {
        padding: 1.2em;
    }
</style>

<div class="pure-g">

<div class="pure-u-2-3" markdown="1">

I recently edited a special issue in Freshwater Biology with Florian Altermatt and Jani Heino on metacommunities in river networks. You can find the special issue [here](https://onlinelibrary.wiley.com/toc/13652427/63/1)

Tonkin, J. D., J. Heino, and F. Altermatt. 2018. Editorial: Metacommunities in river networks: the importance of network structure and connectivity on patterns and processes. <a href="http://dx.doi.org/10.1111/fwb.13045" target="_blank"> Freshwater Biology </a> 63:1-5. [<i class="fa fa-fw fa-file-pdf-o"></i>]({{ "/assets/pdfs/2018_Tonkin_etal_Freshwater_Biology_Editorial.pdf" | absolute_url }})

We compiled a series of papers with the aim of highlighting the importance of the river network on structuring biodiversity, particularly through metacommunity dynamics and associated dispersal processes. The issue covers a wide range of topics (from disease spread and nutrient uptake to trophic dynamics), approaches (from field and lab experiments to modelling and population genetics), taxonomic foci (from diatoms and protists to fish), and geographic locations (from the tropics to the subarctic). 

</div>



<div class="pure-u-1-3" markdown="1">

<div class="l-box">

<img class="pure-img" src="{{ "/assets/img/2018-FWB-SI.png" | absolute_url }}" >

</div>

</div>

</div>


<!--
<i class="fa fa-fw fa-envelope"></i><span style="color:#999"> jdtonkin [at] gmail.com</span>   
<i class="fa fa-fw fa-envelope-o"></i><span style="color:#999"> jonathan.tonkin [at] senckenberg.de</span>   
<i class="fa fa-fw fa-twitter"></i><span style="color:#999"> @jdtonkin</span>   
-->
<!--<a href="https://twitter.com/jdtonkin" class="twitter-follow-button" data-show-count="false">Follow @jdtonkin</a>
<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+'://platform.twitter.com/widgets.js';fjs.parentNode.insertBefore(js,fjs);}}(document, 'script', 'twitter-wjs');</script>
-->

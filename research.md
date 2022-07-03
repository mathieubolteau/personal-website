---
layout: page
title: Research
subtitle: Ph.D Student in Bioinformatics
---


# Overwiew 

Work in progress...


# Publications

<!-- <sup>[Journal Articles](#papers) · [Book Chapters](#chapters) · [Abstracts](#abstracts) · [Datasets](#datasets) · [Other Documents](#other)</sup>  

Here you can find a list of the papers I published, as well as some selected conference abstracts. The references are sorted, listed and formatted with [Jekyll Schollar](https://github.com/inukshuk/jekyll-scholar).   

I intend to keep an open access copy of my papers at [EarthArXiv.org](https://osf.io/preprints/eartharxiv/) and [ArXiv.org](https://arxiv.org/), which means that you can read them even without a subscription to the publisher, but be warned that most of these are [postprints](http://www.sherpa.ac.uk/romeoinfo.html) created from the "accepted manuscript" (that is, they have the exact same content of the final published version, except for the publisher's typesetting). For a final version, please refer to the publisher's website (which may be behind a paywall).  

And if you use reference managers (you should), you can get a file with all my publications: [BibTex](http://en.wikipedia.org/wiki/Bibtex) format: [here](../../downloads/CarlosGrohmann_papers.bib) (good for [JabRef](http://jabref.sourceforge.net/), [Zotero](http://www.zotero.org/) and a bazillion others) [RIS](http://en.wikipedia.org/wiki/RIS_\(file_format\)) format: [here](../../downloads/CarlosGrohmann_papers.ris) (good for [Mendeley](http://www.mendeley.com/) or [EndNote](http://endnote.com/)) (last update: 2021-07)  -->

<!-- &nbsp;   -->
<!-- &nbsp;   -->


<a name="papers"></a>
## Journal Articles
<!-- \* Denotes student co-author.
&dagger; Denotes post-doc co-author. -->

{% bibliography --query @article %}

&nbsp;  
&nbsp; 
<a name="chapters"></a>
## Book Chapters  

{% bibliography --query @inbook %}

&nbsp;  
&nbsp; 
<a name="chapters"></a>
## Proceedings Conference Papers
<!-- (This list changes constantly. Check the Bib/RIS file to see all abstracts. ) -->

{% bibliography --query @inproceedings %}

&nbsp;  
&nbsp; 

<a name="other"></a>
## Others

{% bibliography --query @phdthesis && @mastersthesis %}



---
layout: page
title: Research
---


# Overview 

<p style='text-align: justify;'>With a lifelong interest in computational biology, I have been focusing more particularly on **systems biology** since my master's degree. Now, I am interested in **solving combinatorial problems** using [Answer Set Programming](https://potassco.org/). I discovered this logic programming paradigm during my master's internship when I was trying to solve a reachability problem in a graph. Currently, I am using this paradigm to **model human preimplantation development**, the subject of my thesis, through the **inference of Boolean networks**.</p>



<!------------------ Social links buttons ------------------>


<ul class="list-inline text-center footer-links">

{%- if site.social-network-links.google-scholar -%}
  <li class="list-inline-item">
    <a href="https://scholar.google.com/{{ site.social-network-links.google-scholar }}" title="Google Scholar">
      <span class="fa-stack fa-lg" aria-hidden="true">
        <i class="fas fa-circle fa-stack-2x"></i>
        <i class="fa fa-graduation-cap fa-stack-1x fa-inverse"></i>
      </span>
      <span class="sr-only">Google Scholar</span>
    </a>
  </li>
{%- endif -%}

{%- if site.social-network-links.ORCID -%}
 <li class="list-inline-item">
   <a href="https://orcid.org/{{ site.social-network-links.ORCID }}" title="ORCID">
     <span class="fa-stack fa-lg" aria-hidden="true">
       <i class="fas fa-circle fa-stack-2x"></i>
       <i class="fab fa-orcid fa-stack-1x fa-inverse"></i>
     </span>
     <span class="sr-only">ORCID</span>
   </a>
 </li>
{%- endif -%}

{%- if site.social-network-links.researchgate -%}
  <li class="list-inline-item">
    <a href="https://www.researchgate.net/profile/{{ site.social-network-links.researchgate }}" title="ResearchGate">
      <span class="fa-stack fa-lg" aria-hidden="true">
        <i class="fas fa-circle fa-stack-2x"></i>
        <i class="fab fa-researchgate fa-stack-1x fa-inverse"></i>
      </span>
      <span class="sr-only">ResearchGate</span>
   </a>
  </li>
{%- endif -%}

</ul>

<!------------------ Publications ------------------>

# Publications

<!-- <sup>[Journal Articles](#papers) · [Book Chapters](#chapters) · [Abstracts](#abstracts) · [Datasets](#datasets) · [Other Documents](#other)</sup>  

Here you can find a list of the papers I published, as well as some selected conference abstracts. The references are sorted, listed and formatted with [Jekyll Schollar](https://github.com/inukshuk/jekyll-scholar).   

I intend to keep an open access copy of my papers at [EarthArXiv.org](https://osf.io/preprints/eartharxiv/) and [ArXiv.org](https://arxiv.org/), which means that you can read them even without a subscription to the publisher, but be warned that most of these are [postprints](http://www.sherpa.ac.uk/romeoinfo.html) created from the "accepted manuscript" (that is, they have the exact same content of the final published version, except for the publisher's typesetting). For a final version, please refer to the publisher's website (which may be behind a paywall).  

And if you use reference managers (you should), you can get a file with all my publications: [BibTex](http://en.wikipedia.org/wiki/Bibtex) format: [here](../../downloads/CarlosGrohmann_papers.bib) (good for [JabRef](http://jabref.sourceforge.net/), [Zotero](http://www.zotero.org/) and a bazillion others) [RIS](http://en.wikipedia.org/wiki/RIS_\(file_format\)) format: [here](../../downloads/CarlosGrohmann_papers.ris) (good for [Mendeley](http://www.mendeley.com/) or [EndNote](http://endnote.com/)) (last update: 2021-07)  -->

<!-- &nbsp;   -->
<!-- &nbsp;   -->


<a name="papers"></a>
<!-- ## Journal Articles -->
<!-- \* Denotes student co-author.
&dagger; Denotes post-doc co-author. -->

{% bibliography --query @article %}

<!-- &nbsp;  
&nbsp; 
<a name="chapters"></a>
## Book Chapters  

{% bibliography --query @inbook %}

&nbsp;  
&nbsp; 
<a name="chapters"></a>
## Proceedings Conference Papers
(This list changes constantly. Check the Bib/RIS file to see all abstracts. )

{% bibliography --query @inproceedings %}

&nbsp;  
&nbsp; 

<a name="other"></a>
## Others

{% bibliography --query @phdthesis && @mastersthesis %} -->



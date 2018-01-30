---
layout: index
title: Vinayakumar R
---

---

{% include cv.md %}

## <i class="fa fa-chevron-right"></i> Recent Blog Posts

<table class="table table-hover">
  {% for post in site.posts limit: 5 %}
    {% unless post.draft %}
    <tr>
      <td><a href="{{ post.url }}">{{ post.title }}</a></td>
      <td class="col-md-3" style="text-align: right;">{{ post.date | date: "%B %e, %Y" }}</td>
    </tr>
    {% endunless %}
  {% endfor %}
</table>
<h4><a href="/blog">View all</a></h4>

## <i class="fa fa-chevron-right"></i> Fun Side Projects
+ <a href="http://nlp.amrita.edu/Alg-Design/" target="_blank"> Alg-Design</a>: facilitates to learn Algorithmic thinking for beginners

+ <a href="http://nlp.amrita.edu/Building-Blocks/" target="_blank"> Building-Blocks</a>: Generating 3D design by snapping blocks

+ <a href="http://nlp.amrita.edu/CT-Blocks/" target="_blank"> CT-Blocks</a>: Learning Computational thinking by snapping blocks

+ <a href="http://nlp.amrita.edu/CT-Blocks/" target="_blank"> CT-Blocks Analyser</a>: Analysing CT-Blocks projects

+ <a href="http://github.com/vinayakumarr" target="_blank"> DB-Learn</a>: Studying Relational Algebra concepts by Snapping Blocks

+ <a href="http://nlp.amrita.edu/DB-Learn/" target="_blank"> Digital story telling using Scratch: Engaging children towards digital story telling</a>

---

Last updated on {% include last-updated.txt %}

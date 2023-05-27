# Welcome to Bioinfo Hub

Bioinformatics is an application-oriented domain of biology, which has truly impacted the way biologists do research. It involves the development of computational techniques to handle and analyze biological data, to provide meaningful insights and accelerated solutions to complex problems. It strengthens every omics category in biology including, genomics, transcriptomics, proteomics, metabolomics, phenomics and a lot more. With our labs shrunk to a laptop and with advancements in computational resources, sky is the limit to developing novel algorithms in this field. Although this blog will focus on topics from some very specific sub-domains of bioinformatics (based on the projects that I currently work on), it will expand with time and hopefully encompass all key topics in the field. Do follow this page to explore with me!

# Blog posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

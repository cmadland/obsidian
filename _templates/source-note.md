---
DOI: {{DOI}}
Date: {{date | format ("YYYY")}}
Rating: 0/5
Title: "{{title}}"
ShortSummary: "{{SUMMARY}}"
annotation-target: {{citekey}}.pdf
---
{{TAGS}}

#### [{{title}}]({{citekey}}.pdf)
*Authors*

{{abstract}}

> [!tldr] Summary
> A short summary - or an abstract in 3 sentences, relating to YOU. What did YOU find interesting about this paper. 

> [!cite] Bibliography
>{{bibliography}}

> [!quote] Quotable
> Imagine you would quote this paper in your publication. How would you do it? It is probably just one sentence followed by the reference. It is the most intense condensation of the information in this paper and forces you to be on point. 
> 
> You can have multiple alternatives. 


#### Aim of Paper


#### Key insights 


#### Related

#### Annotations

{% for annotation in annotations %}
{% if annotation.annotatedText %}{{annotation.annotatedText}}{% endif %} 
{% if annotation.imageBaseName %}![[{{annotation. imageBaseName}}]]{% endif %}
{% if annotation.comment %}[[{{annotation.comment}}]]{% endif %} 
{% endfor %}

{{PDF}}
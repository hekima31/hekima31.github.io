---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<!-- ```
\documentclass{article}
\begin{document}
Look at this text,
\begin{minipage}{3cm}
This text is processed in paragraph mode, and then becomes an indivisible \TeX{} box.
\end{minipage}
how strange!
\end{document}
\end{document} -->


```
\alpha
```
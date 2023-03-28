---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}**,<br>
I usually play the support role whether it's by organizing projects or making tools to make game development easier. I am a self-taught developer that is constantly looking for a better way to write clean, scalable, and maintanable code. I also have a certificate of apprenticeship in ICT giving me the necessary skills to tackle any technical challenges thrown my way.

<div class="row">
{% include about/skills.html title="Game Development Skills" source=site.data.game-development-skills %}
{% include about/skills.html title="Languages" source=site.data.language %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
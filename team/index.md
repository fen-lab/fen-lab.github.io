---
title: Team
nav:
  order: 3
#   tooltip: About our team
---

## researchers

{% include list.html data="members" component="portrait" filter="role == 'researcher'" %}
<!-- {% include list.html data="members" component="portrait" filter="role != 'pi'" %} -->

{% include section.html %}
## contact

{% include list.html data="members" component="portrait" filter="role == 'secretary'" %}
{% include section.html %}

## students

{% capture col1 %}
- Lisa Baumüller (Dr. med.)
- Theresa Behle (Dr. med.)
- Louisa Bindig (Dr. med.)
- Michelle Deitzer (Dr. med.)
- Jasmin Jestädt (Dr. med.)
- Julia Kluth (Dr. med.)
- Martin Kühner (Dr. med.)
{% endcapture %}

{% capture col2 %}
- Jamila Martin (Dr. med.)
- Jana Mattes (Dr. med.)
- Annika Pfänder (Dr. med.)
- Mario Rastätter (Dr. med.)
- Anna Sperlein (Dr. med.)
- Oliver Totzauer (Dr. med.)
- Luise Riester (Dr. med.)
{% endcapture %}

{% capture col3 %}
- Ruth Weppelmann (MA)
- Sophia Zieger (Dr. med.)
- Katharina Zientek (Dr. med.)
- Saskia Zimmermann, MSc (PhD)
- Anastasios Ziogas (Dr. med.)
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3%}

{% include section.html %}
## former members

- Michael Bentsch
- Viktoria Pietsch (Dr. med.)
- Stefanie Ruhland (Dr. med.)
- Julia Schlögl (Dr. med. dent.)
- Franca Schultheis (MSc)
- Daniela Mirlach (Dr. med.)
- Maximilian Donges (Dr. med. dent.)
- Chiara Jahn (MSc candidate)
- Ulrike Rubin (Dr. med. candidate)
- Dr. Katrin Sakreida (Postdoc)
- Dr. phil. Miloš Stanković (Postdoc)

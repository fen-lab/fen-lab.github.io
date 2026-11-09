---
title: Team
nav:
  order: 3
#   tooltip: About our team
---

## researchers

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

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
- Viktoria Pietsch (Dr. med.)
- Mario Rastätter (Dr. med.)
- Luise Riester (Dr. med.)
- Stefanie Ruhland (Dr. med.)
{% endcapture %}

{% capture col3 %}
- Julia Schlögl (Dr. med. dent.)
- Sophia Zieger (Dr. med.)
- Katharina Zientek (Dr. med.)
- Saskia Zimmermann, MSc (PhD)
- Anastasios Ziogas (Dr. med.)
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3%}

{% include section.html %}
## former members

- Franca Schultheis (MSc)
- Daniela Mirlach (Dr. med.)
- Maximilian Donges (Dr. med. dent.)
- Chiara Jahn (MSc candidate)
- Ulrike Rubin (Dr. med. candidate)
- Dr. Katrin Sakreida (Postdoc)
- Dr. phil. Miloš Stanković (Postdoc)

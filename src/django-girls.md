---
layout: default
title: Django Girls
---
{% if site.show_django_girls != true %}<div class="box box_red"><p>It looks like nobody is here. Hopefully they're on their way!</p></div>{% else %}
<p>Django Girls is a free one-day web programming workshop for total beginners.</p>

<p>In the workshop, you'll learn the basics of web programming using Django, the free framework that's behind hundreds of thousands of websites, including huge projects like Instagram and Pinterest.</p>

<p>Django Girls is a hugely successful world-wide project that has introduced thousands of women and girls to programming; it has run at PyCon UK since 2015.</p>

<a href="https://djangogirls.org/pyconuk/">Apply to attend Django Girls at PyCon UK {{ site.con_year }}</a>

<figure>
  <img src="/images/django_girls_banner.jpg" alt="The django girls balloon-banner.">
</figure>

<div class="box box_yellow">
  <h3>What you need</h3>
  <p>You don’t need to know anything at all about programming.</p>
  <p>However, you will need to bring your own laptop and to be able to commit to the all-day workshop.</p>
</div>

<figure>
  <img src="/images/django_girls_thinking.jpg" alt="One of the django girls thinking.">
</figure>

<div class="box box_red">
  <h3>Be part of PyCon UK {{ site.con_year }}</h3>
  <p>The workshop is <strong>free of charge</strong> and is part of PyCon UK.</p>
  <p>Django Girls attendees at PyCon UK will be offered a <strong>free conference ticket</strong> to the full multi-day conference.</p>
  <p>We encourage you to make the most of this - it's a fun few days in a wonderful city and you will have the chance to take your programming skills further and be a part of the Python community!</p>
  <p>As complete beginners to programming, you will be especially welcome at PyCon UK {{ site.con_year }}.</p>
  <p>We want to make your introduction to programming as enjoyable as possible.</p>
</div>

<figure>
  <img src="/images/django_girls_assist2.jpg" alt="One of the django girls being assisted- you're not alone.">
</figure>

<div class="box box_blue">
  <h3>PyCon UK is here to support you</h3>
  <p><strong>PyCon UK wants you to be here.</strong></p>
  <p><strong>We provide a free crèche</strong> for your small children, so you don't have to worry about child care. If you need financial assistance to make your attendance possible, <strong>we can help cover transport, accommodation and other costs.</strong> The venue is suitable for attendees with <strong>mobility disabilities,</strong> and if you inform us about other needs, we can help.</p>
  <p>Django Girls is trans-inclusive and non-binary people are warmly welcomed. PyCon UK is a safe and friendly space for people of all identities and operates a strict <a href="/code-of-conduct/">Code of Conduct</a> for the benefit of all attendees.</p>
  <p><a href="/inclusion/">How we support attendees</a></p>
  <p>If you require financial assistance, please indicate this in the relevant question on the application form.</p>
</div>

<figure>
  <img src="/images/django_girls_assist.jpg" alt="Another one of the django girls being assisted- you're not alone.">
</figure>

{% if site.django_girls_applications_open == true %}
[Apply to attend Django Girls at PyCon UK {{ site.con_year }}][dg-at-pycon]
{% else %}
[More about Django Girls at PyCon UK {{ site.con_year }}][dg-at-pycon]
{% endif %}

{% endif %}

[dg-at-pycon]: https://djangogirls.org/pyconuk/

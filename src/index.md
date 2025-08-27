---
layout: default
---

<script type="application/ld+json">
{
    "@context": "https://schema.org",
    "@type": "Event",
    "name": "{{ site.title }}",
    "startDate": "{{ site.con_startDate }}",
    "endDate": "{{ site.con_endDate }}",
    "eventStatus": "EventScheduled",
    "location": {
        "@type": "Place",
        "name": "Contact Theatre",
        "address": {
            "@type": "PostalAddress",
            "streetAddress": "Oxford Road",
            "addressLocality": "Manchester",
            "postalCode": "M15 6JA",
            "addressCountry": "GB"
        }
    },
    "image": [
        "{{ '/images/red_snake.png' | absolute_url }}"
    ]
}
</script>

{% assign links = site.data.links.html.long %}

## PyCon UK will be at {{ links.contactmcr }} from {{ site.con_start }} to {{ site.con_finish }} {{ site.con_year }}.

<p>PyCon UK is a community conference, entirely run by volunteers. If you or your company would like to sponsor us, please get in touch at {{ "sponsorship@uk.python.org" | create_mailto_link }}</p>

{% if site.cfp_closed %}<!--{% endif %}<p>{% if site.cfp_open %}<p>Our CFP is open- if you have an idea for something you'd like to share with our audience: <a href="/call-for-proposals/">Tell us about it!</a>{% else %}CFP coming soon!{% endif %}</p>{% if site.cfp_closed %}-->{% endif %}
<p>{% if site.tickets_open == true %}<p><a href="/tickets">Join us in {{ site.con_location }}!</a>{% else %}Tickets coming soon!{% endif %}</p>

<p>You can follow us on
  <ul>
    <li>{{links.bluesky}}</li>
    <li>{{links.linkedin}}</li>
    <li>{{links.mastodon}}</li>
    <li>{{links.twitter}}</li>
  </ul>
</p>
<br />

<p>PyCon UK related merchandise is available <a href="https://pyconuk.myspreadshop.co.uk/">here</a>.</p>
<br />

<p>Alternatively, you can <a href="https://www.ravelry.com/patterns/library/curly-snake-3">knit your own snakes using patterns created by one of our volunteers, Becky Smith</a>.</p>
<figure>
  <a href="https://www.ravelry.com/patterns/library/curly-snake-3"><img
    src="/images/becky_snakes.jpg"
    alt="A collection of hand knitted snakes."></a>
  <figcaption>
    Photo of snakes created by PyCon UK volunteer Becky Smith.
  </figcaption>
</figure>
<br />

<a href="/faq/">Help, I'm new to Python and PyCon UK! What does all this mean?</a>

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

<p> Thanks everyone for helping make a great {{ site.title }}. We hope to see you again next year!

<div class="box box_blue">
  <h3>Media</h3>
  <p><a href="https://flic.kr/s/aHBqjCuzme">Day 1 pictures</a> | <a href = "https://youtube.com/playlist?list=PLrkpavSsBQZ6bnFa93KWXtMJoBA-a4_f_&si=Xc93N1pDDscJ4KyU">Day 1 videos main stage </a> | <a href="https://youtube.com/playlist?list=PLrkpavSsBQZ41YpNF6EUDUB5wAwwfbKPV&si=Itaz-V1fnDPjdX05" >Day 1 videos space 2</a></p>
  <p> <a href = "https://flic.kr/s/aHBqjCuJgA">Day 2 pictures</a> | <a href = "https://youtube.com/playlist?list=PLrkpavSsBQZ62noXYqRezmjdE7_CCbT9_&si=sn_U01EvXyUWr29N">Day 2 videos main stage</a> | <a href = "https://youtube.com/playlist?list=PLrkpavSsBQZ6tGVw3Ic4ovat0k9wUJSCs&si=3l19StYlmsQQTni5">Day 2 videos space 2</a></p>
  <p> <a href = "https://flic.kr/s/aHBqjCuPNx">Day 3 pictures</a> | <a href = "https://www.youtube.com/playlist?list=PLrkpavSsBQZ6MjNYXtWm_YFEcrLkCxN2w">Day 3 videos main stage</a> | <a href = "https://youtube.com/playlist?list=PLrkpavSsBQZ5eIZIu7vl8UY276vyEyXXr&si=n5YXcettlWflTDes">Day 3 videos space 2</a></p>
</div>


{% if site.cfp_closed %}<!--{% endif %}<p>{% if site.cfp_open %}<p>Our CFP is open- if you have an idea for something you'd like to share with our audience: <a href="/call-for-proposals/">Tell us about it!</a>{% else %}CFP coming soon!{% endif %}</p>{% if site.cfp_closed %}-->{% endif %}

<p>You can follow us on
  <ul>
    <li><a href ="https://www.youtube.com/@PyconUKSoc">YouTube</a></li>
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

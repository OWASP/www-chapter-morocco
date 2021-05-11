---

layout: col-sidebar
title: OWASP Morocco
tags: morocco-tag
level: 0
region: Africa


---


## Welcome

Welcome to the OWASP
Our mission is to enrich Morocco's application security community and cyber security community. We
hope you can join us in accomplishing that.

### Modern Society
#### A modern society focused on the future

Through rooted in its traditions, Morocco offers all the conveniences of modern times

Morocco is a firmly future-focused country that has succeeded in preserving its traditions and promoting its cultural heritage by harnessing them to drive development. The city of Marrakesh is a perfect example: the Medina district and its souks have an unmatched old-fashioned charm, while Guéliz and Hivernage are decked out with the most modern infrastructure and facilities. Far from being in conflict, modernity and tradition together are what makes Morocco strong.

As a visitor, you will enjoy every modern convenience and pleasure. For your accommodations, Morocco is full of hotels in every price range from the major international chains. Plus it also has the biggest international ready-to-wear shops, which are taking advantage of the ideal opportunity for positioning in a fast developing country.

Morocco is striving to avoid the pitfalls of modern life, especially when it comes to the environment, by favoring tourism practices that are respectful of the Earth and local communities. As the author of a sustainable tourism charter and host of COP22, Morocco is on the front lines to preserve our planet.

#### Call For Speakers

With the Morocco chapter, we aim to organize at least 6 local chapter meetings per year.  If you would like to present a talk on Application Security at future OWASP Morocco Chapter events, feel free to reach out to us and let us know - we'd love to have you join us!

Upcoming Meeting/Event(s)
---------------------
<a class='timeclass'>[Meeting at Meetup](https://www.meetup.com/fr-FR/Morocco-OWASP-Meetup-Group/)</a>

{% assign category = site.data.events | where: "category", "Global" | first %}

{% for event in category.events %}
{{event.name}}
{% endfor %}
Check our Upcoming Meetup Events:
{% include chapter_events.html group=page.meetup-group %}

<script type='text/javascript'> $(function(){ $(".timeclass").hover(function() { utc_str = $(this).text(); ndx = utc_str.indexOf(':'); st_hour_str = utc_str.substring(0, ndx); st_min_str = utc_str.substring(ndx + 1, ndx + 3); utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(st_hour_str), parseInt(st_min_str), 0); start_dt = utc_dt.setZone(luxon.DateTime.local().zoneName); ndx = utc_str.lastIndexOf(':'); end_hour_str = utc_str.substring(ndx - 2, ndx - 1); end_min_str = utc_str.substring(ndx + 1, ndx + 3); utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(end_hour_str), parseInt(end_min_str), 0); end_dt = utc_dt.setZone(luxon.DateTime.local().zoneName); popstr = start_dt.toLocaleString(luxon.DateTime.TIME_WITH_SECONDS) + ' to ' + end_dt.toLocaleString(luxon.DateTime.TIME_WITH_SHORT_OFFSET); $(this).prop('title', popstr); }); }); </script>


#### Code of Conduct #### 

We hope you enjoy our events, we care deeply about inclusivity and diversity so that OWASP is a comfortable and welcoming community for everyone. Please reach out to one of our chapter leaders if you have any feedback or would like to speak to us, we take these matters very seriously.

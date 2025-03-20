---
layout: page
title: Home
id: home
permalink: /
---

# hi, i'm siddharth.

i'm most active on [X](https://x.com/siddhxrth10) (sometimes more than i would like)


I spend my weekdays working in [Portkey](https://portkey.ai) and doing cool projects on weekends. I have been lucky to discover the work of inspiring people from around the world early in my life, which has greatly influenced my own work and ideas

---
## Writing

this website is a WIP. i plan to start writing, mostly to capture a trend of changes in my thinking

---
## Things I Believe

#### inspired by [nat](https://nat.org), some things i believe:

- The cost of energy will come close to 0 in the coming decades
- number of iterations is the key to successful things
- Good artists copy, great artists steal

i will probably add more to this list soon --- meanwhile feel free to say hi on [sam.siddharth10@gmail.com](mailto:sam.siddharth10@gmail.com?subject=Hello!)!


<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>

---
layout: page
title: Home
id: home
permalink: /
---

# hi, i'm siddharth.

i'm most active on [X](https://x.com/siddhxrth10) (sometimes more than i would like)

i spend my weekdays working in [Portkey](https://portkey.ai) and doing side projects on weekends. I have been lucky to discover the work of inspiring people from around the world early in my life, which has greatly influenced my own work and ideas

---
## writing

this website is a WIP. i plan to start writing, mostly to capture a trend of changes in my thinking

- [How to develop taste for good work?](taste)

---
## things i believe

#### inspired by [nat](https://nat.org), some things i believe:

- the cost of energy will come close to 0 in the coming decades
- number of iterations is the key to successful things
- good artists copy, great artists steal
- agency is the most important thing if intelligence becomes democratized

i will probably add more to this list soon --- meanwhile feel free to say hi on [sam.siddharth10@gmail.com](mailto:sam.siddharth10@gmail.com?subject=Hello!)!


---
## cool people

i like the idea of writer builders mentioned [here](https://www.workingtheorys.com/p/writer-builder)

there are few things that can give you asymmetric returns in life. this website is one experiment to get asymmetric returns. hopefully someone is interested in what i write and it lands into something tangible. or maybe my future wife reads this, i don't know

here's a list of cool people  on the internet that inspired me to write this (with some web presence):

- Anu Atluru
- Paras Chopra
- Paul Graham
- Alexey Guzey
- Dwarkesh Patel
- Patrick Collison
- Nat Friedman

(tool lazy to add links, you can find them yourself!)


<strong>recently updated notes</strong>

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

---
layout: about
title: about
permalink: /
subtitle: TU/e. Eindhoven. <a href="mailto:marhiar@gmail.com">marhiar@gmail.com</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Eindhoven, the Netherlands</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

> "If you cannot explain something in simple terms, you don't understand it." — Richard Feynman

> "You are under no obligation to remain the same person you were a year ago, a month ago, or even a day ago. You are here to create yourself, continuously." — Richard Feynman

Here's the cleaned up version with typos fixed and minor improvements:

---
layout: about
title: about
permalink: /
subtitle: TU/e. Eindhoven. <a href="mailto:marhiar@gmail.com">marhiar@gmail.com</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Eindhoven, the Netherlands</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

> "If you cannot explain something in simple terms, you don't understand it." — Richard Feynman

> "You are under no obligation to remain the same person you were a year ago, a month ago, or even a day ago. You are here to create yourself, continuously." — Richard Feynman

I was born in Costa Rica and raised in the countryside among coffee plantations. I learned to harvest coffee before I started school. Coffee picking is simple in theory: move plant by plant, inspect carefully, remove only the ripe cherries, leave the green ones for later. That is how you get better coffee. To do it well, you need curiosity and patience. I did it from 6 AM to 4 PM, every day, for three months each year. I started when I was five and kept going until I was twenty-two. Sometimes I joke that I have a PhD in coffee picking.

I carried that same attitude into learning. When something catches my curiosity, I work through it until I can understand it and explain it clearly. Only then do I move on. That habit took me across a few fields. The labels changed. The pattern did not. I kept following problems that forced me to understand, not just to repeat. If I repeat, I get bored.

{% include figure.liquid path="assets/img/paths.jpg" class="img-fluid rounded z-depth-1" caption="Tim Urban @waitbutwhy" %}

Today I am a PhD candidate in the Signal Processing Systems group at Eindhoven University of Technology, working on a question my curiosity won't leave alone: how to reason well when information is incomplete.

My research focuses on real-time probabilistic models for personalized audio processing. The tool I use is variational inference via message passing. The core idea is simple: I research how to build signal processing systems that can represent uncertainty. A concrete target is speech denoising for hearing aids. The hardware is small and the power budget is tight. The world is messy, and uncertainty is everywhere. So the question is not only "how do we enhance speech?" The deeper question is "how do we do it while incorporating uncertainty, in real time, on-device?"

Before the PhD, I spent years working on wearable systems. Wearables taught me not to trust lab results. In controlled settings, models look great on metrics. But in daily life, you move a sensor a few millimeters and the signal changes. Add motion, noise, and real human behavior, and the algorithm fails. This work humbles you. The failure is not mysterious—the system has no honest way to represent uncertainty.

That is why I work with Bayesian approaches. Bayesian inference is a principled way to reason under uncertainty. You start with prior beliefs, update them with data, and obtain a posterior belief. Uncertainty is information about the boundary between what you know and what you do not.

This does not mean Bayesian methods are a free lunch. In practice, they can be expensive to compute, and approximations force trade-offs between complexity and accuracy. Choosing priors is still partly craft. Expert knowledge matters. But at least you can see what you are trading off. You take a messy real-world question and translate it into a probabilistic model. That forces you to write assumptions down explicitly. Then the mathematics tells you what follows from those assumptions, including how uncertain you should be.

"The writer has learned from much experience that this primary emphasis on the logic of the problem, rather than the mathematics, is necessary in the early stages… It is in the conceptual matters (how to make the initial connection between the real-world problem and the abstract mathematics) that they are perplexed and unsure how to proceed." — E. T. Jaynes

The question is learning how to turn a real problem into a model you can actually interrogate. You make a set of assumptions, you write them down, and you build the simplest model that captures what you think matters. Then you do the honest part. You confront it with data and failure cases, and you ask what broke. Was it the assumptions, the structure, or the computation? You revise, simplify, or rebuild. That cycle is the work. Models are never the world, but they can still be useful when treated as tools and stress-tested like tools.

This website is my public notebook. I write to learn and to teach. I try to remove magic words and replace them with working intuition. Sometimes I write a post and realize halfway through that I was wrong about something fundamental. I leave those up. Being wrong in public is how you find the confusion.

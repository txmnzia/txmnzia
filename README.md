# Hi there

I'm a product manager working on data and AI products.

In my free time I build apps for problems I run into. I run each one like a product team made of agents: they help me research the problem, brainstorm solutions, design the UX, process the data, write the code and test quality. I set the direction, coordinate the workstreams and make sure the result is good.

Everything is live at [txmnzia.github.io](https://txmnzia.github.io).

## What I built

* **[Pilzdex](https://txmnzia.github.io/pilz-pokedex/)**
  *Problem:* Mushroom picking is risky, and there was no simple way to identify and log finds.
  *What I did:* A field journal that identifies a mushroom from a photo, even offline. I built a golden dataset of 4k photos the models had never seen and benchmarked 4 image recognition models on precision, recall and safety.

* **[Pilzmap](https://txmnzia.github.io/pilzmap/)**
  *Problem:* Without experienced local foragers to learn from, every forest trip was a gamble.
  *What I did:* A map predicting where mushrooms are likely to appear by combining public datasets on tree species, soil and humidity. I built the data pipeline and validated it against 27k real sightings.

* **[Flavour Pairing](https://txmnzia.github.io/flavour-pairing)**
  *Problem:* Cooking creatively with whatever is in the fridge, without ruining a dish with a bad combination.
  *What I did:* A recommender based on ingredient pairing scores computed from co occurrence in 1M recipes. Now building a hand labelled test set to measure suggestion quality.

* **[Eki Stamp Map](https://txmnzia.github.io/eki-stamp-tracker/)**
  *Problem:* Japan's station stamps are only listed on long Japanese web pages, making it hard to track which ones you have and which lines you've ridden.
  *What I did:* One map of every stamp station plus a personal collection tracker. I scraped and cleaned the data myself, and automated quality checks catch missing or broken data on every change.

* **[Financial Planner](https://txmnzia.github.io/fire-planner/)**
  *Problem:* Generic financial planners can't model detailed personal situations, so they're hard to trust for big decisions.
  *What I did:* A planner with fully configurable parameters and realistic assumptions. It simulates thousands of market histories to show the range of outcomes, and every calculation is covered by consistency tests.

* **[Fog of War](https://txmnzia.github.io/FogOfWar/)**
  *Problem:* Motivation to explore new areas instead of the same routes.
  *What I did:* A game like map that turns exported location history into explored and unexplored regions, with achievements.

* **[Travel Map](https://txmnzia.github.io/travel-map)**
  *Problem:* Not everyone is tech savvy enough to follow a road trip online.
  *What I did:* Draw an itinerary on a map and turn it into a short, playful video you can send to anyone.

## What I learned

* Test a model on data it hasn't seen, and measure the mistake that matters. For mushrooms, that's calling a deadly one edible. Overall accuracy hid that problem.
* Expert rules are a starting point. The data proved some of them wrong.
* A wrong number is worse than a crash, because nobody notices it. The important logic has unit tests that run on every change.
* New data never replaces the old until it passes the quality checks.
* AI agents repeat the same mistakes from one project to the next. I keep a shared rulebook of those lessons that every agent reads before it starts.

**Skills:** model evaluation, golden datasets, precision and recall, data pipelines, data quality, automated testing, Python, JavaScript, React

# Hi, I'm Sam

I'm a lead product manager working on data and AI/LM products.

In my free time I build apps for problems I run into myself. I run each one like a product team made of agents: they help me research the problem, brainstorm solutions, design the UX, collect and process the data, write the code, test the quality, and ship. I set the direction, coordinate the different workstreams and ensure that the solution is right.

Everything is live at [txmnzia.github.io](https://txmnzia.github.io).

## What I built

| App | The problem | What I did |
|---|---|---|
| [Pilzdex](https://txmnzia.github.io/pilz-pokedex/) | Mushroom picking is risky, and I had no simple way to identify and keep track of what I found in nature. | A field journal where I snap a photo and get an identification, even offline. I built a golden dataset of 4k photos the models had never seen and benchmarked 4 image recognition models on precision, recall and safety. |
| [Pilzmap](https://txmnzia.github.io/pilzmap/) | As a new Berliner, I haven't met anyone who could share their mushroom spots with me. Each of my forest trips was a gamble. | I created a map showing where mushrooms are likely to appear by combining public datasets on tree species, soil, and humidity. I built the data pipeline and validated it against 27k real sightings, so now I only go where the odds are high. |
| [Flavour Pairing](https://txmnzia.github.io/flavour-pairing) | I wanted to be creative when cooking with the ingredients in my fridge, without ruining a dish with a bad combination. | A recommender based on th best pairing of ingredients, computed on 1M recipes co-occurrence. I'm now building a hand-labelled test set to measure how good the suggestions are. |
| [Eki Stamp Map](https://txmnzia.github.io/eki-stamp-tracker/) | Japan's station stamps are only listed on long Japanese web pages, and I lost track of which ones I had and which lines I'd ridden. | One map of every stamp station and my own collection. I scraped and cleaned the data myself, and automated data quality checks catch missing or broken data on every change. |
| [Financial Planner](https://txmnzia.github.io/fire-planner/) | Generic financial planners couldn't take my real situation into account, and I didn't trust them for big life decisions. | A planner with all my personal parameters and realistic assumptions. It simulates thousands of possible market histories to show the range of outcomes, and every calculation is covered by strong consistency tests. |
| [Fog of War](https://txmnzia.github.io/FogOfWar/) | I wanted to motivate myself to explore more of my surroundings and discover new areas in my country. | I gamified my GPS data from sources like Strava and Google Maps to create a video game-like map, with unexplored regions and achievements. |
| [Travel Map](https://txmnzia.github.io/travel-map) | Not all my relatives are tech-savvy enough to follow my road trips online. | I created this app where one can draw their itinerary on a map and turn it into a short, playful video to send to anyone |

## What I learned

- Test a model on data it hasn't seen, and measure the mistake that matters. For mushrooms, that's calling a deadly one edible. Overall accuracy hid that problem.
- Expert rules are a starting point. The data proved some of them wrong.
- A wrong number is worse than a crash, because nobody notices it. So the important logic has unit tests that run automatically on every change.
- New data never replaces the old until it passes the quality checks.
- AI agents repeat the same mistakes from one project to the next. I keep a shared rulebook of those lessons that every agent reads before it starts.

**Skills:** model evaluation, golden datasets, precision and recall, data pipelines, data quality, automated testing, Python, JavaScript, React

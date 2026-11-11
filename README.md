# Hi, I'm Sam

I'm a product manager working on data and machine learning products.

In my free time I build apps for problems I run into myself. I run each one like a product team made of AI agents: they help me research the problem, design the screens, collect and clean the data, write and test the code, and ship it. I set the direction, make the calls and check that what comes out is right.

Everything is live at [txmnzia.github.io](https://txmnzia.github.io).

## What I built

| App | The problem | What I did |
|---|---|---|
| [Pilzdex](https://txmnzia.github.io/pilz-pokedex/) | Mushroom picking is risky, and I had no simple way to identify and keep track of what I found in nature. | A field journal where you snap a photo and get an identification, even offline. I built a golden dataset of 3,500 photos the models had never seen and compared 4 image recognition models on precision, recall and safety. The old one called 1 in 3 deadly mushrooms edible, so I replaced it. |
| [Pilzmap](https://txmnzia.github.io/pilzmap/) | Nobody shares their mushroom spots, so every trip into the forest was a gamble. | A map of where the trees, soil and water suit each species, built with a data pipeline over public maps and validated against 27,000 real sightings. The textbook rules turned out to be wrong for Brandenburg, so I corrected them with the data. Now I only go where the odds are high. |
| [Flavour Pairing](https://txmnzia.github.io/flavour-pairing) | I wanted to be creative with what's in my fridge without ruining a dish with a bad combination. | A recommender based on how often ingredients appear together in recipes. I'm now building a hand-labelled test set to measure how good the suggestions really are. |
| [Eki Stamp Map](https://txmnzia.github.io/eki-stamp-tracker/) | Japan's station stamps are only listed on long Japanese web pages, and I lost track of which ones I had and which lines I'd ridden. | One map of every stamp station and my own collection. I scraped and cleaned the data myself, and automated data quality checks catch missing or broken data on every change. |
| [Financial Planner](https://txmnzia.github.io/fire-planner/) | Generic financial planners couldn't take my real situation into account, and I didn't trust them for big life decisions. | A planner with all my personal parameters and realistic assumptions. It simulates thousands of possible market histories to show the range of outcomes, and every calculation is covered by unit tests. |
| [Fog of War](https://txmnzia.github.io/FogOfWar/) | My travel history is split across Google Timeline and Strava, and no map shows what's left to explore. | Combines both into one map that stays dark where I haven't been yet. |
| [Travel Map](https://txmnzia.github.io/travel-map) | My family isn't tech savvy and couldn't follow my road trips. | Draw the route and get a short, light video of it on a simple map that anyone can watch. |

## What I learned

- Test a model on data it hasn't seen, and measure the mistake that matters. For mushrooms, that's calling a deadly one edible. Overall accuracy hid that problem.
- Expert rules are a starting point. The data proved some of them wrong.
- A wrong number is worse than a crash, because nobody notices it. So the important logic has unit tests that run automatically on every change.
- New data never replaces the old until it passes the quality checks.
- AI agents repeat the same mistakes from one project to the next. I keep a shared rulebook of those lessons that every agent reads before it starts.

**Skills:** model evaluation, golden datasets, precision and recall, data pipelines, data quality, automated testing, Python, JavaScript, React

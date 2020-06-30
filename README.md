<img src="http://gamejourney.ru/wp-content/uploads/2016/11/lol-worlds-2016-stadium.jpg" alt="LoL Worlds">

# Tableau Project: League of Legends 2019 Worlds Championship

This analysis tries to rank players in each role, who attended the main stage from the League of Legends 2019 Worlds championship.

**Note:** The final ranking despite showing a trend, does not group the players in a numbered order, instead it shows **strenghts** and **weaknesses** of these players, the reason being that the data obtained its a bit limited and there are way more variables to take into account in order to give a clonclusive result.

Please don't @ me! :D

## What is League of Legends?

League of Legends (LoL) is a multiplayer online battle arena video game developed and published by Riot Games for Microsoft Windows and macOS. Inspired by the Warcraft III: The Frozen Throne mod Defense of the Ancients.

In League of Legends, players assume the role of a "champion" with unique abilities and battle against a team of other player or computer-controlled champions. The goal is usually to destroy the opposing team's "Nexus", a structure that lies at the heart of a base protected by defensive structures, although other distinct game modes exist as well with varying objectives, rules, and maps. Each League of Legends match is discrete, with all champions starting off relatively weak but increasing in strength by accumulating items and experience over the course of the game.

Champions span a variety of roles and blend a variety of fantasy tropes, such as sword and sorcery, steampunk, and Lovecraftian horror. Although the discrete nature of each match prohibits an overarching narrative in-game, the various champions make up a large and ever-evolving fictional universe developed by Riot Games through short stories, comics, cinematics, and books.

TLDR? [Watch me!](https://www.youtube.com/watch?v=Gnsq2lseMk0)

## What is Worlds Championship?

The League of Legends World Championship is the annual professional League of Legends world championship tournament hosted by Riot Games and is the culmination of each season. Teams compete for the champion title, the Summoner's Cup, and a multi-million-dollar championship prize. In 2018, the finals were watched by 99.6 million people, breaking 2017's finals' viewer record. The tournament has been praised for its ceremonial performances, while receiving attention worldwide due to its multiple dramatic and emotional series.

Want to learn more? [Go hype!](https://www.youtube.com/watch?v=igpwG5gLHV8&frags=pl%2Cwn) :)

## Where did I obtained the data from?

I donwloaded the 2019 worlds championship data available for the public at [Oracles Elixir](https://oracleselixir.com/).

## Where to see the project?

You got two options:

- Download the **twb** file found in this repository.
- Visit the [Tableau public link](https://public.tableau.com/profile/edgar.pena#!/vizhome/TableauBI_15934584903420/---------).

# Workflow

I started by looking for the right data, cleaning it from unnecesary or empty values, or values that are duplicated or grouped by team instead of individuals, changing as well data types and formats, all of this by using python and pandas.

Started by breaking down which metrics are most consistent between the teams that win the most, from there I grouped the metrics for each role, to have an idea of which of these metrics are KPIs for them. After that I was able to make a player ranking by grouping and sorting them by the KPIs found.

# Resources

- What is League of Legends? Told by LilyPichu
  https://www.youtube.com/watch?v=Gnsq2lseMk0
- 2019 World Championship Group Stage Opening Tease
  https://www.youtube.com/watch?v=igpwG5gLHV8&frags=pl%2Cwn
- Oracles elixir Data download link
  https://oracleselixir.com/gamedata/2019-worlds/
- Worlds Image
  http://gamejourney.ru/wp-content/uploads/2016/11/lol-worlds-2016-stadium.jpg

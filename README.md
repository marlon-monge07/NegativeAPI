# DeclineAI — The World's First Honest AI

A satirical SaaS landing page where six negativity APIs work in perfect disharmony to reject your ideas, insult your intelligence, give you advice you didn't ask for, and teach you facts nobody needs.

**[Live Demo](https://marlon-monge07.github.io/NegativeAPI/)**

## What Is This?

DeclineAI is a fake AI startup landing page built entirely for fun. Every piece of "AI wisdom" on the page is powered by real, free public APIs that return rejections, insults, useless facts, bad jokes, and unsolicited advice — all auto-refreshing every 10 seconds.

## APIs Used

### Home — Negativity Engine

| API | What It Does | Endpoint |
|-----|-------------|----------|
| [No As A Service (NaaS)](https://github.com/hotheadhacker/no-as-a-service) | Creative rejections | `naas.isalman.dev/no` |
| [Evil Insult Generator](https://evilinsult.com) | Blunt insults | `evilinsult.com/generate_insult.php` |
| [Advice Slip](https://api.adviceslip.com) | Unsolicited advice | `api.adviceslip.com/advice` |
| [Useless Facts](https://uselessfacts.jsph.pl) | Facts nobody needed | `uselessfacts.jsph.pl/api/v2/facts/random` |
| [Matt's Insult API](https://insult.mattbas.org/api/) | Elaborate roasts | `insult.mattbas.org/api/insult.json` |
| [Official Joke API](https://github.com/15Dkatz/official_joke_api) | Bad jokes | `official-joke-api.appspot.com/random_joke` |

### Labs — API Playground ([explore.html](https://marlon-monge07.github.io/NegativeAPI/explore.html))

| API | What It Does | Endpoint |
|-----|-------------|----------|
| [Chuck Norris API](https://api.chucknorris.io) | Random Chuck Norris facts | `api.chucknorris.io/jokes/random` |
| [PokeAPI](https://pokeapi.co) | Random Pokemon with sprites and stats | `pokeapi.co/api/v2/pokemon/{id}` |
| [SWAPI](https://swapi.dev) | Random Star Wars character profiles | `swapi.dev/api/people/{id}` |
| [Numbers API](http://numbersapi.com) | Number trivia, math, dates, years | `numbersapi.com/{number}/{type}` |
| [Fun Translations](https://funtranslations.com/api/) | Yoda, Pirate, Shakespeare & more | `api.funtranslations.com/translate/{lang}` |
| [NASA APOD](https://api.nasa.gov) | Astronomy Picture of the Day | `api.nasa.gov/planetary/apod` |

## Features

- **Hero Quote** — A rotating rejection from the NaaS API with a visual countdown timer and manual "Next" button.
- **Live Ticker** — A scrolling marquee pulling tagged content from all 6 APIs simultaneously.
- **Negativity Dashboard** — Six cards in a grid, each connected to a different API, all auto-refreshing with individual "Next" buttons.
- **The Gauntlet** — Type your idea and watch all 6 APIs take turns destroying it one by one. Responses are pre-fetched in parallel for speed, then revealed sequentially for dramatic effect.
- **Responsive Design** — Looks good on desktop and mobile.
- **Labs Page** — A separate playground with Chuck Norris facts, random Pokemon, Star Wars characters, number trivia, fun translations (Yoda, Pirate, etc.), and NASA's Astronomy Picture of the Day.

## Tech Stack

Zero dependencies. Two HTML files with vanilla HTML, CSS, and JavaScript.

## Run Locally

Just open `index.html` in your browser. No build step, no server, no node_modules.

## License

MIT — do whatever you want with it. The APIs might still say no, though.

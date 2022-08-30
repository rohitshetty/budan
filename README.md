# Budan

## Why

I have been tracking my coffee brewing ritual for the last few months offline, in a notebook.
I love the experience but it has bugged me that I cannot get the data inside into any digital format.

I explored existing options, with a few criteria:

1. Should allow me to export/import data in open formats like csv
2. Should be Opensource preferably

I explored some major options, especially the mobile apps, and did not find any that fits my criteria.
I found only a few Opensource tools that did this, but either they felt weird to work with, were not maintained, or I was not able to get them running locally.

Given this, the goal of this script is to keep it simple and start capturing my coffee brews and store them locally and add features to make my life easier.

## Why is it called Budan

[Baba Budan](https://en.wikipedia.org/wiki/Baba_Budan) is a 16th-century Sufi saint who is believed to have introduced coffee to the Indian subcontinent by smuggling 7 green coffee beans in his beard from the port of Mocha on the way back from his Hajj.
He is said to have planted these beans in the Hill ranges of Chikmaglur, Karnataka.

You can read more about him [here (but would say, citations are needed for this article)](https://www.coffees.gr/baba-budan-story/)

## Installation

Right now, the build process works only on \*nix styled OS, because of chmod and shebang.

### Install the dependencies.

`npm i && npm run build`

### Link the build and get access to `budan` as a cli command.

`npm link`

### Test

`budan`

## Roadmap <sub>(Or feature creep, depends on how you look at it) </sub>

- [ ] Simple CLI script that I can use to capture my brewing parameters and notes off from my offline diary and store it sqlite.
- [ ] Capture what coffee I have ordered.
- [ ] Inventory management of coffee - Capture what quantity of coffee you start out with and what you consume (From daily logs), and alert me when I am few brew away from running out.
- [ ] Capture coffee recipes that can be rendered as [Aramse-styled](https://aramse.coffee/recipe/) chart.
- [ ] Web app where you can view the Recipe using [Aramse-styled](https://aramse.coffee/recipe/) coffee recipe (Maybe interactively progressing with time) + Timer integrated.
- [ ] Integrate capturing of the daily brewing params and notes using the web app.

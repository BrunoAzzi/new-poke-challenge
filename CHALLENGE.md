# Front-end Challenge
Hello friend! We are very excited to invite you to our selection process for new front-end candidates.

The idea behind this coding challenge (or take-home assignment) is to understand better how you work on specific front-end tasks, your thought process, and how you design your code.

The challenge is simple and should take an experienced developer from 6 to 8 hours of work.

You will have one whole week to finish this and deliver it to our team. If you need an extension, let us know beforehand to arrange for us to evaluate your test as soon as possible.

### Evaluation Topics

To make this test super transparent, we are going to evaluate the following topics in your code once you deliver it, in no particular order:
- Challenge completeness
- Challenge proposal comprehension
- Idiomatic writing
- Test coverage
- Best practices usage
- A general architecture for the solution
- Easiness to run
- Automation
- Documentation
- Usage of modern styling standards

This test is a window into your work, so take your time, use the time to create something with quality that showcases your understanding of the frontend ecosystem, tooling, and best practices.

### Restrictions
There are a few restrictions on your choices to develop this test. You should create this solution using any of the following:
- React
- Preact
- Any React compatible framework (Next, Gatsby, among others)

Using Typescript is highly encouraged.

Remember, while we are giving some constraints, we will ask you to justify your choices and why they are good choices.

- You may not use PokeAPI wrapper libraries.
- You can use any CSS preprocessors, like Sass or Less.
- You can use any CSS framework you deem appropriate, such as Tailwind, but you cannot use component libraries, like MDI or bootstrap.

## Challenge
So, we are huge Pokémon fans, and we love them, and we want to catch them all. We want you to design and implement a Pokedex from scratch, using freely available APIs (https://pokeapi.co/).

### Pokemon List
Create a project that can connect to PokeAPI and show us a list of Pokémon. There are several Pokémon in PokeAPI, so be sure that the website can handle all the Pokémon and display them organized.

There is no suggested UI design for this project, so you can be as creative as you’d like.

You should display each Pokémon on a card, together with important information about each:

- A Small picture/icon
- National Dex Number (eg: #001)
- Name (eg: Bulbasaur)
- Types (eg: Grass, Poison)

Your project should support ordering pokemons by name, type, or dex number. When you click on a pokemon, it should show its details page.
Here are a few references you can take a look at from famous pokémon related websites:

- Bulbapedia
- Marriland

### Pokemon Detail
Create a page that shows the pokemon’s details with the following information:
- Dex Number
- Name
- Types
- Stats
- Base stats can reach a maximum of 255, use that to your advantage while coming up with a cool UI!
- An image display
- Should have a way to switch between normal and shiny sprites
- The Pokémon’s Moves.
- Damage class (physical, special)
- Power
- Accuracy
- Type (Grass, Water, etc)
- Description

## Extra credit

If you have time and want to add more features, here are some ideas:

- Show more info available in the API
- Show the pokémon’s species evolutionary line
- Deploy your project somewhere with some CI/CD
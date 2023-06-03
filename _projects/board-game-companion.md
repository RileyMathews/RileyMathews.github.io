---
layout: project
title: Board Game Companion
tags: ruby rails tailwindcss hotwire postgresql flyio docker
---
# Board Game Companion
This idea for this app came from a weekly board game group I was in. We were playing the 'Skyrim Adventure Game' and there were a few pain points. The resources were a little fiddley to work with and keep straight between sessions of the game, and the game did not come with enough dice for us to play multiple battles at once in a turn if we each decided to fight a different enemy.

The app allows users to create game templates and define the resources and dice a game uses. Then they can create a room from a game and invite other users to join. Once in a room the users can manage their own resources and roll the dice for the game while other players can keep track of who has what resources and see a live updating roll log of other player's dice rolls.

The app was originally written as a module in my [django demos](https://github.com/RileyMathews/django-demos/tree/master/resource_tracker) repository. But I eventually wanted to re-write the app using Ruby on Rails as I was starting to find the built in Django support for websockets lacking. Rails' [hotwire](https://hotwired.dev/) project seemed like a perfect fit for what I was trying to do and so I ended up re-writing the project in rails which can be seen at [boardgamecompanion.fly.dev](https://boardgamecompanion.fly.dev).

The app uses Rails with entirely server rendered templates using turbo streams for any live updating. Tailwind CSS is used with a heavy use of Flowbite components.

[See the code here](https://github.com/RileyMathews/board-game-companion)

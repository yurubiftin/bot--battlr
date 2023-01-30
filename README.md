# Week two, Phase two code Challenge: Bot Battlr

## Setup

After cloning down the project:

1. Run `npm install` in your terminal
2. Run `npm start`: This will open the bot-battlr application

##Requirements
Vs code
node
install semantic css in react
react app

## What You Already Have

`BotPage` is the highest component below App, and serves as the main container for all of the pieces of the page.

`BotCollection` and `YourBotArmy` are container components, which are children of `BotPage`. `BotCollection` is where all the bots will be displayed, while `YourBotArmy` (the green portion on the top of the screen) will only display the bots that have been selected by the user.

`BotCard` and `BotSpecs` are presentational components that have been provided for you that will render out information about an individual bot formatted for a list view and for a full view, respectively. They are pre-styled, and it is your responsibility to get the data into them.


## Core Deliverables

As a user, I should be able to:

- See profiles of all bots rendered in `BotCollection`.
- Add an individual bot to my army by clicking on it. The selected bot should render in the `YourBotArmy` component. The bot can be enlisted only **once**. The bot **does not** disappear from the `BotCollection`.
- Release a bot from my army by clicking on it. The bot disappears from the `YourBotArmy` component.
- Discharge a bot from their service forever, by clicking the red button marked "x", which would delete the bot both from the backend and from the `YourBotArmy` on the frontend.

The project can be viewed live using this live link "https://bot-battlr-six-delta.vercel.app"


## license
ISC

## Author
Yurub Ahmed


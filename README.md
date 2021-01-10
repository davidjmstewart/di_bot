# di_bot
A simple ping/pong bot in Node.js + TypeScript that is testable, using dependency injection, based on the [tutorial](https://www.toptal.com/typescript/dependency-injection-discord-bot-tutorial) by [Michał Krakiewicz](https://github.com/mkrakiewicz).

Uses: Node.js, TypeScript, InversifyJS, Mocha, Chai, & ts-mockito.

# Installing

1. `git clone https://github.com/davidjmstewart/di_bot.git && cd di_bot`
2. `npm install`
3. Add your Discord Bot token to the `.env` file **N.B.** It is bad practice to commit credentials to source control. This repo is to allow for reviewing the tutorial by Michał Krakiewicz. Any repo based off this one must ensure that the `.env` file is not committed to source control. 

# Running

## CLI

Compiling the project in watch mode: `npm run watch`

Running the application: `npm start`

Running the tests: `npm test`

## VS Code launch configurations (including debugging)
Launch configurations have been added for VS Code which allow for debugging the main application, as well as the tests. Simply open the `di_bot/` directory in VS Code, navigate to the Run tab (with a debugging icon) and select the desired action and press the play button.

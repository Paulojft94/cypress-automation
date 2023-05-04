# cypress-automation

cypress open
Now you can open Cypress from your project root one of the following ways:

Using npx

Note: npx is included with npm > v5.2 or can be installed separately.

npx cypress open

Or by using yarn

yarn run cypress open

The long way with the full path

./node_modules/.bin/cypress open

Or with the shortcut using npm bin

$(npm bin)/cypress open

After a moment, the Cypress Launchpad will open.

Adding npm Scripts
While there's nothing wrong with writing out the full path to the Cypress executable each time, it's much easier and clearer to add Cypress commands to the scripts field in your package.json file.

{
"scripts": {
"cypress:open": "cypress open"
}
}

Now you can invoke the command from your project root like so:

npm run cypress:open

...and Cypress will open right up for you.

Coffeetape
----------

Run [tape](https://github.com/substack/tape) tests written in coffeescript!

To install: `npm install -g coffeetape`

The command works exactly the same as the regular `tape` runner, just do `coffeetape test/*.coffee` to run your tests. You can pipe `coffeetape` into any standard tap reporter as you would expect.

To write your tests, `require('tape')` and use it exactly like you would if you were writing your tests in javascript. You'll get the same API if you `require()` coffeetape, but it's not recommended.

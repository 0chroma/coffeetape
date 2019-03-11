# Literate CoffeeScript test

	tape = require 'tape'

	add = (a, b)-> a + b

## Test

	tape 'Literate CoffeeScript', (t)->
		t.plan 1

		t.equal add(1, 2), 3, '1 + 2 = 3'

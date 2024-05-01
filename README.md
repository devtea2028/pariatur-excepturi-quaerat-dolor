# @devtea2028/pariatur-excepturi-quaerat-dolor

Remove one or more elements from an array by value

## Installation

	// npm
	$ npm install @devtea2028/pariatur-excepturi-quaerat-dolor

## Usage

	var removeValue = require('@devtea2028/pariatur-excepturi-quaerat-dolor');

	// as a function
	removeValue([ 'apple', 'lemon', 'banana', 'lemon' ], 'lemon'); // [ 'apple', 'banana' ]

	removeValue([ 'apple', 'lemon', 'banana', 'lemon' ], 'lemon', 1); // [ 'apple', 'banana', 'lemon' ]

	// as a method
	Array.prototype.remove = removeValue;

	var list = [ 'apple', 'lemon', 'banana' ];

	list.remove('banana');
	list; // [ 'apple', 'lemon' ]

	Alters the array "by reference" and returns the array.

## License

MIT
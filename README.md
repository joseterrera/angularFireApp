# angularfire-slack

This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.11.1.

## Build & development

Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `grunt test` will run the unit tests with karma.

some notes:

ui-router embraces the machine nature of a routine system. It allows you to define states, and transition your application to those states.
example of states:
$stateProvider is used to define states.
home is a parent state
ui-view will be populated with 3 child states.


ui-router supports multiple views and each can have its own corresponding controller so that each of these regions can be encapsulated and reused throughout the application if needed.
It allows to better bring pieces together or break them apart as needed to meet requirements.

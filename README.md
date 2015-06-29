## Ember Snippets

Ember.js ES6 snippets for Atom editor (ex: ember-cli, ember-app-kit)

## Installation

Run the following command:

```sh
apm install ember-snippets
```

Then reload your Atom.


## Usage

#### Modules

- `active-adapter` ⇥
- `active-serializer` ⇥
- `adapter` ⇥
- `arr-controller` ⇥
- `component` ⇥
- `controller` ⇥
- `helper` ⇥ (uses >= 1.13.x Ember.Helper)
- `bound-helper` ⇥ (DEPRECATED: Ember.Handlebars.makeBoundHelper)
- `initializer` ⇥
- `mixin` ⇥
- `model` ⇥
- `object` ⇥
- `route` ⇥
- `serializer` ⇥
- `transform` ⇥
- `utility` ⇥
- `view` ⇥

Example output for `controller` ⇥

Javascript:
```js
import Ember from 'ember';

export default Ember.Controller.extend({
	// body
});
```

CoffeeScript:
```coffee
NameController = Ember.Controller.extend
	# body

`export default NameController`
```

#### Properties

Used inside Ember objects

- `property` ⇥
- `observer` ⇥
- `on` ⇥
- `actions` ⇥
- `alias` ⇥

Example output for `observer` ⇥

JavaScript:
```js
fooChanged: Ember.observer('foo', function() {
	// body
}),
```

CoffeeScript:
```coffee
fooChanged: Ember.observer 'foo', ->
	# body
```


#### Functions

- `find` ⇥
- `find-id` ⇥
- `run` ⇥

##### Enumerables
- `for-each` ⇥
- `filter` ⇥
- `filter-by` ⇥
- `map` ⇥
- `map-by` ⇥
- `every` ⇥
- `is-every` ⇥
- `some` ⇥
- `is-any` ⇥
- `to-array` ⇥
- `first-object` ⇥
- `last-object` ⇥

##### Logger
- `logger-debug` ⇥
- `logger-error` ⇥
- `logger-info` ⇥
- `logger-log` ⇥
- `logger-warn` ⇥

##### Test Helpers
- `visit` ⇥
- `fill-in` ⇥
- `click` ⇥
- `key-event` ⇥
- `trigger-event` ⇥
- `find-element` ⇥
- `and-then` ⇥

Example output for `find` ⇥

JavaScript:
```js
this.store.find('post');
```

CoffeeScript:
```coffee
this.store.find 'post'
```

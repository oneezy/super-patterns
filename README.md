
<!---

This README is automatically generated from the comments in these files:
super-patterns.html

Edit those files, and our readme bot will duplicate them over here!
Edit this file, and the bot will squash your changes :)

The bot does some handling of markdown. Please file a bug if it does the wrong
thing! https://github.com/PolymerLabs/tedium/issues

-->

[![Build status](https://travis-ci.org/oneezy/super-patterns.svg?branch=master)](https://travis-ci.org/oneezy/super-patterns)

_[Demo and API docs](https://elements.polymer-project.org/elements/super-patterns)_


##&lt;super-patterns&gt;

`super-patterns` is a utility import that includes the definition for the `super-pattern` element, `super-patternset-svg` element, as well as an import for the default pattern set.

The `super-patterns` directory also includes imports for additional pattern sets that can be loaded into your project.

Example loading pattern set:

```html
<link rel="import" href="../super-patterns/maps-patterns.html">
```

To use an pattern from one of these sets, first prefix your `super-pattern` with the pattern set name, followed by a colon, ":", and then the pattern id.

Example using the directions-bus pattern from the maps pattern set:

```html
<super-pattern pattern="maps:directions-bus"></super-pattern>
```

To load a subset of patterns from one of the default `super-patterns` sets, you can
use the [poly-pattern](https://poly-pattern.appspot.com/) tool. It allows you
to select individual patterns, and creates an patternset from them that you can
use directly in your elements.

See [super-pattern](./super-pattern) for more information about working with patterns.

See [super-patternset](./super-patternset) and [super-patternset-svg](./super-patternset-svg) for more information about how to create a custom patternset.



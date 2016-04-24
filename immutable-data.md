### Immutable Data


#### Immutable Data Structures

- **Immutable.js**  
  https://facebook.github.io/immutable-js/  
  Fully-featured data structures library that uses advanced internal data storage to efficiently manage modified references.  Very widely used, but also rather complex.
  
- **seamless-immutable**  
  https://github.com/rtfeldman/seamless-immutable  
  Immutable data structures for JavaScript which are backwards-compatible with normal JS Arrays and Objects.  Uses freezing.
  
- **redux-tcomb**  
  https://github.com/gcanti/redux-tcomb  
  Immutable and type-checked state and actions for Redux (built on tcomb library)
  
- **immu**  
  https://github.com/scottcorgan/immu  
  A TINY, fail-fast, lazy, "naked", simple immutable Javascript objects library.
  
- **icedam**  
  https://github.com/winkler1/icedam  
  Ice Dam: a very lightweight library to freeze data. Data is frozen at the edge, where your Flux container sends it to views.
  
- **updeep**  
  https://github.com/substantial/updeep  
  Easily update nested frozen objects and arrays in a declarative and immutable manner.
  
- **icepick**  
  https://github.com/aearly/icepick  
  Utilities for treating frozen JavaScript objects as persistent immutable collections

#### Immutable Update Utilities


- **immutable-ops**  
  https://github.com/tommikaikkonen/immutable-ops  
A collection of functions to perform immutable operations on plain JavaScript objects and arrays.  Like updeep but with batched mutations and no freezing.  Like icepick, but with batched mutations and a curried API that puts the target object as the last argument. No freezing.

- **Redecorate**  
  https://github.com/Wildhoney/Redecorate  
  Simple module for reducing immutable nested properties in Redux applications.  
  
- **object-path-immutable**  
  https://github.com/mariocasciaro/object-path-immutable  
  Modify deep object properties without modifying the original object (immutability). Works great with React and Redux.
  
- **immutable-path**  
  https://github.com/baptistemanson/immutable-path  
  Immutable path is a simple micro library providing js object selectors and modifiers.  Stick to immutability: modification always returns a new instance of the object.  Free optin and optout: no need to wrap all your plain objects in classes, no init.

- **update-in**  
  https://github.com/dustingetz/update-in/  
  Persistent functional object updates on vanilla js data structures (wraps react-addons-update)
  
- **dot-prop-immutable**  
  https://github.com/debitoor/dot-prop-immutable  
  The motivation for this module is to have a simple utility for changing state in a React-Redux application without mutate existing state of plain JavaScript objects.
  
- **Sprout**  
  https://github.com/herrstucki/sprout/  
  Sprout provides a set of functions to help you work with nested data without all the headaches. Sprout never mutates the original data but returns new versions. This way, plain JavaScript objects (and arrays) can be effectively treated as if they were immutable.
  
- **Scour**  
  https://github.com/rstacruz/scour  
  Traverse objects and arrays immutably.  Scour is a general-purpose library for dealing with JSON trees.  Use it to: manage your Redux datastore; provide a model layer to access data in your single-page app; navigate a large JSON tree easily; rejoice in having a lightweight alternative to Immutable.js.
  
- **Timm**  
  https://github.com/guigrpa/timm  
  Immutability helpers with fast reads and acceptable writes.  Timm's approach: use plain objects and arrays and provide simple mutation functions that will probably not handle all edge cases.
  
- **emerge**  
  https://github.com/Mitranim/emerge  
  Utilities for creating and merging immutable data trees. Friendly to functional programming. Only plain JS objects, no custom classes, no OOP, bring your own data. 
  
- **reduxr-reducer-helpers**  
  https://github.com/chrisdavies/reduxr-reducer-helpers  
  A utility to handle common array manipulation reducer functions.
  
- **immutability-helper**  
  https://github.com/kolodny/immutability-helper  
  "React Immutability Helpers" most likely are [going to be deprecated](https://github.com/kolodny/immutability-helper/issues/1). This library is a drop-in replacement for `react-addons-update` that in addition allows you to extend its functionality.

- **no-mutate**  
  https://github.com/otissv/no-mutate  
  Immutable data structures and methods for plain JavaScript arrays

#### Immutable/Redux Interop

- **redux-immutable**  
  https://github.com/gajus/redux-immutable  
  redux-immutable is used to create an equivalent function of Redux combineReducers that works with Immutable.js state.

- **immutable-redux**  
  https://github.com/unindented/immutable-redux  
  Provides utilities for dealing with Immutable data structures in Redux.
  
- **redux-immutablejs**  
  https://github.com/indexiatech/redux-immutablejs  
  This is a small library that aims to provide integration tools between Redux & ImmutableJs that fully conforms Redux actions & reducers standards.
  
- **redux-immutable-utils**  
  https://github.com/aparticka/redux-immutable-utils  
  Utilities for using Immutable with Redux
  
- **immutable-reducers**  
  https://github.com/phuu/immutable-reducers  
  Create reducers for immutable data structures.

- **redux-seamless-reducers**  
  https://github.com/mrydengren/redux-seamless-reducers  
  Integrate seamless-immutable with Redux
  
- **redux-immutable-combine-reducers**  
  https://github.com/dustinspecker/redux-immutable-combine-reducers  
  A Redux combineReducers that returns an Immutable Map
  
- **Redux Immutable to JS**  
  https://github.com/nakamura-to/redux-immutable-to-js  
  Redux Immutable to JS allows you to convert immutable objects to JS objects automatically when Redux state is required outside reducers.
  
- **redux-tcomb-actions**  
  https://gitlab.com/zdragnar/redux-tcomb-actions  
  This module presents a simple way to generate action creators that provide a bit of type safety via tcomb.

- **node-dux**  
  https://github.com/eknkc/node-dux  
  Seamless-Immutable Redux helpers


#### Alternate Data Management Concepts

- **redux-orm**  
  https://github.com/tommikaikkonen/redux-orm  
  A small, simple and immutable ORM to manage relational data in your Redux store. Provides a Model-like interface on top of a portion of your store, allowing you to define relations between Models, store values as "tables" in your state, and make immutable updates by assigning values to Model fields.

- **reduxdb**  
  https://github.com/wizawu/reduxdb  
  Redux with MongoDB-like API.  Dispatches internal Redux actions in response to API calls like `db.someCollection.insert({id : 1, name "abc"})`.
  
- **redux-schema**  
  https://github.com/ddsol/redux-schema  
  Automatic actions, reducers and validation for Redux.  Designed to make using the immutable state easy to use while keeping the state serializable.
  
- **Vry**  
  https://github.com/JaapRood/vry  
  Data modeling with Immutable.js designed for use with Redux-like architectures.  Defining models using Immutable.js, making it easier to define defaults, parsing, serialisation, merging, identifiying entities, etc. Models are stateless (anaemic), meaning the instances (Immutable.Maps) are passed to the Model's methods as the first argument and a new / updated version is returned. This makes them a great fit to implement Redux reducers.

- **Datascript**  
  https://github.com/tonsky/datascript  
  Immutable database and Datalog query engine for Clojure, ClojureScript and JS

- **jseg**  
  https://github.com/brandonbloom/jseg  
  A super simple, in-memory, JS graph database.

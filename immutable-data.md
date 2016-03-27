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

#### Immutable Update Utilities


- **immutable-ops**  
  https://github.com/tommikaikkonen/immutable-ops  
A collection of functions to perform immutable operations on plain JavaScript objects and arrays.  Like updeep but with batched mutations and no freezing.  Like icepick, but with batched mutations and a curried API that puts the target object as the last argument. No freezing.

- **Redecorate**  
  https://github.com/Wildhoney/Redecorate  
  Simple module for reducing immutable nested properties in Redux applications.  

- **reduxr-reducer-helpers**  
  https://github.com/chrisdavies/reduxr-reducer-helpers  
  A utility to handle common array manipulation reducer functions.
  
- **updeep**  
  https://github.com/substantial/updeep  
  Easily update nested frozen objects and arrays in a declarative and immutable manner.
  
- **icedam**  
  https://github.com/winkler1/icedam  
  Ice Dam: a very lightweight library to freeze data. Data is frozen at the edge, where your Flux container sends it to views.


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


#### Alternate Data Management Concepts

- **redux-orm**  
  https://github.com/tommikaikkonen/redux-orm  
  A small, simple and immutable ORM to manage relational data in your Redux store. Provides a Model-like interface on top of a portion of your store, allowing you to define relations between Models, store values as "tables" in your state, and make immutable updates by assigning values to Model fields.

- **reduxdb**  
  https://github.com/wizawu/reduxdb  
  Redux with MongoDB-like API.  Dispatches internal Redux actions in response to API calls like `db.someCollection.insert({id : 1, name "abc"})`.
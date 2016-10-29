### Action/Reducer/Constant Generators

- Related pages:
  - [Reducers](reducers.md): includes libraries that wrap or create reducers
  - [Actions](actions.md): includes libraries that wrap or create actions


#### Boilerplate Reduction and Simplification

- **redux-act**  
  https://github.com/pauldijou/redux-act  
  An opinionated lib to create actions and reducers for Redux. The main goal is to use actions themselves as references inside the reducers rather than string constants.

- **simpleRedux**  
  https://github.com/philholden/simpleRedux  
  Reduce boilerplate for Redux reducers with dumb actions, create actionCreators, constants and reducers in a single file, actionCreator names are derived by camelCasing the CONSTANT_CASE names.

- **redux-chainsaw**  
  https://github.com/jhsu/redux-chainsaw  
  Allows you to specify action creators and reducers in a tree structure. The keys map to action types.
  
- **redux-reaction**  
  https://github.com/rrdelaney/redux-reaction  
  Goes one step further than redux-actions by placing your actions and reducers in the same place
  
- **Flambeau**  
  https://github.com/BurntCaramel/flambeau  
  Opinionated Redux additions: declarative, pleasant action creators, reducer encapsulation, async support
  
- **redux-dispatcher-reducer**  
  https://github.com/stevenla/redux-dispatcher-reducer  
  Reduce boilerplate in your redux code by using auto-generated action creators that automatically map to reducers

- **dead-simple-redux-helper**  
  https://github.com/armed/dead-simple-redux-helper  
  Dead simple redux helper for actions and reducers
  
- **actionize**  
  https://github.com/aol/actionize  
  Actionize helps you build Redux reducers without having to write large switch statements to handle actions or create action factories to call them. Actionize maintains a set of reducer names and ensures they are unique; this ensures all actions have unique names for dispatching.
  
- **rehash**  
  https://github.com/sodiumjoe/rehash  
  A set of utilities to generate an initial state, a reducer, and an action creator tree for use with redux.
  
- **redux-utils**  
  https://github.com/mindfront/redux-utils  
  Functions for creating and composing reducers and middleware efficiently
  
- **redux-code-generator**  
  https://github.com/jermspeaks/redux-code-generator  
  Pass a yaml file and the generator spits out action, reducer, and test files. Tests are written for Mocha.
  
- **reduxsauce**  
  https://github.com/skellock/reduxsauce  
  Provides a few tools for working with Redux-based codebases.    
  
- **Redux Factory**  
  https://github.com/roblafeve/redux-factory  
  Composable, curried factory for creating Redux reducers and actions. Being curried, you can supply an initial state and define your actions, but omit the prefix argument that is required to finally generate your actionCreator and reducer functions. Doing this allows you to export a base configuration to be used in any number of distinct portions of your state tree.
  
- **redux-setters**  
  https://github.com/jedwards1211/redux-setters  
  Convenient action creator creators for setting fields in redux state
  
- **Redux Action Schema**  
  https://github.com/modernserf/redux-action-schema  
  Redux Action Schema is a library for managing actions in Redux apps. It is a replacement for the constants file, providing stronger type guarantees while reducing boilerplate.
  
- **actionsreducer**  
  https://github.com/Xananax/actionsreducer  
  Simplifies the creation of actions, state, and reducers, and the creation of async actions. Return values are automatically re-assigned to state at the right location, no need for reducers composition.
  
- **redux-standard-actions**  
  https://github.com/yangmillstheory/redux-standard-actions  
  Flux Standard Action utilities for Redux.
  
- **redux-factories**  
  https://github.com/zxdong262/redux-factories  
  A factory lib to produce redux constants and reducers of certain format.

- **cx-redux-utils**  
  https://github.com/crosschx/cx-redux-utils  
  Simple redux boilerplate reduction lib with maximum api clarity as the primary concern.
  
- **redux-action-tools**  
  https://github.com/kpaxqin/redux-action-tools  
  Light-weight action tools with async and optimistic update support, inspired by redux-actions
  
- **redux-local-scope**  
  https://github.com/mgcrea/redux-local-scope  
  Locally scope your redux store modules (eg. types, actions, reducers) to easily reuse them.
  
- **redux-rsi**  
  https://github.com/civicsource/redux-rsi  
  Utility & helper functions for reducing the (already pretty minimal) boilerplate necessary when creating redux reducers & actions.
  
- **redux-action-man**  
  https://github.com/anubhavgupta/redux-action-man  
  Utilities for generating scoped/hierarchical actions with reducers
  
- **Fredux**  
  https://github.com/trabe/fredux  
  https://github.com/trabe/fredux-api-utils  
  Fredux is a utility library to make the development process of redux applications faster and easier. Fredux provides some conventions and tools to create actions which follows some standard structure, create asynchronous actions, and handle pending promise actions when the context of the application changes like in a page navigation.
  
- **redux-routine**  
  https://github.com/ezhikov/redux-routine  
  Set of small utils for creation of basic redux routines as collection reducer (uses Map for collection state), item reducer, actionCreators and basic action types (ADD, REMOVE, CHANGE)
  
- **f1-redux-utils**  
  https://github.com/nicocrm/f1-redux-utils  
  Utility functions for generating actions, creating containers that dispatch actions on mount, and creating reducers that handle prefixed actions
  
  
#### Network Requests and APIs

- **redux-act-async**  
  https://github.com/FredericHeem/redux-act-async  
  Create async actions based on redux-act

- **redux-rest**  
  https://github.com/Kvoti/redux-rest  
  Automatically create Flux action constants, action creators and Redux reducers for your REST API.
  
- **redux-api**  
  https://github.com/lexich/redux-api  
  redux-api solves problem of writing client for communicating with backend. It generates actions and reducers for making ajax call to API endpoints.  Inspired by redux-rest.
  
- **redux-resource**  
  https://github.com/jfairbank/redux-resource  
  Easily create actions for managing server resources like fetching, creating, or updating. Provide action types used in your reducer function for updating your redux store based on results from the server.
  
- **redux-json-api**  
  https://github.com/dixieio/redux-json-api  
  Redux actions, action creators and reducers to make life with JSON APIs a breeze.

- **redux-async-utils**  
  https://github.com/LucaColonnello/redux-async-utils  
  A little utility to know async actions' state in a redux application

- **redux-promise-reducer**  
  https://github.com/rjbma/redux-promise-reducer  
  Easily integrate with redux-promise-middleware.  Create actions with createPromiseAction, which are handled by the middleware, which dispatches new actions when the status of the promise changes.
  
- **redux-utils**  
  https://github.com/newtack/redux-utils  
  Redux-utils makes it easy to combine redux and immutableJS as well as make api calls using FSA conventions.

- **redux-async-collection**  
  https://github.com/QubitProducts/redux-async-collection  
  Creates a reducer, immutable state and actions for an async collection
  
- **redux-reqhelper**  
  https://github.com/ophite/redux-reqhelper  
  Helper for processing requests in redux (work with actions, reducers, selectors)
  
- **redux-rest-resource**  
  https://github.com/mgcrea/redux-rest-resource  
  Generate types, actions and reducers to easily interact with a REST API

- **giadc-redux-json-api**  
  https://github.com/giadc/giadc-redux-json-api  
  A package for consuming and accessing JSON API data with Redux
  
- **redux-request**  
  https://github.com/kongdigital/redux-request  
  Simplified AJAX calls using SuperAgent and Redux-Thunk.  Redux-Request simplifies Restful API calls using redux. It follows the convention of "configuration" over "code" and is designed for applications that make a lot of API calls.
  
- **redux-fetch-helpers**  
  https://github.com/alexjg/redux-fetch-helpers  
  First stab at a few helpers to remove some of the boilerplate when interacting with rest APIs from redux.
  
- **redux-action-api-utils**  
  https://github.com/APSL/redux-action-api-utils  
  Redux actions utility for creating and handling REST API requests
  
- **redux-request-state**  
  https://github.com/alanzanattadev/redux-request-state  
  Redux utils to handle easily requests state and display of components based on it 
  
- **redux-request-utils**  
  https://github.com/rockingskier/redux-request-utils  
  Utility functions to generate network-related actions and sagas, and execute the requests
  
- **redux-superapi**  
  https://github.com/kayak/redux-superapi  
  redux-superapi generates actions and reducers for communicating with a REST backend. Its API is inspired from redux-api, and it uses axios for making the actual AJAX calls. Its goal is short, extensible and highly-readable code.
  
- **redux-apist**  
  https://github.com/exeto/redux-apist  
  Create API-related actions for Redux-Thunk
  
- **redux-jsonapi**  
  https://github.com/andyhite/redux-jsonapi  
  Redux JSON:API is a collection of actions and reducers for Redux that help ease the use of a JSON:API compliant API.
  
- **redux-api-call**  
  https://github.com/tungv/redux-api-call  
  Redux utilities for API calls using fetch
  
- **redux-fetch-resource**  
  https://github.com/StickyCube/redux-fetch-resource  
  redux-fetch-resource is an attempt at a complete solution for making api requests in react/redux applications.

  
#### Other Code Structures

- **redux-duck**  
  https://github.com/sergiodxa/redux-duck  
  Helper function to create Redux modules using the ducks-modular-redux proposal 
  
- **redux-reusable**  
  https://github.com/furious-luke/redux-reusable  
  A small suite of utilities to assist in creating reusable Redux applications.
  
- **Tiny Duck**  
  https://github.com/LockedOn/tiny-duck  
  Tiny Duck is a small library that allows you to define small, reusable collections of reducer actions and compose them together.  Tiny Duck gives you high code reuse and testabilty for your redux reducers.  Tiny Duck was inspired from the pattern of erikras/ducks-modular-redux where you bundle all of your actions, action types and reducers in the one module.
  
- **redux-modules**  
  https://github.com/mboperator/redux-modules  
  A library that takes the Redux module concept to another level with: an intuitive way define actions and state transformations; propType style typechecking for action payloads; auto generated, camelCased action creators; auto prefixed action constants; and a decorator to easily drop module capabilities in to your view
    
- **purescript-redux-utils**  
  https://github.com/osener/purescript-redux-utils  
  Utilities for writing Redux actions and reducers in PureScript
  
- **redux-modules**  
  https://github.com/fullstackreact/redux-modules  
  The overall idea behind redux-modules is to build all of the corresponding redux functionality, constants, reducers, actions in a common location that makes it easy to understand the entire workflow common to a component of an application.  Redux modules is essentially a collection of helpers that provide functionality for common tasks related to using Redux.
  
- **modular-redux-thunk**  
  https://github.com/benbeadle/modular-redux-thunk  
  A ducks-inspired package to help organize actions, reducers, and selectors together.

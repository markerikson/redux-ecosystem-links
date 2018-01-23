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
  
- **redux-state-keys**  
  https://github.com/LFDM/redux-state-keys  
  This library tries to deal with the problem of writing a lot of repetitive boilerplate code, when you are trying to deal with several instances of a same type. Includes functions to generate selectors, action creators, and reducers that target a specific slice of state by name.
  
- **redux-seeds**  
  https://github.com/quinnnned/redux-seeds  
  Factories for Generating Common Redux State Trees
  
- **redux-reducer**  
  https://github.com/webdeveloperpr/redux-reducer  
  Generates prefixed actions and reducers
  
- **Redeclare**  
  https://github.com/modernserf/redeclare  
  Redeclare is an attempt to reduce the boilerplate of Redux configuration in a form that takes advantage of Redux’s best qualities. Its focused on creating types and schemas for actions and state that serve as both documentation and configuration, replacing the need for repetititve files full of constants and complex assemblages of helper functions.
  
- **redux-shuttle**  
  https://github.com/jaylone/redux-shuttle  
  A tool for bundling reducers, action types and actions when using redux and saga
  
- **redux-utils**  
  https://github.com/jcoreio/redux-utils  
  Functions for creating and composing reducers and middleware efficiently 
  
- **redux-duet**  
  https://github.com/jondot/redux-duet  
  Redux action and handlers together, alleviate boilerplate. 
  
- **zeal-redux-utils**  
  https://github.com/CodingZeal/zeal-redux-utils  
  Utility functions for creating actions types, creating FSA-compatible reducers, and globalizing selectors.

- **redux-candy**  
  https://github.com/inuscript/redux-candy  
  Generate updeep based reducer and compatible action creator.

- **redux-act-reducer**  
  https://github.com/hahoocn/redux-act-reducer  
  A lib to create both sync and async actions and reducers for Redux
  
- **redux-scc**  
  https://github.com/TheComfyChair/redux-scc  
  Redux store chunk creator.  It takes a defined structure and uses a set of 'behaviors' (a small collection of ways that a reducer can be updated) to create a set of actions and reducer responses that are each linked by a unique string. A set of action generators, selectors, and reducers are then returned.
  
- **redux-create**  
  https://github.com/marcelmokos/redux-create  
  Create reducers, action types and action creators
  
- **redux_helpers**  
  https://github.com/CurtisHumphrey/redux_helpers  
  Some small utilities to generate simple reducers and action creators
  
- **flow-redux-action-generator**  
  https://github.com/fc/flow-redux-action-generator  
  A proof-of-concept tool for generating action creators and reducers based on Flow types
  
- **async-action-creator**  
  https://github.com/goncy/async-action-creator  
  Generates action types and action creators for start/success/failure states
  
- **redux-shape**  
  https://github.com/awayisblue/redux-shape  
  A simple util for generating redux action & reducer by a state shape definition. 
  
- **Redux-Helpers**  
  https://github.com/AlexRobinson-/Redux-Helpers  
  Assorted utilities for generating action constants, single reducer, multi-reducers, and dynamic reducers
  
- **redux-ts-simple**  
  https://github.com/Cooke/redux-ts-simple  
  Yet another lib for creating typed actions and reducers. This library is FSA-compliant.
  
- **easy-redux**  
  https://github.com/welljs/easy-redux  
  Helpers to generate action creators and reducers
  
- **redux-dictator**  
  https://github.com/thekarel/redux-dictator  
  List your required state variables by name and get a reducer, actions and dispatch-to-props automagically. 88% less Redux boilerplate!  State variables named List get extra actions to easily add and remove items.
  
- **redux-toolbelt**  
  https://github.com/welldone-software/redux-toolbelt  
  A set of tools for quicker, easier and safer redux development.  Create FSA-compliant action creators, async action creators, and compose reducers.
  
- **redux-factories**  
  https://github.com/zxdong262/redux-factories  
  A factory lib to produce redux constants and reducers of certain format.
  
- **redux-motive**  
  https://github.com/loklaan/redux-motive  
  Simplify writing action creators, reducers and effects - without breaking redux. 
  
- **redux-utils**  
  https://github.com/graftss/redux-utils  
  A collection of utilities for generating actions, reducers, and tests
  
- **sleipnir**  
  https://github.com/benoneal/sleipnir  
  A convenience interface for Redux, to remove boilerplate and provide sensible asynchronous action handling.
  
- **redux-helpers**  
  https://github.com/sirqiao/redux-helpers  
  Utilities to create action types, action creators, and reducers for both sync and async actions
  
- **redux-tiles**  
  https://github.com/Bloomca/redux-tiles  
  This library tries to provide minimal abstraction on top of Redux, to allow easy composability, easy async requests, and sane testability.
  
- **redux-ts-simple**  
  https://github.com/Cooke/redux-ts-simple  
  Yet another lib for creating typed actions and reducers. This library is FSA-compliant.
  
- **redux-helpers**  
  https://github.com/mindbox-moscow/redux-helpers  
  Typed factories for your reducers and actions. 
  
- **redux-async-action-reducer**  
  https://github.com/neolivz/redux-async-action-reducer  
  Simple redux action creation and reducer wrapper that makes creating and handling asynchronous and synchronous wrapper easier. It's completely written with type safety in mind, with typescript.
  
- **reduxec**  
  https://github.com/Noviel/reduxec  
  Create reusable, targeted actions and reducers for Redux
  
- **redux-namespaces**  
  https://github.com/9technology/redux-namespaces  
  Utilities for generating namespaced actions, reducers, and state.
  
- **simr**  
  https://github.com/dalexj/simr  
  A library for reducing common functionality in Redux reducers, with pre-generated reducers and action creators that take arguments.
  
- **redux-enjoy-helpers**  
  https://github.com/ya-kostik/redux-enjoy-helpers  
  Utilities for action type creation, creating reducers with reset abilities, and updating arrays
  
- **redux-thunk-action-reducer**  
  https://github.com/neolivz/redux-async-action-reducer  
  Simple redux action creation and reducer wrapper that makes creating and handling asynchronous and synchronous actions easier.
  
- **redux-typed-action-reducer**  
  https://github.com/slivcode/redux-typed-action-reducer  
  A utility for generated TypeScript-typed actions and reducers
  
- **redux-belt**  
  https://github.com/store2be/redux-belt  
  Provides opinionated utilities for generating consistent action creators, as well as action creators and reducers for CRUD operations.
  
- **trampss-redux-factory**  
  https://github.com/Trampss/trampss-redux-factory  
  Factory of Redux reducers and their associated actions and selectors - creates generic reducers, actions and selectors in two lines.
  
- **redux-composable**  
  https://github.com/aakashns/redux-composable  
  Utilities and higher order functions for reducer composition and reuse
  
- **redux-less**  
  https://github.com/lovetingyuan/redux-less  
  Write action creators and reducers with less boilerplate, inspired by Mirror
  
- **redux-enhancer**  
  https://github.com/bamlab/redux-enhancer  
  Utilities to generate action types, action creators, and reducers for async loading states (start, success, failed, reset)
  
- **redux-sketch**  
  https://github.com/NirlStudio/redux-sketch  
  A redux state sketcher to generate a state definition with initial state, action types, action creators and reducer.
  
- **redux-defmap**  
  https://github.com/loehx/redux-defmap  
  Bring structure to your redux actions and reducers.  Accepts lookup tables, simplifies action creators, and validates payloads.
  
- **redux-declare**  
  https://github.com/zhujinxuan/redux-declare  
  Create declarative actions and reducers for synchronous operations, and simplify async actions.
  
- **@articulate/ducks**  
  https://github.com/articulate/ducks  
  A collection of Redux helper functions.  Curried action creator utils, middleware to dispatch functors, reducer lookup table utils, and more.
  
- **redux-msg**  
  https://github.com/argshook/redux-msg  
  Utility functions to help DRY up your Redux code.  Create reducers, selectors, state, and more.
  
- **redux-act-array-async**  
  https://github.com/jiang-12196/redux-act-array-async  
  Create async multi actions and reducers based on redux-act
  
- **atomic-redux**  
  https://github.com/brietsparks/atomic-redux  
  Building blocks for composing normalized collection-based state  
  
- **catalyst-redux**  
  https://github.com/friendsoftheweb/catalyst-redux  
  Allows generating action creators/reducers as "operations" for sync and async behavior, and composition of operations into larger "modules".  Also provides "resource modules" for interacting with a JSON API.
  
- **redux-processor**  
  https://github.com/nicholasrq/redux-processor  
  A tool to help generate actions, reducers, and initial state all together.
  
- **redux-boilerplate-reducer**  
  https://github.com/mimshwright/redux-boilerplate-reducer  
  Quickly create bundles of action types, action creators, and reducers with a few lines of code.
  
- **react-apollo-redux**  
  https://github.com/Drawbotics/react-apollo-redux 
  A small wrapper to automatically dispatch actions in response to apollo mutations.


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
  
- **redux-fetch-resource**  
  https://github.com/StickyCube/redux-fetch-resource  
  redux-fetch-resource is an attempt at a complete solution for making api requests in react/redux applications.
  
- **redux-restapi**  
  https://github.com/ghalex/redux-restapi  
  redux-restapi is an utility for integrating a REST api with Redux. It helps you, to easily integrate your calls to a REST api with your store. It generates actions and reducer for making the calls to the server and can easly be combined with your actions.
  
- **magic-redux-generator**  
  https://github.com/luisfuertes/magic-redux-generator  
  Utils to generate types and action creators for various network requests
  
- **redux-thunk-rest**  
  https://github.com/rtablada/redux-thunk-rest  
  This package is helps remove some of the boilerplate cruft for creating RESTful actions, action creators, and reducers for Redux with Redux Thunk.

- **redux-rest-factories**  
  https://github.com/lohfu/redux-rest-factories  
  Thunk actions and reducers for handling data from a REST API
  
- **redux-easy-async**  
  https://github.com/evanhobbs/redux-easy-async#motivation  
  Redux Easy Async makes handling asynchronous actions, such as API requests, simple, reliable, and powerful.
  
- **redux-simple-api**  
  https://github.com/kazagkazag/redux-simple-api  
  A library that helps handling requests with redux. It is common problem for many developers - a lot of code required to handle asynchronous actions. You can mitigate it using redux-thunk and redux-simple-api.
  
- **redux-fetch-actions**  
  https://github.com/deptno/redux-fetch-actions  
  Functions for doing REST API calls and dispatching actions
  
- **redux-hammock**  
  https://github.com/mitodl/redux-hammock  
  Hammock is a library which allows you to abstract away some details and boilerplate when using redux and fetch with REST endpoints. You just write a little configuration object and hammock generates actions and a reducer for you!
  
- **reduxwork**  
  https://github.com/michalkow/reduxwork  
  A small Redux framework for creating actions and reducers that work with AJAX or WebSocket functions and create real-time apps.
  
- **redux-arc**  
  https://github.com/viniciusdacal/redux-arc  
  A dependency free, 2kb lib to handle async request actions and reducers in redux.
  
- **r3-library**  
  https://github.com/cassaram09/r3-library  
  r3-library (short for React-Redux-Resource) is a small library to handle remote API resources in a CRUD React-Redux application more efficiently. This library creates a new resource predefined with a set of RESTful CRUD actions, but also offers flexibility for custom actions.

- **redux-from-to**  
  https://github.com/bratushka/redux-from-to  
  redux-from-to carries resources from APIs to your redux store.  Stop writing the same old action and reducer logic and DRY up your redux application.
  
- **redux-simple-api**  
  https://github.com/kazagkazag/redux-simple-api  
  Redux Simple Api (RSA) is a library that helps handling requests with redux. It is common problem for many developers - a lot of code required to handle asynchronous actions. You can mitigate it using redux-thunk and redux-simple-api.
  
- **redux-httprequest**  
  https://github.com/henit/redux-httprequest  
  Redux actions & reducer for making http requests
  
- **redux-store-api-helpers**  
   https://github.com/martynovs/redux-store-api-helpers  
   Action creators and middleware for making API calls with Axios
  
- **redux-fetch-duck**  
  https://github.com/ivanwolf15/redux-fetch-duck  
  Simple and flexible API for creating a redux duck to manage a single fetch request, features loading and error states.
  
- **redux-standard-reducers**  
  https://github.com/sagiavinash/redux-standard-reducers  
  A set of utilities to create reducers that are Flux Standard Data Storage compliant.
  
- **redux-rest-fetcher**  
  https://github.com/klooperator/redux-rest-fetcher  
  Small library for creating API endpoint calls and other fetch calls. Can be used in any project, but is meant to be used with redux to dispatch results to store.

  
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
    
- **purescript-redux-utils**  
  https://github.com/osener/purescript-redux-utils  
  Utilities for writing Redux actions and reducers in PureScript
  
- **redux-modules**  
  https://github.com/fullstackreact/redux-modules  
  The overall idea behind redux-modules is to build all of the corresponding redux functionality, constants, reducers, actions in a common location that makes it easy to understand the entire workflow common to a component of an application.  Redux modules is essentially a collection of helpers that provide functionality for common tasks related to using Redux.
  
- **modular-redux-thunk**  
  https://github.com/benbeadle/modular-redux-thunk  
  A ducks-inspired package to help organize actions, reducers, and selectors together.
  
- **re-ducks**  
  https://github.com/alexnm/re-ducks  
  An attempt to extend the original proposal for redux modular architecture

- **reredeux**  
  https://github.com/MrRacoon/reredeux  
  Generate redux state trees, selectors, and actions, using a variation on ducks
  
- **cooldux**  
  https://github.com/iceddev/cooldux  
  A few very simple helpers for the redux ducks pattern
  
- **Duckfactory**  
  https://github.com/espen42/duckfactory  
  Simple creation and use of redux ducks.
  
- **Goosefactory**  
  https://github.com/espen42/goosefactory  
  Simple creation and use of 'geese' - a redux-saga analogy to redux ducks.
  
- **redux-duckling**  
  https://github.com/pghalliday/redux-duckling  
  The redux-duckling library implements an approach that effectively manages namespacing, composing and combining reusable duck-like modules, which due to their smaller nature we refer to as ducklings.
  
- **redux-typed-ducks**  
  https://github.com/mhoyer/redux-typed-ducks  
  Helper for using ducks in conjunction with redux having typing support.
  
- **moducks**  
  https://github.com/moducks/moducks  
  Extremely simple Ducks module provider for the stack of Redux + Redux-Saga. 
  
- **extensible-duck**  
  https://github.com/investtools/extensible-duck  
  An implementation of the Ducks proposal. With this library you can create reusable and extensible ducks.
  
- **saga-duck**  
  https://github.com/cyrilluce/saga-duck  
  Extensible and composable duck for redux-saga
  
- **redux-structure-factory**  
  https://github.com/liebsoer/redux-structure-factory  
  Factory module to create a redux structure
  
- **redux-parts**  
  https://github.com/andreevWork/redux-parts  
  A tool to help recursively generate reducers and actions out of simpler "parts"
  
- **duxx**  
  https://github.com/enriquecaballero/duxx  
  Create simple fetch-and-set reducer duck bundles without the boilerplating 
  
- **redux-ducklings**  
  https://github.com/sammysaglam/redux-ducklings  
  Provides a helper function (createReduxDuckling) to spawn Redux Ducks as unique child instances called Ducklings.
  
- **super-duck**  
  https://github.com/2do2go/super-duck  
  Yet another library for generating Redux ducks
  
- **redux-lumbergh**  
  https://github.com/ImmoweltGroup/redux-lumbergh  
  Embrace best practices for Redux encapsulation.  Provides utilities for generating action constant / action creators / reducers, and combining ducks into a root reducer and root saga.

### Alternate Approaches and Variations

- **redux-controller**  
  https://github.com/lexich/redux-controller  
  redux-controller helps to generate controllers (functions) with access to (dispatch and getState) redux functionality without binding to React components.
  
- **react-redux-controller**  
  https://github.com/artsy/react-redux-controller  
  https://www.reddit.com/r/reactjs/comments/3z13qs/new_library_reactreduxcontroller/  
  Library for creating a controller layer to link React and Redux, on top of react-redux.
  
- **Redacs**  
  https://github.com/daniel-lundin/redacs  
  Experimental redux-like state management with actions and reducers combined into reducer actions
  
- **redux-store**  
  https://github.com/bingomanatee/redux-store  
  A store/action subsystem for redux.  
  
- **react-redux-connect-context**  
  https://github.com/qwtel/react-redux-connect-context  
  Enhanced version of redux' connect that puts action creators in the child context
  
- **redux-viewmodel**  
  https://github.com/tdzl2003/redux-viewmodel  
  React-ViewModel make it possible to write 'ViewModel' classes to reorganize code for reducer implement in Redux.
  
- **Replux**  
  https://github.com/gregthebusker/replux  
  Self contained components and enhancements for Redux
  
- **Redux Model Utilities**  
  https://github.com/jbellsey/redux-model-utils  
  A set of model-building utilities for Redux apps.  Atomic actions and reducers, easy connection to React components, direct read-only access to the model state, subscription change notifications.
  
- **Vada**  
  https://github.com/xogeny/vada  
  https://medium.com/@mtiller/encapsulating-application-logic-with-reactors-392635763e7  
  Code to support a viewless, action driven architecture
  
- **redux-apis**  
  https://github.com/Download/redux-apis  
  Create class-based APIs that hide the fact that Redux is being used.
  
- **redux-tree**  
  https://github.com/dashed/redux-tree  
  Organize your redux stores in a tree-like structure.  redux-trees are tree-like structured schemas where the leaves are either another redux-tree or a redux compatible reducer (not both).
  
- **modular-redux**  
  https://github.com/ariporad/modular-redux  
  Build completely modular applications with redux
  
- **redux-2way-binding**  
  https://github.com/roderickwang/redux-2way-binding  
  Build two way binding with Redux and Immutable.
  
- **redux-interactions**  
  https://github.com/convoyinc/redux-interactions  
  A streamlined approach to managing your Redux action creators and reducers.  These observations have landed us on a pattern where you group related action creators and reducers into a single file, which we call an interaction.
  
- **redux-simple**  
  https://github.com/barbuza/redux-simple  
  Batching react-redux alternative with reverse subscription order.  Exposes Provider and connect with api similar to react-redux
  
- **Gambit**  
  https://github.com/Ghirro/gambit  
  Gambit is a hyper-thin library designed to make building API driven apps with Redux/React easier. It is not a Redux replacement, it is a library built on top of Redux.
  
- **remerge**  
  https://github.com/siawyoung/remerge  
  The sole purpose of Remerge is to provide a consistent interface for defining and manipulating state. It's extremely easy and intuitive to use once you get the hang of it. While there is a slight learning curve, hopefully our examples will ease the learning process.  Although Remerge was built for use with Redux, it can also be used standalone.

- **two-way-rest**  
  https://github.com/l2silver/two-way-rest  
  A react-redux plugin that facilitates changes to the state and backend data sources.

- **Radical**  
  https://github.com/nathan-rice/radical  
  Radical is a client API framework, designed to simplify the creation and maintenance of React/Redux applications. Radical allows you to model your client API and state via the composition of Actions and Namespaces.

- **Tango**  
  https://github.com/Graf009/tango  
  Toolkit for building redux/react applications.  Easy to understand objects instead of crazy functional composition. Bundle groups of middleware, enhancers, and reducers together as "plugins". Dead simple Component API - use ES6 classes, bring back sane behavior, bind component functions scope to class (like old react), never write mapDispatchToProps or mapStateToProps.
  
- **Kea**  
  https://github.com/mariusandra/kea-logic  
  kea-logic lets you create logic stores, and access their contents from React components as props.  Logic stores consist of 1) actions, 2) reducers, 3) selectors and 4) optionally sagas.  Logic stores augment your components, are stored in redux, and are connected via ES6 imports.
  
- **redux-signals**  
  https://github.com/cerebral/redux-signals  
  The Cerebral signals running on Redux
  
- **redux-observe-store-path**  
  https://github.com/d6u/redux-observe-store-path  
  Efficient and descriptive Redux React binding.  Unlike connect in react-redux, redux-observe-store-path will update tree leaf component directly, rather than passing down props at each level. This way we can skip middle level components and directly update deeply nested components.
  
- **Redux Action Thunk**  
  https://github.com/ShMcK/redux-action-thunk  
  Move your actions & types into Redux middleware.  No more importing actions & types. Instead, register your actions on startup and call them by dispatching strings. Redux Action Thunk (RAT) allows you to write more modular Redux code.
  
- **redux-semantic-action-middleware**  
  https://github.com/diosmosis/redux-semantic-action-middleware  
  Redux middleware that lets you define actions as meaningful units, without OOP.
  
- **tinier**  
  https://github.com/zakandrewking/tinier  
  Simple views and bindings to redux, with d3.js in mind
  
- **socrates**  
  https://github.com/matthewmueller/socrates  
  Small (12kb), batteries-included redux stack to reduce boilerplate and promote good habits.
  
- **Strux**  
  https://github.com/jgnewman/strux  
  A layer on top of redux for describing data flow throughout your application in a revolutionary way.
  
- **react-relax**  
  https://github.com/musicglue/react-relax  
  A minimal way of providing redux state to react components that doesn't use context
  
- **redux-plus**  
  https://github.com/ashtonwar/redux-plus  
  The core of Redux is simple. But it comes with a big ecosystem, middleware, action creators, selectors and other things attached that slow down development - a single change in specs shouldn't require changes in 5+ locations to implement. redux-plus makes developers more productive by finding one place for all state-related code: the reducer.
  
- **Conventional Redux**  
  https://github.com/mjaneczek/conventional-redux  
  Make your redux more friendly by adding conventions and writing less code! Combine actions and reducers into a interactor class; Dispatch action in a interactorName:method format (eg. this.dispatch('counter:double')); Handle an action by defining methods in the interactor
  
- **react-redux-oop**  
  https://github.com/newtoncodes/react-redux-oop  
  OOP implementation of redux and react.  It uses plain react, redux and react-redux. No functionality is changed or added to these libraries. It's only a way to organize your app with a bunch of helpful classes. Also it solves the problem with multiple stores and binded action creators.
  
- **redux-store-element**  
  https://github.com/lastmjs/redux-store-element  
  A simple Polymer web component that allows a more declarative use of Redux.
  
- **redux-schema**  
  https://github.com/ddsol/redux-schema  
  https://github.com/ddsol/react-redux-schema  
  Automatic actions, reducers and validation for Redux.  Designed to make using the immutable state easy to use while keeping the state serializable.
  
- **react-redux-classconnect**  
  https://github.com/jondot/react-redux-classconnect  
  Remove cognitive load by moving prop mapping into the component, by using static method references.
  
- **easy-react-redux**  
  https://github.com/dai-shi/easy-react-redux  
  Yet another react redux integration only with stateless function components.
  
- **redux-action-object**  
  https://github.com/vasyas/redux-action-object  
  Defining your Redux reducers and actions using ES6 class syntax.
  
- **redux-entity-store**  
  https://github.com/vasyas/redux-entity-store  
  ORM-like API to access Redux store state
  
- **redux-virtual-dom**  
  https://github.com/subuta/redux-virtual-dom  
  react-redux for your vdom library.  Make your vdom-based development flow easy, with virtual-dom or snabbdom.  Convenient utility(only ~100 line) for Redux.  Automatically memoize your render function for better performance!

- **redux-smooth-bind-actioncreators**  
  https://github.com/dsacramone/redux-smooth-bind-actioncreators  
  Simple utility to faciliate mapping and binding action creators / states to classes.  Reduce the boilerplate of "mapStateToProps" and "mapDispatchToProps" !
  
- **Jumpsuit**  
  https://github.com/jumpsuit/jumpsuit  
  https://medium.com/@tannerlinsley/jumpsuit-react-redux-made-simple-e3186ba1b077  
  Jumpsuit is a powerful and extremely efficient Front-end framework & CLI. It is the fastest way to write scalable react/redux apps with the least overhead.  No boilerplate; Dedicated build system; Scaffolding tools; Minimal API; Simple and scalable state management based on Redux.
  
- **Jumpstate**  
  https://github.com/jumpsuit/jumpstate  
  Jumpstate is a dead-simple state machine for Redux and Vanilla JS that packs some serious power.  Extracted from the Jumpsuit library.

- **vidom**  
  https://github.com/dfilatov/vidom-redux  
  Redux bindings for Vidom
  
- **reduceless-connect**  
  https://github.com/anorudes/reduceless-connect  
  Easy change redux state for ui without creating constants and actions

- **redux-saga-models**  
  https://github.com/vshushkov/redux-saga-models  
  Library to build models layer backed with redux-saga
  
- **redux-easy-models**  
  https://github.com/machadogj/redux-easy-models  
  Easily define your models using standard redux libraries (redux, redux-actions, redux-thunk).
  
- **redux-entity**  
  https://github.com/lelandrichardson/redux-entity  
  An abstraction layer around handling normalized entity storage and data fetching with redux
  
- **redux-fp**  
  https://github.com/rvikmanis/redux-fp  
  Functional programming helpers for Redux.  Uses curried "action-first" reducers, known as "updaters", similar to Elm.
 
- **Relax**
  https://github.com/jayflaherty75/relax  
  Relax provides simple and familiar yet scalable organization of your React/Redux applications.
  
- **Feeble**  
  https://github.com/feeblejs/feeble  
  Feeble is a framework built on top of React/Redux/redux-saga which aims to make building React/Redux applications easier and better.  If you are familiar with React/Redux/redux-saga, you'll love Feeble
  
- **react-redux-stream**  
  https://github.com/noderaider/react-redux-stream  
  Streams a singleton selector result to one or more contexts (components or objects) within a react-redux application.
  
- **dva**
  https://github.com/dvajs/dva  
  https://github.com/dvajs/dva-core  
  https://medium.com/@chenchengpro/dva-1-0-a-lightweight-framework-based-on-react-redux-and-redux-saga-eeeecb7a481d  
  React and redux based, lightweight and elm-style framework. (Inspired by choo).
  
- **redux-config**  
  https://github.com/qftgtr/redux-config  
  Rapidly configure Redux or React Redux.
  
- **Realt**  
  https://github.com/Vnkitaev/realt  
  A new way to work with Redux inspired by Alt
  
- **redux-app-controller**  
  https://github.com/antonpkazakov/redux-app-controller  
  A JavaScript library based on React+Redux combination that allows you to make React-powered SPA based on controllers rather than separate action-creators, reducers and action handlers.
  
- **react-redux-connector**  
  https://github.com/akuzko/react-redux-connector  
  Object-oriented React binding for Redux
  
- **redux-branch**  
  https://github.com/stephenbunch/redux-branch  
  A library for defining "branches" - local stores whose state is merged on top of the parent.  This allows each component to have its own Redux store while still being able to interact with the parent store.
  
- **redux-with-selectors**  
  https://github.com/guillaumearm/redux-with-selectors  
  A redux store enhancer for adding selectors inside the store.  Provide a withSelectors function that take a schema of your selectors, a store and return a new enhanced store.  This will allow you to centralize all your selectors in the redux store, and call them by using getState()
  
- **Petiole**  
  https://github.com/ilkkahanninen/petiole  
  Petiole embraces the idea of Redux reducer bundles, better known as ducks, but takes them further with uniform construction function and throws support for selectors in. In Petiole these bundles are called leaves -- they are the leaf nodes (end-nodes) in our state tree.
  
- **react-redux-subscribe-while-mounted**  
  https://github.com/arnemahl/react-redux-subscribe-while-mounted  
  A utility method to make it easier to subscribe to a Redux store from a React component.
  
- **redux-retro**  
  https://github.com/bencompton/redux-retro  
  A Redux add-on that brings back the clean, minimal-boilerplate syntax you enjoyed with classic Flux libraries like Alt, Reflux, and Flummox, along with better TypeScript support
  
- **redux-quick-actions**  
  https://github.com/cashsun/redux-quick-action  
  Redux action/reducer wrapper that hides synchronous reducers implementation.  redux-quick-action helps abstract type strings, switch statements in reducers and many other implementation details away from you.
  
- **redux-model-s**  
  https://github.com/ophite/redux-model-s  
  Working with redux through models. Involve OOP in redux. Do it more power and add DRY.
  
- **feathersjs-redux-model**  
  https://github.com/Codaisseur/feathersjs-redux-model  
  FeathersJS client that hooks into your Redux store.  Create models that emit actions whenever the socket connection to the service receives any CRUD events.
  
- **redux-actionize**  
  https://github.com/anonmily/redux-actionize  
  Easier Redux Action/Reducer creation. Create actions and reducers all at once, in one place, for less duplication and cleaner, more readable code.   
  
- **react-redux-custom-store**  
  https://github.com/emmenko/react-redux-custom-store  
  Simple wrapper around react-redux. It allows to use different nested Providers by specifying a custom store name.
  
- **react-redux-model**  
  https://github.com/jhudson8/react-redux-model  
  Simple to use XHR fetching and model-oriented utility functions.  Most applications have common and consistent needs. Load data using XHR and know the fetch status so it can be represented with a loading indicator. This lib provides action creators, reducers and React component wrappers that work with each other to simplify and DRY up your code.
  
- **Classy-Redux**  
  https://github.com/machineghost/Classy-Redux/  
  An class-based system for creating Redux reducers 
  
- **redstate**  
  https://github.com/eisisig/redstate  
  Alternative redux api/usage.   Main purpose of playing around with this is to get rid of more of the "plumbings" needed when creating the "redux" part of our apps.  Easily call auto bound actions without importing or needing the dispatch method and enhanced reducer creator that has helper methods that we are always using
  
- **Redux-Jian**  
  https://github.com/xareelee/redux-jian  
  Redux-Jian is a library aiming to simplify how to use Redux. Jian means 'simple' or 'simplify'.  Declare mutators (action creators) in one singleton, and you can get a mutator by its name anywhere. It's highly decoupling and easy to use.  Bind mutators to Redux store once, and you'll no longer need to use mapDispatchToProps in the connect().

- **redux-scene**  
  https://github.com/ryanwade/redux-scene  
  React UI generated from redux state
  
- **duxtape**  
  https://github.com/brianneisler/duxtape  
  Module and util framework for redux. Introduces an abstract module construct for redux. Allows modularization of functionality and easy plug and play workflow
  
- **redux-kv**  
  https://github.com/watert/redux-kv  
  Key-value util component for redux and redux-react usage
  
- **react-redux-wire**  
  https://github.com/jide/react-redux-wire  
  Wire components directly to redux state without using containers.
  
- **Arco**  
  https://github.com/planttheidea/arco  
  A React+Redux framework with standards, conventions, and far less boilerplate
  
- **simple-react-redux**  
  https://github.com/nstraub/simple-react-redux  
  Connect state and actions to props declaratively 

- **redaction**  
  https://github.com/pavelivanov/redaction  
  Redux action creator without string constants and less magic 
  
- **Redux-Reduced-Actions**  
  https://github.com/PlumTreeSystems/Redux-Reduced-Actions  
  A middleware for dispatching actions which contain string lookup paths of data to update.
  
- **redux-global-selectors**  
  https://github.com/guillaumearm/redux-global-selectors  
  A redux store enhancer adding selectors inside the store.
  
- **react-redux-connect-helpers**  
  https://github.com/rongierlach/react-redux-connect-helpers  
  A helpful set of functions for connecting redux state to react components.
  
- **react-redux-connect**  
  https://github.com/afitiskin/react-redux-connect  
  Connect react components to redux store using component static props 
  
- **redux-object-connect**  
  https://github.com/alsiola/redux-object-connect  
  Wraps the connect function from react-redux to enable passing an object in place of a mapStateToProps function. 
  
- **Redux-store-emitter**  
  https://github.com/morulus/redux-store-emitter  
  Decoration for redux, that gives him the ability to distribute events.
  
- **redux-synapse**  
  https://github.com/glitch100/redux-synapse  
  redux-synapse is a library that is heavily inspired by react-redux and acts as an alternative for the binding of react components to the store in a more explicit manner. The primary difference is the nature in which each component must declare explicity what updates should affect the component via its higher order component; a synapse.
  
- **react-redux-propmap**  
  https://github.com/markkup/react-redux-propmap  
  Introduces a PropMap class to make connecting state and actions to components cleaner
  
- **redux-in-place**  
  https://github.com/gartz/redux-in-place  
  A component way to integrate Redux and React. Provides a easy way to make components depend on Redux store structure, by creating it on-the-fly. 
  
- **redux-ddd**  
  https://github.com/alessiodm/redux-ddd  
  Redux bindings inspired by Domain Driven Design principles.  Along the lines of react-redux, redux-ddd provides Redux bindings for generic domain-specific components.
  
- **datavan**  
  https://github.com/ericfong/datavan  
  Define your collections layer over redux state, with mixins to fetch, submit changes to your server. Wraps Redux in a Mongo collection interface.
  
- **React Redux Connected**  
  https://github.com/jimmyhmiller/react-redux-connected  
  React Redux Connected is an opinionated layer on top of react-redux that provides a simple props driven way to connect components.
  
- **redux-updeep**  
  https://github.com/algolia/redux-updeep  
  https://blog.algolia.com/how-we-reduced-boilerplate-and-handled-asynchronous-actions-with-redux/  
  redux-updeep is a small reducer generator that uses updeep to immutably deep merge partial updates into the reducer's state. It's great for reducing boilerplate in your redux actions and reducers!
  
- **NPM-Redux-Interfaces**  
  https://github.com/DaneSirois/npm-redux-interfaces  
  A self contained Redux state management library that allows modular construction.
  
- **erux**
  https://github.com/erux/erux  
  Enhances a Redux store by adding a `store.on()` function, similar to pubsub/event-based programming.
  
- **redux-lenses**  
  https://github.com/rhythnic/redux-lenses  
  Abstractions for interacting with Redux state by using Ramda lenses. 
  
- **Reduxis**  
  https://github.com/simongfxu/reduxis  
  More controllable management, less noise for redux actions and reducers
  
- **slim-redux**  
  https://github.com/aGuyNamedJonas/slim-redux  
  slim-redux is an alternative interface for redux which aims at making working with redux less decoupled and a lot faster while being 100% redux compatible.
  
- **redux-fusion**  
  https://github.com/cif/redux-fusion  
  React bindings for RxJS and Redux - a higher order component that serves as an alternative to react-redux connect. 
  
- **redux-container**  
  https://github.com/ali322/redux-container  
  Simple redux container for react component
  
- **react-redux-reliever**  
  https://github.com/PhilipGarnero/react-redux-reliever  
  A simple package that aims to relieve you from the pain of opening multiple different files and write a lot of boring code each time you want to add a small feature when you're using react and redux.
  
- **teide**  
  https://github.com/lab009/teide/tree/master/packages/teide  
  Toolkit for building redux/react applications.  Spend time building applications rather than wiring modules together.
  
- **redux-static**  
  https://github.com/sandrinodimattia/redux-static  
  Static initialization for Redux. This allows you to define your actions and state in the same static way that you define `propTypes` and `defaultProps`. 
  
- **rxjs-connect**  
  https://github.com/redneckz/rxjs-connect  
  React/Redux are going reactive with RxJS by means of this small library 
  
- **novux**  
  https://github.com/neednova/novux  
  A simple take on Redux, which generates reducers that respond to "UPDATE" and "RESET" actions
  
- **Redux_EM**  
  https://github.com/leonp1991/redux_em  
  This package exposes an api that extends the standard redux offering. redux-em provides a more opinionated and simplified style of writing redux logic.
  
- **dva-reducer**  
  https://github.com/peterlevel1/dva-reducer  
  A reducer helper, primarily intended for use with the DVA Redux-based framework, but can also be used with Redux
  
- **reducerless-redux**  
  https://github.com/arthurgallo/reducerless-redux  
  Redux without reducers.  Includes a redux middleware and store enhancer that maps url's to state, using a single "invisible" reducer.
  
- **redux-acb**  
  https://github.com/archik408/redux-acb  
  Redux Action Creator Binder - an application dispatcher service/helper for Redux infrastructure.
  
- **react-redux-collect**  
  https://github.com/rongierlach/react-redux-collect  
  Helpful function for connecting redux state and actions to React components. This function implements the same core functionality as react-redux-connect-helper's connectStateValue, but by building up mapStateToProps and mapDispatchToProps arguments to be passed to a single connect call.
  
- **redux-atomic-action**  
  https://github.com/clitetailor/redux-atomic-action  
  Allows dispatching state update functions.
  
- **redux-store-controller**  
  https://github.com/mordenius/redux-store-controller  
  Classes for wrapping up a Redux store and setting its state
  
- **react-redux-lite**  
  https://github.com/ganemone/react-redux-lite  
  Lightweight version of the react-redux library
  
- **redux-affix**  
  https://github.com/jmeyers91/redux-affix  
  React-redux's connect function with additional shorthand syntax
  
- **redux-livequery**  
  https://github.com/jeffnian88/redux-livequery  
  Uses RxJS to provide live queries of the Redux store to components
  
- **react-redux-infuser**  
  https://github.com/jgnewman/react-redux-infuser  
  A thin layer wrapping react-redux tools to simplify creating more powerful React containers.
  
- **react-redux-connected**  
  https://github.com/jimmyhmiller/react-redux-connected  
  An opinionated layer on top of react-redux that provides a simple props driven way to connect components.
  
- **redux-lens**  
  https://github.com/dashed/redux-lens  
  Apply a redux reducer and an action at the specified path of your application state tree
  
- **redux-container-builder**  
  https://github.com/orzarchi/redux-container-builder  
  A simpler interface to redux's connect with common utilities built in 
  
- **reduxlet**  
  https://github.com/Rokt33r/reduxlet  
  Create a redux store, which is context-free, for a single container component. Let's use actions and reducer instead of using this.setState!  Also, lots of sugar is inside by default. Binding actions to dispatch, composing enhancers and applying middleware become much easier
  
- **react-component-redux**  
  https://github.com/pashaigood/react-component-redux  
  A library that tries to abstract the low-level usage of Redux, without the need to write actions or action creators.
  
- **react-dedux**  
  https://github.com/tiagomapmarques/react-dedux  
  Abstractions around Redux for state management in React
  
- **causality-redux**  
  https://github.com/AndrewBanks10/causality-redux  
  https://github.com/AndrewBanks10/react-causality-redux  
  An extension to Redux that facilitates a cause-and-effect programming paradigm, and significantly reduces redux and react-redux coding.
  
- **Redux-Auto**  
  https://github.com/codemeasandwich/redux-auto  
  Automatically generate Redux stories and actions from your folder and file structure, using Webpack's context.
  
- **redux-class**  
  https://github.com/Rewieer/redux-class  
  Bringing class-style reducer factory to your redux stack.
  
- **redux-domain** 
  https://github.com/aight8/redux-domain  
  Manage your redux store, reducers, sagas in domains
  
- **react-dedux**  
  https://github.com/tiagomapmarques/react-dedux  
  Redux abstraction for state management in React 
  
- **redux-state-connect**  
  https://github.com/NikolayBorisov/redux-state-connect  
  Help to connect to native React Component State
  
- **react-redux-models**  
  https://github.com/tz5514/react-redux-models  
  Reducer logic and a higher-order component for managing model classes
  
- **react-redux-action-provider**  
  https://github.com/dsdenes/react-redux-action-provider  
  Automatically maps your action creators to your Redux store, and provides them to the child components through this.context.actions.  This saves you writing mapDispatchToProps boilerplate in every component.
  
- **redux-looking-glass**  
  https://github.com/zachcoyle/redux-looking-glass  
  Redux requires too much boilerplate - let's use it as a primitive!  Builds lens-based reducers and action creators using Ramda.
  
- **redux-redactions**  
  https://github.com/selsamman/redux-redactions  
  Reactions simplifies actions and reducers: actions and reducers defined right next to each other, no need for action type strings, no need to worry about not mutating the state, no need to wire togethe a reducer hierarchy, and in fact you don't define reducers - you just define functions that return a state slice.
  
- **redux-modules**  
  https://github.com/wtgtybhertgeghgtwtg/redux-modules  
  A simplistic alternate approach to https://github.com/procore/redux-modules.
  
- **disprux**  
  https://github.com/xaviercobain88/disprux  
  Command/Event Proxy for Redux 
  
- **duxen**  
  https://github.com/applitopia/duxen  
  High performance data engine maintaining complex immutable state for reactive applications. Fully integrated with Immutable.js, Redux, and Meteor.  Define a schema for your entire app state, and Duxen compiles the schema to generate reducers and action creators and handles the state using Immutable.js.
  
- **redux-o-actions**  
  https://github.com/grundiss/redux-o-actions  
  Another library for dispatching class instances as actions
  
- **Reduxable**  
  https://github.com/underscopeio/reduxable  
  Reusable Redux without boilerplate, by defining "state classes" for reducers.
  
- **remodule**  
  https://github.com/otissv/remodule  
  Taming Redux with modules.  Remodule works the same as Redux but removes the tedious tasks of organizing, splitting and collating files. Also does away with the need for constants.
  
- **selectem**  
  https://github.com/sibnerian/selectem  
  Shorthand for react-redux's mapStateToProps. Need some props? Just select 'em!
  
- **globalProvider**  
  https://github.com/mbssantos/globalProvider  
  Global store for partial Redux apps.
  
- **redux-mobx-connect**  
  https://github.com/ds300/redux-mobx-connect  
  react-redux is a remarkable piece of battle-tested engineering with a work-of-art API. This... is not that.  This is a so-simple-it's-almost-dumb connector for redux stores which uses MobX to hook stuff together.
  
- **redux-shared-store**  
  https://github.com/zachary-sierakowski/redux-shared-store  
  A store setup wrapper that includes the ability to dynamically add middleware and reducers.
  
- **redux-event-stream**  
  https://github.com/ajhyndman/redux-event-stream  
  A thin wrapper around Redux that exposes an API inspired by Event Sourcing.
  
- **react-redux-controllers**  
  https://github.com/FactorialComplexity/react-redux-controllers  
  Microframework for structuring code of React/Redux applications, by adding a Controller class and Containers to connect them to the view. 
  
- **yax**  
  https://github.com/d-band/yax  
  Yet another store using redux. (Inspired by vuex and dva) 
  
- **redux-registry**  
  https://github.com/kwhitley/redux-registry  
  Redux, minus the boilerplate.  Redux is amazing, but the verbosity (const definitions, switch statements in primary reducers, etc) and fragmentation of the redux definitions can be painful to implement. This module adds a heap of magic with just enough flexibility to be useful. It basically just removes the repetitive parts and simplifies the cutting and pasting.
  
- **fast-redux**  
  https://github.com/dogada/fast-redux  
  Redux extension with O(1) speed and dynamic importing of reducers/actions.
  
- **Mirror**  
  https://github.com/mirrorjs/mirror  
  A simple and powerful React framework with minimal API and zero boilerplate. (Inspired by dva and jumpstate). Mirror is a front-end framework based on React, Redux and react-router. It encapsulates state management, routing and other essential things to build web apps together in very few methods, and makes it much easier to use:
  
- **fantasyland-redux**  
  https://github.com/philipnilsson/fantasyland-redux  
  Fantasyland-redux is a fork of Redux.  This library is based on the observation that it is possible to add state selectors to reducers while maintaining all the same operations we're used to from Redux.  We add map and other operations from the fantasyland spec to reducers, while remaining backwards compatible with react-redux, redux-thunk and other middlewares, as well as with automatically adapting Redux style reducers.
  
- **react-redux-boilerout**  
  https://github.com/ulisesbocchio/react-redux-boilerout  
  Boilerplate eliminator for React projects using Redux.  Skip action creators, and create reducers with classes.
  
- **recon**  
  https://github.com/ascension/recon  
  Redux Controller Pattern.  Reduces boilerplate by introducing a Controller to manage specific slices of the store, actions, reducers, and selectors.
  
- **redux-store-events**  
  https://github.com/akuzko/redux-store-events  
  Simple, minimalistic and flexible way to organize redux logic 
  
- **silhouette**  
  https://github.com/DuncanWalter/silhouette  
  Atomic state management inspired by redux, observables, and optics. 
  
- **lucio**  
  https://github.com/Marswang92/lucio  
  Simple, intuitive, composable state management for React apps.  Inspired by dva, based on redux, redux-loop.
  
- **redux-needs**  
  https://github.com/LUKKIEN/redux-needs  
  Bind actions to changes in your Redux state based on the needs of your active Redux components.
  
- **redux-echos**  
  https://github.com/NirlStudio/redux-echos  
  A lightweight redux middleware to decouple and serialise state dependencies.
  
- **redux-bind-selectors**  
  https://github.com/blgm/redux-bind-selectors  
  A Redux store enhancer for computing derived state by binding selectors to a Redux store, so that getState() incorporates derived data.
  
- **native-redux-component**  
  https://github.com/ricardo-ch/native-redux-component  
  Want to use redux without using react ? Redux Component is a native implementation of react component which permits to watch your state and trigger render() method of your child component whenever it changes.  It also has the ability to render only when parts of the state change.
  
- **react-redux-presenters**  
  https://github.com/joefiorini/react-redux-presenters  
  Functional library for separating state & behavior from react components.  This library aims to help keep your React components clean by providing a consistent pattern for managing redux mapStateToProps/mapDispatchToProps boilerplate.
  
- **redoodle**  
  https://github.com/palantir/redoodle  
  An addon library for Redux that enhances its integration with TypeScript. Redoodle includes a few major categories of addons that can be used individually and play well with each other: Typed Actions, or "finally my reducers will stop breaking when I refactor"; Compound Actions, or "my action creators are finally sane";  Immutable typesafe state manipulation functions; Some opinions on state management.

- **focus-redux-reducer**  
  https://github.com/tavantzo/focus-redux-reducer  
  A class-based Redux reducer.
  
- **reduxModuleCreator**  
  https://github.com/Mtnt/reduxModuleCreator  
  Class-based controller logic linked to a Redux store
  
- **actionware**  
  https://github.com/wellguimaraes/actionware  
  Redux with less boilerplate, actions statuses and controlled side-effects in a single shot.  No more action creators and action types, just actions and reducers; actions dispatch their result automatically; error status for every action with no extra code; busy status for every async action; cancellable actions.
  
- **vuact**  
  https://github.com/breachofmind/vuact  
  Wraps up React components and Redux stores with a Vue/VueX inspired API.
  
- **reduxBreeze**  
  https://github.com/Lukasz-pluszczewski/reduxBreeze  
  Powerful redux wrapper to make handling redux actions and reducers a breeze! 
  
- **redux-wrapper-extended**  
  https://github.com/anjarpw/redux-wrapper-extended  
  Shortcuts for Redux.  Provides classes to wrap reducers and stores.
  
- **redux-channels**  
  https://github.com/kubischj/redux-channels  
  Creates a wrapper for Redux stores to handle action types both when dispatching actions, and in the reducer functions instead of the user.  The name of the channel would be the type passed along to the store on a dispatch, and the manager would select and call the matching channels subscribers to handle state change.
  
- **Mickey**  
  https://github.com/mickeyjsx/mickey  
  Lightweight front-end framework for creating React and Redux based app painlessly.  Based on Redux, Redux-Saga, and React-Router, inspired by dva.  
  
- **react-redux-simple-autoconnect**  
  https://github.com/oxyno-zeta/react-redux-simple-autoconnect  
  Uses propTypes declared in the Component to link state properties or actions (dispatch is automatically added) to Component.  The library will bind properties by listing state and actions object keys.
  
- **fluxuate**  
  https://github.com/bowheart/fluxuate  
  A suite of opt-in, high-level abstractions on top of Redux, using annotations on classes to reduce boilerplate.
  
- **React Redux Props Helper**  
  https://github.com/baron816/react-redux-props-helper  
  Simple module for mapping state and dispatch to React props by name
  
- **redux-jive**  
  https://github.com/robbymurphy/redux-jive  
  Class-based action creators and reducers to help with Redux wiring
  
- **redux-jedi**  
  https://github.com/loehx/redux-jedi  
  Brings structure to a Redux application.  Actions, reducers and middleware in one file, action consts defined only once, clear structure, payload validation.
  
- **redux-extra**  
  https://github.com/emr550m/redux-extra  
  A Redux wrapper that provides state path subscriptions, a reducer registry, and more.
  
- **resolve**  
  https://github.com/reimagined/resolve  
  reSolve is a framework for developing apps based on CQRS and Event Sourcing, with React + Redux on the client. It can help you easily overcome the differences between your domain and technical languages, and focus on your application code.
  
- **redux-connect-standalone**  
  https://github.com/viniciusdacal/redux-connect-standalone  
  Higher Order Component to allow you to use Redux without the need of a single root provider 
  
- **treact-tredux**  
  https://github.com/ykforerlang/treact-tredux  
  A tiny React-Redux

- **zelektree**  
  https://github.com/maxhallinan/zelektree  
  Embed selectors in a Redux state tree.  This is a convenient way for components to share selectors that are used widely throughout an app.
  
- **redux-reactors**  
  https://github.com/ganemone/redux-reactors  
  A small library (~20 loc) for creating action/reducer combinations, also known as reactors, which are reducers inside of actions.
  
- **rematch**  
  https://github.com/rematch/rematch  
  Rematch makes Redux both easier to work with and more scalable. Helpful for both small and large applications. View agnostic - works with React, Vue, etc.
  
- **reslice**  
  https://github.com/mike-es6/reslice  
  Reslice is a library that wraps a more object-oriented interface around Redux, without removing the underlying state-as-Javascript-object approach.  The motivation for Reslice is a large system where, except at the lowest level, the unit of reusability is a combination of React component + action creators/reducers + selectors, and where we want to be able to place the data associated with such a component at any point in the Redux state tree in each SPA.
  
- **no-redux**  
  https://github.com/ln613/no-redux  
  A react/redux library which automates all redux flows.
  
- **resa**  
  https://github.com/wangtao0101/resa  
  A simple framework based on redux, redux-saga, redux-action. 
  
- **mccree**  
  https://github.com/xughv/mccree  
  Based on the redux, redux-saga, and react-redux packages, McCree provides an easy way to organize state, reducer and effect as Model .
  
- **react-redux-procedures**  
  https://github.com/remhume/react-redux-procedures  
  A wrapper for react-redux's connect to allow execution of multiple actions in a single procedure 
  
- **redux-easy**  
  https://github.com/mvolkmann/redux-easy  
  A set of utility functions to make it easier to use Redux.  No string constants, no reducers with switch statements, no nested reducers.
  
- **redux-modules**  
  https://github.com/procore/redux-modules  
  https://github.com/mboperator/redux-modules-middleware  
  A refinement on the Redux module concept with developer experience in mind. It provides: a concise, intuitive way to define actions and state transformations; action creator middleware for transforming actions before they're dispatched; a decorator that handles mapping state and actions to components; a modified Redux Provider that dynamically registers new reducers as connected components mount;

- **redux-setstate-reducer**  
  https://github.com/romellogoodman/redux-setstate-reducer  
  Allows dispatching a `setState` action that either contains an object to merge in, or a reducer function that updates the state.
  
- **redux-connect-component**  
  https://github.com/datchley/redux-connect-component  
  A more declarative approach to working with Redux without writing numerous HoC containers. Uses a component based approach and children functions similar to approaches in react-motion and react-router.
  
- **redux-mastermind**  
  https://github.com/Neil-G/redux-mastermind  
  Clean state management for your Redux store based on "updaters", with Firebase integration
  
- **redux-proxy-selectors**  
  https://github.com/luwes/redux-proxy-selectors  
  Redux enhancer to access selectors directly from state as getters.
  
- **redux-knife-manager**  
  https://github.com/madetheforcebewithyou/redux-knife-manager  
  Redux Knife Manager is the lightweight library for easily managing, encapsulating and generating the redux entities such as action, reducer, selector and so on.
  
- **Reactium**  
  https://github.com/Atomic-Reactor/Reactium  
  A framework for creating React + Redux apps using the domain driven design (DDD) paradigm. 
  
- **redux-command-handler**  
  https://github.com/fabioelizandro/redux-command-handler  
  A library that aims to separate commands from events instead of have just actions. Using this libraries all redux actions becames events and events are generate just by commands.
  
- **redux-way**  
  https://github.com/lobor/redux-way  
  A small, simple and immutable model to manage data in your Redux store.
  
- **redux-get**  
  https://github.com/luwes/redux-get  
  Redux enhancer to access state props and selectors via a simple store.get() method.
  
- **redux-decorators**  
  https://github.com/qens/redux-decorators  
  A library for making development with redux more comfortable and efficient via decorators
  
- **redux-multistore**  
  https://github.com/i-think-rapido/redux-multistore  
  Provides multistore functionality for a redux store using redux-observable
  
- **beautiful-react-redux**  
  https://github.com/theKashey/beautiful-react-redux  
  https://github.com/theKashey/memoize-state  
  A proxy-based state memoization library, with small wrappers for `connect` that encapsulate using it for your `mapState` functions
  
- **redux-context-provider**  
  https://github.com/jamrizzi/redux-context-provider  
  Inject redux into react context 
  
- **coredux**  
  https://github.com/kana-sama/coredux  
  Dualism to Redux. Two-way combining of redux modules.
  
- **react-lot**  
  https://github.com/didrio/react-lot  
  A dead simple React store that can easily be updated and accessed from any React component. Built on top of Redux so the devTools extension can be used. Follows Redux's philosophy of never directly mutating state and always returning a fresh state on updates.

  
  
#### Redux-Inspired Libraries

- **statty**  
  https://github.com/vesparny/statty  
  A tiny and unobtrusive state management library for React and Preact apps 
  
- **refunk**  
  https://github.com/jxnblk/refunk/  
  Simple React functional setState
  
- **reless-js**  
  https://github.com/Alber70g/reless-js  
  Relessjs = Redux - Actions. Call the reducer directly. Redux without the maintenance. No more need to update Actions, Names, Constants, and Reducers' switch-cases in multiple places. 
  
- **Repatch**  
  https://github.com/jaystack/repatch  
  Repatch is just a simplified Redux, that let you create actions more briefly by dispatching reducers directly.
  
- **redux-zero**  
  https://github.com/concretesolutions/redux-zero  
  Redux without reducers
  
- **babydux**  
  https://github.com/bcherny/babydux  
  A paper-thin, 100% typesafe Redux for babies 
  
- **stent**  
  https://github.com/krasimir/stent  
  Stent is combining the ideas of redux with the concept of state machines 

- **svelte-state**  
  https://github.com/Conduitry/svelte-state  
  A very small, simple library for managing state in a Svelte app. Steals the most useful bits from redux and react-redux and presents them as a single library with no dependencies.
  
- **reduxion**  
  https://github.com/msindwan/reduxion  
  Another take on redux that combines elements of flux for clarity and convenience including a global dispatcher for actions. It also makes use of ES6 features including inheritence and class notation for reducers.
  
- **relite**  
  https://github.com/Lucifier129/relite  
  a redux-like library for managing state with simpler api (1kb)
  
- **hydux**  
  https://github.com/hydux/hydux  
  An Elm-like redux alternative inspired by Hyperapp, Elmish, Elm, Redux, etc.
  
- **unistore**  
  https://github.com/developit/unistore  
  A tiny ~650b centralized state container with component bindings for Preact.
  
- **zedux**  
  https://github.com/bowheart/zedux  
  A high-level, declarative, composable form of Redux 
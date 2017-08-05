### Middleware

**Related Topics:**

- [Side Effects](side-effects.md)
- [Middleware - Async Behavior](middleware-async.md)
  - [Async Behavior - Promises](middleware-async.md#promises)
  - [Async Behavior - Timeouts and Delays](middleware-async.md#timeouts-and-delays)
  - [Async Behavior - Other Async Actions](middleware-async.md#other-async-actions)
- [Middleware - Network Requests](middleware-network-requests.md)
  - [Network Requests - Fetch](middleware-network-requests.md#fetch)
  - [Network Requests - Axios](middleware-network-requests.md#axios)
  - [Network Requests - General](middleware-network-requests.md#general)
- [Middleware - Sockets and Adapters](middleware-sockets-adapters.md)
  - [Sockets and Adapters - Websockets](middleware-sockets-adapters.md#websockets)
  - [Sockets and Adapters - Firebase](middleware-sockets-adapters.md#firebase)
  - [Sockets and Adapters - Meteor](middleware-sockets-adapters.md#meteor)
  - [Sockets and Adapters - Other Connections](middleware-sockets-adapters.md#other-connections)
  
  

#### Action Grouping and Interception

- **redux-combine-actions**  
  https://github.com/itsmepetrov/redux-combine-actions  
  A Redux middleware that allows you to easily combine async actions and dispatch them either sequentially or in parallel.
  
- **redux-sequence-action**  
  https://github.com/jasonslyvia/redux-sequence-action  
  A middleware enabling sequential action dispatch for Redux.
  
- **redux-next**  
  https://github.com/RnbWd/redux-next  
  Recurse Redux actions
  
- **redux-signals**  
  https://github.com/itaylor/redux-signals  
  A redux middleware that allows the creation of 'signal' actions that don't have reducers of their own, but instead dispatch other actions.
  
- **redux-action-listeners**  
  https://github.com/rhythnic/redux-action-listeners  
  This is Redux middleware for listening to actions. The middleware is configured with actionListeners, and those action listeners are called after the reducer runs. The action listeners receive the action and the store.
  
- **redux-handle-actions**  
  https://github.com/joshrtay/redux-handle-actions  
  Redux middleware for handling actions.
  
- **redux-white-black**  
  https://github.com/rnsloan/redux-white-black  
  Redux middleware to execute a callback on action types using a whitelist or blacklist approach
  
- **redux-interceptor**  
  https://github.com/Simonify/redux-interceptor  
  redux-interceptor is a middleware for intercepting Redux actions and deferring their execution to a later time.
  
- **redux-cut**  
  https://github.com/leonaves/redux-cut  
  Middleware to block redux actions based on provided criteria.
  
- **redux-action-transform-middleware**  
  https://github.com/benwiley4000/redux-action-transform-middleware  
  Generates Redux middleware for applying a given transformer function to a given sub-object target on each dispatched action (if it exists). This target's key is specified as a string and can be deeply nested (e.g. 'req.data').
  
- **redux-action-enhancer**  
  https://github.com/bdwain/redux-action-enhancer  
  Enhance your actions with values from the store. Inspired by connected components in react-redux.
  
- **redux-error-middleware**  
  https://github.com/johnrhampton/redux-error-middleware  
  Middleware that dispatches defined actions when the current action has an error.
  
- **redux-multi-conditional**  
  https://github.com/JamesRandall/redux-multi-conditional  
  Conditionally dispatch multiple actions from one action creator
  
- **redux-validation**  
  https://github.com/mkamakura/redux-validation  
  Validate action properties
  
- **redux-action-watch**  
  https://github.com/mrdivyansh/redux-action-watch  
  Provides features to listen actions dispatched to Redux.
  
- **redux-rules**  
  https://github.com/choko-org/redux-rules  
  Make your code more easy to reason about with a more natural language for your logic, using rules fired by actions and reacting to a given set of facts. Based on the forward-chaining rules in Clojure called Clara.
  
- **redux-actions-sequences**  
  https://github.com/AndrewRevinsky/redux-actions-sequences  
  Make sequences of redux actions trigger a new action
  
- **redux-action-enhancer-middleware**  
  https://github.com/jurassix/redux-action-enhancer-middleware  
  Middleware that provides an enhancing function to dispatched actions, with optional filtering to target only certain actions.
  
- **redux-listener**  
  https://github.com/matthias-reis/redux-listener-middleware  
  A Redux middleware that acts as a general listener on actions that are dispatched to the Redux store, with rules for handling different actions.
  
- **Redux Transform**  
  https://github.com/contrarian/redux-transform  
  Field transformation middleware for Redux. 
  
- **suber**  
  https://github.com/oskarhane/suber  
  A message bus compatible with Redux middlewares 
  
- **redux-array**  
  https://github.com/vgabor/redux-array  
  Redux middleware to dispatch array of actions
  
- **redux-action-listener**  
  https://github.com/Dionid/redux-action-listener  
  A middleware and component to notify components when a given action is dispatched
  
- **redux-tap**  
  https://github.com/markdalgleish/redux-tap  
  Simple side-effect middleware for Redux.  Create middleware that match a predicate and run a callback accordingly.
  
- **redux-entry**  
  https://github.com/ThatBean/redux-entry  
  Process dispatched action before it reaches the store 
  
- **redux-observable-middleware**  
  https://github.com/d6u/redux-observable-middleware  
  Redux middleware for subscribing to observables in action creators.
  
- **redux-streams**  
  https://github.com/Industrial/redux-streams  
  Store middleware for Redux that lets you dispatch streams of actions.
  
- **redux-middleware-oneshot**  
  https://github.com/michaelcontento/redux-middleware-oneshot  
  Create Redux actions from arbitrary sources out of middlewares.
  
- **action-validate**  
  https://github.com/chbinghu/action-validate  
  Validate that actions match the Flux Standard Action definition
  
- **redux-validate-actions**  
  https://github.com/asn007/redux-validate-actions  
  A small tool to automatically validate redux actions based on a predicate and log wrongly formatted actions into console 
  
- **redux-prevent-repeat-dispatch**  
  https://github.com/rgabs/redux-prevent-repeat-dispatch  
  A redux middleware to prevent dispatching of repeat actions for a specific period of time.
  
- **redux-orchestrate**  
  https://github.com/domagojk/redux-orchestrate  
  Middleware for coordinating actions using a simple config object. Aims to support most common operations with a config object, including intercepting/transforming actions, making network requests, debouncing, and delaying.
  
- **redux-chain**  
  https://github.com/julesterrien/redux-chain  
  Allows you to dispatch multiple actions calls using a single dispatch call.
  
- **redux-camel**  
  https://github.com/kenny-hibino/redux-camel  
  Redux Camel middleware makes sure that action objects use camelCase keys before reaching reducers.
  
- **redux-validator**  
  https://github.com/MaxLi1994/redux-validator  
  Action parameter validator middleware for redux
  
- **redux-hook-middleware**  
  https://github.com/kamataryo/redux-hook-middleware  
  A Redux middleware to provide easy hooks on pre/post dispatch.
  
- **redux-tsa**  
  https://github.com/contrarian/redux-tsa  
  Async friendly validation middleware for Redux 
  
- **redux-action-enhancer**  
  https://github.com/bdwain/redux-action-enhancer  
  Dependency injection for redux actions. Enhance your actions with values from the store. Inspired by connected components in react-redux.
  
- **redux-subscriber**  
  https://github.com/yoyeung/redux-subscriber-middleware  
  A middleware to allow subscribing to specific actions and running a provided callback function
  
- **redux-camelizer**  
  https://github.com/hiyamamo/redux-camelizer  
  Camelize middleware for Redux
  
- **redux-intercept-action**  
  https://github.com/jasonmorita/redux-intercept-action  
  Redux middleware to intercept and redirect FSA actions before they hit reducers.  Useful for handling actions coming in asyncronously from outside your app.
  
- **redux-actionkit**  
  https://github.com/WA9ACE/redux-actionkit  
  A simple redux side-effect library that lets you add callbacks to be run when requested actions are dispatched
  
- **redux-pre-post-action-middleware**  
  https://github.com/slivcode/redux-pre-post-action-middleware  
  A middleware for executing user-provided callbacks before or after actions are passed onward.
  
- **redux-provider**  
  https://github.com/logaritmdev/redux-provider  
  A middleware that abstract (mostly) async operations in its own layer. An action that is registered as a provider will be invoked first and the original action will be executed only when the provider dispatches the same action.
  
- **redux-iterator**  
  https://github.com/benjmac/redux-iterator  
  Redux Iterator middleware is capable of receiving Sets, Maps, Arrays, Objects and Generators. Once the middleware is reached, they’re iterated over and the nested actions are dispatched to the Redux store.
  
- **redux-aop**  
  https://github.com/modernserf/redux-aop  
  Aspect-Oriented Programming helpers for Redux middleware.  This is a collection of helper functions (or "combinators") for common patterns in redux middleware. It borrows ideas and terminology from Aspect-Oriented programming, and may remind you of alias_method_chain or before_action in Ruby on Rails.
  
- **redux-entry**  
  https://github.com/ThatBean/redux-entry  
  A Redux middleware to process dispatched actions.  Provide callbacks that listen for specific actions, can block the current action, and have access to the store.
  
- **redux-delayed**  
  https://github.com/n4bcak3/redux-delayed  
  Redux middleware for accepting actions with delayed dispatch
  
- **redux-fries**  
  https://github.com/nicolasdelfino/redux-fries  
  Greasy™ middleware for subscribing to actions and creating tasty side-effects in your code 
  
- **redux-lifesaver**  
  https://github.com/americanexpress/redux-lifesaver  
  lifesaver is a middleware that keeps track of how many times actions of the same type are dispatched within a given period. If a single action type is dispatched more times than the allowed amount within a given period, subsequent dispatches of that action type will be blocked from the reducer for the same period. At the end of the period, the most recently attempted dispatch of that action type will go through.
  
  
#### Analytics

- **redux-analytics**  
  https://github.com/markdalgleish/redux-analytics  
  Analytics middleware for Redux.
  
- **rn-redux-mixpanel**  
  https://github.com/danscan/rn-redux-mixpanel  
  Configurable redux middleware that sends your actions & user profile data to Mixpanel. It also works with React Native.
  
- **redux-keen**  
  https://github.com/pavelvolek/redux-keen  
  Redux middleware for sending analytics to Keen.
  
- **redux-segment**  
  https://github.com/rangle/redux-segment  
  Segment.io analytics integration for redux.
  
- **redux-rollbar-middleware**  
  https://github.com/netguru/redux-rollbar-middleware  
  Redux middleware that integrates Rollbar. If exception happens during the action, it will send information to Rollbar
  
- **redux-reporter**  
  https://github.com/northwesternmutual/redux-reporter  
  Redux middleware for reporting actions to third party APIs. Extremely useful for analytics and error handling.  Author has specialized versions for Adobe DTM, NewRelic, and Optimizely.
  
- **redux-beacon**  
  https://github.com/rangle/redux-beacon  
  Analytics integration for Redux and ngrx/store.  Use with React, RN, and Angular. Send analytics to Google Analytics, Google Tag Manager, Segment.io, Amplitude, and more.
  
- **redux-tracking**  
  https://github.com/Shotzoom/redux-tracking  
  Provides tracking support for redux. Currently only support mixpanel.
  
- **redux-insights**  
  https://github.com/hyperlab/redux-insights  
  Redux middleware for analytics and tracking with an awesome API. Comes with Google Analytics support, but it's very easy to write your own adoptions!
  
- **track-action-middleware**  
  https://github.com/bspaulding/track-action-middleware  
  A middleware for interfacing actions with some other event tracking or analytics system.
  
- **redux-ga-middleware**  
  https://github.com/ohwhen/redux-ga-middleware  
  Redux middleware to track redux actions as GA events.
  
- **redux-metrics**  
  https://github.com/Liftitapp/redux-metrics  
  Transform your actions to metrics. use Segment, Mixpanel or custom lib to report your events power by Liftit
  
  
#### Data Management

- **redux-falsy**  
  https://github.com/ashaffer/redux-falsy  
  Drop falsy values that have been dispatched into redux. This may be a candidate for the simplest redux middleware possible.

- **redux-normalizr-middleware**  
  https://github.com/wbinnssmith/redux-normalizr-middleware  
  Combines redux middleware and normalizr to make flattening nested data a snap
  
- **redux-make-immutable**  
  https://github.com/kwhitaker/redux-make-immutable  
  Redux middleware to coerce native javascript types into the equivalent Immutable.js types. Works with both Flux Standard Actions and non-standard actions.
  
- **redux-make-mori**  
  https://github.com/kwhitaker/redux-make-mori  
  Redux middleware to coerce native javascript types into the equivalent Mori types. 
  
- **Redux Provider Middleware**  
  https://github.com/reduxible/redux-provider-middleware  
  A redux middleware which provides Angular-like providers.
  
- **redux-inject**  
  https://github.com/bradharms/redux-inject  
  Redux middleware generator that allows dependencies to be injected into action creators.
  
- **redux-schema-middleware**  
  https://github.com/NapalmDeath/redux-schema-middleware  
  Using NormalizrJS to normalize redux action payload
  
- **realm-redux-snapshot-middleware**  
  https://github.com/sargant/realm-redux-snapshot-middleware  
  Simple redux middleware that recursively converts action payloads of type Realm.Result or Realm.Object into plain objects and arrays.
  
  
#### Other
  
- **redux-action-tracker**  
  https://github.com/gfogle/redux-action-tracker  
  Set of middlewares for Redux to instrument and track actions and their corresponding child actions.
  
- **redux-string**  
  https://github.com/igl/redux-string  
  Allow dispatching of a string as action-type
  
- **redux-favicon**  
  https://github.com/joshwcomeau/redux-favicon  
  Redux middleware that displays colourful notification badges in the favicon area.
  
- **Redux Worker Middleware**  
  https://github.com/keyanzhang/redux-worker-middleware  
  The goal of the middleware is to provide an unopinionated workflow that delegates expensive operations to Web Workers. 
  
- **Redux Sounds**  
  https://github.com/joshwcomeau/redux-sounds  
  Redux middleware that lets you easily trigger sound effects on actions. Makes it completely trivial to do so, by adding a meta property to any action.
  
- **postal-redux-middleware**  
  https://github.com/dehamilton/postal-redux-middleware  
  Middleware to interact with Postal.js
  
- **redux-worker**  
  https://github.com/chikeichan/redux-worker  
  Helps you build multi-threaded JavaScript applications by moving your reducer into a Web Worker. It also provides a simple API for you to register tasks to be executed in the web worker outside of Redux. 

- **Redux Provider**  
  https://github.com/reduxible/redux-provider-middleware  
  The providerMiddleware provides providers that similar with providers of Angular.js. A providerMiddleware injects providers that returns new or cached objects to action. It also similar with Spring Beans.

- **redux-publish-action**  
  https://github.com/oriweingart/redux-publish-action  
  Redux middleware for showing another user's interaction with your application in your browser using PubNub.  Using this middleware you can see what your users see in their application or you can show them what you see on your end. Useful for demos and debug sessions.
  
- **redux-elm-middleware**  
  https://github.com/stoeffel/redux-elm-middleware  
  Elm middleware for redux.  Write bulletproof business logic, handle state and effects, still have the rich react/redux ecosystem at your paws, slowly convert a redux/react app into Elm.
  
- **redux-cookies**  
  https://github.com/MrCheater/redux-cookies  
  Redux cookies-middleware and cookies-actions for Isomorphic(Universal) cookies
  
- **Redux Electron IPC Middleware**  
  https://github.com/mariotacke/redux-electron-ipc  
  A Redux middleware to reduce code around ipc calls in an Electron application. You can send and receive IPC events with a simple api.
  
- **redux-queryparam-middleware**  
  https://github.com/BartWaardenburg/redux-queryparam-middleware  
  Redux middleware which will store (part of) the payload of specified actions in the url and is able to retrieve an initial state from the url
  
- **redux-replaceable-middleware**  
  https://github.com/pgte/redux-replaceable-middleware  
  Redux middleware that allows replacement with another middleware.
  
- **redux-cookie**  
  https://github.com/iroy2000/redux-cookie  
  Redux cookie middleware for both client and server ( universal )
  
- **redux-custom-middlewares**  
  https://github.com/guillaumearm/redux-custom-middlewares  
  Middlewares inside your FSA actions
  
- **rex-cookies**  
  https://github.com/linear-bits/rex-cookies  
  React Redux cookie middleware 
  
- **redux-middlewares**  
  https://github.com/ryo33/redux-middlewares  
  Utility functions to generate new middlewares.
  
- **redux-scraper**  
  https://github.com/therewillbecode/redux-scraper  
  Web scraping middleware for Redux using Cheerio and Axios 
  
- **redux-dynamic-middlewares**  
  https://github.com/pofigizm/redux-dynamic-middlewares  
  Allows adding or removing redux middlewares dynamically
  
- **redux-ipc-electron**  
  https://github.com/Dilatorily/redux-ipc-electron  
  This library uses Electron's IPC to synchronizes the Redux store between the main process and the renderer process(es).
  
- **redux-download-middleware**  
  https://github.com/bzenkobogdan/redux-download-middleware  
  A small middleware to download a file and dispatch actions on success/failure
  
- **redux-middleware-injector**  
  https://github.com/arojunior/redux-middleware-injector  
  Middleware injector for Redux.  With this lib you can write your own middleware wherever you want, like in the action creators file. You don't need to import all the middlewares before create the store in applyMiddleware.
  
- **redux-css**  
  https://github.com/Dash-OS/redux-css  
  Use the redux pattern to control CSS Variables. You provide redux-style reducers that set your variable values when changed, allowing you to style your app in many new ways.
  
- **redux-postmessage-raf**  
  https://github.com/vkammerer/redux-postmessage-raf  
  A redux middleware to use @vkammerer/postmessage-raf , allowing actions to be posted to web workers
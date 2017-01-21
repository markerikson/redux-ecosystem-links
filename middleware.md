### Middleware


#### Promises

- **redux-promise**  
  https://github.com/acdlite/redux-promise  
  FSA-compliant promise middleware for Redux.
  
- **redux-simple-promise**  
  https://github.com/alanrubin/redux-simple-promise  
  FSA-compliant promise middleware for Redux with simple behaviour with minimal boilerplate declarations.
  
- **redux-catch-promise**  
  https://github.com/DenisIzmaylov/redux-catch-promise  
  Extended replacement of redux-thunk middleware to supporting async-await functions and implement server-side rendering for React components with asynchronous state.
  
- **redux-async**  
  https://github.com/symbiont-io/redux-async  
  RSA-compliant actions which resolve when any prop is a promise middleware for Redux.
  
- **redux-promise-middleware**  
  https://github.com/pburtchaell/redux-promise-middleware  
  Redux middleware for resolving and rejecting promises with conditional optimistic updates
  
- **redux-deferred**  
  https://github.com/wyvernnot/redux-deferred  
  Redux middleware for jQuery Deferred object
  
- **redux-promises**  
  https://github.com/CrocoDillon/redux-promises  
  Promise based middleware for Redux to deal with asynchronous actions. redux-promises is backwards compatible with redux-thunk.
  
- **redux-optimist-promise**  
  https://github.com/mathieudutour/redux-optimist-promise  
  FSA-compliant promise middleware middleware for Redux and automatically add necessary for redux-optimist.
  
- **redux-async-middleware**  
  https://github.com/reducks/redux-async-middleware  
  Provides a middleware for handling asynchronous actions.
  
- **redux-pending**  
  https://github.com/adriancooney/redux-pending  
  A promise middleware that you add to your store and will handle resolving the promises and dispatching pending actions. It's based heavily around redux-promise.
  
- **redux-promised**  
  https://github.com/bobmonteverde/redux-promised  
  FSA-compliant promise middleware for redux with optimistic update support
  
- **redux-await-middleware**  
  https://github.com/zenato/redux-await-middleware  
  Await(Promise) middleware for Redux.  Await middleware supprorts FSA actions.
  
- **redux-object-to-promise**  
  https://github.com/mathieudutour/redux-object-to-promise  
  Redux middleware to transform an object into a promise
  
- **redux-payload-promise**  
  https://github.com/zavalit/redux-payload-promise  
  Async Redux Action on a Promise base
  
- **redux-loading-promise-middleware**  
  https://github.com/kallaspriit/redux-loading-promise-middleware  
  Middleware for Redux that turns promises into several dispatches of loading, success and error states, confirming to flux standard action schema.
  
- **redux-promise-loading**  
  https://github.com/amorphousxd/redux-promise-loading  
  Redux middleware and reducer for handling redux promise loading indicator
  
- **redux-pack**  
  https://github.com/lelandrichardson/redux-pack  
  Sensible promise handling and middleware for redux
  
- **redux-pinky**  
  https://github.com/themostaza/redux-pinky  
  Yet another Redux middleware for dispatching async actions.  A more "redux-vanilla" version of redux-pack.
  
- **redux-promises-concluder**  
  https://github.com/arashmilani/redux-promises-concluder  
  A Redux middleware to keep track of active promises and notify when all resolved. Useful in server side rendering of single page applications. 
  
  
#### Timeouts and Delays

- **redux-timeout**  
  https://github.com/gpfunk/redux-timeout  
  Gives ability to call functions if certain actions have not been dispatched in x amount of time.
  
- **redux-trigger**  
  https://github.com/coderkevin/redux-trigger  
  a Redux middleware which allows delayed dispatching of an action based on a trigger state in the Redux store.
  
- **redux-debounced**  
  https://github.com/ryanseddon/redux-debounced  
  Debounce allows you to discard a fast paced action from updating your state until a certain period of time passes after the last action is fired.
  
- **redux-delay**  
  https://github.com/Laiff/redux-delay  
  Delay redux actions
  
- **Redux Action Buffer**  
  https://github.com/rt2zz/redux-action-buffer  
  A middleware for redux that buffers all actions into a queue until a breaker condition is met, at which point the queue is released (i.e. actions are triggered).
  
- **Quince**  
  https://github.com/defact/quince  
  Queueing middleware for Redux.
  
- **redux-throttle-actions**  
  https://github.com/pirosikick/redux-throttle-actions  
  A Redux middleware which throttles actions.
  
- **redux-debounce**  
  https://github.com/wyze/redux-debounce  
  A middleware for Redux to debounce actions.
  
- **redux-async-queue**  
  https://github.com/zackargyle/redux-async-queue  
  ReduxAsyncQueue middleware makes queueing redux actions painless. This allows you to fire multiple actions simultaneously and have them execute asynchronously in order. 
  
- **redux-throttle**  
  https://github.com/mathieudutour/redux-throttle  
  Redux middleware to throttle your actions
  
- **optimistic-middleware**  
  https://github.com/Workpop/optimistic-middleware  
  Optimistically apply actions that will be reverted on error.
  
- **redux-queue-offline**  
  https://github.com/mathieudutour/redux-queue-offline  
  Queue actions when offline and dispatch them when getting back online.
  
- **redux-q**  
  https://github.com/ConciergeAuctions/redux-q  
  redux-q lets you enqueue any function in a queue that is mapped to an action type. The next time that action is dispatched each callback will be called with that action and the queue will be cleared.
  
- **Redux Optimistic Actions**  
  https://github.com/Audicy/redux-optimistic-actions  
  Middleware for managing optimistic actions based on promises
  
- **redux-optimistic**  
  https://github.com/conorhastings/redux-optimistic  
  Simple, user controlled optimistic updates for redux. 
  
- **redux-enqueue**  
  https://github.com/jacobp100/redux-enqueue  
  Simple queue system for redux. Use with redux-thunk.
  
- **redux-trigger-middleware**  
  https://github.com/saintcrawler/redux-trigger-middleware  
  Middleware that lets you call predefined functions on certain actions.
  
- **redux-delayed-dispatch**  
  https://github.com/beaucollins/redux-delayed-dispatch  
  Delayed Dispatch is setTimeout/clearTimeout but in middleware form with some small enhancements.
  
- **redux-timer-middleware**  
  https://github.com/matpaul/redux-timer-middleware  
  Simple middleware to dispatch actions periodically
  
- **redux-when**  
  https://github.com/jameslnewell/redux-when  
  Redux middleware for delaying dispatch of an action until a condition evaluates to true.
  
  
#### Other Async Actions
  
- **redux-await**  
  https://github.com/kolodny/redux-await  
  Manage async redux actions sanely.  This module exposes a middleware, reducer, and connector to take care of async state in a redux app.

- **redux-future**  
  https://github.com/stoeffel/redux-future  
  FSA-compliant future monad middleware for Redux, based on redux-promise.
  
- **redux-either**  
  https://github.com/stoeffel/redux-either  
  FSA-compliant either monad middleware for Redux, based on redux-future.
  
- **redux-wait**  
  https://github.com/ForbesLindesay/redux-wait  
  A helper to let you wait for redux actions to be processed in a universal app.
  
- **redux-save**  
  https://github.com/Legitcode/redux-save  
  Full featured middleware for handling async actions and automagically saving data (For RN & Web)
  
- **redux-notify**  
  https://github.com/zalmoxisus/redux-notify  
  Redux middleware to notify when an action from the list is dispatched.
  
- **redux-co**  
  https://github.com/kilianc/redux-co  
  redux-co is a drop-in replacement for redux-thunk (and indeed passes its test suite). It's meant to support async actions through yieldables as well as plain thunk functions.
  
- **Redux Thunk Inject**  
  https://github.com/producthunt/redux-thunk-inject  
  A drop-in replacement for redux-thunk that lets you inject additional variables into your action creators.
  
- **redux-fsa-thunk**  
  https://github.com/jtpalmer/redux-fsa-thunk  
  FSA-compliant thunk middleware for Redux.
  
- **redux-method-middleware**  
  https://github.com/abhiaiyer91/redux-method-middleware  
  Similar to Promise Middleware, handle asynchronous callback functions via Redux Middleware
  
- **redux-codi**  
  https://github.com/laat/redux-codi  
  Redux middleware with dependency injection and async control flow.  Enables async/await style actions with co, and simple dependency injection in the middleware creator.
  
- **redux-di**  
  https://github.com/laat/redux-di  
  Thunk middleware with dependency injection
  
- **redux-sync-promise**  
  https://github.com/shanhaichik/redux-sync-promise  
  Middleware for writing asynchronous actions in synchronous style
  
- **wait-for-redux-thunk**  
  https://github.com/kkotlarski/wait-for-redux-thunk  
  Simple middleware providing hooks after every async action and a final callback when all async actions are completed. Very useful when building universal react applications with redux-thunk.

- **redux-generator-thunk**  
  https://github.com/geckoboard/redux-generator-thunk  
  Allows you to write action creators that return a generator function instead of an action.
  
- **redux-pull-actors**  
  https://github.com/nrn/redux-pull-actors  
  Middleware for doing additional asynchronous work based on redux actions and state transitions.
  
- **redux-iterators**  
  https://github.com/aabenoja/redux-iterators  
  Redux middleware for handling action creators that return iterators
  
- **Redux Triple Barreled Actions**  
  https://github.com/davidfurlong/redux-triple-barreled-actions  
  Redux Middleware which provides a syntax for dispatching async actions
  
- **Redux Service**  
  https://github.com/ThatBean/redux-service  
  Service middleware for Redux.
  
- **redux-seq-dispatch**  
  https://github.com/dayzhou/redux-seq-dispatch  
  Redux middleware for dispatching promise- or array-valued actions
  
- **redux-amrc**  
  https://github.com/lewis617/redux-amrc  
  Redux async middleware and reducer creator for dispatching async actions with less boilerplate.
  
- **redux-middleware-async**  
  https://github.com/robinpowered/redux-middleware-async  
  Redux middleware for performing predictable asynchronous actions.
  
- **redux-generator**  
  https://github.com/xuyuanxiang/redux-generator  
  Middleware for redux to resolve generator function actions.  
  
- **redux-sane**  
  https://github.com/xiaody/redux-sane  
  A redux middleware that provides sane default behaviors for non-object actions. Dispatch whatever you like: function(thunk)/promise/generator.
  
- **redux-client-middleware**  
  https://github.com/intactile/redux-client-middleware  
  A redux middleware handling async client actions.  Acts like a combination of redux-thunk and a promise middleware.


#### Action Grouping and Interception

- **redux-combine-actions**  
  https://github.com/itsmepetrov/redux-combine-actions  
  A Redux middleware that allows you to easily combine async actions and dispatch them either sequentially or in parallel.
  
- **redux-batch-middleware**  
  https://github.com/mrydengren/redux-batch-middleware  
  Batch middleware for Redux. Inspired by redux-batched-actions.
  
- **redux-sequence-action**  
  https://github.com/jasonslyvia/redux-sequence-action  
  A middleware enabling sequential action dispatch for Redux.
  
- **redux-multi**  
  https://github.com/ashaffer/redux-multi  
  Dispatch multiple actions from one action creator
  
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
  
- **redux-batch-actions**  
  https://github.com/gtg092x/redux-batch-actions  
  Batch Redux actions.
  
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
  
  
#### Sockets and Adapters

- **redux-socket**  
  https://github.com/quirinpa/redux-socket  
  A redux middleware that allows you to trigger a socket request on the client-side and dispatch an action in response.
  
- **redux-observable-middleware**  
  https://github.com/d6u/redux-observable-middleware  
  Redux middleware for subscribing to observables in action creators.
  
- **redux-via**  
  https://github.com/rstuven/redux-via  
  redux-via provides a basis for using Redux across boundaries with Flux Standard Actions.
  
- **redux-streams**  
  https://github.com/Industrial/redux-streams  
  Store middleware for Redux that lets you dispatch streams of actions.
  
- **cape-redux-socket**  
  https://github.com/cape-io/cape-redux-socket  
  Socket middleware, reducer, actions, constants
  
- **redux-middleware-oneshot**  
  https://github.com/michaelcontento/redux-middleware-oneshot  
  Create Redux actions from arbitrary sources out of middlewares.
  
- **redux-socket-middleware**  
  https://github.com/madewithlove/redux-socket-middleware  
  Redux middleware that dispatches an action to all connected clients
  
- **socket.io-redux**  
  https://github.com/sergiodxa/socket.io-redux  
  Redux middleware to emit actions to a socket.io server
  
- **redux-ws**  
  https://github.com/arturmuller/redux-ws  
  Redux middleware for WebSockets communication.
  
- **twiliojs-redux**  
  https://github.com/yarcub/twiliojs-redux  
  Twilio's javascript SDK middleware for Redux.
  
- **redux-action-emit-middleware**  
  https://github.com/pafciu17/redux-action-emit-middleware  
  Middleware for emitting redux actions over socket
  
- **redux-loopback**  
  https://github.com/TimPerry/redux-loopback  
  Loopback middleware for redux
  
- **redux-zmq**  
  https://github.com/code-mancers/redux-zmq  
  A redux middleware for zeromq
  
- **redux-matter**  
  https://github.com/KyperTech/redux-matter  
  Redux middleware, actions, and reducer for Matter.
  
- **redux-effects-socketio**  
  https://github.com/alexjg/redux-effects-socketio  
  Redux effects middleware for socketio
  
- **redux-socket-io**  
  https://github.com/nkt/redux-socket-io  
  Socket.io middleware for Redux.
  
- **redux-ddp**  
  https://github.com/rclai/redux-ddp  
  Get DDP collection data synced straight into a Redux store instead of minimongo and attempting optimistic updates.
  
- **redux-react-firebase**  
  https://github.com/tiberiuc/redux-react-firebase  
  Use Firebase with React and Redux in ES6.  Integrated into Redux, automatic binding/unbinding, declarative decorator syntax for React components, support for nested props, 0ut of the box support for authentication (with auto load user profile).
  
- **feathers-react-redux**  
  https://github.com/saiichihashimoto/feathers-react-redux  
  Unofficial Feathers bindings for React-Redux.  React-Redux is great. Feathers is fantastic. feathers-react-redux aims to tie these two together.
  
- **redux-socket-cluster**  
  https://github.com/mattkrick/redux-socket-cluster  
  A socket-cluster state snatcher.  Socket cluster is awesome, but it doesn't share it's state, so you always have to go to your stored socket to find out. This tiny package grabs all the tasty little state bits & sticks em in your redux store. Then, it sets up listeners for updates to keep those state bits nice and fresh.
  
- **redux-saga-sc**  
  https://github.com/stipsan/redux-saga-sc  
  Provides sagas to easily dispatch redux actions over SocketCluster websockets

- **redux-firebase**  
  https://github.com/colbyr/redux-firebase  
  Declarative firebase queries for redux.

- **firedux**  
  https://github.com/adjohnson916/firedux  
  Firedux (fiery·ducks) wraps the Firebase JavaScript API to dispatch Redux actions that optimisically & immediately read/write to an in-memory subset of your data from Firebase, then asynchronously pull & push data in the background.  Also supports some authentication methods and actions.

- **este-redux-firebase**  
  https://github.com/este/este-redux-firebase  
  Standalone module of Este's Firebase/Redux integration lib

- **refire**  
  https://github.com/hoppula/refire  
  Declarative Firebase bindings for Redux and React.  Refire keeps your local Redux store in sync with selected Firebase paths. You can declaratively bind Firebase paths as Strings, Objects or Arrays.  You can also specify queries based on Redux state (e.g. currently logged in user or route parameter) and Refire will automatically subscribe and unsubscribe your bindings when state changes.

- **redux-firebase**  
  https://github.com/gobadiah/redux-firebase  
  Provides some added functionality when using redux with firebase, such as anonymous use, offline recovery.  Redux firebase makes the connection between your firebase backend and your redux store, using a schema.
  
- **redux-meteorware**  
  https://github.com/shawnmclean/redux-meteorware  
  Meteor middleware for Redux.  This Redux middleware allows us to subscribe and load meteor data through actions and have them returned to the reducers when loaded.
  
- **redux-channels**  
  https://github.com/danielfarrell/redux-channels  
  Connector library for redux and websocket channels(ie, socket.io/Phoenix/ActionCable)
  
- **pouch-redux-middleware**  
  https://github.com/pgte/pouch-redux-middleware  
  Redux Middleware for syncing state and a PouchDB database.  Propagates state changes into PouchDB. Propagates PouchDB changes into the state.
  
- **redux-pubnub-action-sync-middleware**  
  https://github.com/danislu/redux-pubnub-action-sync-middleware  
  Middleware for syncing redux actions between app instances via pubnub.
  
- **redux-firebasev3**  
  https://github.com/prescottprue/redux-firebasev3  
  Use Firebase with React and Redux in ES6
  
- **redux-sockjs**  
  https://github.com/superwf/redux-sockjs  
  Use sockjs to pub and sub redux actions
  
- **ez-redux**  
  https://github.com/dcoellarb/ez-redux  
  Library to manage parse objects and simplify integration with parse
  
- **meteor-redux-middleware**  
  https://github.com/samybob1/meteor-redux-middlewares  
  Redux middlewares that allow you to sync the store with Mongo and any reactive sources
  
- **Redux Swagger Client**  
  https://github.com/noh4ck/redux-swagger-client  
  Add asynchronous Swagger api calls to Redux
  
- **redux-socket.io-middleware**  
  https://github.com/czytelny/redux-socket.io-middleware  
  Another dead-simple middleware which allows you to connect Redux and Socket.io. It uses meta property of your action object to recognize whether send it to backend, or not. 
  
- **resocket**  
  https://github.com/laumair/resocket  
  Resocket is a socket.io wrapper and middleware for React and Redux applications.  It helps you abstract away all the socket.io implementations in your app. 
  
- **redux-firebase-mirror**  
  https://github.com/pcardune/redux-firebase-mirror  
  A library to help you easily mirror firebase data inside a redux store. 
  
- **redux-cablecar**  
  https://github.com/ndhays/redux-cablecar  
  A Redux middleware to connect Redux with Rails 5 ActionCable 
  
- **redux-socket.io-connect**
  https://github.com/michaelmitchell/redux-socket.io-connect  
  Relays Redux actions to the server, where reducer-like "handlers" can execute server code and dispatch actions back to the client.
  
  
#### Network Requests

- **redux-request**  
  https://github.com/TossShinHwa/redux-request  
  Uses either fetch or superagent to make requests.
  
- **reduxr-async**  
  https://github.com/chrisdavies/reduxr-async  
  Easily and cleanly handle AJAX in Redux.
  
- **redux-api-middleware**  
  https://github.com/agraboso/redux-api-middleware  
  Redux middleware for calling an API.
  
- **redux-axios-middleware**  
  https://github.com/svrcekmichal/redux-axios-middleware  
  Redux middleware for fetching data with axios HTTP client
  
- **redux-callApi-middleware**  
  https://github.com/fskinner/redux-callApi-middleware  
  Redux middleware for API calls through Axios
  
- **redux-request-middleware**  
  https://github.com/founderlab/redux-request-middleware  
  Works like redux promise middleware. Resolves request objects from superagent or BackboneORM models. Can work with anything with a similar callback style api.
  
- **redux-fetch-middleware**  
  https://github.com/LuckyZhou880808/redux-fetch-middleware  
  A middleware for redux that help to fetch data from rest API
  
- **redux-axios-api-middleware**  
  https://github.com/mikeyamadeo/redux-axios-api-middleware  
  redux middleware using axios making api calls with redux easy
  
- **rictus**  
  https://github.com/defact/rictus  
  Redux middleware for promise-based resource requests
  
- **redux-autobahn**  
  https://github.com/saadtazi/redux-autobahn  
  A redux middleware for WAMP protocol using autobahn.
  
- **redux-track-async**  
  https://github.com/lronhoj/redux-track-async  
  A lib for tracking pending async requests. Exposes middleware & a reducer
  
- **multi-action-api-middleware**  
  https://github.com/gkosharov/multi-action-api-middleware  
  Redux api middleware for handling simultaneous asynchronous action dispatches (api calls).
  
- **redux-fetch-middleware**  
  https://github.com/RevoltTV/redux-fetch-middleware  
  A middleware for Redux that uses isomorphic-fetch to perform network requests
  
- **redux-composable-fetch**  
  https://github.com/jasonslyvia/redux-composable-fetch  
  A fetch middleware with extensible and opt-in functionalities like cache or log for Redux
  
- **redux-req**  
  https://github.com/jedirandy/redux-req  
  A redux middleware for handling HTTP requests  It's based on plain old XHR, though not as fancy as fetch, it simply does the job and there's no need for extra dependencies.
  
- **redux-http-middleware**  
  https://github.com/sky-uk/redux-http-middleware  
  Make http requests by dispatching actions!  The goal of this module is to move the imperative handling of HTTP requests out of Redux applications. Instead HTTP requests are declared as actions and the success or failure of the request is dispatched as another action.
  
- **redux-cached-api**  
  https://github.com/VerenigingCampusKabel/redux-cached-api  
  Redux middleware for calling and caching a (REST) API
  
- **redux-api-middleman**  
  https://github.com/CodementorIO/redux-api-middleman  
  A Redux middleware extracting the asynchronous behavior of sending API requests.
  
- **redux-remote-resource**  
  https://github.com/tylerFowler/redux-remote-resource  
  Flexible Redux middleware for making remote API calls
  
- **redux-graphql-middleware**  
  https://github.com/gtg092x/redux-graphql-middleware  
  Generate GraphQL queries with Redux middleware .
  
- **redux-fetcher**  
  https://github.com/vgno/redux-fetcher  
  Really simple isomorphic fetch for Redux. Can be used in any Redux project that uses redux-api-middleware.
  
- **redux-middleware-fetch**  
  https://github.com/fantasywind/redux-middleware-fetch  
  Redux Whatwg Fetch Middleware
  
- **redux-rest-easy**  
  https://github.com/oscarekholm/redux-rest-easy  
  A simple Redux middleware for declarative data fetching - helps you REST easy
  
- **redux-api-promise-middleware**  
  https://github.com/restlessbit/redux-api-promise-middleware  
  Middleware that gives you a uniform way to define API actions in Redux applications.
  
- **redux-middleware-async**  
  https://github.com/robinpowered/redux-middleware-async  
  Redux middleware for performing predictable asynchronous actions and tracking request status
  
- **Data Pipeline**  
  https://github.com/iwate/data-pipeline  
  Fetch URLs and modify data as it returns 
  
- **redux-token-api-middleware**  
  https://github.com/eadmundo/redux-token-api-middleware  
  A redux middleware for making calls to APIs with token-based auth, automatically requesting a new token if needed. Actions can be calls to single or multiple API endpoints.
  
- **redux-routed-api-middleware**  
  https://github.com/aliaksandr-master/redux-routed-api-middleware  
  Redux api middleware for separate your api routes, api actions, and interceptors. provide state normalization, db reducer 
  
- **redux-callapi-middleware**  
  https://github.com/Reaverart/redux-callapi-middleware  
  Redux CallAPI Middleware to make API calls in generic and declarative way. 
  
  
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
  https://github.com/ezekielchentnik/redux-reporter  
  https://github.com/ezekielchentnik/redux-adobe-dtm  
  https://github.com/ezekielchentnik/redux-newrelic  
  https://github.com/ezekielchentnik/redux-optimizely  
  Redux middleware for reporting actions to third party APIs. Extremely useful for analytics and error handling.  Author has specialized versions for Adobe DTM, NewRelic, and Optimizely.
  
- **redux-gtm**  
  https://github.com/rangle/redux-gtm  
  Synchronize Redux actions with Google Tag Manager events
  
  
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
  
- **redux-middlewares**  
  https://github.com/ryo33/redux-middlewares  
  Utility functions to generate new middlewares.
  
- **redux-scraper**  
  https://github.com/therewillbecode/redux-scraper  
  Web scraping middleware for Redux using Cheerio and Axios 
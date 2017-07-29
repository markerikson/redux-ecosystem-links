### Store

- Related pages:
  - [Store Persistence](store-persistence.md): libraries for persisting Redux store state, including addons for specific libraries

#### Synchronization

- **redux-live**  
  https://github.com/eitak/redux-live  
  https://github.com/eitak/redux-live-localdb  
  https://github.com/eitak/redux-live-socketio  
  Redux Live a framework for persisting Redux actions to a database and synchronising them across multiple clients. 
  
- **Redux Share**  
  https://github.com/baptistemanson/redux-share-server  
  https://github.com/baptistemanson/redux-share-client  
  Share redux state across the network between clients and servers
  
- **redux-sync**  
  https://github.com/Autarc/redux-sync  
  A store enhancer for Redux which allows to mirror one store as a part of another and keeps them in sync.
  
- **redux-swarmlog**  
  https://github.com/philholden/redux-swarmlog  
  A super simple way of writing distributed Redux applications. The Redux action log is persisted in an IndexDB and synced with other peers via a WebRTC Swarm using Swarmlog.
  
- **redux-scuttlebutt**  
  https://github.com/grrowl/redux-scuttlebutt  
  Self-replicating, self-ordering log of actions shared between all clients. Using the power behind redux's hot reloading and time travel, your client dispatches actions itself and so does every other client, they share the state, and it all just works.
  
- **redux-scuttlebutt-signatures**  
  https://github.com/grrowl/redux-signatures  
  Cryptographic signing of your redux (or flux) actions 
  
- **redux-ipc**  
  https://github.com/vutran/redux-ipc  
  Log your Redux state and actions to a node backend via WebSockets.
  
- **redux-action-sync**  
  https://github.com/czak/redux-action-sync  
  redux-action-sync is an action persistence middleware for Redux applications. A simple solution for keeping state synchronised across multiple clients. It uses a single-endpoint backend as an alternative to CRUD APIs.
  
- **redux-electron-store**  
  https://github.com/samiskin/redux-electron-store/  
  A redux store enhancer that allows automatic synchronization between electron processes

- **redux-peerjs-store-enhancer**  
  https://github.com/jurassix/redux-peerjs-store-enhancer  
  Use PeerJS to easily distribute Redux actions to remote peers.
  
- **Redux Websocket Action Transfer**  
  https://github.com/lttb/redux-wsat  
  This package allows to create middleware that transfer redux actions between client and server via websocket.  The main point is moving redux actions to the next level of services interactions and use it like messaging protocol between different service components, not only frontend. It can be useful for realtime applications with microservice architecture.
  
- **rehub**  
  https://github.com/oakfang/rehub  
  A Redux middleware to share actions via WebRTC 
  
- **redux-peer-connection**  
  https://github.com/jcblw/redux-peer-connection  
  A set of redux tools that enable peer to peer connections between two browsers. It uses simple peer under the hood.
  
- **react-redux-socket**  
  https://github.com/trouve-antoine/react-redux-socket  
  Lightweight library to handle redux actions at server side using sockets.  That means that: redux actions can be re-router to a server (instead of the redux reducers); a server can emit a redux action straight to the redux reducers.

- **redbone**  
  https://github.com/ya-kostik/redbone  
  Library for client -> server -> client redux dispatching
  
- **redux-sync-reducer**  
  https://github.com/darthmaim/redux-sync-reducer  
  High order reducer to sync states between tabs 
  
- **redux-via**  
  https://github.com/rstuven/redux-via  
  redux-via provides a basis for using Redux across boundaries with Flux Standard Actions.
  
- **cross-tab-middleware**  
  https://github.com/stutrek/cross-tab-middleware  
  Redux middleware for sending actions across open browser tabs 
  
- **redux-bolt**  
  https://github.com/vvinhas/redux-bolt  
  https://github.com/vvinhas/redux-bolt-server  
  A small middleware for Redux that lets you dispatch Redux Actions to a server running SocketIO. Your actions will then be replicated to all clients listening to that socket or to a specific channel.
  
- **redux-state-sync**  
  https://github.com/AOHUA/redux-state-sync  
  A light weight middleware to sync your redux state across browser tabs. This module will listens to the window storage event and triggers exactly the same actions triggered in other tabs to make the redux state sync.
  
- **remote-redux-five**  
  https://github.com/ericwpeterson/remote-redux-five  
  A simple client/server protocol that enables Get, Set, Watch, UnWatch, and Call actions on remote redux stores. 
  
- **redux-local-storage-action**  
  https://github.com/khell/redux-local-storage-action  
  Dispatch actions using localStorage to multiple Redux stores on the same domain. 
  

#### Store Change Subscriptions

- **redux-watch**  
  https://github.com/jprichardson/redux-watch  
  Watch/observe/monitor Redux store state changes.  Creates store subscription callbacks that can do comparisons based on object paths or Reselect selectors.
  
- **redux-subscribe**  
  https://github.com/ashaffer/redux-subscribe  
  Subscribe to a path in your redux state atom.  Uses a middleware shared path strings for improved performance and dynamic subscription handling.
  
- **redux-changes**  
  https://github.com/sprightco/redux-changes  
  Process changes in redux with path matching.  Uses a higher-order reducer that does comparisons, and uses a path string with a matching syntax.
  
- **redux-observers**  
  https://github.com/xuoe/redux-observers  
  Observe Redux state changes and dispatch actions on change.
  
- **redux-observer**  
  https://github.com/jimf/redux-observer  
  Redux middleware for observing state change and taking action when changes of interest occur.
  
- **redux-when**  
  https://github.com/jameslnewell/redux-when  
  Delay dispatching an action until a condition is true.
  
- **redux-store-observer**  
  https://github.com/jonnyreeves/redux-store-observer  
  redux-store-observer provides a thin wrapper around Redux's store#subscribe() to allow you to respond to state changes.
  
- **redux-spy**  
  https://github.com/erikras/redux-spy  
  A higher order component decorator to read from a Redux store without subscribing to all its changes
  
- **pull-redux**  
  https://github.com/ahdinosaur/pull-redux  
  use redux as a through pull stream

- **redux-on-state-change**  
  https://github.com/franjohn21/redux-on-state-change  
  Extremely simple middleware to observe Redux state changes.  It's simply to have a place to handle tangentially related logic that doesn't belong in components or reducers but relies on knowing about state or action updates.
  
- **redux-subscriptions**  
  https://github.com/xaviervia/redux-subscriptions  
  Higher-level API for the Redux store.subscribe.  redux-subscriptions keeps the previous state for you and gives you the ability of running diffs in the state (using object-difference) so that you can do something when part of the state is updated, much like the React bindings for Redux work.
  
- **redux-add-action-listener**  
  https://github.com/carnesen/redux-add-action-listener-enhancer  
  A store enhancer that adds a second set of subscriptions for dispatched actions
  
- **redux-subscriber**  
  https://github.com/ivantsov/redux-subscriber  
  Subscribe to changes in any part of redux state
  
- **redux-state-change-listener**  
  https://github.com/sharingapples/redux-state-change-listener  
  Simple library for listening on changes of specific parts of a redux state tree 
  
- **redux-detector**  
  https://github.com/piotr-oles/redux-detector  
  Redux Detector enhancer allows you to use state changes detectors with redux. Detector is a simple and pure function which compares two states and returns list of actions for some states configurations. It can be used for reacting on particular state transitions.
  
- **redux-subscribe-reselect**  
  https://github.com/tswaters/redux-subscribe-reselect  
  A tiny utility to subscribe to state changes returned from a reselect selector 
  
- **redux-wait-for-state**  
  https://github.com/karl/redux-wait-for-state  
  A small utility to that resolves a promise when a selector predicate returns truthy
  
- **watch-redux**  
  https://github.com/Wizcorp/watch-redux  
  A library that makes observing changes in a Redux store using selectors very easy, and efficient. It provides watching for changes with full granularity.
  
- **redux-whenever**  
  https://github.com/caiogondim/redux-whenever.js  
  Subscribe to a state subtree (or leaf) and run callbacks whenever it evaluates to a given value.
  
- **redux-selector-subscribe**  
  https://github.com/apostrophest/redux-selector-subscribe  
  Subscribe to changes in your Redux state via selector functions 
  
- **redux-on**  
  https://github.com/toplan/redux-on  
  Store enhancer for Redux which support adding specific subscriptions
  
- **listate**  
  https://github.com/gamtiq/listate  
  Library to listen/observe/watch changes of Redux store state.
  
- **redux-store-watch**  
  https://github.com/ralusek/redux-store-watch  
  Watches specific paths on redux's store. This is achieved by either providing a selector function whose results will be compared between current and previous state, or a string path whose value will be checked on the current and previous state.
  
- **redux-subscribe-ts**  
  https://github.com/anwfr/redux-subscribe-ts  
  Subscribe to a path in your redux state, get notified when sub-state changed with state diff 
  
- **redux-detector**  
  https://github.com/piotr-oles/redux-detector  
  Redux Detector enhancer allows you to detect state changes in redux. A detector is a simple and pure function which compares two states and returns action or list of actions for some states transitions.
  
- **redux-watch-immutable**  
  https://github.com/Danetag/redux-watch-immutable  
  Watch/observe Redux store state changes using Immutable.js.  Redux-watch is a small but helpful library that associate a callback() to a path-to-the-store. Unfortunately, it's not optimized/made to work with Immutable.js. So we took the main concept and made it work.
  
- **reactive-redux-state**  
  https://github.com/Jawnkuin/reactive-redux-state  
  Make non-UI related redux state reactive.  Uses reselect to memoize the preview sub state or some data derived from state, when state changes, corresponding listeners will be called.
  
- **redux-actors**  
  https://github.com/lronhoj/redux-actors  
  This module provides ability to define actors with Redux. Actors are functions that handle changes in state and perform actions, including dispatching another Action.
  
- **redux-pure-subscribe**  
  https://github.com/tsirlucas/redux-pure-subscribe  
  A store subscribe function that checks if state has changed before trigger. 
  
  
#### Batching and Notifications

- **redux-batched-subscribe**  
  https://github.com/tappleby/redux-batched-subscribe  
  Store enhancer for redux which allows batching of subscribe notifications that occur as a result of dispatches.  Semi-similar use case as redux-batched-actions.
  
- **redux-batch**  
  https://github.com/manaflair/redux-batch  
  Enhance your Redux store to support batched actions.  Based on redux-batched-subscribe, but focused on batched actions instead of debouncing notifications.
  
- **redux-batched-updates**  
  https://github.com/acdlite/redux-batched-updates  
  Batch React updates that occur as a result of Redux dispatches, to prevent cascading renders.
  
- **redux-skip-by-action**  
  https://github.com/tshelburne/redux-skip-by-action  
  Store enhancer for redux that enables skipping subscriber notifications for individual actions.
  
- **redux-debounce-listener**  
  https://github.com/nakamura-to/redux-debounce-listener  
  Redux Debounce Listener allows you to delay invoking listeners. If you use this with React, rendering cost may be reduced.
  
- **redux-batch-enhancer**  
  https://github.com/abc123s/redux-batch-enhancer  
  Batch subscriber notification for an array of actions (including complex actions, e.g. thunks).
  
- **redux-limiter**  
  https://github.com/joaker/redux-limiter  
  Throttle the rate of change notifications from a redux store to stateless components (NOTE: not for use with stateful components)
  
- **redux-batched-actions**  
  https://github.com/tshelburne/redux-batched-actions  
  Batching action creator and associated higher order reducer for redux that enables batching subscriber notifications for an array of actions.  Semi-similar use case as redux-batched-subscribe.
  
- **redux-batch-middleware**  
  https://github.com/mrydengren/redux-batch-middleware  
  Batch middleware for Redux. Inspired by redux-batched-actions.
  
- **redux-multi**  
  https://github.com/ashaffer/redux-multi  
  Dispatch multiple actions from one action creator
  
- **redux-batch-actions**  
  https://github.com/gtg092x/redux-batch-actions  
  Batch Redux actions.
  
- **redux-batcher**  
  https://github.com/tugorez/redux-batcher  
  Higher order reducer that enables batching actions and also plays well with redux-saga
  
  
#### Integration and Interop

- **redux-shared-worker**  
  https://github.com/burakcan/redux-shared-worker  
  A higher order Redux store that runs the actual store in a SharedWorker or WebWorker. 
  
- **redux-web-worker**  
  https://github.com/deebloo/redux-web-worker  
  Redux implementation in a web worker (experiment). The entire state is kept in a separate thread. (this also gives the added benefit of immutable objects)
  
- **redux-webext**  
  https://github.com/ivantsov/redux-webext  
  Allows you to use Redux for managing the state of your WebExtension.
  
- **react-chrome-redux**  
  https://github.com/tshaddix/react-chrome-redux  
  A set of utilities for building Redux applications in Google Chrome extensions.
  
- **electron-redux**  
  https://github.com/hardchor/electron-redux  
  Use redux in the main and browser processes in electron 
  
- **redux-external-dispatchers**  
  https://github.com/npr/redux-external-dispatchers  
  A Redux store enhancer to let non-Redux pieces of your application dispatch actions into Redux without also having access to Redux state.
  
- **react-native-redux-listener**  
  https://github.com/line64/react-native-redux-listener  
  A Redux store enhancer that automatically hooks to React Native event listeners and dispatches all events as primitive actions that can be handled by the reducers of your app.
  
- **redux-enhancer-react-native-appstate**  
  https://github.com/bamlab/redux-enhancer-react-native-appstate  
  Connect your App State changes directly to your Redux store!
  
- **electron-redux-connector**  
  https://github.com/sylhero/electron-redux-connector  
  A  bridge for electron and redux communication 
  
- **redux-electron-global-dispatch**  
  https://github.com/kube/redux-electron-global-dispatch  
  Redux Middleware for dispatching Actions between Electron processes
  
- **redux-electron-initial-state**  
  https://github.com/kube/redux-electron-initial-state  
  Redux Store Initial State Enhancer between Electron Processes 
  
- **workux**  
  https://github.com/sammkj/workux  
  Redux in a web worker.  Separate app business logic from the main thread, leaving only the UI and animation stuffs.
  
- **redux-bridge**  
  https://github.com/barodeur/redux-bridge  
  Experimentation to share redux state between ReactNative and WebView inside an app 
  
  
#### Other

- **redux-lift**  
  https://github.com/izaakschroeder/redux-lift  
  Store composition for redux.  Lifting allows you to "lift" your state, reducers and actions into another context. Lifting is a kind of store enhancer that is a superset of middleware.
  
- **redux-plugins-immutable**  
  https://github.com/jcoreio/redux-plugins-immutable  
  Asynchronously load Redux reducers and middleware, React Components, etc. in app plugins.
  
- **redux-plugins-immutable-react**  
  https://github.com/jcoreio/redux-plugins-immutable-react  
  React helper components for redux-plugins-immutable
  
- **redux-plugins-immutable-hot-loader**  
  https://github.com/jcoreio/redux-plugins-immutable-hot-loader  
  Webpack loader that hot-reloads plugins made with redux-plugins-immutable when you make changes to them.
  
- **redux-mount-store**  
  https://github.com/RetailMeNotSandbox/redux-mount-store  
  Redux store enhancer that makes it possible to mount sub-stores
  
- **redux-online-store-enhancer**  
  https://github.com/jurassix/redux-online-store-enhancer  
  Automatically detect if you are online or offline.  Adds a top-level "online" attribute that will dynamically change as the browser goes online and offline.
  
- **epic-linker**  
  https://github.com/epixode/epic-linker  
  This package supports modular applications based on react and redux-saga, by creating generators that yield "bundles" that can be composed together to form the application.
  
- **redux-stack**  
  https://github.com/jondot/redux-stack  
  Redux Stack is a library that helps you build modular, structured, and cleaner redux apps.  Redux Stack introduces a concept of initializers. Small pieces of integration code, per library, that "declares" how it integrates. Redux Stack will mesh these together to create your personalized store builder.
  
- **redux-injectable-store**  
  https://github.com/lelandrichardson/redux-injectable-store  
  Redux store with injectable reducers for use with bundle splitting, large apps, and SPAs.
  
- **redux-visibility**  
  https://github.com/patch-notes/redux-visibility  
  A store enhancer for Redux that allows to hide parts of the state 
  
- **redux-dispatch-monitor**  
  https://github.com/jBox/redux-dispatch-monitor    
  Initialize redux state asynchronously with multiple async actions. 
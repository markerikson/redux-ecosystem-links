### Store



#### Store Persistence

- **redux-persist**  
  https://github.com/rt2zz/redux-persist  
  Persist and rehydrate a redux store.  The core idea behind redux-persist is to provide performant persistence and rehydration methods. At the same time redux-persist is designed to minimize complexity by knowing as little about your application as possible.
  
- **redux-persist-crosstab**  
  https://github.com/rt2zz/redux-persist-crosstab  
  Add cross tab syncing to your redux app with 1 line. This tiny module listens to the window for redux-persist storage events. When an event occurs it will dispatch a rehydrate action.
  
- **redux-persist-transform-compress**  
  https://github.com/rt2zz/redux-persist-transform-compress  
  Uses lz-string to compress state before storing.
  
- **redux-persist-migrate**  
  https://github.com/wildlifela/redux-persist-migrate  
  Migrate redux state between versions
  
- **redux-persist-transform-encrypt**  
  https://github.com/maxdeviant/redux-persist-transform-encrypt  
  Encrypt your Redux store.
  
- **redux-persist-transform-expire**  
  https://github.com/gabceb/redux-persist-transform-expire  
  Add expiration to your persisted store

- **redux-localstorage**  
  https://github.com/elgerlambert/redux-localstorage  
  Store enhancer that syncs (a subset) of your Redux store state to localstorage.
  
- **redux-localstorage-slicer**  
  https://github.com/ngokevin/redux-localstorage-slicer  
  Custom slicer for redux-localstorage that allows reducers to define their own persistence configuration.
  
- **redux-localstorage-immutable**  
  https://github.com/jakelazaroff/redux-localstorage-immutable  
  Enhancer for redux-localstorage that allows you to persist an immutable store

- **redux-storage**  
  https://github.com/michaelcontento/redux-storage  
  Persistence layer for redux with flexible backends.  Save and load the Redux state with ease.
  
- **redux-storage-decorator-engines**  
  https://github.com/allegro/redux-storage-decorator-engines  
  Composing decorator for redux-storage to use different storage types like redux-storage-engine-localstorage or redux-storage-engine-sessionstorage including custom engines (i.e. to load information from cookies) in a single application.
  
- **redux-pouchdb**  
  https://github.com/vicentedealencar/redux-pouchdb  
  Sync store state to pouchdb
  
- **redux-owl**  
  https://github.com/rt2zz/redux-owl  
  Redux One Way Linking.  This is a simple method for supporting offline sync.  The basic concept is, try to execute the action, on failure add it to a retry queue. Every so often process the retry queue until success is achieved. 
  
- **redux-live**  
  https://github.com/eitak/redux-live  
  https://github.com/eitak/redux-live-localdb  
  https://github.com/eitak/redux-live-socketio  
  Redux Live a framework for persisting Redux actions to a database and synchronising them across multiple clients. 
  
- **redux-action-store**  
  https://github.com/oakfang/redux-action-store  
  Save and load actions to persist state
  
- **redux-session-storage**  
  https://github.com/conorhastings/redux-session-storage  
  Redux middleware for recording redux actions for a particular session to session storage
  
- **redux-persistent-state-snapshot**  
  https://github.com/Marcoga/redux-persistent-state-snapshot  
  Middleware to persist your state in a Redux app.
  
- **redux-simple-localstorage**  
  https://github.com/MoombaDS/redux-simple-localstorage  
  Ridiculously simple implementation for serialising the entire Redux store to local storage and retrieving it on application restart.

- **Redux Share**  
  https://github.com/baptistemanson/redux-share-server  
  https://github.com/baptistemanson/redux-share-client  
  Share redux state across the network between clients and servers
  
- **redux-smooth-storage**  
  https://github.com/dsacramone/redux-smooth-storage  
  Small program to store your react redux store or stores in local storage or session storage
  
- **redux-state-archiver**  
  https://github.com/schwers/redux-state-archiver  
  A collection of React components for serializing your redux state.  
  
- **redux-sync**  
  https://github.com/Autarc/redux-sync  
  A store enhancer for Redux which allows to mirror one store as a part of another and keeps them in sync.
  
- **redux-swarmlog**  
  https://github.com/philholden/redux-swarmlog  
  A super simple way of writing distributed Redux applications. The Redux action log is persisted in an IndexDB and synced with other peers via a WebRTC Swarm using Swarmlog.
  
- **redux-async-initial-state**  
  https://github.com/KELiON/redux-async-initial-state  
  Redux middleware for async loading of initial app state.
  
- **persistent-redux**  
  https://github.com/explorigin/persistent-redux  
  Persistent-Redux is a drop-in middleware that will save your Redux state and restore it on the next page load.  Previously this tool focused on PouchDB but now it offers an adapter API to use any backend.
  
- **redux-store-sync**  
  https://github.com/lokhmakov/redux-store-sync  
  Redux store sync middleware
  
- **redux-simple-storage-middleware**  
  https://github.com/BartWaardenburg/redux-simple-storage-middleware  
  Simple redux middleware which will store the current state tree in either session- or localstorage
  
- **redux-scuttlebutt**  
  https://github.com/grrowl/redux-scuttlebutt  
  Self-replicating, self-ordering log of actions shared between all clients. Using the power behind redux's hot reloading and time travel, your client dispatches actions itself and so does every other client, they share the state, and it all just works.
  
- **Redux-Session**  
  https://github.com/HelpfulHuman/Redux-Session  
  Redux middleware for automatic setting and hydration of state data in external storage.
  
- **redux-ipc**  
  https://github.com/vutran/redux-ipc  
  Log your Redux state and actions to a node backend via WebSockets.
  
- **redux-action-sync**  
  https://github.com/czak/redux-action-sync  
  redux-action-sync is an action persistence middleware for Redux applications. A simple solution for keeping state synchronised across multiple clients. It uses a single-endpoint backend as an alternative to CRUD APIs.
  
- **redux-electron-store**  
  https://github.com/samiskin/redux-electron-store/  
  A redux store enhancer that allows automatic synchronization between electron processes


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
  
- **redux-batched-subscribe**  
  https://github.com/tappleby/redux-batched-subscribe  
  Store enhancer for redux which allows batching of subscribe notifications that occur as a result of dispatches.  Semi-similar use case as [redux-batched-actions](https://github.com/tshelburne/redux-batched-actions).
  
- **redux-batched-updates**  
  https://github.com/acdlite/redux-batched-updates  
  Batch React updates that occur as a result of Redux dispatches, to prevent cascading renders.
  
- **redux-when**  
  https://github.com/jameslnewell/redux-when  
  Delay dispatching an action until a condition is true.

- **redux-skip-by-action**  
  https://github.com/tshelburne/redux-skip-by-action  
  Store enhancer for redux that enables skipping subscriber notifications for individual actions.
  
- **redux-store-observer**  
  https://github.com/jonnyreeves/redux-store-observer  
  redux-store-observer provides a thin wrapper around Redux's store#subscribe() to allow you to respond to state changes.
  
- **redux-spy**  
  https://github.com/erikras/redux-spy  
  A higher order component decorator to read from a Redux store without subscribing to all its changes
  
- **redux-debounce-listener**  
  https://github.com/nakamura-to/redux-debounce-listener  
  Redux Debounce Listener allows you to delay invoking listeners. If you use this with React, rendering cost may be reduced.
  
- **pull-redux**  
  https://github.com/ahdinosaur/pull-redux  
  use redux as a through pull stream

- **redux-on-state-change**  
  https://github.com/franjohn21/redux-on-state-change  
  Extremely simple middleware to observe Redux state changes.  It's simply to have a place to handle tangentially related logic that doesn't belong in components or reducers but relies on knowing about state or action updates.
  
- **redux-subscriptions**  
  https://github.com/xaviervia/redux-subscriptions  
  Higher-level API for the Redux store.subscribe.  redux-subscriptions keeps the previous state for you and gives you the ability of running diffs in the state (using object-difference) so that you can do something when part of the state is updated, much like the React bindings for Redux work.
  
- **redux-batch-enhancer**  
  https://github.com/abc123s/redux-batch-enhancer  
  Batch subscriber notification for an array of actions (including complex actions, e.g. thunks).
  
- **redux-limiter**  
  https://github.com/joaker/redux-limiter  
  Throttle the rate of change notifications from a redux store to stateless components (NOTE: not for use with stateful components)
  
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
  
- **redux-shared-worker**  
  https://github.com/burakcan/redux-shared-worker  
  A higher order Redux store that runs the actual store in a SharedWorker or WebWorker. 
  
- **redux-undoredo**  
  https://github.com/ajainarayanan/redux-undoredo  
  A generic undo-redo reducer that can be used for any redux store. Similar to omnidan/redux-undo, but written to add undo/redo capability as an addon/enhancer to an already existing Redux store.
  
- **redux-web-worker**  
  https://github.com/deebloo/redux-web-worker  
  Redux implementation in a web worker (experiment). The entire state is kept in a separate thread. (this also gives the added benefit of immutable objects)
  
- **redux-mount-store**  
  https://github.com/RetailMeNotSandbox/redux-mount-store  
  Redux store enhancer that makes it possible to mount sub-stores
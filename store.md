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
  
- **redux-pouchdb**  
  https://github.com/vicentedealencar/redux-pouchdb  
  Sync store state to pouchdb
  
- **redux-owl**  
  https://github.com/rt2zz/redux-owl  
  Redux One Way Linking.  This is a simple method for supporting offline sync.  The basic concept is, try to execute the action, on failure add it to a retry queue. Every so often process the retry queue until success is achieved. 
  
- **redux-live**  
  https://github.com/eitak/redux-live  
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
  
#### Other

- **redux-lift**  
  https://github.com/izaakschroeder/redux-lift  
  Store composition for redux.  Lifting allows you to "lift" your state, reducers and actions into another context. Lifting is a kind of store enhancer that is a superset of middleware.
  

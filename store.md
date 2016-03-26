### Store



#### Store Persistence

- **redux-persist**  
  https://github.com/rt2zz/redux-persist  
  Persist and rehydrate a redux store.  The core idea behind redux-persist is to provide performant persistence and rehydration methods. At the same time redux-persist is designed to minimize complexity by knowing as little about your application as possible.

- **redux-localstorage**  
  https://github.com/elgerlambert/redux-localstorage  
  Store enhancer that syncs (a subset) of your Redux store state to localstorage.

- **redux-storage**  
  https://github.com/michaelcontento/redux-storage
  Persistence layer for redux with flexible backends.  Save and load the Redux state with ease.
  
- **redux-pouchdb**  
  https://github.com/vicentedealencar/redux-pouchdb  
  Sync store state to pouchdb
  
- **redux-owl**  
  https://github.com/rt2zz/redux-owl  
  Redux One Way Linking.  This is a simple method for supporting offline sync.  The basic concept is, try to execute the action, on failure add it to a retry queue. Every so often process the retry queue until success is achieved. 
  

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
  
- **redux-batched-subscribe**  
  https://github.com/tappleby/redux-batched-subscribe  
  Store enhancer for redux which allows batching of subscribe notifications that occur as a result of dispatches.  Semi-similar use case as [redux-batched-actions](https://github.com/tshelburne/redux-batched-actions).
  
- **redux-batched-updates**  
  https://github.com/acdlite/redux-batched-updates  
  Batch React updates that occur as a result of Redux dispatches, to prevent cascading renders.

  
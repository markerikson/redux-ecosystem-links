### Store Persistence


#### Persistence Libraries

- **redux-persist**  
  https://github.com/rt2zz/redux-persist  
  Persist and rehydrate a redux store.  The core idea behind redux-persist is to provide performant persistence and rehydration methods. At the same time redux-persist is designed to minimize complexity by knowing as little about your application as possible.

- **redux-localstorage**  
  https://github.com/elgerlambert/redux-localstorage  
  Store enhancer that syncs (a subset) of your Redux store state to localstorage.
  
- **redux-offline**  
  https://github.com/jevakallio/redux-offline  
  https://github.com/redux-offline/redux-offline/issues
  Persistent Redux store for Reasonaboutable™? Offline-First applications, with first-class support for optimistic UI. Use with React, React Native, or as standalone state container for any web app.
  Note: the original "jevakallio" repo has become inactive, so the repo was forked to a "redux-offline" organization.
  
- **redux-storage**  
  https://github.com/react-stack/redux-storage  
  Persistence layer for redux with flexible backends.  Save and load the Redux state with ease.
  
- **redux-pouchdb**  
  https://github.com/vicentedealencar/redux-pouchdb  
  Sync store state to pouchdb
  
- **redux-owl**  
  https://github.com/rt2zz/redux-owl  
  Redux One Way Linking.  This is a simple method for supporting offline sync.  The basic concept is, try to execute the action, on failure add it to a retry queue. Every so often process the retry queue until success is achieved. 
  
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

- **redux-smooth-storage**  
  https://github.com/dsacramone/redux-smooth-storage  
  Small program to store your react redux store or stores in local storage or session storage
  
- **redux-state-archiver**  
  https://github.com/schwers/redux-state-archiver  
  A collection of React components for serializing your redux state.  
  
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
  
- **Redux-Session**  
  https://github.com/HelpfulHuman/Redux-Session  
  Redux middleware for automatic setting and hydration of state data in external storage.
  
- **redux-eventstore**  
  https://github.com/camjackson/redux-eventstore  
  Redux middleware for reading and writing actions to Event Store.  Meant for event-based persistence on the server. 
  
- **redux-gatorade**  
  https://github.com/michael-iglesias/redux-gatorade  
  Need to hydrate state from URL parameters? Redux-gatorade is a simple solution that allows you to hydrate different parts of your state tree from URL parameters.
  
- **redux-simple-storage-middleware**  
  https://github.com/BartWaardenburg/redux-simple-storage-middleware  
  Simple redux middleware which will store the current state tree in either session- or localstorage. This helps creating an awesome developer experience when combined with hot reloading.
  
- **redux-pouchdb-store-enhancer**  
  https://github.com/jurassix/redux-pouchdb-store-enhancer  
  Redux PouchDB Enhancer to store actions locally, sync with remote CouchDB, and time travel by applying remote actions locally and then compute distributed nextState.
  
- **Redux-State-Sync**  
  https://github.com/AOHUA/redux-state-sync  
  A very light weight middleware to sync your redux state across browser tabs.
  
- **redux-replicate**  
  https://github.com/loggur/redux-replicate  
  Creates a Redux store enhancer designed to replicate actions and states. Declaratively connect application state to data sources and create efficient, scalable, and reliable software with minimal effort. 
  
- **redux-store-sessionstorage**  
  https://github.com/ppallesws/redux-store-sessionstorage  
  Store enhancer that syncs (a subset) of your Redux store state to sessionstorage. 
  
- **record-redux**  
  https://github.com/GA-MO/record-redux  
  Record your action to local storage 
  
- **redux-react-session**  
  https://github.com/bernabe9/redux-react-session  
  Redux React Session provides an API that allows to manage sessions through the app, with authorization function for react-router and a persisted session.
  
- **Redux Phoenix**  
  https://github.com/brainhub-adam/redux-phoenix  
  Restore redux state from previous sessions like a phoenix from ashes.
  
- **session-store**  
  https://github.com/zipdrug/session-store  
  A redux store that manages a session lifecycle 
  
- **redux-state-save**  
  https://github.com/bytefunc/redux-state-save  
  A small library for saving and loading Redux state from file storage or localStorage
  
- **redux-recovery**  
  https://github.com/hajjiTarik/redux-recovery  
  a redux-middleware that allows to persist, purge, rehydrate the store 
  
- **pouch-redux-middleware**  
  https://github.com/pgte/pouch-redux-middleware  
  Redux Middleware for syncing state and a PouchDB database.  Propagates state changes into PouchDB. Propagates PouchDB changes into the state.
  
- **redux-local-storage**  
  https://github.com/mahaplatform/redux-local-storage  
  Redux middleware for accessing local storage
  
- **redux-localstorage-simple**  
  https://github.com/kilkelly/redux-localstorage-simple  
  Save and load Redux state to and from LocalStorage. Supports Immutable.js data structures. 
  
- **redux-localstore**  
  https://github.com/arojunior/redux-localstore  
  Subscribe Redux Store and replicate to localStorage, so users can refresh the page and keep the App state
  
- **redux-checkpoints**  
  https://github.com/workemy/redux-checkpoints  
  Save / Load functionality for Redux states. 
  
- **node-persistent-redux**  
  https://github.com/Jense5/node-persistent-redux  
  Provides a very straighforward way to write a redux store to disk. This can be useful in case you want to store a configuration, like for example with electron.
  
- **redux-persist-to-localstorage**  
  https://github.com/purposeindustries/redux-persist-to-localstorage  
  A dead-simple redux store enhancer for adding localStorage persistance 
  
- **redux-replay**  
  https://github.com/kareemf/redux-replay  
  Transport-agnostic Redux action persistence, retrieval, and replay. Designed to work with redux-logger's persistence mechanism.
  
- **redux-browser-storage**  
  https://github.com/planttheidea/redux-browser-storage  
  Use redux to manage specific data saved in either localStorage or sessionStorage
  
- **redux-pouchdb-sync-models**  
  https://github.com/TobiasBales/redux-pouchdb-sync-models  
  A middleware to sync models between redux state and a pouchdb with efficient storage and conflict resolution 
  
- **redux-cookies-middleware**  
  https://github.com/grofers/redux-cookies-middleware  
  redux-cookies-middleware is a Redux middleware which watches for changes in Redux state & stores them in browser cookie.
  
- **redux-session-manager-middleware**  
  https://github.com/ssilve1989/redux-session-manager-middleware  
  Manage your client-side redux application state 
  
- **redux-session-manager**  
  https://github.com/ssilve1989/redux-session-manager  
  Redux Store Enhancer that serializes state to sessionStorage 
  
- **redux-dev-state-persist**  
  https://github.com/abradley2/redux-dev-state-persist  
  Redux Dev State Persist (RDSP) provides hot-reloading without having to use any sort of Browserify or Webpack plugin- and no mucking about with specific hot-reloading integrations API. Just persist your state!
  
- **panmnesia**  
  https://github.com/EternalDeiwos/panmnesia  
  A command registry and redux-based aggregate store for a PouchDB-based event stream. 
  
- **redux-persistable**  
  https://github.com/actra-development-oss/redux-persistable  
  State persistance for redux stores supporting immutable.js, lazy reducers, versioned states, migrations and merged storage
  
- **persist-reducer**  
  https://github.com/nicocrm/persist-reducer  
  Simple helper functions to persist a Redux reducer state to local storage 
  
  
#### Redux-Persist Addons

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
  
- **redux-persist-migrate-semver**  
  https://github.com/srtucker22/redux-persist-migrate-semver   
  Migrate redux state between versions with redux-persist.

- **redux-persist-transform-immutable**  
  https://github.com/rt2zz/redux-persist-transform-immutable  
  Add immutable sub-reducer support to redux-persist. 
  
- **redux-persist-immutable**  
  https://github.com/rt2zz/redux-persist-immutable  
  A wrapper around redux-persist that provides ImmutableJS support.
  
- **redux-persist-immutable-state**  
  https://github.com/rufman/redux-persist-immutable-state  
  Implements stateIterator, stateGetter, stateSetter and stateReconciler for an ImmutableJS root state.
  
- **redux-persist-transform-filter**  
  https://github.com/edy/redux-persist-transform-filter  
  Filter transformator for redux-persist
  
- **redux-persist-transform-expire**  
  https://github.com/gabceb/redux-persist-transform-expire  
  Add expiration to your persisted store 
  
- **redux-persist-restful-storage**  
  https://github.com/qwe852/redux-persist-restful-storage  
  Restful storage for redux-persist 
  
- **redux-persist-cookie-storage**  
  https://github.com/abersager/redux-persist-cookie-storage  
  Redux Persist storage adapter for cookies 
  
- **redux-persist-node-storage**  
  https://github.com/pellejacobs/redux-persist-node-storage  
  Redux persist adaptor for Node localStorage
  
- **redux-persist-state-manager**  
  https://github.com/rt2zz/redux-persist-state-manager  
  Replacement for autoRehydrate with state migrations, hard set rehydrated values, helpful log messages, and implemented as a higher order reducer
  
- **redux-persist-memory-storage**  
  https://github.com/modosc/redux-persist-memory-storage  
  Redux Persist memory storage adapter.
  
- **redux-persist-transform-passwords**  
  https://github.com/CharlieHess/redux-persist-transform-passwords  
  Store some parts of your state in the macOS Keychain, Credential Vault on Windows, or libsecret on Linux. Uses keytar. Adheres to the redux-persist transform API, but async transforms must be enabled.
  
- **redux-persist-storage-node**  
  https://github.com/odensc/redux-persist-storage-node  
  redux-persist storage for Node.js/Electron.
  
- **redux-persist-sensitive-storage**  
  https://github.com/CodingZeal/redux-persist-sensitive-storage  
  redux-persist storage engine for react-native-sensitive-info
  
- **redux-persist-model**  
  https://github.com/henrytao-me/redux-persist-model  
  Utils for persisting model-related data
  
- **redux-persist-electron-storage**  
  https://github.com/psperber/redux-persist-electron-storage  
  Redux persist adaptor for electron-store 
  
- **redux-persist-realm**  
  https://github.com/Osedea/redux-persist-realm  
  A Realmjs interface for redux-persist 
  

#### Redux-Storage Addons

- **redux-storage-engine-indexed-db**  
  https://github.com/prateekbh/redux-storage-engine-indexed-db  
  indexedDb engine for redux-storage   
  
- **redux-storage-engine-localstorage**  
  https://github.com/react-stack/redux-storage-engine-localStorage  
  window.localStorage engine for redux-storage  
  
- **redux-storage-engine-localStorageFakePromise**  
  https://github.com/react-stack/redux-storage-engine-localStorageFakePromise  
  Like redux-storage-engine-localstorage - but it does not require a environment with ES6 Promises.
  
- **redux-storage-engine-reactNativeAsyncStorage**  
  https://github.com/react-stack/redux-storage-engine-reactNativeAsyncStorage  
  react-native/AsyncStorage based engine for redux-storage   
  
- **redux-storage-engine-remoteendpoint**  
  https://github.com/bionexo/redux-storage-engine-remoteendpoint  
  A remote endpoint storege engine for redux-storage 
  
- **redux-storage-merger-simple**  
  https://github.com/react-stack/redux-storage-merger-simple  
  Merge plain old JS structures (default)
  
- **redux-storage-engine-immutablejs**  
  https://github.com/react-stack/redux-storage-merger-immutablejs  
  ImmutableJS compatible merger for redux-storage 
  
- **redux-storage-engine-jsurl**  
  https://github.com/axe312ger/redux-storage-engine-jsurl  
  Store your state as url hash via redux-storage and jsurl
  
- **redux-storage-decorator-debounce**  
  https://github.com/react-stack/redux-storage-decorator-debounce  
  Delay and merge save opertations of redux-storage 
  
- **redux-storage-decorator-engines**  
  https://github.com/allegro/redux-storage-decorator-engines  
  Composing decorator for redux-storage to use different storage types like redux-storage-engine-localstorage or redux-storage-engine-sessionstorage including custom engines (i.e. to load information from cookies) in a single application.
  
- **redux-storage-decorator-filter**  
  https://github.com/michaelcontento/redux-storage-decorator-filter  
  Filter decorator for redux-storage to only store a subset of the whole state tree.
  
- **redux-storage-decorator-immutablejs**  
  https://github.com/react-stack/redux-storage-decorator-immutablejs  
  ImmutableJS decorator for redux-storage. Use this to convert the loaded state tree (or parts of it) into a ImmutableJS structure.
  
- **redux-storage-decorator-migrate**  
  https://github.com/mathieudutour/redux-storage-decorator-migrate  
  Migrate decorator for redux-storage to version the storage with migration 
  

#### Redux-Localstorage Addons
  
- **redux-localstorage-slicer**  
  https://github.com/ngokevin/redux-localstorage-slicer  
  Custom slicer for redux-localstorage that allows reducers to define their own persistence configuration.
  
- **redux-localstorage-immutable**  
  https://github.com/jakelazaroff/redux-localstorage-immutable  
  Enhancer for redux-localstorage that allows you to persist an immutable store
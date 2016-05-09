### Reducers


#### Reducer Utilities

- **multireducer**  
  https://github.com/erikras/multireducer  
  A utility to wrap many copies of a single Redux reducer into a single key-based reducer.
  
- **reduce-reducers**  
  https://github.com/acdlite/reduce-reducers  
  Reduce multiple reducers into a single reducer from left to right.

- **redux-modules**  
  https://github.com/mboperator/redux-modules  
  A library for defining clear, boilerplate free Redux reducers with typechecked action payloads. Based on the redux duck paradigm proposed by erikras.
  
- **redux-delegator**  
  https://github.com/lapanoid/redux-delegator  
  Compose reducers in a structured way 
  
- **create-reducer**  
  https://github.com/nrn/create-reducer  
  Create a redux reducer from an object of action handling functions, keyed by the actions they handle. Has createReducer.compose(fns) helper function to combine multiple action handlers into a single action. 
  
- **redux-map-reducers**  
  https://github.com/zippyui/redux-map-reducers  
  Redux reducer that maps over an object of action types.
  
- **reduxr-obj-reducer**  
  https://github.com/chrisdavies/reduxr-obj-reducer  
  A utility to create Redux reducers from simple objects.
  
- **reduxr-scoped-reducer**  
  https://github.com/chrisdavies/reduxr-scoped-reducer  
  A utility to create Redux reducers which only respond to prefixed actions.
  
- **reducer-chain**  
  https://github.com/bydooweedoo/reducer-chain  
  reducer-chain helps you to chain redux reducers with given state and action, then keep last updated state.
  
- **reducer-pipe**  
  https://github.com/bydooweedoo/reducer-pipe  
  reducer-pipe helps you to pipe redux reducers with given state and action, passing previously returned state to next reducer, then keep last updated state.
  
- **reducer-sandbox**  
  https://github.com/bydooweedoo/reducer-sandbox  
  reducer-sandbox helps you to reuse your redux reducers in different place without conflict them.
  
- **redux-create-reducer**  
  https://github.com/kolodny/redux-create-reducer  
  Publishing createReducer from Redux's Reducing Boilerplate page.
  
- **redux-action-reducer**  
  https://github.com/troch/redux-action-reducer  
  Remove redux reducer boilerplate
  
- **Redux Reducer**  
  https://github.com/chetanism/redux-reducer  
  This library is intended to provide a little more object-oriented approach to write reducers. All it does is provide Reducer and CombineReducers classes to get rid of switch-case. Additionally it also lets you modify reducers dynamically.
  
- **redux-reducer**  
  https://github.com/nathanial/redux-reducer  
  A small library for writing redux actions with less boilerplate using classes.
  
- **redux-switch-action**  
  https://github.com/qwtel/redux-switch-action  
  Slightly more concise reducer switching for Flux Standard Actions.
  
- **make-reducer**  
  https://github.com/reactbits/make-reducer  
  Functions to easily build redux reducers without boilerplate code.
  
- **ReduMan**  
  https://github.com/ajlopez/ReduMan  
  Reducer manager, it can be used as a replace for switch in Redux reducers
  
- **create-redux-reducer-from-map**  
  https://github.com/TehShrike/create-redux-reducer-from-map  
  A personal preference for building reducers for Redux.
  
- **redux-polymorphic**  
  https://github.com/yesmeck/redux-polymorphic  
  Another attempt to reuse your reducers, inspired from multireducer

- **combined-reduction**  
  https://github.com/convoyinc/combined-reduction  
  Like Redux's combineReducers, but more better!  Allows definition of nested reducers and multiple top-level reducers.
  
- **redux-reducer-delegate**  
  https://github.com/wmira/redux-reducer-delegate  
  Create a reducer by delegating types to sub reducers.  A way to create reducers by composing sub-reducers. This prevent the switch statements.
  
- **redux-blower**  
  https://github.com/JiriChara/redux-blower  
  Faster and nicer reducers for your Redux applications. Say "NO!" to switch statements!
  
- **redux-modifiers**  
  https://github.com/calvinfroedge/redux-modifiers  
  A collection of generic functions on top of ImmutableJS and Redux Actions for simplifying your reducers. Declare your reducers and state as plain old javascript objects, but take advantage of Immutable guarantees and data structure traversal utilities.
  
- **redux-commons**  
  https://github.com/KodersLab/redux-commons  
  Easily create common reducers by just composing functions
  
- **redux-frr**  
  https://github.com/e-jigsaw/redux-frr  
  Redux Filter and Reduce Reducers.
  
- **Simr**  
  https://github.com/dalexj/simr  
  A library for reducing common functionality in Redux reducers
  
#### Higher-Order Reducers

- **redux-undo**  
  https://github.com/omnidan/redux-undo  
  Higher order reducer to add undo/redo functionality to redux state containers
  
- **redux-ignore**  
  https://github.com/omnidan/redux-ignore  
  Higher-order reducer to ignore redux actions
  
- **redux-recycle**  
  https://github.com/omnidan/redux-recycle  
  Higher-order reducer to reset the redux state on certain actions
  
- **redux-optimist**  
  https://github.com/ForbesLindesay/redux-optimist  
  Optimistically apply actions that can be later commited or reverted.
  
- **redux-optimistic-ui**  
  https://github.com/mattkrick/redux-optimistic-ui  
  A reducer enhancer to enable type-agnostic optimistic updates
  
- **Redux Entities**  
  https://github.com/itsmepetrov/redux-entities  
  Higher-order reducer for store entities received from gaearon's normalizr and makes it easy to handle them.
  
- **redux-cache**  
  https://github.com/simplesmiler/redux-cache  
  Higher order cache reducer
  
- **redux-multiplex**  
  https://github.com/reducks/redux-multiplex  
  Provides a higher-order reducer for managing multiple instances of the same redux state subtree.

- **redux-meta-reducer**  
  https://github.com/DerekCuevas/redux-meta-reducer  
  A redux higher order reducer to simplify the state of fetched data.
  
- **Indexed List Reducer Generator**  
  https://gist.github.com/elado/95484b754f31fcd6846c7e75de4aafe4  
  A high-order-reducer that manages dynamic indexed lists (by ID)
  
- **Redux Undo Immutable**  
  https://github.com/idealeric/redux-undo-immutable  
  A higher order reducer to add undo/redo to redux state containers using immutable js.  It is conceptually identical to redx-undo and shares almost the same API.
  
  
#### Advanced Reducer Use Cases

- **redux-operations**  
  https://github.com/mattkrick/redux-operations  
  https://medium.com/@matt.krick/solving-redux-s-shortcoming-in-150-locs-540979ce6cf9  
  https://medium.com/@matt.krick/introducing-redux-operations-332ab56e468b    
  Adds additional logic to reducers to handle ordering of reducer handling, dynamic state creation, and display of reducer behavior in the Redux DevTools.
  
- **redux-components**  
  https://github.com/wcjohnson/redux-components  
  A component model for Redux state trees based on the React.js component model and other familiar design patterns from the React ecosystem.  Allows creation of "reducer components" that can be dynamically added and removed, and targeted with scoped actions.
  
- **redux-reducer-factory**  
  https://github.com/mclauia/redux-reducer-factory  
  A configurable createReducer factory (i.e. it is a factory for making a createReducer function) that essentially allows projects to insert extra generic reducers (enhancers) before and after individual domain reducers are invoked, without muddying those individual domains.
  
- **redux-reducers-meld**  
  https://github.com/mclauia/redux-reducer-meld  
  A beforeReduce enhancer for use with redux-reducer-factory that can meld previous and initial state to flesh out default state of partial state hydration (for example, when persisting only specific parts of your state tree to local storage)
  
- **redux-reset**  
  https://github.com/wwayne/redux-reset  
  A store enhancer to allow resetting the state based on a specific action
  
- **redux-list-reducer**  
  https://github.com/mattikl/redux-list-reducer    
  redux-list-reducer is a factory function for creating Redux reducers that operate on lists.
  
- **rereduce**  
  https://github.com/slorber/rereduce  
  Simple reducer library for Redux. It's like Reselect but for reducers.  By using aggressive memoization, reducers can depend on each others in an efficient way, without having to query Redux store.  It works fine with time-travel debugging and server-side rendering, because reducers remains totally stateless pure functions.  It permits to replace the imperative waitFor of original Flux implementation by a purely functional approach.
  
- **redux-waitfor**  
  https://github.com/dtinth/redux-waitfor  
  Reducer combinator that allows reducers to wait upon each other.
  
- **topologically-combine-reducers**  
  https://github.com/KodersLab/topologically-combine-reducers  
  A way to combine reducers by their dependencies and access at their ancestor's values.
  
- **incremental-redux-reducers**  
  https://github.com/tazsingh/incremental-redux-reducers  
  Incrementally load Redux reducers into a single store
  
- **redux-register**  
  https://github.com/dexbol/redux-register  
  An Redux enhancer for registering reducer by namespace
  

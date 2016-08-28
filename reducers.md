### Reducers


#### Reducer Utilities

- **multireducer**  
  https://github.com/erikras/multireducer  
  A utility to wrap many copies of a single Redux reducer into a single key-based reducer.
  
- **reduce-reducers**  
  https://github.com/acdlite/reduce-reducers  
  Reduce multiple reducers into a single reducer from left to right.
  
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
  
- **fineCombine**  
  https://github.com/pcarden/fine-combine  
  Combines reducer collections, even when they have duplicate keys.
  
- **redux-merge-reducers**  
  https://github.com/kuy/redux-merge-reducers  
  A decorator to make your Redux's reducers mergeable.
  
- **stack-feature-store-redux**  
  https://github.com/gp-technical/stack-feature-store-redux  
  An alternative redux combineReducers function for use with feature package oriented applications
  
- **reduxerit**  
  https://github.com/jurgob/reduxerit  
  reduxerit is strongly influenced from redux-modifiers (https://github.com/calvinfroedge/redux-modifiers), It tries to simplify writing the redux reducer, but without using immutablejs.
  
- **combineSectionReducers**  
  https://github.com/ryo33/combine-section-reducers  
  Section reducers is the same as reducers but it requires the third argument to get the entire state.  (sectionState, action, state) => newSectionState
  
- **Redux Conditional**  
  https://github.com/ypxing/redux-conditional  
  Conditionally apply actions to Redux reducers to make sharing reducers easy.
  
- **redux-concatenate-reducers**  
  https://github.com/ryo33/redux-concatenate-reducers  
  Concatenates reducers and merges states returned by them.
  
- **create-reducer-redux**  
  https://github.com/johnnyji/create-reducer-redux  
  Create simple and functional reducers that can listen to multiple action creators.
  
- **redux-tk**  
  https://github.com/geowarin/redux-tk  
  Utility functions for generating reducers.
  
- **better-combine-reducers**  
  https://github.com/shinout/better-combine-reducers  
  Better redux combineReducers, initial state injectable.
  
- **redux-callback-reducer**  
  https://github.com/soofty/redux-callback-reducer  
  redux-callback-reducer allows any function or class method to make a reducer for your state, without adding any additional actions.
  
- **redux-curried-reducers**  
  https://github.com/rvikmanis/redux-curried-reducers  
  Curried reducer utilities for Redux - create reducers declaratively via function composition.  Works really well with functional utilities like lodash-fp and Ramda.
  
  
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
  
- **redux-reset**  
  https://github.com/abhiaiyer91/redux-reset  
  Higher Order Reducer for resetting multiple parts of your state tree
  
- **path-reducer**  
  https://github.com/appfeel/path-reducer  
  This is a reducer function to modify the app state via path (100% compatible with redux). At this development stage, it only works with immutable-js state objects.
  
- **initializable-reducer**  
  https://github.com/oreshinya/initializable-reducer  
  Initializing reducers action and associated higher order reducer for redux.
  
- **Redux-Queue**  
  https://github.com/JBlaak/Redux-Queue  
  Higher order reducer to easily cope with async actions.
  
- **redux-schema-sanitizing-reducer**  
  https://github.com/kjessec/redux-schema-sanitizing-reducer  
  Returns a reducer that immutably sanitizes input state. Easily composable with your existing reducer.
  
- **redux-reset-reducer**  
  https://github.com/CyberInt/redux-reset-reducer  
  Higher-order Redux reducer which resets state to original reducer's initial state
  
- **redux-reuse**  
  https://github.com/CyberInt/redux-reuse  
  Helper utility to create higher-order reducers to reuse your action handlers in existing Redux reducers
  
- **redux-payload**  
  https://github.com/CyberInt/redux-payload  
  Higher-order Redux reducer which returns payload for specific actions
  
- **redux-map-state**  
  https://github.com/CyberInt/redux-map-state  
  Higher-order Redux reducer which helps apply your existent reducers on any format of state
  
- **redux-undoable**  
  https://github.com/linn/redux-undoable  
  A reducer enhancer (or higher order reducer) that provides undo/redo functionality for Redux by replaying actions (rather than storing previous state)
  
- **redux-pipeline**  
  https://github.com/gtg092x/redux-pipeline  
  Redux Pipeline combines reducers into a single, manageable sequence.
  
  
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
  
- **remerge**  
  https://github.com/siawyoung/remerge  
  The sole purpose of Remerge is to provide a consistent interface for defining and manipulating state. It's extremely easy and intuitive to use once you get the hang of it. While there is a slight learning curve, hopefully our examples will ease the learning process.  Although Remerge was built for use with Redux, it can also be used standalone. It is completely framework-agnostic.
  
- **reducify**  
  https://github.com/gtg092x/reducify  
  Generate redux reducers with less effort 

### Actions

- Related pages:
  - [Action/Reducer/Constant Generators](action-reducer-generators.md): includes libraries that generate actions and reducers
  - [Use Cases](use-cases.md): includes libraries that provide their own actions for various domains
  - [Middleware](middleware.md): includes libraries that modify actions in some way


#### Action Creation Utilities

- **redux-actions**  
  https://github.com/acdlite/redux-actions  
  Flux Standard Action utilities for Redux.

- **redux-namespaced-actions**  
  https://github.com/skleeschulte/redux-namespaced-actions  
  Wrapper for redux-actions to easily add namespaces to action types.
  
- **Redux Actions Magic**  
  https://github.com/felixmc/redux-actions-magic  
  Syntax magic for the redux-actions module, meant to remove repetitive typing of action names, that might slightly reduce development time and bug generation.

- **redux-batched-actions**  
  https://github.com/tshelburne/redux-batched-actions  
  Batching action creator and associated higher order reducer for redux that enables batching subscriber notifications for an array of actions.  Semi-similar use case as [redux-batched-subscribe](https://github.com/tappleby/redux-batched-subscribe).
  
- **actions**  
  https://github.com/Legitcode/actions  
  This is a utility for injecting actions in redux. The idea came from having a huge project with actions all over the place. What if we treated actions like routes and made a file with a list of them?
  
- **redux-easy-actions**  
  https://github.com/grigory-leonenko/redux-easy-actions  
  Sugar library for creating Redux or Flux actions.
  
- **Redux Action Helpers**  
  https://github.com/keuller/redux-action-help  
  Includes utility functionx to generate simple and dynamic actions.
  
- **redux-action-types**  
  https://github.com/ripeworks/redux-action-types  
  Shortcut for making normal and async action types.
  
- **redux-simple-actions**  
  https://github.com/xiamidaxia/redux-simple-actions  
  Create actions based on objects with functions
  
- **async-redux-actions**  
  https://github.com/spalger/async-redux-actions  
  A simple wrapper around async redux actions.
  
- **Faction**  
  https://github.com/af/faction  
  Utilities and conventions for managing Redux (or Flux) actions.  Co-locate your action types and action creators and keep them DRY, automatically dispatch follow-up actions when your async actions complete, validate arguments sent to each actionCreator
  
- **redux-purify**  
  https://github.com/alpacaaa/redux-purify  
  Allows definition of actions by passing named reducers in an object
  
- **reduxr-obj-actions**  
  https://github.com/chrisdavies/reduxr-obj-actions  
  A utility to create auto-typed Redux actions from an object.
  
- **redux-promise-thunk**  
  https://github.com/kpaxqin/redux-promise-thunk  
  Create thunk generator to dispatch Flux-Standard-Action in each phase of Promise.
  
- **redux-api-action-creators**  
  https://github.com/AlanFoster/redux-api-action-creators  
  API Action Creators for Redux
  
- **create-action**  
  https://github.com/nkt/create-action  
  Helpers for creating FSA compatible actions.
  
- **action-names**  
  https://github.com/Versent/action-names  
  Utility functions to generate action name triplets for CRUD ops.

- **redux-request**  
  https://github.com/kongdigital/redux-request  
  Redux-Request simplifies Restful API calls using redux. It follows the convention of "configuration" over "code" and is designed for applications that make a lot of API calls.
  
- **redux-glue**  
  https://github.com/jfairbank/redux-glue  
  Glue together actions to create testable, sequenced actions.
  
- **async-actions**  
  https://github.com/doordash/async-actions  
  Async action creator for use with redux and redux-thunk. Uses whatwg-fetch and dispatches IN_PROGRESS, SUCCESS, and FAIL events during the lifecycle of an async request.
  
- **redux-actions-class**  
  https://github.com/Lokua/redux-actions-class  
  Create action creators and types with minimal redundancy.
  
#### Other Action Use Cases  
  
- **redux-actionemitter**  
  https://github.com/sgentle/redux-actionemitter  
  An experimental module for representing Redux actions as events. In this model, reducers become observers, switch statements become event listeners, and dispatch() emits events.
  
- **Redux Smart Action**  
  https://github.com/stephan83/redux-smart-action  
  SmartActions add a layer on top of actions to do things depending on whether an action would modify the state. When a SmartAction is called, it returns an object instead of dispatching immediately. The returned object tells you whether executing it would change the state, and a method to execute it.
  
- **Redux Undo Stack**  
  https://github.com/stephan83/redux-undo-stack  
  An undo stack for redux. It works by storing incremental changes instead of entire states, which is optimal when working with large data. It works in combination with SmartActions.
  
- **redux-queue-offline**  
  https://github.com/mathieudutour/redux-queue-offline  
  Queue actions when offline and dispatch them when getting back online
  
- **redux-bind-action-groups**  
  https://github.com/eyasliu/redux-bind-action-groups  
  A small utility to bind dispatch to nested objects full of action creators.

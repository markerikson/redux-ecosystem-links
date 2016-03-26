### Actions

- Related pages:
  - [Utilities](utilities.md): includes libraries that generate actions and reducers
  - [Use Cases](use-cases.md): includes libraries that provide their own actions for various domains
  - [Middleware](middleware.md): includes libraries that modify actions in some way


#### Action Creation Utilities

- **redux-actions**  
  https://github.com/acdlite/redux-actions  
  Flux Standard Action utilities for Redux.

- **redux-namespaced-actions**  
  https://github.com/skleeschulte/redux-namespaced-actions  
  Wrapper for redux-actions to easily add namespaces to action types.

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
  
  
#### Other Action Use Cases  
  
- **redux-actionemitter**  
  https://github.com/sgentle/redux-actionemitter  
  An experimental module for representing Redux actions as events. In this model, reducers become observers, switch statements become event listeners, and dispatch() emits events.
  
- **Redux Smart Action**  
  https://github.com/stephan83/redux-smart-action  
  SmartActions add a layer on top of actions to do things depending on whether an action would modify the state. When a SmartAction is called, it returns an object instead of dispatching immediately. The returned object tells you whether executing it would change the state, and a method to execute it.
  
- **redux-queue-offline**  
  https://github.com/mathieudutour/redux-queue-offline  
  Queue actions when offline and dispatch them when getting back online
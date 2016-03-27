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
  
  
#### Other Async Actions
  
- **redux-await**  
  https://github.com/kolodny/redux-await  
  Manage async redux actions sanely.  This module exposes a middleware, reducer, and connector to take care of async state in a redux app.
  
- **Redux Async Initial State**  
  https://github.com/KELiON/redux-async-initial-state  
  Redux middleware for async loading of initial app state.

- **redux-future**  
  https://github.com/stoeffel/redux-future  
  FSA-compliant future monad middleware for Redux, based on redux-promise.
  
- **redux-io**  
  https://github.com/stoeffel/redux-io  
  FSA-compliant io monad middleware for Redux, based on redux-future.
  
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
  
  
#### Network Requests

- **redux-request**  
  https://github.com/TossShinHwa/redux-request  
  Uses either fetch or superagent to make requests.
  
- **reduxr-async**  
  https://github.com/chrisdavies/reduxr-async  
  Easily and cleanly handle AJAX in Redux.
  
  
#### Analytics

- **redux-analytics**  
  https://github.com/markdalgleish/redux-analytics  
  Analytics middleware for Redux.
  
- **rn-redux-mixpanel**  
  https://github.com/danscan/rn-redux-mixpanel  
  Configurable redux middleware that sends your actions & user profile data to Mixpanel. It also works with React Native.
  
  
  
#### Other

- **redux-validator**  
  https://github.com/MaxLee1994/redux-validator  
  Action parameter validator middleware for redux
  
- **redux-action-tracker**  
  https://github.com/gfogle/redux-action-tracker  
  Set of middlewares for Redux to instrument and track actions and their corresponding child actions.
  
- **redux-string**  
  https://github.com/igl/redux-string  
  Allow dispatching of a string as action-type
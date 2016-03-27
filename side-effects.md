### Side Effects


- **redux-thunk**  
  https://github.com/gaearon/redux-thunk  
  The simplest possible side effects approach: dispatch functions instead of objects, which then get access to `dispatch` and `getState`.  (Variations on the concept listed on the [Middleware](middleware.md) page.)
  
- **redux-saga**  
  https://github.com/yelouafi/redux-saga  
  Generator-based side effects approach.  Create "sagas", which act like background threads or daemons that can listen for actions and dispatch objects describing side effects.
  
- **react-redux-saga**  
  https://github.com/threepointone/react-redux-saga  
  React bindings for redux-saga, allowing you to dynamically start sagas by mounting them as React components
  
- **redux-saga-combine-latest**  
  https://github.com/jhewlett/redux-saga-combine-latest 
  Wait for several action types to be dispatched before handling them
  
- **redux-loop**  
  https://github.com/raisemarketplace/redux-loop  
  Sequence your effects naturally and purely by returning them from your reducers.  Also returns descriptive objects, which are executed later.
  
- **redux-side-effects**  
  https://github.com/salsita/redux-side-effects  
  Redux toolset for keeping all the side effects inside your reducers while maintaining their purity, using generators.
  
- **redux-action-side-effects**  
  https://github.com/jonnyreeves/redux-action-side-effects  
  Trigger side effects after actions have been reduced.
  
- **redux-task**  
  https://github.com/sskyy/redux-task  
  A Side Effects enhancer for redux. The idea is simple: By given an asynchronous task(such as submitting data to server) a name, redux-task will create and handle the task state for you automatically. Then you can retrieve the state with the task name in your component easily. No need to create store state like isSubmitting or submitFailed and manully change them any more. 
  
- **redux-saga-rxjs**  
  https://github.com/salsita/redux-saga-rxjs  
  RxJS implementation of the Saga pattern for Redux.
  
- **redux-remotes**  
  https://github.com/rt2zz/redux-remotes  
  Trigger side-effects (e.g. async actions) via dispatch. Vaguely similar to cerebral signals or elm side effects.
  
- **redux-side-effect-reducers**
  https://github.com/matystl/redux-effect-reducers  
  Library that enable returning of effects in reducers for redux library
  
- **redux-side-effect**  
  https://github.com/gregwebs/redux-side-effect  
  Side Effect middleware for Redux. Lets you specify side effects in your reducing function that dispatch new actions.
  
- **redux-reactions**  
  https://github.com/winstonewert/redux-reactions  
  A reactions approach to side-effects in redux.
  
- **redux-yield-effect**  
  https://github.com/wizardzloy/redux-yield-effect  
  Declarative side effects for redux with generators
  
- **redux-walk**  
  https://github.com/xaviervia/redux-walk  
  An async extension for Redux that keeps you functional
  
- **redux-process**  
  https://github.com/maksimsco/redux-process  
  Process manager for Redux to orchestrate complex/asynchronous operations in one place.
  
- **redux-fork**  
  https://github.com/floxjs/fork  
  Non blocking async call effects.
  
  
#### Redux-Effects extensions

- **redux-effects**  
  https://github.com/redux-effects/redux-effects  
  Virtual DOM for effects and impurities. You write pure functions, redux-effects handles the rest.
  
- **bind-effect**  
  https://github.com/redux-effects/bind-effect  
  Bind to the result of an effectful action
  
- **declarative-promise**  
  https://github.com/redux-effects/declarative-promise  
  Produce declarative specifications of your promise chains. Designed to be used in conjunction with redux-effects
  
- **redux-effects-events**  
  https://github.com/redux-effects/redux-effects-events  
  Provides access to event listeners on window and document
  
- **redux-effects-localstorage**  
  https://github.com/redux-effects/redux-effects-localstorage  
  Redux effects driver for localStorage
  
- **redux-effects-random**  
  https://github.com/redux-effects/redux-effects-random  
  Random number generator for redux-effects
  
- **redux-effects-cookie**  
  https://github.com/redux-effects/redux-effects-cookie  
  Access and manipulate cookies in redux-effects middleware in an isomorphic way.
  
- **redux-effects-timeout**  
  https://github.com/redux-effects/redux-effects-timeout  
  Driver and set of action creators for timing related effects in redux-effects.
  
- **redux-effects-fetch**  
  https://github.com/redux-effects/redux-effects-fetch  
  Declarative data fetching for redux  
  
- **redux-effects-fetch-fixture**  
  https://github.com/team-boris/redux-effects-fetch-fixture  
  An extension for redux-effects-fetch, which lets you define fixtures for your FETCH actions. Now you are able to develope completely without any REST backend.
  
- **redux-effects-credentials**  
  https://github.com/redux-effects/redux-effects-credentials  
  Add credentials to fetch requests when conditions are met
  
- **redux-effects-location**  
  https://github.com/redux-effects/redux-effects-location  
  redux-effects middleware for dealing with location/url
  
- **redux-flo**  
  https://github.com/redux-effects/redux-flo  
  Redux style control flow middleware - inspired by haskel's free monad approach to io and co.
  

### Side Effects - Functions

- **redux-thunk**  
  https://github.com/gaearon/redux-thunk  
  The simplest possible side effects approach: dispatch functions instead of objects, which then get access to `dispatch` and `getState`.  (Variations on the concept listed on the [Middleware](middleware.md) page.)
  
- **redux-action-side-effects**  
  https://github.com/jonnyreeves/redux-action-side-effects  
  Trigger side effects after actions have been reduced.
  
- **redux-thunk-effects**  
  https://github.com/shakacode/redux-thunk-effects  
  Thunk-like handling with additions.
  
- **redux-thunktions**  
  https://github.com/ohjames/redux-thunktions  
  An FSA compatible redux thunk middleware ideal for use with redux-actions and/or redux-promise-middleware.
  
- **redux-effects**  
  https://github.com/redux-effects/redux-effects  
  Virtual DOM for effects and impurities. You write pure functions, redux-effects handles the rest.
  
- **redux-async-action**  
  https://github.com/kevhuang/redux-async-action  
  Dispatches FSA actions for asynchronous Redux actions 
  
- **redux-thunk-status**  
  https://github.com/dieseljobs/redux-thunk-status  
  Simple redux async action status management 
  
- **redux-thunk-subscribe**  
  https://github.com/AugurProject/redux-thunk-subscribe  
  Similar to Redux Thunk, but with subscribe available to thunks (in addition to dispatch and getState) so they can add listeners to the store on-the-fly.
  
- **redux-optimistic-thunk**  
  https://github.com/ecomfe/redux-optimistic-thunk  
  redux-optimistic-thunk is a redux-thunk like middleware with optimistic UI supported.
  
- **redux-managed-thunk**  
  https://github.com/ecomfe/redux-managed-thunk  
  A redux-thunk compatible middleware with managed feature to help write more controllable and reusable thunks 
  
- **redux-thunk-state-adapter**  
  https://github.com/bspaulding/redux-thunk-state-adapter  
  A utility to provide a facade of getState to an externally owned thunk. This is useful when you are sharing action creators which compose selectors that assume a certain state shape.
  
- **redux-ready-wrapper**  
  https://github.com/borisding/redux-ready-wrapper  
  A variation of redux-thunk that dispatches a READY_ACTION before your actual action, and always returns a promise for chaining
  
- **thunk-kickoff**  
  https://github.com/chrisgervang/thunk-kickoff  
  Get promises out the door and into your store!  Thunk Kickoff wraps async actions with request status (success, pending, fail), and provides essential request lifecycle functions. It builds on top of redux-thunk.
  
- **selector-action**  
  https://github.com/sibnerian/selector-action  
  A small abstraction over redux-thunk which allows you to pass in selectors and an action creator function that receives the extracted data, similar to how Reselect's `createSelector` API works.
  
- **redux-thunks**  
  https://github.com/w33ble/redux-thunks  
  Simple thunk creator for redux.  This is meant to smooth over the use of redux-thunk mixed with the use of redux-actions.
  
- **redux-serial-effects**  
  https://github.com/wix/redux-serial-effects  
  A middleware library for managing side-effects based on state changes, following an actual vs. expected philosophy, and supporting composability.
  
- **redux-thunk-ajax**  
  https://github.com/mividtim/redux-thunk-ajax  
  Make JSON REST AJAX requests with redux-thunk 
  
- **redux-thunk-catch**  
  https://github.com/shoaibkalsekar/redux-thunk-catch  
  A redux thunk alternative with error handling support.
  
- **redux-thunkx**  
  https://github.com/Bhoos/redux-thunkx  
  A redux thunk middleware with extendable arguments.  It works exactly like redux-thunk with an additional feature of extendable arguments.
  
- **redux-thunkx-timer**  
  https://github.com/Bhoos/redux-thunkx-timer  
  A controlled timer for running future actions
  
- **redux-thunk-timeout**  
  https://github.com/Bhoos/redux-thunk-timeout  
  A redux-thunk based timeout manager for redux actions
  
- **redux-call-effect**  
  https://github.com/tomasz-sodzawiczny/redux-call-effect  
  A declarative way to call action creators.
  
- **redux-super-thunk**  
  https://github.com/Atomic-Reactor/redux-super-thunk  
  Thunk middleware for Redux that adds the store as an argument.
  

#### Redux-Effects extensions
  
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
  
- **redux-effects-http-cache**  
  https://github.com/leesiongchan/redux-effects-http-cache  
  Cache HTTP requests to fetch requests to prevent duplicated requests.
  
- **redux-effects-fetch-fixture**  
  https://github.com/gutefrage/redux-effects-fetch-fixture  
  An extension for redux-effects-fetch, which lets you define fixtures for your FETCH actions. Now you are able to develop completely without any REST backend.
  
- **redux-effects-steps**  
  https://github.com/recruit-tech/redux-effects-steps  
  Another version of redux-effects handling error action properly.
  
- **redux-effects-socket.io**  
  https://github.com/recruit-tech/redux-effects-socket-io  
  socket.io bindings for redux-effects family 
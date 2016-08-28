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
  
- **redux-saga-debounce-effect**  
  https://github.com/madewithlove/redux-saga-debounce-effect  
  A small debounce effect for redux-saga
  
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

- **redux-tap**  
  https://github.com/markdalgleish/redux-tap  
  Simple side-effect middleware for Redux.

- **redux-io**  
  https://github.com/stoeffel/redux-io  
  Wrap side-effects in an IO monad.
  
- **reelm**  
  https://github.com/tihonove/reelm  
  Awesome effect management library for redux
  
- **redux-epic**  
  https://github.com/BerkeleyTrue/redux-epic  
  Redux-Epic is a library built to do complex/async side-effects and server side rendering(SSR) data pre-fetching using RxJS.
  
- **redux-observable**  
  https://github.com/redux-observable/redux-observable  
  RxJS 5-based middleware for Redux. Compose and cancel async actions and more.
  
- **react-redux-observable**  
  https://github.com/redux-observable/react-redux-observable  
  React helpers for redux-observable
  
- **redux-observable-process-fetch**  
  https://github.com/istarkov/redux-observable-process-fetch  
  This middleware add caching, refetching, pre and post loading actions support for async data loading services like Observable.ajax or any other service with signature (...args: Array<any>) => Observable<any>.
  
- **redux-haiku**  
  https://github.com/xaviervia/redux-haiku  
  redux-haiku proposes is that any side-effect can be treated just like a DOM side-effect–that is, it can be done as the result of a state change. The state change can be identified by running a diff between the new and the old states on the segment of the state that the side-effect cares about, in the meanwhile reusing established patterns such as selectors, mapStateToProps, mapDispatchToProps, etc.
  
- **redux-elmish**  
  https://github.com/minedeljkovic/redux-elmish  
  The Elm Architecture in Redux, statically checked using flow.  Attempts to be as close as possible to Elm Architecture in means of composition and static typing, and not lose Redux good parts (devtools) in the process.
  
- **redux-stream**  
  https://github.com/mcoetzee/redux-stream  
  Use RxJS 5 to compose side effect streams.  When composing your module's side effects, you have access to all state streams, which allows you to react to an independent module's state changes and produce side effects from it.
  
- **redux-logic**  
  https://github.com/jeffbski/redux-logic  
  Redux middleware for organizing business logic and action side effects.
  
- **redux-effex**  
  https://github.com/brentvatne/redux-effex  
  Spin off async functions to perform side effects
  
  
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
  
- **redux-effects-http-cache**  
  https://github.com/leesiongchan/redux-effects-http-cache  
  Cache HTTP requests to fetch requests to prevent duplicated requests.
### Side Effects - Other Approaches


#### Reducer-Based Effects

- **redux-loop**  
  https://github.com/raisemarketplace/redux-loop  
  Sequence your effects naturally and purely by returning them from your reducers.  Also returns descriptive objects, which are executed later.

- **redux-side-effect-reducers**  
  https://github.com/matystl/redux-effect-reducers  
  Library that enable returning of effects in reducers for redux library
  
- **redux-side-effect**  
  https://github.com/gregwebs/redux-side-effect  
  Side Effect middleware for Redux. Lets you specify side effects in your reducing function that dispatch new actions.
  
- **redux-elmish**  
  https://github.com/minedeljkovic/redux-elmish  
  The Elm Architecture in Redux, statically checked using flow.  Attempts to be as close as possible to Elm Architecture in means of composition and static typing, and not lose Redux good parts (devtools) in the process.
  
- **redux-funk**  
  https://github.com/mheiber/redux-funk  
  Enables you to declaratively specify effects in Redux reducers. You can use it to express in reducers not just what should happen, but also, what should happen next, while keeping reducers pure.  Similar to Redux Loop, but the implementation is much simpler and shorter, and it enables you to program with reducers without having to worry about lifting effects.

- **redux-funk-immutable**  
  https://github.com/srikanthkyatham/redux-funk-immutable  
  A tiny lib for creating Redux Funk that operate on Immutable JS maps
  
- **redux-reducer-effects**  
  https://github.com/cubik-oss/redux-reducer-effects  
  Redux enhancer which adds support for managed effects to the reducer, allowing you to return side effects as data in your reducer function.



#### Other

- **redux-remotes**  
  https://github.com/rt2zz/redux-remotes  
  Trigger side-effects (e.g. async actions) via dispatch. Vaguely similar to cerebral signals or elm side effects.
  
- **redux-reactions**  
  https://github.com/winstonewert/redux-reactions  
  A reactions approach to side-effects in redux.
  
- **redux-walk**  
  https://github.com/xaviervia/redux-walk  
  An async extension for Redux that keeps you functional (now deprecated)
  
- **redux-process**  
  https://github.com/maksimsco/redux-process  
  Process manager for Redux to orchestrate complex/asynchronous operations in one place.
  
- **redux-io**  
  https://github.com/stoeffel/redux-io  
  Wrap side-effects in an IO monad.
  
- **redux-haiku**  
  https://github.com/xaviervia/redux-haiku  
  redux-haiku proposes is that any side-effect can be treated just like a DOM side-effect–that is, it can be done as the result of a state change. The state change can be identified by running a diff between the new and the old states on the segment of the state that the side-effect cares about, in the meanwhile reusing established patterns such as selectors, mapStateToProps, mapDispatchToProps, etc.
  
- **redux-effex**  
  https://github.com/brentvatne/redux-effex  
  Spin off async functions to perform side effects
  
- **redux-reactor**  
  https://github.com/eiriklv/redux-reactor  
  Redux middleware for handling side effects by reacting to dispatched actions
  
- **refx**  
  https://github.com/aduth/refx  
  Redux middleware for triggering side effects.  To perform side effects, you define effects as an object of action type keys whose values are functions which trigger additional effects.
  
- **petux**  
  https://github.com/tempname11/petux  
  The Redux ecosystem still lacks a solution for side effects that (A) is easy to use, (B) is easy to reason about, (C) scales well. Petux is a humble attempt to solve this problem. It is meant to be used in real-world production applications of any complexity.
  
- **redux-executor**  
  https://github.com/piotr-oles/redux-executor  
  Redux enhancer for handling side effects.
  
- **redux-se**  
  https://github.com/DJercic/redux-se  
  Redux middleware that allows you to trigger side effects with redux actions.  It's a library that meets thunks and sagas in the middle.  Side effects are triggered by actions that flow through redux store, and complexity of your side-effects are up to you.
  
- **redux-background**  
  https://github.com/monvillalon/redux-background  
  redux-background allows you to create background tasks on redux. This package is very similar to redux-thunk or redux-promise but adds several features, like statistics, progress and rescheduling.
  
- **redux-free-flow**  
  https://github.com/yiransheng/redux-free-flow  
  Free Monad Action Creators for Redux.  Lets you write pure, composable and versatile redux store interactions (both sync and async)
  
- **reservice**  
  https://github.com/zordius/reservice  
  An isomorphic/universal asynchronous tasks solution for redux. 
  
- **redux-tx**  
  https://github.com/majo44/redux-tx  
  Transactions for Redux, using zone.js
  
- **redux-heat**  
  https://github.com/batata-frita/redux-heat  
  Redux side-effects as a function of state.
  
- **redux-saga-promise**  
  https://github.com/Vlemert/redux-saga-promise  
  Generator-less implementation of Redux-Saga
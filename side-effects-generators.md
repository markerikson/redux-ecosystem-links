### Side Effects - Generators


- **redux-saga**  
  https://github.com/redux-saga/redux-saga  
  Generator-based side effects approach.  Create "sagas", which act like background threads or daemons that can listen for actions and dispatch objects describing side effects.
  
- **redux-ship**  
  https://github.com/clarus/redux-ship  
  Redux Ship is a Redux middleware for side effects which focuses on: composition: you can duplicate and reuse sub-stores, as you would do with React components; typing: you can type check your code with 100% coverage in Flow; testing: you can run unit tests of your side effects, by taking snapshots of their execution traces.
  
- **redux-side-effects**  
  https://github.com/salsita/redux-side-effects  
  Redux toolset for keeping all the side effects inside your reducers while maintaining their purity, using generators.
  
- **redux-yield-effect**  
  https://github.com/wizardzloy/redux-yield-effect  
  Declarative side effects for redux with generators
  
- **Redux Rungen**  
  https://github.com/youknowriad/redux-rungen  
  Generator middleware for Redux (Based on rungen).  Similar to redux-saga, but with some simplifications.  
  
- **redux-task**  
  https://github.com/sskyy/redux-task  
  A Side Effects enhancer for redux. The idea is simple: By given an asynchronous task(such as submitting data to server) a name, redux-task will create and handle the task state for you automatically. Then you can retrieve the state with the task name in your component easily. No need to create store state like isSubmitting or submitFailed and manully change them any more. 
  
- **redux-fork**  
  https://github.com/floxjs/fork  
  Non blocking async call effects.
  
- **reelm**  
  https://github.com/tihonove/reelm  
  Awesome effect management library for redux
  
- **redux-typed-saga**  
  https://github.com/goshakkk/redux-typed-saga  
  Redux-typed-saga is an alternative, well-typed take on the awesome redux-saga. The inspiration for typing side effects came from Redux Ship. However, Redux Ship has a totally different paradigm.  This experimental project aims to rethink redux-saga with types as first-class citizens.
  

#### Redux-Saga extensions  

- **react-redux-saga**  
  https://github.com/threepointone/react-redux-saga  
  React bindings for redux-saga, allowing you to dynamically start sagas by mounting them as React components
  
- **redux-saga-debounce-effect**  
  https://github.com/madewithlove/redux-saga-debounce-effect  
  A small debounce effect for redux-saga
  
- **redux-saga-combine-latest**  
  https://github.com/jhewlett/redux-saga-combine-latest  
  Wait for several action types to be dispatched before handling them

- **redux-saga-helpers**  
  https://github.com/sebinsua/redux-saga-helpers  
  Error-handling for redux-saga.  This library provides a selection of small utilities to better handle sagas.

- **redux-saga-sugar**  
  https://github.com/jasonHzq/redux-saga-sugar  
  Utilities for redux-saga: polling, fetching, and more.

- **eslint-plugin-redux-saga**  
  https://github.com/pke/eslint-plugin-redux-saga  
  ESLint rules for redux-saga.
  
- **redux-saga-process**  
  https://github.com/Dash-OS/redux-saga-process  
  Redux Saga Process (RSP) introduces an opinionated pattern for building modular, clean, and powerful redux-sagas by running them within ES6 classes and providing them with an encapsulated, simple, and powerful API. 
  
- **redux-saga-kit**  
  https://github.com/wix-private/redux-saga-kit  
  Utilities to help create and manage sagas.
  
- **redux-saga-watch-actions**  
  https://github.com/heygrady/redux-saga-watch-actions  
  Helper methods for managing sagas that respond to actions. Similar in style to redux-actions.
  
- **redux-saga-hoc**  
  https://github.com/hajjiTarik/redux-saga-hoc  
  A react HOC that can be plugged into react components and the saga middleware saga.  It allows adding, starting, and stopping saga functions within a react component.
  
- **redux-belt**  
  https://github.com/store2be/redux-belt  
  Opinionated helpers for Redux and Redux-Saga, including action creators and saga triggering
  
- **redux-saga-utils**  
  https://github.com/DmitryFillo/redux-saga-utils  
  High level utils for redux-saga. These utils are based on the native redux-saga effects.
  
- **redux-saga-api-call**  
  https://github.com/goncy/redux-saga-api-call  
  A simple method to simplify api calls, instead of calling the api and catch the response and error to dispatch the success and failure action, this call will do that for you.
  
- **redux-saga-request**  
  https://github.com/DylanVann/redux-saga-request  
  Helper for running async functions and dispatching actions in redux saga.
  
- **saga-monitor**  
  https://github.com/clarketm/saga-monitor  
  Simple, elegant, and configurable redux-saga monitor 
  
- **action-sagas**  
  https://github.com/manaflair/action-sagas  
  Add extra capabilities to your action creators by allowing them to dispatch sagas
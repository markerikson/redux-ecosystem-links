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
  https://github.com/wzrdzl/redux-yield-effect  
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
  
- **corrie**  
  https://github.com/alex-shnayder/corrie  
  Embrace the power of coroutines to restrain side effects 
  
- **edge-effects**  
  https://github.com/eiriklv/edge-effects  
  Pluggable runtime effects engine (think redux-saga, except entirely pluggable) 
  
- **redux-fibers**  
  https://github.com/elierotenberg/redux-fibers  
  Managed async coroutines/fibers for Redux 
  
- **effects-as-data-redux**  
  https://github.com/orourkedd/effects-as-data-redux  
  Connects Redux and the author's "effects-as-data" library for declarative side effects.
  
- **redux-iterate**  
  https://github.com/doasync/redux-iterate  
  Use (async) generators as action creators to yield actions. This middleware will handle dispatched iterators ('nextable' objects).
  
- **redux-thunk-generators**  
  https://github.com/doasync/redux-thunk-generators  
  Thunk middleware for Redux supporting generators 
  

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
  
- **redux-saga-routines**  
  https://github.com/afitiskin/redux-saga-routines  
  A smart action creator for Redux Saga. Useful for any kind of async actions like fetching data. Also fully compatible with Redux Form. Reworked idea of redux-saga-actions
  
- **redux-saga-thunk**  
  https://github.com/diegohaz/redux-saga-thunk  
  Dispatching an action handled by redux-saga returns promise
  
- **redux-saga-rn-alert**  
  https://github.com/itinance/redux-saga-rn-alert  
  Alert.alert()-Support for side effects with redux-saga in react-native-apps 
  
- **redux-saga-location**  
  https://github.com/itinance/redux-saga-location  
  Helps to fetch geo-location within a saga (or any other generator function) and put the result into the redux-store.
  
- **saga-task-manager**  
  https://github.com/Dash-OS/saga-task-manager  
  A Task Manager to help manage forked tasks from redux-saga. Tasks have a "category" and "id" which is used to identify and ensure we don't run more than one of any given task.
  
- **SagaObservable**  
  https://github.com/Dash-OS/saga-observable  
  Abstracts the PromiseQueue lib to add the redux-saga cancellation logic on top. This allows us to easily wait for future actions / events in our sagas.
  
- **saga-geolocation-observer**  
  https://github.com/Dash-OS/saga-geolocation-observer  
  Use saga-observables to provide a simple way to use the HTML5 Geolocation API with redux-saga 
  
- **redux-saga-rest**  
  https://github.com/zach-waggoner/redux-saga-rest  
  A thin wrapper around the Fetch API that integrates with redux-saga and supports request/response middleware.
  
- **redux-saga-compose**  
  https://github.com/sdd/redux-saga-compose  
  Small utility for redux-saga to allow composing of middleware sagas, in the style of koa-compose.  This module is intended for use when redux-saga is used in order to orchestrate a very complex data pipeline.
  
- **resaga**  
  https://github.com/QuanDhz/resaga  
  A reusable Reducer and Saga HOC library.  Resaga helps handle fetching data and dispatching actions when the data is fetched.
  
- **react-redux-toolbox**  
  https://github.com/bamlab/react-redux-toolbox  
  Set of utils for React and Redux development.  Saga decorators to handle loading status and API exceptions, plus a component and reducer for loading status.
  
- **redux-saga-api**  
  https://github.com/shengnian/redux-saga-api  
  A REST style API fetch for redux-saga 
  
- **redux-saga-timeout**  
  https://github.com/itinance/redux-saga-timeout  
  setTimeout-Support within redux-saga 
  
- **redux-saga-api-call-routines**  
  https://github.com/alvelig/redux-saga-api-call-routines  
  Adds authentication header to any "*_REQUEST" action, and refreshes tokens if a 403 error is returned.
  
- **recompose-saga**  
  https://github.com/robinpowered/recompose-saga  
  A recompose-like library for redux-saga
  
- **reduxSagaOneLiners**  
  https://github.com/kjr247/reduxSagaOneLiners  
  Reusable generic sagas for making CRUD API calls
  
- **redux-saga-queue**  
  https://github.com/gleb-smagliy/redux-saga-queue  
  High level effect to handle actions sequentially 
  
- **redux-saga-catch**  
  https://github.com/cyrilluce/redux-saga-catch  
  Helpers for redux-saga that auto-wrap sagas with try-catch to prevent a thrown error from stopping all sagas.
  
- **redux-saga-requests**  
  https://github.com/klis87/redux-saga-requests  
  Redux-Saga addon to simplify handling of AJAX requests. It supports Axios and Fetch API, in the future additional integrations will be added, as they can be implemented in a plugin fashion.
  
- **redux-saga-crud-service**  
  https://github.com/eakarpov/redux-saga-crud-service  
  Generates crud methods for services using saga middleware 
  
- **redux-saga-injector**  
  https://github.com/isychev/redux-saga-injector  
  A lightweight library for dynamic connections of sagas. The library provides service for quick and easy connection/disconnection of sagas anytime and anywhere in your code
  
- **redux-saga-takeuntil**  
  https://github.com/sh1989/redux-saga-takeuntil  
  A utility that is useful if you wish to start a saga when a particular action is dispatched, and then cancel it when another action is dispatched.
  
- **redux-saga-requests**  
  https://github.com/klis87/redux-saga-requests  
  Redux-Saga addon to simplify handling of AJAX requests. It supports Axios and Fetch API, but different integrations could be added, as they are implemented in a plugin fashion.
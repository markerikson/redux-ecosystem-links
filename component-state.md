### Component/Local State and Encapsulation


#### Component/Local State

- **redux-ui**  
  https://github.com/tonyhb/redux-ui  
  Easy UI state management for react redux.  Think of redux-ui as block-level scoping for UI state.

- **redux-react-local**  
  https://github.com/threepointone/redux-react-local  
  Creates component wrappers with per-instance local state stored in Redux, as well as locally scoped actions and reducers
  
- **redux-component**  
  https://github.com/tomchentw/redux-component  
  Manage a component's local state using a local redux store.  A isolated redux store is created for each React component instance.
  
- **redux-state**  
  https://github.com/babotech/redux-state  
  connect() style implementation of storage a local state for reusable components
  
- **redux-component-state**  
  https://github.com/cef62/redux-component-state  
  Component level state's manager using redux reducers to support on-demand store creation.
  
- **redux-bind**  
  https://github.com/sorrycc/redux-bind  
  A Higher Order Component to keep component state in a Redux store.
  
- **redux-extract-state**  
  https://github.com/caojs/redux-extract-state  
  Extract local component state to redux store.
  
- **Redux Namespace**  
  https://github.com/evanrs/redux-namespace  
  Dead simple tool moving component local state to a Redux store namespace.
  
- **redux-as-component**  
  https://github.com/lapanoid/redux-as-component  
  Wrap your app to use it as component inside other app
  
- **redux-state-props**  
  https://github.com/soulie/redux-state-props  
  stateProps is as a Higher-order Component to insert state as props into Stateless React Components in a declarative way (see stateProps for more info).  This package extends stateProps to use redux as a store.
  
- **redux-ephemeral**  
  https://github.com/ashaffer/redux-ephemeral  
  Library for managing transient local state in redux. Uses a hash array mapped trie internally, so it is extremely performant by default, but you still deal only with plain JS objects, and your redux state atom is still serializable in the same way.
  
- **relux**  
  https://github.com/namelos/relux  
  Generate dynamic actions and reducers.
    
- **react-redux-substate**  
  https://github.com/titoasty/react-redux-substate  
  Create substates to isolate your components.  This is a very simple way to add substates to the components. It does not ensure fractality of the components because substates are stored in the app state.
  
- **react-redux-isolate**  
  https://github.com/Trimma/react-redux-isolate  
  Isolate Redux apps to sandboxed state subtrees.  Provides a way for multiple react-redux apps to share the same state tree, adhering to the principle of Single Source Of Truth, without requiring changes to the apps. It enables you to use sub-apps inside your redux app, without using multiple stores, and without requiring that you write your sub-apps in a particular manner. 
  
- **react-redux-setstate**  
  https://github.com/rundmt/react-redux-setstate  
  Use this.props.setState just like this.setState.
  
- **Redux "subapps" example**  
  https://gist.github.com/gaearon/eeee2f619620ab7b55673a4ee2bf8400  
  A small snippet from Dan Abramov demonstrating setting up a separate store for each individual "sub-app" instance in a page.
  
- **ReduxLocal**  
  https://github.com/Wildhoney/ReduxLocal  
  Redux helper for maintaining pseudo-local state in a single tree.  Philosophies: Reducers should only exist in one place, rather than assigned to individual components; Be able to dictate which components are updated with shouldComponentUpdate; Provide an overt distinction between standard dispatches and pseudo-local dispatches; Allow actions to be written without pseudo-local actions in mind.

- **redux-ui-state**  
  https://github.com/jamiecopeland/redux-ui-state  
  Component state for Redux applications
  
- **react-state-redux**  
  https://github.com/ryo33/react-state-redux  
  Clear away states from React components.  It helps us move states to the Redux store from React components, especially when your components is dynamically used in many places. 
  
- **redux-container-state**  
  https://github.com/HansDP/redux-container-state  
  https://github.com/HansDP/redux-container-state-globalstate  
  https://github.com/HansDP/redux-container-state-saga  
  https://github.com/HansDP/redux-container-state-thunk  
  Local container state for Redux based on the Elm Architecture.  This project evolves the ideas of redux-elm, but avoids opinions about specific implementations of Side Effects and tries to be more in line with the Redux approach of reducers.
  
- **redux-internal-state**  
  https://github.com/josepot/redux-internal-state  
  https://github.com/josepot/react-redux-internal-state  
  Manage the internal state of your components from the redux-store
  
- **redux-fractal**  
  https://github.com/gcazaciuc/redux-fractal  
  Local component state & actions in Redux.  Provides the means to hold up local component state in Redux state, to dispatch locally scoped actions and to react to global ones.  What Redux fractal offers is a Redux private store for each component with the notable difference that the component state is actually held up in your app's state atom, so all global and components ui state live together.
  
- **isolated-react-redux**  
  https://github.com/neekey/isolated-react-redux  
  Provide a isolated redux style way to handle state for components
  
- **Lean Redux**  
  https://github.com/epeli/lean-redux  
  Redux state like local component state. Basic Redux state access and updating should be simple as it is with the component local state. Redux state can be scoped to the components. Plays well with other tools in the Redux community. Lean Redux is build on top of the new connectAdvanced() primitive of React Redux 5.0 and implements the same optimizations as connect().
  
- **Modux**  
  https://github.com/PCreations/modux-js  
  modux-js is a lightweight framework to seamlessly build modular, composable, encapsulated and fractable redux apps.  The main goal of this project is to let you write vanilla redux and let modux-js encapsulate it for you by scoping your actions, reducers, selectors and sagas. Your moduxes are only aware of their own context. 
  
- **redux-state-keys**  
  https://github.com/LFDM/redux-state-keys  
  Utility functions to scope behavior to certain state keys
  
- **redux-fly**  
  https://github.com/MrEfrem/redux-fly  
  A simple set of APIs to manage React component state in Redux, reuse components, and gradually register reducers at any place in the Redux tree.
  
- **redux-doghouse**  
  https://github.com/DataDog/redux-doghouse  
  http://engineering.datadoghq.com/redux-doghouse--creating-reusable-react-redux-components-through-scoping/  
  redux-doghouse is a library that aims to make reusable components easier to build with Redux by scoping actions and reducers to a particular instance of a component.  It includes tools to help you build Scoped Actions and Scoped Reducers with minimal modifications to your code.
  
- **redux-dialog**  
  https://github.com/suciuvlad/redux-dialog  
  A Higher Order Component using react-redux to keep dialog state in a Redux store
  
- **react-redux-uuid**  
  https://github.com/eloytoro/react-redux-uuid  
  A place to keep your disposable but application-related component state data
  
- **redux-setstate**  
  https://github.com/dustinws/redux-setstate  
  A setState api for purely functional components.
  
- **Redux Subspace**  
  https://github.com/ioof-holdings/redux-subspace  
  For a Redux connected React component, SubspaceProvider allows you to present a sub-view of the state to the component, allowing it to be ignorant of parent state structure. This means you can reuse these components in multiple parts of your app, or even multiple applications that have different store structures.

- **redux-dynamix**  
  https://github.com/jake-daniels/redux-dynamix  
  Redux Dynamix is a store enhancer that allows you dynamically add and remove reducers (and therefore slices of application state). 
  
- **redux-scope**  
  https://github.com/bsingr/redux-scope  
  An idea for modularizing redux components using a scoped store 
  
- **redux-actuator**  
  https://github.com/molefrog/redux-actuator  
  Trigger events inside components by reacting on pure state changes. Actuator keeps you from writing component lifecycle hooks boilerplate code by providing declarative API.
  
- **react-redux-sub-app**  
  https://github.com/rtkhanas/react-redux-sub-app  
  A small component to allow defining Redux sub-apps within a component tree
  
- **react-redux-combine-components**  
  https://github.com/simlrh/react-redux-combine-components  
  With React Redux Combine Components you can assign components to different properties of the state tree the same way you do with reducers. This aids reusability, as components need to know nothing about global state, and improves performance as they are only rerendered on change to their substree, instead of the global state.
  
- **redux-fragments**  
  https://github.com/Talamond/redux-fragments  
  A helper library for managing and reusing redux state, actions and react components. 
  
- **redux-container**  
  https://github.com/ali322/redux-container  
  Helps create a store for individual components
  
- **prism**  
  https://github.com/salsita/prism  
  React / Redux action composition made simple, using the action wrapping approach from Elm. (Formerly Redux-Elm)
  
- **redux-scope-helpers**  
  https://github.com/georgeawwad/redux-scope-helpers  
  Functions for generating scoped action creators and reducers
  
- **redux-atom**
  https://github.com/bulicmatko/redux-atom  
  https://github.com/bulicmatko/react-redux-atom  
  Small utilities to generate encapsulated Redux logic and connected React components
  
- **with-component-state**  
  https://github.com/chee/with-component-state  
  Higher order component that will automatically create state for your redux components, and give you the prop componentState as well as the prop setState which works like this.setState on class components.
  
- **redux-local-state**  
  https://github.com/t-benze/redux-local-state  
  A library for defining "local" Redux sub-stores by ID
  
- **redux-rubberstamp**  
  https://github.com/mahaplatform/redux-rubberstamp  
  Pattern for hosting multiple versions of a component tree inside the main state tree
  
- **redux-fancy**  
  https://github.com/DJercic/redux-fancy  
  Manage your UI state with Redux.  Each component gets a setState prop function that behaves similar to React setState, and all the props that were passed through initial state.
  
- **pyradux**  
  https://github.com/zaptree/pyradux  
  Composable Redux state for React.  Allows for creating redux stores that are tied to a component similar to local state. This means a new redux store for each instance of a component using pyradux will be created.
  
- **redux-interface**  
  https://github.com/booqable/redux-interface  
  A reducer and HOC for tracking component state
  
- **redux-transient**  
  https://github.com/lucasconstantino/redux-transient  
  provides a Redux store enhancer that will listen for specific action for adding and removing new reducers. It will keep an array with the store's original reducer and the temporary ones.  To facilitate usage with React, redux-transient also provides a Higher-Order component to attach a transient reducer during a React component's life cycle - meaning it will attach when mounting, and detach when unmounting.
  
- **alveron**  
  https://github.com/rofrischmann/alveron  
  Alveron is a highly opinionated state architecture for React using Redux.  It is heavily inspired by The Elm Architecture and aims to simplify component-based state management.
  
- **redux-fractal-connect**  
  https://github.com/typeetfunc/redux-fractal-connect  
  Make connect to Redux store fractal 
  
- **react-attach**  
  https://github.com/NikolayBorisov/react-attach  
  Attach Redux Store to a React Original Component State
  
- **redux-copier**  
  https://github.com/DreamAndDead/redux-copier  
  redux-copier helps to make High Order Component reusable again, by allowing multiple instances of components with separate behavior.
  
- **react-redux-set-local**  
  https://github.com/fongandrew/react-redux-set-local  
  Local Redux state in React without writing your own reducers.  Like react-redux, we use a higher-order component to connect a presentational component with a specific portion of our Redux state. Unlike react-redux (and some other prior attempts to create "local" Redux state), rather than passing down a dispatch function, we pass down a setLocal function that we can use to replace existing state.
  
- **Redaim**  
  https://github.com/Noviel/redaim  
  Redaim - reusable actions and reducers for redux. Aim domain's target - add additional dimension for actions and reducers to specify where exactly on the state tree action should be applied.
  
- **redux-plugin**  
  https://github.com/samuelchvez/redux-plugin  
  Redux sub-architecture for 'plugin' React components.  Helps define and manage reducers and state for components that are managed by Redux.
  
- **react-redux-ui-state**  
  https://github.com/jasonmorita/react-redux-ui-state  
  React higher order component to provide UI state for components.  Reduce the need to reach for setState to save time for simple flags, reduce reducer boilerplate for properties like UI flags, Reduce tediousness of instances of the same component needing the same flags.
  
  
#### Simplified / Key-Value State

- **Redux Cursor**  
  https://github.com/Dashlane/redux-cursor  
  Local private slices of a global store for component encapsulation in a Redux model.  Redux does not like the cursors in their general implementation, but the criticism is focused purely on the low-level ability to mutate the state at will. redux-cursor resolves that by relying on actions just as base Redux.
  
- **redux-mount**  
  https://github.com/popc0rn/redux-mount  
  Mount data on a path and change state values on the fly. No need to create reducers, actions, or selectors to handle view-specific state yourself.
  
- **reduceless**  
  https://github.com/nosovsh/reduceless  
  Redux helpers to avoid odd reducers, actions and constants.  Specify a path into your state, get it passed in and a setter to update it.
  
- **Reduction Sauce**  
  https://github.com/ericwooley/reduction-sauce  
  Simple key value reducers without boilerplate
  
- **redux-values**  
  https://github.com/alexesDev/redux-values  
  Simple key-value storage for Redux
  
- **react-redux-private-props**  
  https://github.com/dylanonelson/react-redux-private-props  
  React/Redux add-on for managing private component state in a Redux store 
  
#### Modularity and Encapsulation

- **redux-brick**  
  https://github.com/leeching/redux-brick  
  redux-brick is a simplified building strategy of Redux apps. Redux system could be built from Redux bricks.
  
- **modular-react-redux**  
  https://github.com/dchambers/modular-react-redux  
  Allows you to build your 'react-redux' application as a set of modular swappable components, but still have a single global Redux store for the entire app.
  
- **redux-features**  
  https://github.com/jcoreio/redux-features  
  https://github.com/jcoreio/react-redux-features  
  A powerful feature-oriented programming framework for redux
  
- **redux-plugin**  
  https://github.com/neurosnap/redux-plugin  
  A work-in-progress library for organizing code by feature without worrying about circular dependencies.  Redux-Plugin is a dependency injector that creates clear boundaries between plugins.
  
- **redux-segmentize**  
  https://github.com/robbyemmert/redux-segmentize  
  Organize your redux store into partitions. Automatically manage state for each instance of your components. 
  
- **redux-register-module**  
  https://github.com/birdy-/redux-register-module  
  Allows you to register reducer and saga handler from your module. With this, your module stays a standalone package.
  
- **redux-blocks**  
  https://github.com/alonbardavid/redux-blocks  
  redux-blocks is a library for isolating and combining redux modules (referred to here on out as blocks). It makes writing reusable redux code easier and more flexible.
  
- **duxtape**  
  https://github.com/brianneisler/duxtape  
  Module and util framework for redux.  Introduces an abstract module construct for redux. Allows modularization of functionality and easy plug and play workflow, with a hook system for extending the functionality of redux
  
- **redux-segments**  
  https://github.com/dennisgulich/redux-segments  
  Library for writing reusable redux modules.  Writing reducers, action creators and mapping everything to the UI is tedious and time consuming, redux-segments solves this issue by breaking up the redux boilerplate into generic reusable modules.

- **redux-stack**  
  https://github.com/jondot/redux-stack  
  A library that helps you build modular, structured, and cleaner redux apps.  Redux Stack introduces a concept of initializers. Small pieces of integration code, per library, that "declares" how it integrates. Redux Stack will mesh these together to create your personalized store builder.
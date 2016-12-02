### Component/Local State and Encapsulation

- **redux-ui**  
  https://github.com/tonyhb/redux-ui  
  Easy UI state management for react redux.  Think of redux-ui as block-level scoping for UI state.

- **redux-react-local**  
  https://github.com/threepointone/redux-react-local  
  Creates component wrappers with per-instance local state stored in Redux, as well as locally scoped actions and reducers
  
- **Redux Cursor**  
  https://github.com/Dashlane/redux-cursor  
  Local private slices of a global store for component encapsulation in a Redux model.  Redux does not like the cursors in their general implementation, but the criticism is focused purely on the low-level ability to mutate the state at will. redux-cursor resolves that by relying on actions just as base Redux.
  
- **redux-brick**  
  https://github.com/leeching/redux-brick  
  redux-brick is a simplified building strategy of Redux apps. Redux system could be built from Redux bricks.
  
- **redux-component**  
  https://github.com/tomchentw/redux-component  
  Manage a component's local state using a local redux store.  A isolated redux store is created for each React component instance.
  
- **redux-state**  
  https://github.com/babotech/redux-state  
  connect() style implementation of storage a local state for reusable components
  
- **redux-mount**  
  https://github.com/popc0rn/redux-mount  
  Mount data on a path and change state values on the fly. No need to create reducers, actions, or selectors to handle view-specific state yourself.
  
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
  https://www.npmjs.com/package/redux-state-props  
  stateProps is as a Higher-order Component to insert state as props into Stateless React Components in a declarative way (see stateProps for more info).  This package extends stateProps to use redux as a store.
  
- **redux-ephemeral**  
  https://github.com/ashaffer/redux-ephemeral  
  Library for managing transient local state in redux. Uses a hash array mapped trie internally, so it is extremely performant by default, but you still deal only with plain JS objects, and your redux state atom is still serializable in the same way.
  
- **relux**  
  https://github.com/namelos/relux  
  Generate dynamic actions and reducers.
  
- **reduceless**  
  https://github.com/nosovsh/reduceless  
  Redux helpers to avoid odd reducers, actions and constants.  Specify a path into your state, get it passed in and a setter to update it.
  
- **Reduction Sauce**  
  https://github.com/ericwooley/reduction-sauce  
  Simple key value reducers without boilerplate
    
- **react-redux-substate**  
  https://github.com/titoasty/react-redux-substate  
  Create substates to isolate your components.  This is a very simple way to add substates to the components. It does not ensure fractality of the components because substates are stored in the app state.
  
- **redux-values**  
  https://github.com/alexesDev/redux-values  
  Simple key-value storage for Redux
  
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
  
- **modular-react-redux**  
  https://github.com/dchambers/modular-react-redux  
  Allows you to build your 'react-redux' application as a set of modular swappable components, but still have a single global Redux store for the entire app.
  
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
  
- **redux-uuid**  
  https://github.com/mkramb/redux-uuid  
  A place to keep your disposable but application-related component state data
  
- **Redux Subspace**  
  https://github.com/ioof-holdings/redux-subspace  
  For a Redux connected React component, SubspaceProvider allows you to present a sub-view of the state to the component, allowing it to be ignorant of parent state structure. This means you can reuse these components in multiple parts of your app, or even multiple applications that have different store structures.
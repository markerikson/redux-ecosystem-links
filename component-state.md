### Component/Local State

- **redux-ui**  
  https://github.com/tonyhb/redux-ui  
  Easy UI state management for react redux.  Think of redux-ui as block-level scoping for UI state.

- **redux-react-local**  
  https://github.com/threepointone/redux-react-local  
  Creates component wrappers with per-instance local state stored in Redux, as well as locally scoped actions and reducers

- **Redux-Staged-State**  
  https://github.com/mboperator/redux-modules  
  The goal of this library is to provide a convenient way to manage transient state in a redux application.  The idea is similar to that of redux-form, but it differs in that it does not focus on forms, but on staged state, that is, parts of the state the a user intends to change but has not committed yet. Staged state may appear in different forms.
  
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

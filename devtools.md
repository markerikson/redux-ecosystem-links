### DevTools and Debugging


#### DevTools

- **Redux DevTools**  
  https://github.com/gaearon/redux-devtools  
  DevTools for Redux with hot reloading, action replay, and customizable UI 
  
- **Redux DevTools Extension**  
  https://github.com/zalmoxisus/redux-devtools-extension  
  Browser extension to show DevTools UI in separate browser windows rather than in-page (currently Chrome only)
  
- **Remote Redux DevTools**  
  https://github.com/zalmoxisus/remote-redux-devtools  
  Use Redux DevTools remotely for React Native, hybrid, desktop and server side Redux apps.
  
  
#### DevTools Monitors

- **Log Monitor**  
  https://github.com/gaearon/redux-devtools-log-monitor  
  The default monitor for Redux DevTools with a tree view
  
- **Dock Monitor**  
  https://github.com/gaearon/redux-devtools-dock-monitor  
  A resizable and movable container for other monitors.

- **Inspector Monitor**  
  https://github.com/alexkuz/redux-devtools-inspector  
  A state monitor that provides a convenient way to inspect "real world" app states that could be complicated and deeply nested, by pinning keys of interest and showing state diffs.
  
- **Diff Monitor**  
  https://github.com/whetstone/redux-devtools-diff-monitor  
  The primary goal of this monitor is to highlight the changes to an application's state from action to action.
  
- **Filterable Log Monitor**  
  https://github.com/bvaughn/redux-devtools-filterable-log-monitor/  
  Filterable tree view monitor for Redux DevTools.  Actions are collapsed by default but they can be expanded by clicking on the action type. Strings and regular expressions can be used to filter actions by type as well as to filter the state tree by nodes or values.
  
- **Chart Monitor**  
  https://github.com/romseguy/redux-devtools-chart-monitor  
  A chart monitor for Redux DevTools.  It shows a real-time view of the store aka the current state of the app.
  
- **Slider Monitor**  
  https://github.com/calesce/redux-slider-monitor  
  Uses a slider based on react-slider to slide between different recorded actions. It also features play/pause/step-through.
  
- **Dispatch Monitor**  
  https://github.com/YoruNoHikage/redux-devtools-dispatch  
  A monitor that lets you manually dispatch actions to see how the app reacts.
  
- **Import Export Monitor**  
  https://github.com/lapanoid/redux-import-export-monitor  
  A simple monitor for Redux DevTools that enables exporting, then importing the serialized state of a Redux application. It looks like a prompt() modal, but without the character limit.
  

#### Logging
  
- **redux-logger**  
  https://github.com/fcomb/redux-logger  
  Redux middleware that logs state diffs after actions are dispatched.
  
- **redux-node-logger**  
  https://github.com/low-ghost/redux-node-logger  
  Just a logger middleware for redux that will write all redux actions and state changes to the node console. Entirely based on redux-logger
  
- **redux-diff-logger**  
  https://github.com/fcomb/redux-diff-logger  
  Diff logger between states for redux
  
- **redux-debug**  
  https://github.com/lapwinglabs/redux-debug  
  debug() as redux middleware. Similar to redux-logger, but works both on the server and in the client.
  
- **redux-raven-middleware**  
  https://github.com/ngokevin/redux-raven-middleware  
  Redux middleware for sending error reports to Sentry through raven-js.
  
- **redux-perf-middleware**  
  https://github.com/AvraamMavridis/redux-perf-middleware  
  Redux performance middleware, Measure the time that the actions need to change the state
  
- **redux-log**  
  https://github.com/joshrtay/redux-log  
  Simple log of redux actions, good for testing.
  
- **redux-log-slow-reducers**  
  https://github.com/michaelcontento/redux-log-slow-reducers  
  Warn about slow reducers used in your redux app
  
- **redux-state-trail**  
  https://github.com/darthtrevino/redux-state-trail  
  This middleware tracks a trail of actions of a user interacting with an application. This trail may be posted to a development server and replayed in development mode.
  
- **Redux State History**  
  https://github.com/inakianduaga/redux-state-history  
  Redux store enhancers / component for tracking and visualizing state changes & debugging remote sessions.  Inspired by the redux devtools and redux slider monitor, this package provides state recording/playback (i.e. "time travel") abilities for redux applications.
  
- **redux-log-errors**  
  https://github.com/kolodny/redux-log-errors  
  redux store enhancer to log errors while dispatching
  
  
 #### Linting
 
- **redux-immutable-state-invariant**  
  https://github.com/leoasis/redux-immutable-state-invariant  
  Redux middleware that detects mutations between and outside redux dispatches. For development use only.
  
- **redux-ensure-fsa**  
  https://github.com/meadow/redux-ensure-fsa  
  redux-ensure-fsa provides a middleware function to use as part of the redux dispatch chain. It is intended for use in development only to check that all actions at the end of the chain follow the Flux Standard Action protocol.
  
- **redux-fsa-linter**  
  https://github.com/maxmechanic/redux-fsa-linter  
  Redux middleware that validates incoming actions with Flux Standard Action. 
  
- **redux-unhandled-actions**  
  https://github.com/socialtables/redux-unhandled-action  
  Redux middleware that logs an error to the console when an action is fired and the state is not mutated
  
- **redux-action-propcheck**  
  https://github.com/itaylor/redux-action-propcheck  
  A Redux middleware that can check your redux action's property types against a provided specification of expected property types.
  
- **redux-freeze-state**  
  https://github.com/jfpalacios/redux-freeze-state  
  Use freezeState with your reducer to find spots in your app where you are mutating state. It is not recommended to use this in production as it recursively freezes objects and could affect performance.
  
- **redux-freeze**  
  https://github.com/buunguyen/redux-freeze  
  Redux middleware that prevents state from being mutated anywhere in the app. When mutation occurs, an error will be thrown by the runtime. This is useful during development mode to ensure that no part of the app accidentally mutates the state.
  
- **redux-validator**  
  https://github.com/MaxLee1994/redux-validator  
  Action parameter validator middleware for redux
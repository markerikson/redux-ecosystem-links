### DevTools and Debugging


#### DevTools

- **Redux DevTools**  
  https://github.com/gaearon/redux-devtools  
  DevTools for Redux with hot reloading, action replay, and customizable UI 
  
- **Redux DevTools Extension**  
  https://github.com/zalmoxisus/redux-devtools-extension  
  Browser extension to show DevTools UI in separate browser windows rather than in-page (currently Chrome only)
  
  
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
  

#### Debugging and Development

- **redux-immutable-state-invariant**  
  https://github.com/leoasis/redux-immutable-state-invariant  
  Redux middleware that detects mutations between and outside redux dispatches. For development use only.
  
- **redux-ensure-fsa**  
  https://github.com/meadow/redux-ensure-fsa  
  redux-ensure-fsa provides a middleware function to use as part of the redux dispatch chain. It is intended for use in development only to check that all actions at the end of the chain follow the Flux Standard Action protocol.
  
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
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
  
- **Reactotron**  
  https://github.com/skellock/reactotron  
  Control, monitor, and instrument your React DOM and React Native apps. From the comfort of your TTY.
  
- **react-gui-debugger**  
  https://github.com/dittonjs/react-gui-debugger  
  A dock that lets you view you components props and state without putting debuggers and console.logs all over the place. Inspired by redux-devtools.
  
- **redux-saga-devtools**  
  https://github.com/redux-saga/redux-saga-devtools  
  Saga monitor and UI devtool for redux-saga.
  
- **Seedux**  
  https://github.com/reduxify/seedux  
  A Chrome developer tool that provides a new tab that actively logs and visualizes the Redux data flow, enabling easier, faster debugging of any React-Redux implementation.
  
- **Redux DevTools Instrumentation**  
  https://github.com/zalmoxisus/redux-devtools-instrument  
  Redux enhancer used along with Redux DevTools or Remote Redux DevTools.
  
- **React-Sight**  
  https://github.com/React-Sight/React-Sight  
  Visualization tool for React component trees, with support for Fiber, React-Router v4, and Redux
  
- **remotedev-react-state**  
  https://github.com/jhen0409/remotedev-react-state  
  Inspecting / time travelling state changes of a React component on the Redux DevTools Extension or React Native Debugger 
  
- **redux-viewer**  
  https://github.com/AmitMY/redux-viewer  
  A simple CLI tool to view the graph of events and actions based on parsing specific documentation comments.
  
- **reselect-tools**  
  https://github.com/skortchmark9/reselect-tools  
  https://github.com/skortchmark9/reselect-devtools-extension  
  Debugging tools for Reselect.  Check selector dependencies, inputs, outputs, and recomputations at any time.  Output a JSON representation of your selector graph.  Tools include a library and a Chrome browser extension.
  
- **kuker**  
  https://github.com/krasimir/kuker  
  A browser devtools extension that can show events and changes from many sources, including Redux stores, Redux-Saga, Vue, Angular, MobX, DOM elements,a nd many more
  
  
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
  
- **Multiple Monitor**  
  https://github.com/YoruNoHikage/redux-devtools-multiple-monitors  
  Integrate multiple monitors to your redux devtools.
  
- **Redux DevTools Clipboard**  
  https://github.com/ryanashcraft/redux-devtools-clipboard  
  Dispatch your actions manually to test if your app reacts well.
  
- **Redux DevTools Profiler Monitor**  
  https://github.com/pbomb/redux-devtools-profiler-monitor  
  A custom monitor for Redux DevTools to profile a given action in Chrome DevTools
  
- **Periscope Monitor**  
  https://github.com/shea-hawkins/periscope  
  In-depth monitoring for Redux applications.  View actions on a timeline, group by type, and more.
  
- **Upload-Download Monitor**  
  https://github.com/Nase00/redux-devtools-upload-download-monitor  
  A monitor for Redux DevTools to enable uploading and downloading of serialized application states. Pairs well with Redux Slider Slider Monitor!  This is a re-implementation of Redux Import Export Monitor, with the goal being to work well with very large application states.
  

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
  
- **mole-redux**  
  https://github.com/molejs/mole-redux  
  mole-redux is a tiny helper library that works as a middleware for redux, allowing easy state-action molejs. Underneath, it uses the report() method from mole-reporter one of the three independent packages that form the whole molejs service stack.
  
- **redux-catch**  
  https://github.com/sergiodxa/redux-catch  
  Error catcher middleware for Redux reducers and middlewares.
  
- **redux-bug-reporter**  
  https://github.com/dtschust/redux-bug-reporter  
  A bug reporter and bug playback tool for redux.  Includes easy bug reporting, logging of state, redaction of sensitive information, easy bug playback, and more.
  
- **redux-simple-logger**  
  https://github.com/pinn3/redux-simple-logger  
  Super simple cli logger middleware for redux
  
- **redux-action-replay-middleware**  
  https://github.com/danislu/redux-action-replay-middleware  
  Middleware for storing redux actions in localstorage and replaying them later. Usefull for QA reproducing bugs etc.
  
- **Redux TrackJS Action Logger**  
  https://github.com/timarney/redux-trackjs-logger  
  Logs user actions to TrackJS so you can replay them later.
  
- **redux-vcr**  
  https://github.com/joshwcomeau/redux-vcr  
  A Redux devtool that lets you replay user sessions in real-time.
  
- **redux-bugsnag-middleware**  
  https://github.com/netguru/redux-bugsnag-middleware  
  Redux middleware that wraps exceptions in actions and sends them to Bugsnag with current state
  
- **redux-action-log**  
  https://github.com/AgentME/redux-action-log  
  A redux store enhancer which allows you to record the redux action history and access it. It can be configured to have a maximum number of actions to keep in the history. Early actions will be removed from the history, and the redux state of the beginning of the history will be recorded.
  
- **redux-bugsnag**  
  https://github.com/restorando/redux-bugsnag  
  Redux middleware that logs to Bugsnag
  
- **redux-log-diff**  
  https://github.com/Bebersohl/redux-log-diff  
  A simple redux middleware that logs changes to the state after every action. 
  
- **redux-trace**  
  https://github.com/hajjiTarik/redux-trace  
  A logging middleware that shows action and state contents as console tables
  
- **raven-for-redux**  
  https://github.com/captbaritone/raven-for-redux  
  Logs all dispatched actions to Raven as "breadcrumbs" and attaches your current Redux store as additional context.  Inspired by redux-raven-middleware but with a slightly different approach.
  
- **redux-airbrake**  
  https://github.com/alexcastillo/redux-airbrake  
  Redux middleware for Airbrake error logging
  
- **redux-action-logger**  
  https://github.com/hudl/redux-action-logger  
  A simple, extensible redux middleware system to generate logs from actions. The intent of this library is to make logging and event reporting as simple and consistent as possible.
  
- **redux-logging-reducer**  
  https://github.com/tristanls/redux-logging-reducer  
  Adds logging of dispatched actions to your reducer functionality storing dispatched actions in the reducer's store.
  
- **redux-heartbeat**  
  https://github.com/alechill/redux-heartbeat  
  A middleware for Redux providing a heartbeat that contains batched log of actions occurring between each beat.  Created for incrementally collecting usage data for driving analytics, contextual error reporting, even persisting replayable user sessions.
  
- **redux-request-manager**  
  https://github.com/sashafklein/redux-request-manager  
  Attaches a lightweight object to window which tracks request history as a tree and provides a simple interface for tracking actions going out through redux-api-middleware or internally.
  
- **redux-promise-middleware-times**  
  https://github.com/lemonleon/redux-promise-middleware-times  
  Record the time consumed by each asynchronous action, asynchronous solutions that rely on redux-promise-middleware.
  
- **reselect-devtools**  
  https://github.com/ajwhite/reselect-devtools  
  A set of devtools to help debug reselect selectors by logging changes.
  
- **redux-action-replay**  
  https://github.com/recruit-tech/redux-action-replay  
  Replay your redux actions in your application through Puppeteer.  Useful for renderer metrics and screenshots.
  
- **redux-logdown**  
  https://github.com/caiogondim/redux-logdown.js  
  redux-logdown is a tiny logger library for Redux written with logdown that supports localStorage.debug for enabling/disabling store logging.
  
- **redux-usage-report**  
  https://github.com/aholachek/redux-usage-report  
  This library tracks the way your app is using the data in your Redux store. By setting up the monitor in devtools you can see a live view of when different parts of your store are accessed
  
  
#### Mutation Detection

- **redux-immutable-state-invariant**  
  https://github.com/leoasis/redux-immutable-state-invariant  
  Redux middleware that detects mutations between and outside redux dispatches. For development use only.
  
- **redux-freeze-state**  
  https://github.com/jfpalacios/redux-freeze-state  
  Use freezeState with your reducer to find spots in your app where you are mutating state. It is not recommended to use this in production as it recursively freezes objects and could affect performance.
  
- **redux-freeze**  
  https://github.com/buunguyen/redux-freeze  
  Redux middleware that prevents state from being mutated anywhere in the app. When mutation occurs, an error will be thrown by the runtime. This is useful during development mode to ensure that no part of the app accidentally mutates the state.
  
- **redux-freezer**  
  https://github.com/tarodenberg/redux-freezer  
  Redux middleware that freezes store state after each update.
  
- **purityWarningReduxConnect**  
  https://gist.github.com/lelandrichardson/ff2392199b62c26759f2bf235676758b  
  A shallow-equality comparison function and wrapper for `connect` that will warn if a `mapState` function accidentally mutates values.  Used by AirBnB internally.

- **mutation-sentinel**  
  https://github.com/flexport/mutation-sentinel  
  https://flexport.engineering/optimizing-react-rendering-part-2-7b2e9a9ea21f  
  A library that uses ES6 Proxies to help detect accidental mutations
  
- **redux-pure-connect**  
  https://github.com/mmahalwy/redux-pure-connect  
  Check and log whether react-redux's connect method is passed methods that create impure props.   Built on top of lelandrichardson's gist for ensuring purity on mapStateToProps and other methods passed to connect.
  
- **redux-freeze-tag**  
  https://github.com/abbreviatedman/redux-freeze-tag  
  A tiny, tiny library that adds customizable immutability to Redux. It does this by using freeze-tag to enhance the reducer(s) you use to create your Redux store.
  
  
#### Linting and Validation

Also see the [Mutation Detection](#mutation-detection) section just above.
  
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
  
- **redux-validator**  
  https://github.com/MaxLi1994/redux-validator  
  Action parameter validator middleware for redux
  
- **redux-uncaught-promise**  
  https://github.com/laat/redux-uncaught-promise  
  Handle uncaught promises returned from dispatch.
  
- **redux-check**  
  https://github.com/jarredwitt/redux-check  
  Lets you run validations against parts of your state or against the action that was dispatched.
  
- **redux-duplicate-actions**  
  https://github.com/daviemakz/redux-duplicate-actions  
  A redux middleware that detects duplicate actions & shows this in the console
  
- **validstate**  
  https://github.com/lifechurch/validstate  
  Validstate is a javascript plugin for React+Redux applications to quickly validate state.
  
- **redux-json-schema-middleware**  
  https://github.com/simpleigh/redux-json-schema-middleware  
  JSON Schema middleware for Redux. Validates dispatched actions.
  
- **redux-validation**  
  https://github.com/mkamakura/redux-validation  
  Validate action properties
  
- **redux-validate-actions**  
  https://github.com/asn007/redux-validate-actions  
  A small tool to automatically validate redux actions based on a predicate and log wrongly formatted actions into console 
  
- **redux-payload-validator**  
  https://github.com/tomoyuki-tanaka/redux-payload-validator  
  Redux middleware for FSA payload validation.
  
- **redux-action-validator**  
  https://github.com/michael-martin-al/redux-action-validator  
  Extensible class to validate Redux/Flux action properties and ensure consistency across large projects.
  

#### Component Update Monitoring

- **React Render Visualizer**  
  https://github.com/redsunsoft/react-render-visualizer  
  A component mixin that overlays a tooltip indicating when a component has re-rendered and why, as well as animating the component's outline.

- **"WhyDidYouUpdateMixin"**  
  http://benchling.engineering/deep-dive-react-perf-debugging/  
  The article contains a useful props-diffing mixin that logs change information to the console.

- **should-component-update-dev**  
  https://github.com/ConciergeAuctions/should-component-update-dev  
  A development replacement for shouldComponentUpdate that gives you the "why?"
  
- **why-did-you-update**  
  https://github.com/garbles/why-did-you-update  
  Puts your console on blast when React is making unnecessary updates.  Inspired by Benchling's mixin, but monkey-patches React instead.
  
- **ReactPerfTool**  
  https://github.com/RamonGebben/react-perf-tool  
  ReactPerfTool tries to give you a more visual way of debugging performance of your React application. It does this by using the addons delivered by the React team and community to get measurements and visualize this using graphs. This makes it easier to spot bottlenecks.
  
- **React Monocle**  
  https://github.com/team-gryff/react-monocle  
  React Monocle is a developer tool for generating visual representations of your React app's component hierarchy.
  
- **lcHOC**  
  https://github.com/viktorbergehall/lcHOC  
  lcHOC is a HOC (higher order component) in React that visualize rendering and logs helpful information.  Enhance each component you want to study with lcHOC and every time that component updates, a green flash wraps the component (much like paint flashing in devtools) and debugging information is logged to the console.
  
- **react-wastage-monitor**  
  https://github.com/MalucoMarinero/react-wastage-monitor  
  https://blog.listium.com/introducing-react-wastage-monitor-404565d679b2  
  A utility that detects wasted rendering time on incorrectly developed Pure Components
  
- **fuego**  
  https://github.com/apiv/fuego  
  A component render time benchmarking suite for React 

- **react-component-benchmark**  
  https://github.com/paularmstrong/react-component-benchmark  
  A component to help benchmark React components and their trees. This project aims to provide a method for gathering benchmarks of component tree mount, update, and unmount timings.
  
- **reactopt**  
  https://github.com/reactopt/reactopt  
  A CLI React performance optimization tool that identifies potential unnecessary re-rendering.
  
- **shallow-equal-explain**  
  https://github.com/OliverJAsh/shallow-equal-explain  
  A function that returns an object explaining the difference (instead of the usual boolean). Useful for debugging React `PureComponent`s. 
### Middleware - Sockets and Adapters


#### Websockets

- **redux-socket**  
  https://github.com/quirinpa/redux-socket  
  A redux middleware that allows you to trigger a socket request on the client-side and dispatch an action in response.
  
- **cape-redux-socket**  
  https://github.com/cape-io/cape-redux-socket  
  Socket middleware, reducer, actions, constants
  
- **redux-socket-middleware**  
  https://github.com/madewithlove/redux-socket-middleware  
  Redux middleware that dispatches an action to all connected clients
  
- **socket.io-redux**  
  https://github.com/sergiodxa/socket.io-redux  
  Redux middleware to emit actions to a socket.io server
  
- **redux-ws**  
  https://github.com/arturmuller/redux-ws  
  Redux middleware for WebSockets communication.
  
- **redux-effects-socketio**  
  https://github.com/alexjg/redux-effects-socketio  
  Redux effects middleware for socketio
  
- **redux-socket-io**  
  https://github.com/nkt/redux-socket-io  
  Socket.io middleware for Redux.
  
- **redux-socket-cluster**  
  https://github.com/mattkrick/redux-socket-cluster  
  A socket-cluster state snatcher.  Socket cluster is awesome, but it doesn't share it's state, so you always have to go to your stored socket to find out. This tiny package grabs all the tasty little state bits & sticks em in your redux store. Then, it sets up listeners for updates to keep those state bits nice and fresh.
  
- **redux-saga-sc**  
  https://github.com/stipsan/redux-saga-sc  
  Provides sagas to easily dispatch redux actions over SocketCluster websockets
  
- **redux-socket.io-middleware**  
  https://github.com/czytelny/redux-socket.io-middleware  
  Another dead-simple middleware which allows you to connect Redux and Socket.io. It uses meta property of your action object to recognize whether send it to backend, or not. 
  
- **resocket**  
  https://github.com/laumair/resocket  
  Resocket is a socket.io wrapper and middleware for React and Redux applications.  It helps you abstract away all the socket.io implementations in your app. 
  
- **redux-socket.io-connect**
  https://github.com/michaelmitchell/redux-socket.io-connect  
  Relays Redux actions to the server, where reducer-like "handlers" can execute server code and dispatch actions back to the client.
  
- **redux-socket.io-middleware**  
  https://github.com/Vandise/redux-socket.io-middleware  
  An implementation of a generic socket.io middleware. Implemented with the notion that the application will be utilizing mutliple sockets.
  
- **redux-sockjs**  
  https://github.com/superwf/redux-sockjs  
  Use sockjs to pub and sub redux actions
  
- **redux-channels**  
  https://github.com/danielfarrell/redux-channels  
  Connector library for redux and websocket channels(ie, socket.io/Phoenix/ActionCable)
  
- **redux-action-emit-middleware**  
  https://github.com/pafciu17/redux-action-emit-middleware  
  Middleware for emitting redux actions over socket
  
- **redux-saga-websocket**  
  https://github.com/wangtao0101/redux-saga-websocket  
  Websockets for redux and redux-saga, which can integrate all websocket channels to one channel
  
- **monux**  
  https://github.com/ericwpeterson/monux  
  Marrying Redux and MonObjects to provide a structured state shape and maximize code reuse with socket.io.
  
- **redux-socket.io**  
  https://github.com/itaylor/redux-socket.io  
  An opinionated connector between socket.io and redux.
  
- **redux-socket.io-client**  
  https://github.com/my0sot1s/redux-socket.io-client  
  Simple Middleware for realtime with socket.io-client 
  
- **redux-sockjs-middleware**  
  https://github.com/nelsongarym/redux-sockjs-middleware  
  A redux middleware that manages a sockjs connection and subscriptions
  
- **redux-websocket**  
  https://github.com/giantmachines/redux-websocket  
  A Redux middleware for managing data over a WebSocket connection.  This middleware uses actions, dispatched with Redux to interact with a WebSocket server including connect, disconnect, message sending, and message receiving. All actions follow the Flux Standard Action model.
  
- **redux-websocket-middleware**  
  https://github.com/notgiorgi/redux-websocket-middleware  
  Native WebSocket integration in redux 
  
- **redux-sockets**  
  https://github.com/SharonGrossman/redux-sockets  
  A simple module to help simplify the integration of socket.io with your redux application. Emits client actions to the server if a socket payload is presented, initializes socketio connection and handles connection actions to the server and client.
  
- **redux-autobahn-js**  
  https://github.com/brycedarling/redux-autobahn-js  
  Autobahn-js middleware for Redux 
  
- **redux-autobahn**  
  https://github.com/saadtazi/redux-autobahn  
  A redux middleware for WAMP protocol using autobahn.
  
- **redux-socket-middleware**  
  https://github.com/AlexChittock/redux-socket-middleware  
  Passes redux actions to a web sockets server for server-side processing. 
  

#### Firebase

- **redux-react-firebase**  
  https://github.com/tiberiuc/redux-react-firebase  
  Use Firebase with React and Redux in ES6.  Integrated into Redux, automatic binding/unbinding, declarative decorator syntax for React components, support for nested props, 0ut of the box support for authentication (with auto load user profile).
  
- **redux-firebase**  
  https://github.com/colbyr/redux-firebase  
  Declarative firebase queries for redux.

- **firedux**  
  https://github.com/adjohnson916/firedux  
  Firedux (fiery·ducks) wraps the Firebase JavaScript API to dispatch Redux actions that optimisically & immediately read/write to an in-memory subset of your data from Firebase, then asynchronously pull & push data in the background.  Also supports some authentication methods and actions.

- **este-redux-firebase**  
  https://github.com/este/este-redux-firebase  
  Standalone module of Este's Firebase/Redux integration lib

- **refire**  
  https://github.com/hoppula/refire  
  Declarative Firebase bindings for Redux and React.  Refire keeps your local Redux store in sync with selected Firebase paths. You can declaratively bind Firebase paths as Strings, Objects or Arrays.  You can also specify queries based on Redux state (e.g. currently logged in user or route parameter) and Refire will automatically subscribe and unsubscribe your bindings when state changes.

- **redux-firebase**  
  https://github.com/gobadiah/redux-firebase  
  Provides some added functionality when using redux with firebase, such as anonymous use, offline recovery.  Redux firebase makes the connection between your firebase backend and your redux store, using a schema.
  
- **redux-firebasev3**  
  https://github.com/prescottprue/redux-firebasev3  
  Use Firebase with React and Redux in ES6
  
- **redfire**  
  https://github.com/ThadeuLuz/redfire  
  Microscopic Redux state + Firebase bindings 
  
- **Redux-Firebase-Actions**  
  https://github.com/distilagency/Redux-Firebase-Actions  
  A set of Redux actions and accompanying reducer for Firebase
  
- **redux-firebase-mirror**  
  https://github.com/pcardune/redux-firebase-mirror  
  A library to help you easily mirror firebase data inside a redux store. 
  
- **reduxonfire**  
  https://github.com/edoardolincetto/reduxonfire  
  Just a simple, scalable implementation of Firebase with Redux for React.js 
  
- **redux-saga-firebase**  
  https://github.com/n6g7/redux-saga-firebase  
  A redux saga integration for firebase
  
- **duckbase**  
  https://github.com/WadePeterson/duckbase  
  React + Redux Wrapper for Firebase
  
- **firebase-sync**  
  https://github.com/tasking/firebase-sync  
  Bind your firebase backend to your redux state with a dead simple component based approach.

- **reduxfire**  
  https://github.com/ThadeuLuz/reduxfire  
  Redux is a predictable state container for JavaScript apps. Firebase complements it perfectly by providing an easy-to-use, realtime data source for populating redux's state by dispatching actions. With ReduxFire, it only takes a few lines of JavaScript to integrate Firebase data into your (pure|React|Angular|Vue|*) Redux application.

#### Meteor

- **redux-ddp**  
  https://github.com/rclai/redux-ddp  
  Get DDP collection data synced straight into a Redux store instead of minimongo and attempting optimistic updates.
  
- **redux-meteorware**  
  https://github.com/shawnmclean/redux-meteorware  
  Meteor middleware for Redux.  This Redux middleware allows us to subscribe and load meteor data through actions and have them returned to the reducers when loaded.
  
- **meteor-redux-middleware**  
  https://github.com/samybob1/meteor-redux-middlewares  
  Redux middlewares that allow you to sync the store with Mongo and any reactive sources
  
- **reactive-redux**  
  https://github.com/vjau/reactive-redux  
  Allow you to generate a reactive data source for Meteor/Tracker from a part of a Redux tree. 
  
- **ddp-connector**  
  https://github.com/theclinician/ddp-connector  
  DDP client bindings for react-redux
  

#### Other Connections

- **redux-zmq**  
  https://github.com/code-mancers/redux-zmq  
  A redux middleware for zeromq
  
- **redux-matter**  
  https://github.com/KyperTech/redux-matter  
  Redux middleware, actions, and reducer for Matter.
  
- **redux-pubnub-action-sync-middleware**  
  https://github.com/danislu/redux-pubnub-action-sync-middleware  
  Middleware for syncing redux actions between app instances via pubnub.
  
- **ez-redux**  
  https://github.com/dcoellarb/ez-redux  
  Library to manage parse objects and simplify integration with parse
  
- **Redux Swagger Client**  
  https://github.com/noh4ck/redux-swagger-client  
  Add asynchronous Swagger api calls to Redux
  
- **redux-cablecar**  
  https://github.com/ndhays/redux-cablecar  
  A Redux middleware to connect Redux with Rails 5 ActionCable 

- **horizon-redux**  
  https://github.com/shanecav/horizon-redux  
  A small library that helps you connect Horizon.io with Redux in a flexible, non-intrusive way.
  
- **feathers-react-redux**  
  https://github.com/saiichihashimoto/feathers-react-redux  
  Unofficial Feathers bindings for React-Redux.  React-Redux is great. Feathers is fantastic. feathers-react-redux aims to tie these two together.
  
- **Django Redux**  
  https://github.com/fcurella/django_redux  
  A re-usable bridge between Django channels and Redux.

- **twiliojs-redux**  
  https://github.com/yarcub/twiliojs-redux  
  Twilio's javascript SDK middleware for Redux.
 
- **redux-loopback**  
  https://github.com/TimPerry/redux-loopback  
  Loopback middleware for redux
  
- **feathers-redux-immutable**  
  https://github.com/collegepulse/feathers-redux-immutable  
  An immutable, redux data store for FeathersJS services.
  
- **deepstream-redux**  
  https://github.com/bunchtogether/deepstream-redux  
  Tools for connecting Redux to a Deepstream server.
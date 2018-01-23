### Utilities

**Related Topics**

- [Entity/Collection Management](entity-collection-management.md)


#### Data Manipulation and Normalization

- **memoize-immutable**  
  https://github.com/memoize-immutable/memoize-immutable  
  An efficient memoizer for functions that only receive immutable arguments. Ideal for Redux and similar environments.  Dependency free!
  
- **normalizr**  
  https://github.com/gaearon/normalizr  
  Normalizes deeply nested JSON API responses according to a schema, producing flatter and unduplicated state.
  
- **denormalizr**  
  https://github.com/gpbl/denormalizr  
  Denormalizr takes an entity normalized by normalizr, and returns its complete tree including all the referred entities.
  
- **denormalizr-immutable**  
  https://github.com/dehbmarques/denormalizr-immutable  
  Denormalizer for normalizr using immutable data
  
- **Redux Tree**  
  https://github.com/stefanroex/redux-tree  
  Denormalize your immutable Redux store
  
- **salvage**  
  https://github.com/xogeny/salvage  
  A library for updating only those values that have changed in a Javascript value
  
- **model-environment**  
  https://github.com/tomascharad/model-environment  
  Super lightweight environment that permits to define relations between objects when receiving data from normalized api's
  
- **redux-variants**  
  https://github.com/homezen/redux-variants  
  Variants system for Redux (with optional React helpers)
  
- **fetch-for-redux**  
  https://github.com/gavacho/fetch-for-redux  
  Fetches ajax responses suitable for dispatching in a redux action
  
- **jsonapi-normalizer**  
  https://github.com/stevenpetryk/jsonapi-normalizer  
  Normalizes JSONAPI for use in Redux or similar systems.
  
- **react-entity-getter**  
  https://github.com/TheGnarCo/react-entity-getter  
  A helper function to query redux state for entities
  
- **remerger**  
  https://github.com/frankwallis/remerger  
  Creates recursively memoized deep merge functions for use with react-redux connect
  
- **json-api-normalizer**  
  https://github.com/yury-dymov/json-api-normalizer  
  Utility to normalize JSON API data for redux applications
  
- **redux-object**  
  https://github.com/yury-dymov/redux-object  
  Builds complex JS object from normalized redux store. Works best with json-api-normalizer.
  
- **denormalize-with-state**  
  https://github.com/ashleyw/denormalize-with-state  
  denormalize-with-state takes data denormalized by denormalizr and merges in extra state.
  
- **json-api-denormalizr**  
  https://github.com/willsoto/json-api-denormalizr  
  Denormalize JSON API responses for Redux applications 
  
- **normal-it**  
  https://github.com/jdrouet/normal-it  
  Normalizes and denormalizes JSON according to relational schema, inspired by Normalizr
  
  
#### Selectors

- **reselect**  
  https://github.com/reactjs/reselect  
  Simple “selector” library for Redux inspired by getters in NuclearJS.  Can compute derived data efficiently using memoization and composition.
  
- **reselect-change-memoize**  
  https://github.com/kbrownlees/reselect-change-memoize  
  A simple memoize function for reselect which performs a callback everytime the result changes.

- **redux-threads**  
  https://github.com/stonevanzuiden/redux-threads  
  Helpers for reusable combinations of selectors, actions and reducers in redux.
  
- **cape-select**  
  https://github.com/cape-io/cape-select  
  Reselect-inspired utility/selector functions
  
- **reselect-map**  
  https://github.com/HeyImAlex/reselect-map  
  Selectors for mapping over collections
  
- **reduxql**  
  https://github.com/AppHubPlatform/reduxql  
  Proof of concept for using GraphQL to select data from a Redux store.
  
- **react-graphql-redux**  
  https://github.com/youknowriad/react-graphql-redux  
  This library allows you to use GraphQL to query your Redux store
  
- **datavan**  
  https://github.com/ericfong/datavan
  wrap redux into mongodb api and can sync with server

- **re-reselect**  
  https://github.com/toomuchdesign/re-reselect  
  Enhance Reselect selectors by wrapping createSelector function and returning a memoized collection of selectors indexed with the cache key returned by a custom resolver function.  Useful to reduce selectors recalculation when the same selector is repeatedly called with one/few different arguments.
  
- **selectorator**  
  https://github.com/planttheidea/selectorator  
  selectorator is an abstraction API for creating selectors via reselect with less boilerplate code.
  
- **define-selectors**  
  https://github.com/b6pzeusbc54tvhw5jgpyw8pwz2x6gs/define-selectors  
  A utility to help with the ordering of selector definitions
  
- **rememo**  
  https://github.com/aduth/rememo  
  Memoized selectors for Redux and other immutable object derivation.  Differs from Reselect by encouraging you to consider the derivation first-and-foremost without requiring you to build up the individual dependencies ahead of time.
  
- **reselectie**  
  https://github.com/ralusek/reselectie  
  Memoized selector library for any immutable data structure (such as a redux immutable store). This library serves as a smaller, faster alternative to reselect AND re-reselect.
  
- **bo-selecta**  
  https://github.com/hnrysmth/bo-selecta  
  Syntactic sugar for redux selectors: `select('users').from(state).byId(userId)`
  
- **red-ux**  
  https://github.com/codemeasandwich/red-ux  
  Provides a genSelectState utility to improve selector caching behavior, and a shouldUpdate function for simple `shouldComponentUpdate` implementation
  
- **combine-section-selectors**  
  https://github.com/iofjuupasli/combine-section-selectors  
  Combine selectors from state to one set of selectors. Useful with redux and combineReducer or combine-section-reducer 
  
- **combine-selectors-redux**  
  https://github.com/tapayne88/combine-selectors-redux  
  Utility function for combining selectors when working with redux. Much like combineReducers it helps for defining selector functions within the reducers. 
  
- **selectem**  
  https://github.com/sibnerian/selectem  
  Shorthand for react-redux’s mapStateToProps. Need some props? Just select 'em!
  
- **redux-getters**  
  https://github.com/fakundo/redux-getters  
  Provides an additional layer of getters between the store and components. The getter returns data from the store if they are there, otherwise it returns stub and invokes fetch action.
  
  
#### Functional Programming
  
- **redux-transducers**  
  https://github.com/acdlite/redux-transducers  
  Transducer utilities for Redux.
  
- **recompose**  
  https://github.com/acdlite/recompose  
  Recompose is a React utility belt for function components and higher-order components. Think of it like lodash for React.
  
- **redux-rx**  
  https://github.com/acdlite/redux-rx  
  RxJS utilities for Redux.  
  
- **redux-bacon**  
  https://github.com/aparticka/redux-bacon  
  Utilities for attaching Bacon.js to Redux
  
- **react-compose**  
  https://github.com/UniversalAvenue/react-compose  
  Compose React components with a functional api.  
  
- **Redux Consumer Toolkit**  
  https://github.com/RocketPuppy/redux-consumer-toolkit  
  Implements several functions that are useful for combining, composing, and altering reducers and selectors (consumers). Each of this functions returns a memoized consumer, similar to reselect, so data isn't re-computed unnecessarily. The inspiration for this library was fantasyland-redux, only instead of basing it off of the fantasyland specification it is based off of the static-land specification. 
  
- **compound**  
  https://github.com/pdme/compound  
  Like compose, but with rest params also being passed in. This is particularly useful in redux reducers, for example, when you want to apply multiple modifiers to the state, using the same action object.
  
- **redux-fun** 
  https://github.com/guillaumearm/redux-fun  
  Utilities for composing and piping reducers, selectors, and middleware
### Immutable Data


#### Immutable Data Structures



#### Immutable Update Utilities


- **immutable-ops**  
  https://github.com/tommikaikkonen/immutable-ops  
A collection of functions to perform immutable operations on plain JavaScript objects and arrays.  Like updeep but with batched mutations and no freezing.  Like icepick, but with batched mutations and a curried API that puts the target object as the last argument. No freezing.

- **Redecorate**  
  https://github.com/Wildhoney/Redecorate  
  Simple module for reducing immutable nested properties in Redux applications.  



#### Alternate Data Management Concepts

- **redux-orm**  
  https://github.com/tommikaikkonen/redux-orm  
  A small, simple and immutable ORM to manage relational data in your Redux store. Provides a Model-like interface on top of a portion of your store, allowing you to define relations between Models, store values as "tables" in your state, and make immutable updates by assigning values to Model fields.

- **reduxdb**  
  https://github.com/wizawu/reduxdb  
  Redux with MongoDB-like API.  Dispatches internal Redux actions in response to API calls like `db.someCollection.insert({id : 1, name "abc"})`.
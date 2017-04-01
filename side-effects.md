### Side Effects

For comparisons between side effect approaches, see [What is the right way to do asynchronous operations in Redux?](https://decembersoft.com/posts/what-is-the-right-way-to-do-asynchronous-operations-in-redux/).

#### Widely Used Tools

- **redux-thunk**  
  https://github.com/gaearon/redux-thunk  
  The simplest possible side effects approach: dispatch functions instead of objects, which then get access to `dispatch` and `getState`.  (Variations on the concept listed on the [Middleware](middleware.md) page.)
  
- **redux-saga**  
  https://github.com/redux-saga/redux-saga  
  Generator-based side effects approach.  Create "sagas", which act like background threads or daemons that can listen for actions and dispatch objects describing side effects.
  
- **redux-loop**  
  https://github.com/raisemarketplace/redux-loop  
  Sequence your effects naturally and purely by returning them from your reducers.  Also returns descriptive objects, which are executed later.
  
- **redux-observable**  
  https://github.com/redux-observable/redux-observable  
  RxJS 5-based middleware for Redux. Compose and cancel async actions and more.
  
- **redux-logic**  
  https://github.com/jeffbski/redux-logic  
  Redux middleware for organizing business logic and action side effects.
  
  
#### Side Effect Libraries By Approach

- [Side Effects - Functions](side-effects-functions.md)
- [Side Effects - Generators](side-effects-generators.md)
- [Side Effects - Observables](side-effects-observables.md)
- [Side Effects - Reducers/Other](side-effects-other.md)
# Typed Recompose


The type definition for [`recompose`](https://github.com/acdlite/recompose.git)

Let's [discuss](https://github.com/acdlite/recompose/issues/231)

## 0.20.0 List of the methods `//TODO implement those`
* Higher-order components
  + ~~`mapProps()`~~
  + ~~`withProps()`~~
  + `withPropsOnChange()`
  + `withHandlers()`
  + ~~`defaultProps()`~~
  + `renameProp()`
  + `renameProps()`
  + `flattenProp()`
  + ~~`withState()`~~
  + `withReducer()`
  + `branch()`
  + `renderComponent()`
  + `renderNothing()`
  + `shouldUpdate()`
  + ~~`pure()`~~
  + ~~`onlyUpdateForKeys()`~~
  + ~~`onlyUpdateForPropTypes()`~~
  + ~~`withContext()`~~
  + ~~`getContext()`~~
  + ~~`lifecycle()`~~
  + `toClass()`
* Static property helpers
  + `setStatic()`
  + ~~`setPropTypes()`~~
  + `setDisplayName()`
* Utilities
  + `compose()`
  + `getDisplayName()`
  + `wrapDisplayName()`
  + `shallowEqual()`
  + `isClassComponent()`
  + `createEagerElement()`
  + `createEagerFactory()`
  + `createSink()`
  + ~~`componentFromProp()`~~
  + `nest()`
  + `hoistStatics()`
* Observable utilities
  + `componentFromStream()`
  + `mapPropsStream()`
  + `createEventHandler()`
  + `setObservableConfig()`


## LICENSE

MIT

## Contributing

You are welcome!

Fisrt, take a look at `index.d.ts` file. I've used `connect`'s definition 
from `react-redux` library for HOC (to be honest I still don't get why it called so).

Then at `test/test.tsx` you can see usage examples. Basically testing of 
annotations means «write your typical code samples and make sure that code compiles by `tsc`».
So if you see that provided annotation won't work in particular (still typical)
case, please let me know.

----

Generated by [`generator-typings`](https://github.com/typings/generator-typings) 1.0.12

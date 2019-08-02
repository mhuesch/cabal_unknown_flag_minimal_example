Example of cabal giving a somewhat confusing error message when an undefined flag is referenced.

```
$ cabal new-build
Resolving dependencies...
Map.!: given key is not an element in the map
CallStack (from HasCallStack):
  error, called at libraries/containers/Data/Map/Internal.hs:610:17 in containers-0.6.0.1:Data.Map.Internal
```

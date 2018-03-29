# cljsjs/react-datepicker

[](dependency)
```clojure
[cljsjs/react-datepicker "0.55.0-0"] ;; latest release
```
[](/dependency)

This jar comes with `deps.cljs` as used by the [Foreign Libs][flibs] feature
of the ClojureScript compiler. After adding the above dependency to your project
you can require the packaged library like so:

```clojure
(ns application.core
  (:require [cljsjs.react-datepicker]))

(def date-picker (.createFactory js/React (.-default js/DatePicker)))
```

[flibs]: https://clojurescript.org/reference/packaging-foreign-deps
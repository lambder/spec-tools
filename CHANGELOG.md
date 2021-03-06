## 0.2.2 (2017-06-12)

* Spec Record `describe*` uses the map syntax, e.g. `(st/spec clojure.core/string? {}` => `(st/spec {:spec clojure.core/string?})`

* Spec Records inherit `::s/name` from underlaying specs, fixes [#56](https://github.com/metosin/spec-tools/issues/56)

## 0.2.1 (2017-06-09)

* fixed `explain*` for Spec Records

* updated deps:

```clj
[org.clojure/clojure "0.1.123"] is available but we use "0.1.108"
[org.clojure/clojure "1.9.0-alpha17"] is available but we use "1.9.0-alpha16"
[org.clojure/clojurescript "1.9.562"] is available but we use "1.9.542"
```

**[compare](https://github.com/metosin/spec-tools/compare/0.2.0...0.2.1)**

## 0.2.0 (2017-05-16)

* **BREAKING**: update spec to `alpha16`:
  * `clojure.spec` => `clojure.spec.alpha`, `cljs.spec` => `cljs.spec.alpha` etc.

* updated deps:

```clj
[org.clojure/spec.alpha "0.1.108"]
[org.clojure/clojure "1.9.0-alpha16"] is available but we use "1.9.0-alpha15"
[org.clojure/clojurescript "1.9.542"] is available but we use "1.9.518"
```

**[compare](https://github.com/metosin/spec-tools/compare/0.1.1...0.2.0)**

## 0.1.1 (2017-05-10)

* Remove hard dependency on ClojureScript, thanks to [Kenny Williams](https://github.com/kennyjwilli). [#52](https://github.com/metosin/spec-tools/pull/52)

**[compare](https://github.com/metosin/spec-tools/compare/0.1.0...0.1.1)**

## 0.1.0 (2017-05-04)

* Initial release.

# minimal lein-git-deps repo

I got this to work by making my `project.clj` look like

```clojure
  :source-paths [
                 ...
                 ".lein-git-deps/hello-lib"]

  :git-dependencies [["https://github.com/jcreedcmu/hello-lib.git"]]

  :plugins [
            ...
            [lein-git-deps "0.0.2-SNAPSHOT"]]
```
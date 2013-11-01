# lein-externs

A Leiningen plugin to extract externs for your ClojureScript project

## Usage

Put `[lein-externs "0.1.1"]` into the `:plugins` vector of your
project.clj file or your `:user` profile

Create the externs with:

    $ lein externs > externs.js

or, specify a build, e.g.:

    $ lein externs release > externs.js



## License

Copyright © 2013 Rasmus Buchmann, Erik Ouchterlony, Benjamin Teuber

Distributed under the Eclipse Public License, the same as Clojure.

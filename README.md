# hiccup-watch

This is a leiningen plugin that just watches for changes in your [Hiccup](https://github.com/weavejester/hiccup) source files. ***"Hiccup is a library for representing HTML in Clojure"***.


## Usage


To use this plugin across your projects, put `[hiccup-watch "0.1.1"]` into the `:plugins` vector of your `:user` profile.

Or if you are on Leiningen 1.x do `lein plugin install hiccup-watch 0.1.1`.

To install this plugin at a project level, put `[hiccup-watch "0.1.1"]` into the `:plugins` vector of your project.clj.

You can set this configuration `{:hiccup-watch {:input-dir "in/" :output-dir "out/"}}` in your project.clj. Then you can just call the plugin like so.

    $ lein hiccup-watch


Or you can just pass in those parameters directly. This also acts as an override to the configured values.

    $ lein hiccup-watch :input-dir in/ :output-dir out/


## License

Copyright © 2014 Interrupt Software Inc.

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.


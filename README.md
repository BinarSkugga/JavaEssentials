# This list is subjective

## Multi purpose

* [google/guava](https://github.com/google/guava)
  * Multi purpose library with implementation of utils functions and objects.
* [apache/commons-lang](https://github.com/apache/commons-lang)
  * Same as guava but focused on strings. The Apache Commons library suite is well known and mature.

## HTTP

* [square/okhttp](https://github.com/square/okhttp)
  * Even after the implementation of the HTTP client in Java 9 okhttp is above and beyond for http requests.
  * Retrofit does the job as well for simpler uses. 
* [square/picasso](https://github.com/square/picasso)
  * Load images asynchronously, handles caching and loading. This library is a charm for any android projects.
* [undertow-io/undertow](https://github.com/undertow-io/undertow)
  * Need a simple lightweight webserver ? Undertow works in seconds and can be wrapped into a mini-jetty.

## Code Generation & Reflection

* [google/auto](https://github.com/google/auto)
  * Don't generate any code without this, as simple as that.
* [square/javapoet](https://github.com/square/javapoet)
  * Elegant and object oriented, this is a life saver for any annotation processor.
* [ronmamo/reflections](https://github.com/ronmamo/reflections)
  * I don't know why this is not in core Java yet. If you need to get multiple classes with certain annotations, this is for you. (Doesn't work on android because of compile format)

## JSON
* [square/moshi](https://github.com/square/moshi)
  * Moshi is the cute version of GSON without losing any performance.
* [auth0/java-jwt](https://github.com/auth0/java-jwt)
  * If you ever need JWTs this works like a charm.
  
## Misc
* [google/flogger](https://github.com/google/flogger)
  * Logging is a big part of coding and Java made it a pain for years, here's the solution.
* [google/tink](https://github.com/google/tink)
  * Don't do crypto by yourself, use Tink. This thing simplfies it so much you'll feel like a hacker-man.
* [xdrop/fuzzywuzzy](https://github.com/xdrop/fuzzywuzzy)
  * Reimplementation of the python library with the same name. Very usefull for searching and auto-completion.
* [java-native-access/jna](https://github.com/java-native-access/jna)
  * Better version of JNI.

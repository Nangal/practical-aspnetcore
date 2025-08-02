# Datastar (7)

The following samples show how to use [Datastar](https://data-star.dev/) hypermedia framework using .NET 10 and [pico](https://picocss.com) CSS framework.

* [Hello World](hello-world)
  
  Use `data-on-load` attribute with `@get` action to receive SSE event from a Minimal API endpoint that returns `datastar-patch-elements` SSE event type.

* [Backend SSE patch-signals](backend-patch-signals)

  This sample demonstrates how the backend can patch signals through SSE and how the UI reacts with it. The sample adds 3 seconds delays on the SSE response so the changes on the UI is visible.   

* [Backend SSE patch-signals 2](backend-patch-signals-2)

  Similar to previous sample except this time we add an extra signal and did not initialize any of the them.

* [Backend SSE patch-signals 3](backend-patch-signals-3)

  This sample shows how to use `filterSignals` option to only send specific signals to the backend.

* [Backend SSE patch-signals 3](backend-patch-signals-4)

  This sample shows the backend add one extra signal to be used for later action at the UI.

* [data-attr](data-attr)

  This example shows how to use `data-attr` to set HTML attribute to an expression. This sample demonstrates the usage of direct value, object and also signal expression.

* [data-bind](data-bind)

  This sample shows how to use `data-bind` to bind input (text, textarea, select, radio, checkbox, range) values to signals.
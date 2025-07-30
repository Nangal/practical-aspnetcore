# Datastar (4)

The following samples show how to use [Datastar](https://data-star.dev/) hypermedia framework using .NET 10 and [pico](https://picocss.com) CSS framework.

* [Hello World](hello-world)
  
  Use `data-on-load` attribute with `@get` action to receive SSE event from a Minimal API endpoint that returns `datastar-patch-elements` SSE event type.

* [Backend SSE patch-signals](backend-patch-signals)

  This sample demonstrates how the backend can patch signals through SSE and how the UI reacts with it. The sample adds 3 seconds delays on the SSE response so the changes on the UI is visible.   

* [Backend SSE patch-signals 2](backend-patch-signals-2)

  Similar to previous sample except this time we add an extra signal and did not initialize any of the them.

* [Backend SSE patch-signals 3](backend-patch-signals-3)

  This sample shows how to use `filterSignals` option to only send specific signals to the backend.
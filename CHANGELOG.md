1.3
=====

- `HttpApp.close()` will no longer exit the process, just the HTTP server.
- `HttpApp.close()` now accepts a callback argument instead of exit code.


1.2
===

- Big refactoring of `HttpApp`. Request are not handled in the App class
  anymore but have their own `HttpAppRequest` instance.

1.1
===

- Renamed `App.shutdown()` to `App.close()`.
- Renamed `App.cleanup()` to `App.onClose()`.
- Started keeping changelog.
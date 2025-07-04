# template_server

An example of an HTTP server using the shelf package and Docker.

## Getting started

You will need to add server routes in the [`routes`] folder, ensuring that any new routes/APIs implement the [`Api`] class. Two files for [`login`] and [`user`] routes are already provided, so you can copy one of these and adjust the duplicate according to your needs. For example, if you want a route that serves instances of a class `Event`, you could make a new file `event.dart` containing a class `EventApi` (that implements [`Api`]).

<!-- Links -->
[`routes`]: lib/routes
[`login`]: lib/routes/login.dart
[`user`]: lib/routes/user.dart
[`Api`]: lib/routes/api.dart

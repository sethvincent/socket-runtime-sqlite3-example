# socket runtime + sqlite3 example

This is a very simple journaling app made with [Socket Runtime](https://github.com/socketsupply/socket) and [Sqlite3](https://www.sqlite.org/index.html), in 169 lines of html, css, and js!

That doesn't include the [sqlite3 extension to Socket Runtime](src/extensions/sqlite3), but that was copied from the socket repo.

The entire app is in the [index.html file, like it's 20 years ago and we're writing php but like, it's good](src/index.html).

This example clearly isn't something that should be shipped to users, but I bet it wouldn't take much to get to a reasonable alpha version.

## See also
This example is heavily based on the sqlite3 test extension here: https://github.com/socketsupply/socket/tree/master/test/src/extensions/sqlite3
That includes everything in the [scripts](scripts/) and [src/extensions/sqlite3](src/extensions/sqlite3) directories.

## License
[MIT](LICENSE.md)

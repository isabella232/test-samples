# Sample documents for testing Scribus

This collection of files are useful for testing Scribus' behavior.

If possible, each file should either

- contain one page that has the tested content on the left side and an image frame with an image showing the right behavior or
- have one or multiple PNG files (one per page) showing the expected result

If you want to contribute a sample you can fork this repository, add a directory with

- the new `.sla` file
- all the external resources needed to test the file (fonts, images, ...; you can use "File > Collect for output" to get all the file in one directory),
- a `README.md` explaining what is being tested
and finally  make a pull request.

Or you can zip your files and add it to the [Scribus bug tracker](http://bugs.scribus.net).

The files that are useful for the Scribus team will also be added to the [official test directory](https://github.com/scribusproject/scribus/tree/master/resources/tests) in the Scribus repository.

## License

By default, the distribution and modification of the files in this repository is regulated by the Creative Common CC 0 license.

Single files or directory can be contributed under different licenses, under the condition that it's compatible with the GPL 2 license used by the Scribus team.

# Twitter Clone

A Twitter clone using Ruby on Rails. This had been built from progressing
through the [Ruby on Rails book by Michael Hartl](https://3rd-edition.railstutorial.org/book).

## License

All source code is available under the MIT License. See
[LICENSE.md](LICENSE.md) for details.

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

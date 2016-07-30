# GemdatadirBug

This is just for illustrating a bug in RubyGems 2.5 that changed the Gem.datadir behaviour.

Simply clone this repository, bundle and run the program as follows:

```
git clone https://github.com/davidsiaw/gemdatadir_bug
cd gemdatadir_bug
bundle
bundle exec gemdatadir_bug
```

The output is `PASS` if the behaviour is correct and `FAIL` if it is not
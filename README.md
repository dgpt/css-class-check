# CSS Class Checker

Identifies unused css classes in your code!
60% of the time it works every time.

Performs a basic grep for things that look like class names in a given file
and searches for any instances of those class name in the provided path.

# Usage
```bash
$ css-class-check /file/to/pull/css/classes/from.css /path/to/search
```

# Installation
```bash
ln -s css-class-check ~/bin/
```

Or replace `~/bin` with a directory on your `PATH`

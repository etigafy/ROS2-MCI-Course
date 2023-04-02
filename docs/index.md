# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

# New Code

## Code Annotation examples
Some `code` here

### Plain Code Block
A plain code block:

```
Some code here
def myfunction():
// some comment
```

#### Code for a specific Language
Some more code with `py` at the start:

``` py
import tensorflow as tf
def whaterver()
```

#### With a title
``` py title="bubble_sort.py"
def bubble_sort(item):
    for i in range(len(items)): 
        for j in range(len(items) - 1  - i):
            if items[j] > items [j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### With linenumbers
``` py title="bubble_sort.py" linenums="1"
def bubble_sort(item):
    for i in range(len(items)): 
        for j in range(len(items) - 1  - i):
            if items[j] > items [j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```
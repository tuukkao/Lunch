## What is this?
`lunch` can be used to view (Finnish) Sodexo menues on the terminal.

## How to use
- You need at least Python 3.6 to run this script. Tested on Python 3.8.
- Copy `lunch` somewhere on your path and make it executable. Alternatively you can use the provided setup.py script (`python setup.py install`).
- Obtain the id's of your favourite Sodexo restaurants. You can find the id by looking at the url of the restaurant's daily JSON feed right before the date. For example for the Hermia 5 restaurant the id would be *107*.
- Print the menu by running `lunch -r <id>` or perhaps make an alias: `alias lunch-h5='lunch -r 107'`. Use the `-d/--date` option to specify an arbitrary date.

## Todo
- [ ] Tabular output
- [ ] Allow reordering/omitting individual courses based on their index

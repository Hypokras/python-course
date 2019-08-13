Now we're ready to really build our quote bot. To test things out, we'll read all the quotes from a file and print the first one.

First, you can remove our test quote, the print statement on line 2. You can either comment it out by adding a `#` at the start of the line, or remove it completely.

Next, remove the other comments by deleting `#` from the start of the other four lines to get Python code like this:

```
  f = open("quotes.txt")
  quotes = f.readlines()
  f.close()

  print(quotes)
```

Here we are opening the `quotes.txt` file, reading all the lines into a new _variable_ called `quotes`, then closing the file (defined by the variable `f`). Finally, we print out the quotes.

You can run this code and we'll get a dump of _all_ the quotes in the quotes file. That's because Python stored them all in an _array_, which is a single variable that holds a list of values.

## Print the first element of an array

Since we only want one quote, we need to edit our code to print only the first value in the `quotes` array.

In your code, find the print line and add this special modifier `[0]` so that the line now reads:
`  print(quotes[0])`

The square brackets tell Python that we want a specific item in the array. Since it starts counting at zero, we've grabbed the first item.

## Comment with the first quote

Run your code and copy the value to your clipboard.

Paste the quote as a comment here and I'll follow up with next steps!

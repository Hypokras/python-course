Now that you're familiar with arrays, it's time to find a random line.

## Generate a random number

Rather than `[0]` or `[13]` for our array value, we want the number to be chosen at random. Of course, it can't be any number. It should be a whole number between 0 and 13.

To generate random numbers, we'll use a Python _module_, a built-in extension of the language.

At the very top of your `get-quote.py` file (above the `def` line), add this line:
`import random`

Now find where you print out one value from the array. _Before_ that line, add the following:
```
  last = 13
  rnd = random.randint(0, last)
```

The `last` variable holds the highest index for the array. Then our random number is stored in `rnd` using the `random.randint` function, which takes the lowest-possible number (zero) and the highest-possible number (stored in `last`).

> **Note** If you want to add or remove quotes from your text file, you could change the last variable to update automatically:
> `  last = len(quotes) - 1`

Finally, update the line where we print a single quote. Instead of including a number between the brackets, we'll put our random number variable:
`  print quotes[rnd]`

Try running your code a few times with `python get-quote.py` and your quotes should now be chosen at random.

## Push your changes

It's been awhile since we've saved our code in the repo. Take the oppportunity now:

- `git add get-quote.py`
- `git commit -m "Random quote bot is working"`
- `git push`

When I see the push come through, I'll comment here!

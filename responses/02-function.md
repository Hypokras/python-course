🎉 Good job! You just pushed your first Python code! Now let's try making some changes...

Notice that the first and last lines of the Python file reference `main()`. That's a Python function and it runs automatically every time you call the script. But only because _we told it to_.

Try changing the name to something else--almost anything, as long as it doesn't have spaces and isn't a [reserved word](https://docs.python.org/2.0/ref/keywords.html).

Maybe use a synonym of main, such as `primary`.

The important thing is to change it in _both places_, the first line and the last line.

Now run your code again: `python get-quote.py`

If you get an error, you might have only changed `main` in one place, or removed the important `()` from after the name. You'd also get an error if you changed that `__main__` thing (line 10), so leave that one be.

## Push your changes

When your Python script is running, you'll see the quote again.

To move on to the next step, push your changes:

- `git add get-quote.py`
- `git commit -m "Renamed the primary function"`
- `git push`

When I see the push come through, I'll share your next steps!

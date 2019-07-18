Now you're ready to start coding. Let's get familiar with the files in our repo:

- `README.md`: a markdown introduction to this project
- `get-quote.py`: the file where we'll write our Python code
- `quotes.txt`: a text file with a list of quotes

Open up `get-quote.py` and comment out line 2 by removing the `#` from the beginning of the line.

Now let's try running that Python script. From the command line, type: `python get-quote.py`

You should see our first quote, the one hard-coded into line 2, printed out in your terminal:
`Keep it logically awesome.`

## Push your changes

You've edited your local code, so you have a more recent version than is stored in this repository. You can check that any time by running: `git status`

It should show one file modified. Every time we want to send our local changes to GitHub, we need to perform three steps:

1. Add the file(s) with changes: `git add get-quote.py`
2. Commit the changes: `git commit -m "Hello World!"`
3. Push the changes: `git push`

Once you've completed these steps, we'll write some more Python.

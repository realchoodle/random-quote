# README

`rq` is a Bash script that picks a random quote from a `quotes.txt` file in the same directory. `quotes.txt` uses the format `quote_author_work`, where `_` is the separator for each field. Do not separate lines with empty newlines; if you do, you may get an empty quote. `rq` only uses Bash builtins.

## To-Do

- [ ] Add function to wrap text based on `$COLUMNS`
- [ ] Add a fourth citation or date field
- [ ] Make the script easier to interact with on the cli

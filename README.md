# README

`rq` is a Bash script that picks a random quote from a `quotes.txt`. `quotes.txt` uses the format `quote_author_work`, where `_` is the separator for each field. Do not separate lines with empty newlines; if you do, you may get an empty quote. `rq` only uses Bash builtins.

## To-Do

- [ ] Add function to wrap text dynamically based on `$COLUMNS`
- [ ] Figure out way to justify the quote attribution to the right
- [ ] Add a fourth citation or date field

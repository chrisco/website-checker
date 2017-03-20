# website-checker

Pings list of websites using cURL to see if they're up and there are no errors.

## How To Use

1. Edit `website-checker.sh` (tell it which list to check and what to output).
2. Edit `list.txt` and/or `list-failures.txt` (one domain per line).
3. Make sure `failures.txt` is empty.
4. Run from `~/c3/website-checker`.
5. Run with `$ ./website-checker.sh`.
6. Check `failures.txt` for list of failures.

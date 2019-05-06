# Gredit (Grep & Edit)

Grep and open each match in `$EDITOR`.

Known working editors are vi and nano.

## Usage
```
Usage: gredit [-ilrqh] [-e exclude] regexp [location]

Arguments:
  -e <file/directory> Ignore all matches in file/directory
  -i                  Match case-insensitive
  -l                  List matches instead of editing them
  -r                  Search recursively
  -q                  Quiet (don't ask for confirmation before opening editor)
  -h                  Print this help
```

## License
Apache-2.0

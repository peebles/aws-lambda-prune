# Prune Old Lamda Functions

Use this script to prune older versions of a AWS lambda function.  By default the last
three versions of the function are kept, as well as the version names "$LATEST" and any
versions pointed to by aliases.

## Usage

```bash
AWS_ACCESS_KEY_ID=<YOUR-KEY> AWS_SECRET_ACCESS_KEY=<YOUR-SECRET> AWS_REGION=<YOUR-REGION> \
    ./bin/prune [ --keep 3 ] functionName
```


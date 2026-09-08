# Claude-Test1

An interactive HTML view of `test1.csv`.

## Run locally

`index.html` loads the CSV with `fetch`, so serve the repository with a local
web server instead of opening the file directly:

```sh
python3 -m http.server
```

Then open <http://localhost:8000/> in a browser. Use the search field to
filter records and click a column heading to sort the table.

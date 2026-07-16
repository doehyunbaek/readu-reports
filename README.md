# ReadU Reports

A static report of documentation bugs submitted to upstream maintainers and their landed fixes.
See [readu repository](https://github.com/sola-st/readu) for the code and data related to the reports.

## View locally

Serve the repository with a local HTTP server so the page can load `report.json`:

```sh
python3 -m http.server
```

Then open <http://localhost:8000>.

## Files

- `index.html` — report viewer with repository and status filters
- `report.json` — report data

## License

This project is licensed under the [MIT License](LICENSE).

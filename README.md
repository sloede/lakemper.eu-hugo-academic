# lakemper.eu

Main site since October 2022. See [`README.orig.md`](README.orig.md) for original README.

## Updating references
First, update entries in `publications.bib`. Then, install `academic` CLI from
https://github.com/GetRD/academic-file-converter.

Finally, enter the cloned website repository and run
```shell
academic --verbose import publications.bib content/publication/ --compact --overwrite
```


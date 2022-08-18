# How is the PDF file created?
The PDF file is created with the command `pdfmom`, which requires the most recent versions of `groff` and `mom`.
More information can be found at [github](https://github.com/0xR3V/Bibles)

```shell
pdfmom -k CEI.mom > CEI.pdf
```

### SHA256 checksums for the files
```txt
fac7de024e05dbf0c7e511ea9cf5996277e6643a89047462ed75b414df5c0416 CEI.mom
8a0cbe894b20715ec1415cccb33f9dc3ccbcafc4a19c7d3c719715ebd9cdf8f9 stylesheet.mom
162d5767f14c2fe2efbe37acff34119b94c3b0150d38e12de0a0ae1df209fa62 CEI.pdf
```

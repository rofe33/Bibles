# How is the PDF file created?
The PDF file is created with the command `pdfmom`, which requires the most recent versions of `groff` and `mom`.
More information can be found at [github](https://github.com/0xR3V/Bibles).

```shell
pdfmom -k RVA-nuevo-testamento.mom > RVA-nuevo-testamento.pdf
```

### SHA256 checksums for the files
```txt
a36ace5f784ca5f8579141f7ab87971f79eb8f62d971a1a60d2411b1b7480ec3 RVA-nuevo-testamento.mom
58ada4a2855d37f52644fde0531c96eb34cdf53d6db61dc1b9e5098c736ed452 stylesheet.mom
30f6e5ce0f95b9d165dc0501dd7f72f288ffb2e3467b8e8a14465bf0d8fec83a RVA-nuevo-testamento.pdf
```

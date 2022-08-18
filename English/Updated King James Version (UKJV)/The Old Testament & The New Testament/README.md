# How is the PDF file created?
The PDF file is created with the command `pdfmom`, which requires the most recent versions of `groff` and `mom`.
More information can be found at [github](https://github.com/0xR3V/Bibles)

```shell
pdfmom -k UKJV.mom > UKJV.pdf
```

### SHA256 checksums for the files
```txt
9f396a765f8ccc5868f460eb06beed1cbe2937a18700f1c0fd58ba4fe861053c stylesheet.mom
b6af29e216b303bde28501b8124e785421a0ee25cf6b9aa8acc6ec153113b038 UKJV.mom
76d720f41fe1a94530d48337e0ae63c536a8952afd28b150f72b41f9617b9864 UKJV.pdf
```

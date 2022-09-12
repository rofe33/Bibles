# How is the PDF file created?
The PDF file is created with the command `pdfmom`, which requires the most recent versions of `groff` and `mom`.
More information can be found at [github](https://github.com/0xR3V/Bibles).

```shell
pdfmom -k YLT.mom > YLT.pdf
```

### SHA256 checksums for the files
```txt
6333d7b9da981757fb60319d45e2bf1fa94d4044f357a9b307fd3950849c9357 stylesheet.mom
a9b2503ac0cfb4896a67f98fd9697fad98e147d2d4fa774789f30d56b387ef1f YLT.mom
70439bbdc46d2a7ca105bd71a8d2bef589dde78aaec5c11352ba4d5ff90cfad3 YLT.pdf
```

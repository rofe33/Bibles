# How is the PDF file created?
The PDF file is created with the command `pdfmom`, which requires the most recent versions of `groff` and `mom`.
More information can be found at [github](https://github.com/0xR3V/Bibles)

```shell
pdfmom -k UKJV-the-new-testament.mom > UKJV-the-new-testament.pdf
```

### SHA256 checksums for the files
```txt
533ac99b94ae2e34f67c8a731d63970953dcab270ba001a15fda9b2835fe1bc3 stylesheet.mom
2594f84472e6d42725522d7a10cb7eec005a836ea22392d7d649b50fb3f056df UKJV-the-new-testament.mom
9cfa5cba4c0af9b2ac95c08476d7ccea5e96d48df9c1c0d83d56bcdbe2dd79ca UKJV-the-new-testament.pdf
```

# How is the PDF file created?
The PDF file is created with the command `pdfmom`, which requires the most recent versions of `groff` and `mom`.
More information can be found at [github](https://github.com/0xR3V/Bibles).

```shell
pdfmom -k AKJV.mom > AKJV.pdf
```

### SHA256 checksums for the files
```txt
730c64488facb31ba9e62e50c2d58e52d83658edb67e1b9f659b307ae0733dad AKJV.mom
4259c78e8a985628adbbe340797124812b5b7762d3df4e68726ea0c664894364 stylesheet.mom
2185da3c5d5553b50bfa0ad2c412b4ddcf9c28eefb2eeeffe00157c7904bfdc4 AKJV.pdf
```

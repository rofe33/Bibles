# How is the PDF file created?
The PDF file is created with the command `pdfmom`, which requires the most recent versions of `groff` and `mom`.
More information can be found at [github](https://github.com/0xR3V/Bibles).

```shell
pdfmom -k TCNT-the-new-testament.mom > TCNT-the-new-testament.pdf
```

### SHA256 checksums for the files
```txt
b357d176596b8cb491706e47e021ab156c6ed59016c609d02052bad58e2b07a1 stylesheet.mom
7afcf71e7f244bee294f4545f2ea35b5ef06c17cc64f245c0df68de89b3e267d TCNT-the-new-testament.mom
5ab8eb9f43de60d1c52c4938c37c343c36c1bfc64e9ac619d99639943afa8d1c TCNT-the-new-testament.pdf
```

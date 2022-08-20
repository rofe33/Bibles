# How is the PDF file created?
The PDF file is created with the command `pdfmom`, which requires the most recent versions of `groff` and `mom`.
More information can be found at [github](https://github.com/0xR3V/Bibles).

```shell
pdfmom -k RVA.mom > RVA.pdf
```

### SHA256 checksums for the files
```txt
385bcaabade6ecd36a2d01095e65f42f4dbb9946c40b0c565a579e76467a4a38 RVA.mom
75c9d2de020c5aff6f2950fde4d26abd0f9256e60db938180820f4ac876b8bbf stylesheet.mom
4637221c07bb6c75bed3d256ab74b111544128cbb0537c1d4fa95fca0fa8a232 RVA.pdf
```

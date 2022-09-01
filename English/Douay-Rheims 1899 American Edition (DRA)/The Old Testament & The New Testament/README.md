# How is the PDF file created?
The PDF file is created with the command `pdfmom`, which requires the most recent versions of `groff` and `mom`.
More information can be found at [github](https://github.com/0xR3V/Bibles).

```shell
pdfmom -k DRA.mom > DRA.pdf
```

### SHA256 checksums for the files
```txt
81da7fa557485bc9629526980315ed160202322d79451cb93a4640831c5d566d DRA.mom
414ff5344d8654c042c4507d2269164082caadadb6f0a11ba6e983bc8752e443 stylesheet.mom
6e69a3f92a897dd8061582ce29f937029f06e2caed7658e011cc3076bd174acb DRA.pdf
```

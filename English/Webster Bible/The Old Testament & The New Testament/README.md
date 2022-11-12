# How is the PDF file created?
The PDF file is created with the command `pdfmom`, which requires the most recent versions of `groff` and `mom`.
More information can be found at [github](https://github.com/0xR3V/Bibles).

```shell
pdfmom -k Webster.mom > Webster.pdf
```

### SHA256 checksums for the files
```txt
e123ee4e3da7a1cdac8d860d0e843b7c16195f70930f009a6056487ef259e386 stylesheet.mom
4d59b65758ffb5e41b4b36772d0970a62806a020e88eda77ac5e2a9ebc95ad8e Webster.mom
f08acfd2ac7b6fd5c16448c0ff67f274a8dbaeffff4c26380d181869b6904494 Webster.pdf
```

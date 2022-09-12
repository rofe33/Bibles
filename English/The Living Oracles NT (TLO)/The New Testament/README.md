# How is the PDF file created?
The PDF file is created with the command `pdfmom`, which requires the most recent versions of `groff` and `mom`.
More information can be found at [github](https://github.com/0xR3V/Bibles).

```shell
pdfmom -k TLO-the-new-testament.mom > TLO-the-new-testament.pdf
```

### SHA256 checksums for the files
```txt
2b6689feccfc67beb3acd8f77139122dd7b3220c49199cdcaf8f1a1f6b49eec0 stylesheet.mom
aaa6e68d4b6a4f645a33392c2efaa1ed25002373b489c68520a2909ac266b93e TLO-the-new-testament.mom
eebc5e8c939b85e0a1e457f7f4b1f379f74c34fdffed2d4218e58a6f9c843215 TLO-the-new-testament.pdf
```

# How is the PDF file created?
The PDF file is created with the command `pdfmom`, which requires the most recent versions of `groff` and `mom`.
More information can be found at [github](https://github.com/0xR3V/Bibles).

```shell
pdfmom -k ACV.mom > ACV.pdf
```

### SHA256 checksums for the files
```txt
cd821f8830896554743f9f350b7086d8bfd5ca2fc39188adcd5153255a55361c ACV.mom
350a99068c8dbec020ef8d00fbadd7d3f28a0b8e0d9a3f9eb2622251008bfc09 stylesheet.mom
de530e8ca5f351191e48c7b4a7c158d18faaac80a02de0a9783a0843cf72e4f4 ACV.pdf
```

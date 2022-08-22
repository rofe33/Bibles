# How is the PDF file created?
The PDF file is created with the command `pdfmom`, which requires the most recent versions of `groff` and `mom`.
More information can be found at [github](https://github.com/0xR3V/Bibles).

```shell
pdfmom -k DARBY.mom > DARBY.pdf
```

### SHA256 checksums for the files
```txt
df37086256ea3a17e34ec38bfa4214134808d4b7f3fae145c17aac64bbe5219f DARBY.mom
7dffdaf3e4540c619090cbdfe3ca6aa2dcecfe46365d3afa81aa1727c6f9c2e4 stylesheet.mom
d1bcb7e4699c0da1e21995afd6c6f2367217abccbcc5f414eb6bdaa85c155560 DARBY.pdf
```

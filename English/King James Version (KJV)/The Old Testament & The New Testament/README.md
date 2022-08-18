# How is the PDF file created?
The PDF file is created with the command `pdfmom`, which requires the most recent versions of `groff` and `mom`.
More information can be found at [github](https://github.com/0xR3V/Bibles)

```shell
pdfmom -k KJV.mom > KJV.pdf
```

### SHA256 checksums for the files
```txt
4bb138304433d0ca0d318b9ea0133add3bf9a0f299c0cb7eecce044d4fcead42 KJV.mom
340e4e36aeaa0096420c1540428ec83c88888b807b6fc91692e22971e460fea2 stylesheet.mom
3769675d54c3a36fcec335412574ad4809b90296ddfc80ffa3ef7f35213145ea KJV.pdf
```

<div align="center">
"Jesus said to him, I am the way, the truth, and the life: no man comes to the Father, but by me." - John 14:6 (AKJV)
</div>

<hr>

<div align="center">
    <a href="https://github.com/0xR3V/Bibles#introduction">Introduction</a>
    -
    <a href="https://github.com/0xR3V/Bibles#a-list-of-all-the-bibles">A List of All the Bibles</a>
    -
    <a href="https://github.com/0xR3V/Bibles#why-groff-mom">Why Groff-mom?</a>
    -
    <a href="https://github.com/0xR3V/Bibles#contact-me">Contact Me</a>
</div>

# Introduction
This repository contains **Public Domain** bibles in different languages and versions.

There is a directory for each language, as well as a sub-directory for each version of that language.

Each version includes three directories:
- **The New Testament**
- **The Old Testament**
- **The Old Testament & The New Testament**

Each with 4 files:
- **stylesheet.mom** - where all styling will take place.
- Pre-generated **PDF** file.
- A file containing bible content written in mom syntax.
- **README.md**

Here's an example:
```txt
English
└── Bible in Basic English (BBE)
   ├── The New Testament
   │  ├── BBE-the-new-testament.mom
   │  ├── BBE-the-new-testament.pdf
   │  ├── README.md
   │  └── stylesheet.mom
   ├── The Old Testament
   │  ├── BBE-the-old-testament.mom
   │  ├── BBE-the-old-testament.pdf
   │  ├── README.md
   │  └── stylesheet.mom
   └── The Old Testament & The New Testament
      ├── BBE.mom
      ├── BBE.pdf
      ├── README.md
      └── stylesheet.mom
```

The **PDF** file is generated using `stylesheet.mom`, and the default design in `stylesheet.mom` is for **A5** papers. Also you can change every detail in `stylesheet.mom`,  such as the paper size to **A4** or **LETTER**.
However, before making any changes, consult first mom's documentation. More information can also be found in `stylesheet.mom`


# A List of All the Bibles
- [ ] العربية (Arabic) (AR)
	- [ ] الكتاب المقدس - فان دايك (SVD)
- [ ] English (EN)
	- [ ] A Conservative Version (ACV)
	- [ ] Aionian Bible
	- [ ] American King James Version (AKJV)
	- [ ] American Standard Version (ASV)
	- [x] Bible in Basic English (BBE)
	- [ ] Darby Translation (DARBY)
	- [ ] Douay-Rheims 1899 American Edition (DRA)
	- [ ] Geneva Bible 1599
	- [x] King James Version (KJV)
	- [ ] Montgomery New Testament (MNT)
	- [ ] Revised King James New Testament (RKJNT)
	- [ ] The Emphasized Bible by J. B. Rotherham (Rotherham)
	- [ ] The Living Oracles NT (TLO)
	- [ ] Twentieth Century New Testament (TCNT)
	- [ ] Updated King James Version (UKJV)
	- [ ] Webster Bible
	- [ ] Weymouth NT 1912 (Weymouth)
	- [ ] World English Bible (WEB)
	- [ ] World Messianic Bible
	- [ ] Young's Literal Translation (YLT)
- [ ] Español (Spanish) (ES)
	- [ ] Reina-Valera Antigua (RVA)
	- [ ] Versión Biblia Libre
- [ ] Français (French) (FR)
	- [x] La Sainte Bible
	- [ ] Louis Segond (LSG)

More bible versions/languages will be added in the future.


# Why Groff-mom?
I chose [Groff](https://www.gnu.org/software/groff/) because it's installation is minimal, and [mom](https://www.schaffter.ca/mom/mom-01.html) provides an easy way to style a document.

# Contact Me
Please contact me or open an issue if you have any concerns or suggestions.
- Email: `r3veal@protonmail.ch`

<div align="right">
<p>
	<strong>...All The Glory To God.</strong>
</p>
</div>

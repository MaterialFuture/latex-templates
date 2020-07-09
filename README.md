# LaTeX Templates

These LaTeX Templates are for anyone to use. I use these templates for when I'm creating documents or for when I want to learn more regarding LaTeX.

What is in this repository is what I use currently or what I have used in the past, so please keep that in mind. If you don't like something, change it, just like with HTML/CSS you make it what you want. I will add templates as I fix them up for public use by removing any sensitive info and of course adding comments for people to easily understand what is going on.

## Emacs

Emacs is my preferred way to edit LaTeX documents with it's AUCTeX package, because it's as easy as `C-c C-c RET` anytime I want to compile. AUCTeX also has BibTex and Biber for compiling citations for LaTeX. My preferred way to create documents is creating a LaTeX template, then putting that bad boy into my `+org.el` file and writing away with `org-mode`.

## Other Ways

While I prefer using Emacs these should all still work in whatever environment you want them to as long as you have the packages required by the document, typically something like `texlive-all` or something to that regard is needed before working with LaTeX but I would recommend looking into that more deeply for yourself as it differs for each operating system. Each system and configuration of LaTeX will differ so refer to the [Arch Wiki for TeX Live](https://wiki.archlinux.org/index.php/TeX_Live).

## Notes

In here I'll include not just plain `.tex` files but also Makefiles and other org examples as well as documentation on how to run said templates that require more than just AUCTeX in Emacs.

Some of the templates may require `xelatex` or `lualatex` depending on fonts and packages so please be aware of that. In the future I may create an org doc or PDF that goes over how one can work with all the templates. 

## Goals

My goals are to make these LaTeX templates accessible and usable for anyone that knows LaTeX or is wanting to learn, and furthermore making these templates look good and not like the default LaTeX.


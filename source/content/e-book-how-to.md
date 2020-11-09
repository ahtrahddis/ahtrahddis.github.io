+++
title = "e-book creation how-to"
+++

# E-book Creation
 
 For the creation of all these e-books, the following procedure is followed:

- the text is pasted & formatted with / written in / converted to [markdown](https://en.wikipedia.org/wiki/Markdown) (and very rarely to html)

- the markdown (**.md**) file is converted to **epub** using [pandoc](https://pandoc.org/)

- the **epub** file is edited with [calibre](https://calibre-ebook.com/) and finally...

- the **epub** file is converted to **mobi** and **azw3** with [calibre](https://calibre-ebook.com/)

- for **azw3** files, additional soft hyphenation is added using [hyphenate this!](https://www.mobileread.com/forums/showthread.php?t=208534) calibre plugin

Note, that for some texts, **pdf** files are provided too. These ones have either been created:

- with the "quick 'n dirty" method of conversion via calibre, which is a bad solution as there is very little formatting control

- by exporting the epub to **docx/odt**, further editing with Libreoffice (and sometimes with MS Office), re-formatting and finally exporting to **pdf**

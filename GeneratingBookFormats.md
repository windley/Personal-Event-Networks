Use [pandoc](http://johnmacfarlane.net/pandoc/) to generate an epub file. Be sure to use the metadata.xml file. 

```
pandoc -f markdown -t epub --epub-metadata=metadata.xml -o backbone-fundamentals.epub README.md
```

You can use [Kindlegen](http://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000234621) to generate a mobi file from
a pandoc ebook:

```
kindlegen backbone-fundamentals.epub
```

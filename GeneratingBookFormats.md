
# ePub 
Use [pandoc](http://johnmacfarlane.net/pandoc/) to generate an epub file. Be sure to use the metadata.xml file. 

```
pandoc -f markdown -t epub --epub-metadata=metadata.xml -o personal-event-networks.epub README.md
```

# Mobi
You can use [Kindlegen](http://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000234621) to generate a mobi file (that can be loaded on the Kindle) from a pandoc ebook:

```
kindlegen personal-event-networks.epub
```

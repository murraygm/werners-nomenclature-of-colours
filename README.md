# werners-nomenclature-of-colours
Data version of colour tables from the 1814 book by By P. Syme; "Werner's Nomenclature of Colours Adapted to Zoology, Botany, Chemistry, Mineralogy, Anatomy, and the Arts". The book Charles Darwin used to describe colours in nature on his HMS Beagle voyage. See it in full: (https://archive.org/details/gri_c00033125012743312)

**Data structure**
* Number : Colour number id from book (1-110) 
* Names : Text colour name from book
* Colours	: URL to page on Archive.org with parent colour swatch table (in book it's a painted colour chip)
* Animal : Text description of animal for reference from book 
* Vegetable : Text description of vegetable for reference from book 
* Mineral	: Text description of mineral for reference from book 
* Category : Chapter category from book (mostly plural - Blacks, Whites, Blues, Greens, Purples, Yellows, Browns but also Red and Orange)

* Component parts (OCR transcribed)	: Component parts text from book (via OCRed text file on Archive.org) 
* sampled colour value - hex: hex colour without #
* sampled colour value - rgb: comma separated rgb set
* sampled colour value - hsl: comma separated HSL (full degrees 0-359, %, %) set
* sampling scan quality: rough indication of colour balance (Good, OK, Bad) to hint at sampled colour's accuracy
* sampling notes: Note of technique to get colour value
* IntArcOrg image url: Direct link to image on Archive.org for parent colour swatch table 

The text is as close to the book as possible, with caps and oddities. Also the first 6 column names match to the book's table. One oddity in the data is Colour 109. In the book facsimile I have (based on British Museum's copy) it clearly says 'Olive Brown' both in the table and in the text. However, in the Internet Archive scans it says 'Clove Brown' but 'Olive Brown' in the text.

I added the hex/rbg/hsl sampling values for fun mostly. Simple eyedropper samples from Photoshop and not from color corrected scans, just the Internet Archive scans so can seem a little off. 

**Why did I do this?**

I'm doing a few side projects involving colour analysis and stumbled across this brilliant data resource: [Corpora](https://github.com/dariusk/corpora) by [Darius Kazemi](https://github.com/dariusk).
The color datasets are great and as this book wash fresh to hand, not to big, and seemingly not available as data I thought it would be a good addition. 

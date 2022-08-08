# PDS-converter
Converts NASA Planetary Data System (PDS) text label into JSON object

Currently supports only ***.LBL labels which contain description of fields of corresponding xxxx.TAB file.

Examples: 
- [this file](https://pds-imaging.jpl.nasa.gov/data/mer/spirit/mer2po_0xxx/index/edrindex.lbl) (28 KB) contains the list of fields of [this file](https://pds-imaging.jpl.nasa.gov/data/mer/spirit/mer2po_0xxx/index/edrindex.tab) (181 MB)
- [this file](https://pds-imaging.jpl.nasa.gov/data/mer/spirit/mer2po_0xxx/index/rdrindex.lbl) (14 KB) contains the list of fields of [this file](https://pds-imaging.jpl.nasa.gov/data/mer/spirit/mer2po_0xxx/index/rdrindex.tab) (772 MB)

You can both load a local file or paste the contents of the file; online files (URL) not yet supported.


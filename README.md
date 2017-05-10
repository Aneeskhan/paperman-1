# paperman


### Adding new papers
```
sh addpaper.sh <path-to-PDF-file> [<path-to-BIB-file>]
```
It is optional to provide a BibTex file.
In case a BibTex file is not provided, the user will be prompted to incert the BibTex information
after adding a new paper PDF.

### Searching for papers
Searching by words inside the paper content:  
```
python search.py --words <list of words separated by white space>
```
Searching by the name of the authors:  
```
python search.py --authors <list of authors separated by white space>
```

by ROCHA, Rodrigo C. O.  
http://rcor.me/

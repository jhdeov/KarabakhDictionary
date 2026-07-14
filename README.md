Sargsyan 2013 is a dictionary of Karabakh Armenian. An online scanned copy of the dictionary is found on [Nayiri]([Ղարաբաղի](http://www.nayiri.com/imagedDictionaryBrowser.jsp?dictionaryId=101&dt=HY_HY&pageNumber=27).

As part of the [Learn4Artsakh](https://www.learnforartsakh.com/) initiative, we found a PDF of the dictionary. But the PDF had an OCR format that did not include Armenonological diacritic markers like the umlaut. We are slowly digitizing that dictionary into a TSV format. 

The dictionary is around 800 pages, which we divided into 27 Excel sheets. This repository contains the subsets of the dictionary which we have finished reformatting into TSVs.

Each  TSV contains the following columns:
* index: unique index number for each row
* headword_index: unique index that specifies if some row indicates a new lemma, a new sense (ending in s1, s2, etc.), or a new phrase (ending in p1, p2, etc.)
* headword: lemma form
* etymology
* POS: part of speech
* definition
* example sentence
* note

# InterlineWord
Interline Word is a web based text editor. You can edit, store (in Workspace Floor) and download your files.
This is the stand alone version. It works without the other palmonda files.

## Store Files
Interline Word uses a HDD-like filesystem working in the browser using the localStorage api. This api makes possibe to store strings in a special storag.
I emulate using js a storage space for your files. Using the other palmonda apps, you can manage and clear this space.

### How does it work?
Palmonda apps write an index file and store strings. This strings can become cleared (= delet: clear string, clear part of index).

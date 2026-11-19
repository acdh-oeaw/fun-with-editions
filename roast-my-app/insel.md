# Die Insel

<https://dieinsel.acdh.oeaw.ac.at/>

Timo:
- good keyboard-user accessibility (skip to main, tab-key control)
- would heading structure for metadata pop-ups improve accessibility even further (such as for screen readers)?
- all Insel issue cards on the start page get a `[jg]=I` filter on the link URL, even if they are from, say, Jahrgang II, which results in a mismatch between image/transcription and table of contents on the returned issue page
  - the image/transcription shown on the issue page fit the starting-page card (say, cover of Jahrgang II issue)
  - you get the table of contents corresponding to the Jahrgang-I filter
(tested for card "Nr. 12 Viertes Quartal September 1902": link is https://dieinsel.acdh.oeaw.ac.at/Insel-02-04-12_a0001.html?dieinsel_index_articles[menu][jg]=I&dieinsel_index_articles[menu][issue]=12&dieinsel_index_articles[sortBy]=dieinsel_index_articles/sort/num:asc, but should be https://dieinsel.acdh.oeaw.ac.at/Insel-02-04-12_a0001.html?dieinsel_index_articles[menu][jg]=II&dieinsel_index_articles[menu][issue]=12&dieinsel_index_articles[sortBy]=dieinsel_index_articles/sort/num:asc)
- transcription of decoration symbol <img width="56" height="60" alt="image" src="https://github.com/user-attachments/assets/f01fa339-2dca-4bbc-86e6-8909ac1d006f" /> is  Unicode Character "⟳" (U+27F3), which would seem to add some (perhaps confusing) semantics (esp in web-app/browser context: refresh/reload etc.)

Thomas:
- Search: In the search results it is difficult to see which link belongs to which preview text.
- Search for "Dora": JG III, Quartal 1, Heft 3, Seite NaN - probably because it is a match in the table of contents.
- Search: The introductory text is somehow wrong: For a full text search you don't need a POS tagging. Instead it is necessary for the Corpus Query Language to work.
- As Timo said the used symbols are not appropriate. Maybe it is better to use pictures instead.
- Register: "und Titeln" - Text not visible.
- Register: The search field does not match the menue: "Autoren, Illustratoren und Titeln" - "Autoren und Illustratoren".
- Register: When navigating between pages with the numbers in the navigation bar the browser jumps to the start of the page.
- Main navigation: Add more space or a border on the left side of "Intro".
- Line breaks in the transcriptions: Maybe it would be better for readability to make a running text with small symbols for line breaks.
- When clicking the refresh button the filter parameters remain instead of the fresh page.
- In the navigation menue on the left side of the facsimile view it is not possible to scroll down to the issue numbers except you scroll through the complete table of contents.
- It seems that the table of contents are not complete for all issues / more than one issue.
- JG III, Heft 6, Titelblatt: "Baltbasar" instead of "Balthasar" (probably an OCR error).

Martin:
sorry, can't be there. I really like the images and the colours and how easy it is to use! congratulations!
- page numbers in the transcript appear not to be centered (the original is)
- Download possibilities? Open Source?
- Personally I would like to have a (prefilled) bibliographic source on any page I can copy and paste, including the possibility to only quote the original
- I don’t like that the blue bar on top is see through
- Why no Editionsprinzipien? I/J, Schaft-s, why "=" instead of the proper UTF-sign "⹀"   

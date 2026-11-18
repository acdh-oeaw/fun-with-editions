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

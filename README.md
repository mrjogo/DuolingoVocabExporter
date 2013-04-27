Vocabulary export script for [Duolingo](http://duolingo.com/)
===
Written by Ruddick Lawrence
---

Duolingo is an innovative (free!) way to learn new languages, but they don't provide an easy way to study just the vocabulary. Some people (like me) learn very quickly by studying flashcards, so I created this script to put the Duolingo vocabulary into CSV form (which can then easily be imported into a flashcard program/website).

### To run from the browser console:
1. Navigate to the Duolingo vocabulary page you want to convert (such as http://duolingo.com/#/vocab). Note that the script works on both the whole vocabulary and any subcategories.
1. Open up your browser's console (on Chrome it's Chrome menu > Tools > JavaScript Console)
1. Copy and paste the contents of duolingo-vocab-exporter.js into the console and press enter.

Because of how the vocabulary pages work (they progressively load more words as you scroll to the bottom), you may have to wait a little as the script repeatedly scrolls down and loads all of the words. When it is finished, the page will be replaced by the CSV output, which you can copy into a new file and save with a .csv file extension.

### To turn into a bookmarklet:
1. Minify the code by copy and pasting the contents of duolingo-vocab-exporter.js into jscompress.com and pressing "Compress Javascript".
1. Create a new bookmark and title it whatever you want.
1. In the bookmark's URL field, type "javascript:" (without the quotes), and paste the minified code from step 1.

This will allow you to click that bookmark while on any Duolingo vocab page to run the script.
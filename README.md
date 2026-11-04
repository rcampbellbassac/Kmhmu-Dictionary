# Kmhmu' Dictionary
A place for every Kmhmu' word!

## Want to help?
Please help us add words to this dictionary. Once completed, it will be used to help build language support for the Kmhmu' language across multiple platforms, libraries and applications.

## Files
- **`kmhmudict.txt`**: Kmhmu' words in Lao script, one per line, in the same format as ICU's
  `laodict.txt`, so it can be used for word breaking (ICU, LibreOffice and similar tools).
- **`kmhmudict-details.tsv`**: one row per word with the Roman-script form, how often it occurs,
  where it was found, and its review status. Columns:
  `lao`, `roman`, `count`, `sources` (`luke`, `bfc`), `name` (proper name), `same_as_lao` (spelled
  like an existing Lao dictionary word), `clashes_with_lao` (in testing, this entry changed how ICU
  splits ordinary Lao text), `status` (`unreviewed` until a Kmhmu' reader confirms it), `gloss_lao`,
  `gloss_credit`, `first_ref` (first place the word occurs).

## Where the first words came from
The first 1,880 words were collected from Roman-script Kmhmu' texts and converted to Lao script by
rule. They have **not yet been checked by a Kmhmu' reader**; see `status` in the details file.
- *Bible Portions in Khmu* (the Gospel of Luke), Wycliffe Bible Translators USA, via the Digital
  Bible Society (non-commercial use). Only the word list is used here, not the text.
- Seven Khmu stories from Bible for Children (bibleforchildren.org).
- Three words and Lao glosses from Tawakuqbri (PR #1, 2024).

The Roman-to-Lao conversion follows the orthography tables of the *Kmhmu'-Lao-French-English
Dictionary* (Suksavang Simana', Somseng Sayavong and Elisabeth Preisig, 1994) and Miller (2013),
*A description of Kmhmu' Lao script-based orthography*, Mon-Khmer Studies 42:12-25. It reproduces
all 76 example words given in those sources. See `RESOURCES.md`.

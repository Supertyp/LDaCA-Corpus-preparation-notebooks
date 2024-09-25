# LDaCA-Corpus-preparation-notebooks
notebooks for corpus preparation

------------------------------

## ELAN

Notebooks to use on folder of ELAN files

- **ELAN_change_tier_names.ipynb**
> Change all tier names based on customizable rules.
 
- **ELAN_remove_tiers.ipynb**
> Filter all ELAN files to only include the tiers you want and remove all others. E.g. non-participant tiers, tiers internal to the research team

- **ELAN_to_CSV.ipynb**
> create a csv file for each ELAN file in folder

- **ELAN_change_text_content.ipynb**

> This srcipt produces a complete inventory of every character in 
> a folder full of ELAN files
> In a second step the user can decide how to handle each found character.
> Used to replace unwanted characters like curly apostrphies: ’ becomes '.
> Remove unwanted characters (e.g. non-printable characters, e.g. apostrophes curly vs. non; ), double spaces (currently Elan only)

- **ELAN_commander.html**
> Same as ELAN_change_text_content but with User Interface. Available online at: **https://www.gerlingo.com/ELAN_commander.html**

- **ELAN inventory**
> Obtain a list of Elan tiers in each file in a corpus + content, number of annotations, number of words
> also available through user interface; **https://www.gerlingo.com/config_maker.html**

- **ELAN_anonymize_transcrition.ipynb**
> Identify proper nouns (currently Elan only)
> Assists with de-identification of transcripts: Identifies all words that occur capitalised (and never non-capitalised), and produces a list from which the user can choose which to give pseudonyms to

----------------------------

## Forced alignment notebook
- **ELAN_wav2vec_words_and_letters_Forced_alignment.ipynb**
> From orthographic transcriptions aligned at the level of the phrase produces alignments at the level of the phonological segment



## ELAN / csv / text
- **Change_file_names.ipynb**
> Change all file names in folder. This is a simple string replacement and works on any file 
> This srcipt produces a complete inventory of every character in 
> a folder full of ELAN files

-------------------------

## csv / text
- Combine files – combine multiple files to form a single corpus (coming soon)

## csv - Requires customisation
- Remove characters (coming soon)
- Remove a defined set of characters (e.g. transcription symbols, e.g. [ ] for overlaps, @ for laughter etc.) (coming soon)


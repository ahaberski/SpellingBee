# SpellingBee
SpellingBee is a custom dictionary of 15,224 entomological terms to improve the spellchecking of entomological manuscripts. Word processor spellcheck functions do not recognize many entomological terms and will incorrectly flag them as spelling errors. Installing SpellingBee will significantly reduce the prevalence of these errors. SpellingBee will not overwrite users' existing custom dictionaries, but supplement them. SpellingBee is compatible with most word processing applications

Citations make the world go round! If you use it, please cite it:

Haberski, A., C. Silva. 2026. Introducing SpellingBee: the Entomological Spellchecker. American Entomologist. 72 (1).

## Installation instructions for Microsoft Word. 
Instructions for other applications can be found in their respective "Help" menus.
  
  Windows:
    
    1.	Download SpellingBee.dic and save it to the desired folder.
   
    2.	Open the Custom Dictionaries dialog box: From the toolbar go to File > Options > Proofing.
    
    3.	Select Add.
    
    4.	Locate the folder containing SpellingBee and then double-click the dictionary file.

  MacOS:
    
    1.	Download SpellingBee.dic and save it to the desired folder.
   
    2.	Open the Spelling & Grammar dialog box: From the toolbar go to Word > Preferences > Spelling & Grammar.
    
    3.	Select Dictionaries.
    
    4.	Select Add.
   
    5.	Locate the folder containing SpellingBee, click the dictionary file and select Open.

## Statistical test
### Methods
We tested SpellingBee’s efficacy on articles from five journals published by the Entomological Society of America with open-source articles: Environmental Entomology, Insect Systematics and Diversity, Journal of Insect Science, Journal of Integrated Pest Management, and Journal of Medical Entomology. Combined, these journals encompass a broad scope of entomological subdisciplines. Our search was limited to “open-access” or “free” research articles, which yielded 11,183 results. Ten were chosen at random from each journal (n = 50) and the principal text (introduction, methods, results, conclusions, and captions) was copied and pasted into Microsoft Word v16.65 as plain text. We excluded reference sections because they contain numerous proper nouns and abbreviations that would inflate the number of false positives and slow down the test.

We then ran the spellcheck tool with the standard dictionary, and again with the standard dictionary plus SpellingBee to compare the number of errors detected. The proofing language was set to American English. We assumed that published manuscripts contain relatively few genuine spelling errors, and the majority of detections would be false positives. The difference in the mean number of reported errors was compared with a paired T-test. Flagged words were then extracted using a custom macro script and categorized by error type. 
### Results
Our evaluation on published journal articles found SpellingBee significantly reduced the number of false positives detected during spellcheck (t = 3.77, df = 49, p = 0.0004; Table 1). 

**Table 1:** Comparison of errors reported during spellcheck of 10 articles each from 5 journals (n = 50) published by the Entomological Society of America, using SpellingBee versus the standard Microsoft Word dictionary. Table values are means ± standard errors.

All journals combined (n=50)
- standard dictionary: 233.8 ± 36
- standard dictionary + SpellingBee: 211.5 ± 32 *

Environmental Entomology (n=10)
- 149.7 ± 42
- 141.0 ± 40 *

Insect Systematics and Diversity (n=10)
- 573.0 ± 21
- 500.3 ± 20 *

Journal of Insect Science (n=10)
- 127.4 ± 125
- 114.3 ± 111

Journal of Integrated pest Management (n=10)
- 174.3 ± 34
- 167.2 ± 33 *

Journal of Medical Entomology (n=10)
- 144.7 ± 22
- 134.8 ± 20

"*" indicates significantly different means at α = 0.05.


**Table 2:** Relative proportion of error types detected while using SpellingBee. 
- Taxonomic names: 51%
- Other proper nouns: 32%
- Abbreviations: 11%Other: 5%
- Non-english words: 1%
- Genuine spelling errors: <1%

## Acknowledgements
  Peter Adler, Michael Caterino, Curt Harden

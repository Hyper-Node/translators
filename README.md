# translators
Translators for german/korean 


## general definition 

We aim to make a new translator program or use an existing
one for translating korean texts to german and vice versa. 

The program should run locally and shouldn't send files 
to an remote server. 

In the end it should translate batches of files and might 
also have a GUI.


## stuff we have
lots of already human-translated korean and german texts 

## ideas so far 
 - use google-translator as an app version with offline data, improve offline korean/german data 
 - open source machine translation engine, which runs locally we improve dataset by training
    * use apertium (www.apertium.org), create a language pair german korean 
    * use apertium do korean-english, english-korean translation  
    * use moses (https://github.com/moses-smt/mosesdecoder)
    * use phrasal (java) (https://github.com/stanfordnlp/phrasal)
    * use joshua (java) (https://cwiki.apache.org/confluence/display/JOSHUA/Apache+Joshua+%28Incubating%29+Home)
    
 - use a library for grammar detection, setup grammar detection, refator grammar use  dictionaries to translate 
 - obfuscate texts and send them to google-translator deobfoscate translated text 
 - use a library e.g. python / javascript for translation 
    * 
  




###interesting read 
- moses engl-korean: https://www.taus.net/think-tank/reports/translate-reports/constructing-korean-english-machine-translation-systems-and-evaluating-translation-quality
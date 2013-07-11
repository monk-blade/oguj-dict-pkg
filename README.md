Installation
=============

##Linux

- Download debian file from here . [Link](https://github.com/codejar-lab/oguj-dict-pkg/blob/master/oguj-dict-pkg1.1_all.deb)
- Open it via Gdebi Package installer or Ubuntu software Center or via command line.
- Open Stardict and search English words [Offline] and it will work.


##Android

- Download Colordict application from Google Play store.[Link](https://play.google.com/store/apps/details?id=com.socialnmobile.colordict&hl=en)
- Download zip file from here.[Link](https://github.com/codejar-lab/oguj-dict-pkg/blob/master/Android/opengujarat_android_all.zip)
- Uncompress downloaded file at /Internal Memory/dictdata/(In your android phone)
- Search in colordict app(Offline)
- All android version works. If you find gujarati font rendering problem then it is your phone problem.

##Kindle 1-4/Paperwhite/Touch

- Download zip file from here.[Link](https://github.com/codejar-lab/oguj-dict-pkg/blob/master/Android/opengujarat_android_all.zip)
- Install stardict-tools in ubuntu 
  
  `sudo apt-get install stardict-tools` 

( **Windows users** : Stardict editor, which you can find here: http://stardict.sourceforge.net/other.php )
- Open stardict-editor through terminal.
- Decompile using stardict-editor(input:ifo file).This will generate one text file.
- Once you have such a file, use tab2opf.py from [here](http://www.klokan.cz/projects/stardict-lingea/)
  This is a free python script by Petr Klokan, so you’ll need python isntalled(no need for linux.only windows users
  have to install python).

- Type `tab2opf.py -utf dictionary.txt` into the command line to run the script.This will give you a dictionary.opf file, and a number of dictionary0.html files

- Edit the dictionary.opf file, to specify the name of the dictionary, and the input/output output languages.

- Get mobigen.exe form - [here](http://www.mobipocket.com/soft/prcgen/mobigen.zip)

- Extract mobigen exe

- Run mobigen.exe dictionary.opf (Ubuntu : `wine mobigen.exe dictionary.opf`)

- If you did everything right, you’ll get dictionary.mobi which’ll be the gujarati dictionary for kindle.

- Other dictionary files are available from: http://stardict.sourceforge.net/Dictionaries.php

Cheers! Happy Hacking !

#####REMEMBER : KINDLE DOES NOT SUPPORT UTF-8 LANGUAGES (GUJARATI,HINDI ETC) SO YOU MAY SEE SOME FONT RENDERING PROBLEM USING THIS DICTIONARY BUT TEXT IS READABLE.અરે યાર.કઈક તો જતું કરવું પડે ને ...

####Read credit of Database of 60,000 words goes to [GujaratiLexicon.com](http://www.gujaratilexicon.com)

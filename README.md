# Mac_Dictionary_MN
English-Mongolian dictionary to Mac dictionary app

Англи Монгол толь бичгийг MacOS толь бичгийн апп дээр нэмэх

1. Download the dictionary files from en-mn directory.

2. The tool we use for convert dictionary file to MacOS dictionary --> https://pypi.org/project/pyglossary/

4. Installation: 

  - sudo easy_install pip3(if you don't have pip3)
  - sudo pip3 install lxml beautifulsoup4 html5lib
  - need to install these two developer package 

    - GNU make as part of [Command Line Tools for Xcode](http://developer.apple.com/downloads).
    - Dictionary Development Kit as part of [Additional Tools for Xcode](http://developer.apple.com/downloads). Extract to `/Developer/Extras/Dictionary Development        Kit`

5. Commands that used for convert it by using pyglossary and install it to Dictionary app:

    - python3 [main.py](http://main.py/) --write-format=AppleDict altangerel/altangerel_english_mongolian_dictionary.ifo english_mongolia.dictionary

    - make

    - make install
  
6. Screenshot of quick look:

  ![Test Image 1](https://github.com/N3TBOY/Mac_Dictionary_MN/blob/master/en-mn/Screen%20Shot%202020-07-31%20at%2018.19.10.png)

Dictionary files downloaded and used from: https://github.com/ochko/stardict-mn-dics

Mongolian keyboard layout guide: http://mongoliankeyboardformac.blogspot.com/

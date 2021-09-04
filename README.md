 # Enigma Machine
This is a project that I worked on extensively to solidify my understanding of Python, Github, Anaconda, and Jupyter. In the process I also learned about the Google Translate API I implemented as well as the time function I used to speed test and optimize my code.

**Working Enigma Simulator.ipynb: **
The functioning and most up-to-date example of my Enigma work. It has a default message within it, so you can download the
code and run it immediately with 100% accurate code decryption. In the second cell of this file is a Google Translate API 
to translate the German result into English, but it involves the credentials to my Google Cloud account which I have not uploaded to Github.

**Enigma Development Folder: **
The remaining code and functions that were not used in the final product, but may be potentially useful in the future.

**German Dictionary Attempt Folder: **
The result of the Enigma machine is a long string of letters without spaces which would be easily readable by a German speaker. I don't speak German, and wanted to translate the result to English at the end of the code.Google Translate requires spaces between the words, so after doing some research, I found an example that could do the same task in English. It would take an English dictionary (most common 10,000 words) and then apply it to the string to infer where spaces should've appeared. I programatically created a German dictionary by scraping several German newspapers and created a large dictionary. Upon application to the string, the spaces were not revealed correctly and 30 minutes of tinkering did not improve the result.
 

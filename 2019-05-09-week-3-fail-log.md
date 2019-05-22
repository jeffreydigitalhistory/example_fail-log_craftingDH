# Week 3 fail log

(Note: This is a scratch pad; record of commands, code written, memos to self of websites gone for help etc)

Activities for this week:  
- The Dream Case  
- Wget  
- Writing a program to extract data from a webpage  
- Encoding transcribed text  
- Collecting data from Twitter  
- Coverting images to text with Tesseract  

The Dream Case was pretty straightforward - just using nano to log what was searched in the dbs and saved into Github

Wget was interesting and had a bunch of useful options that I didn't know of!  
Recording some here for future reference:  
wget -r --no-parent -w 2 --limit-rate=20k http://activehistory.ca/papers/  
wget -m -w 2 --limit-rate=20k http://activehistory.ca  

I liked that we also did a bit of Python scripting - I won't include it since it seems to be specific to this module

Encoding the transcription was definitely something new I've never done before and made me really dive into the content and check for specific people, places and arguments that could be important. 

The line that you would need to change the xml to point to the new xsl is the href at the top of the xml file that currently references the other one.

For the API component, I struggled a bit on this one. When trying to open the Jupyter binder, it spit out a series of errors that rendered it unusable. I think the purpose of this was suppose to be a command terminal of some sort but unfortunately it didn't work out as expected. I then turned to the working "non-interactive" notebook on the bottom and was able to find the three APIs listed in the exercise. However, I was a bit confused as to how to approach this - are we changing the keywords or something else fundamentally in the code? Edit: After bringing up the issue with the Professor, he quickly fixed it and was able to use the server component well.  
Something to note: For open context use "obj" for url params  

The fifth exercise, mining twitter was interesting! A bit of hiccups were discovered (as outlined a bit in the reflection) but good after that point. Some useful commands:  
- twarc search electricarchaeo  
- twarc search electricarchaeo > electricarchaeo.jsonl  
- Voyant is a cool tool to look at data!

Tesseract went smoothly for the most part. There was one point when I was installing imagemagick where I think I had to do an apt-get update in order for it to work; just a minor hiccup.  
Pretty cool commands:  
convert -density 300 ~/war-diary/e001518087.jpg -depth 8 -strip -background white -alpha off e001518087.tiff  
tesseract e001518087.tiff output.txt  

install.packages('magick')  
install.packages('magrittr')  
install.packages('pdftools')  
install.packages('tesseract')  
library(magick)   
library(magrittr)  
library(pdftools)  
library(tesseract)  
text <- image_read("/war-diary/e001518087.jpg") %>%  
  image_resize("2000") %>%   
  image_convert(colorspace = 'gray') %>%   
  image_trim() %>%   
  image_ocr()  
write.table(text, "/ocr-test/R.txt")  

## Comments/Concerns

Overall enjoyed this week's material as well. A lot of useful commands and tools were used! Some of it was a bit more troublesome to use than others (for small reasons) but diving into it a bit solved the issue most of the time (or asking someone else)

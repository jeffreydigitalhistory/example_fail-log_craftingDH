# Week 4 fail log

(Note: This is a scratch pad; record of commands, code written, memos to self of websites gone for help etc)

## Activities for this week:  
### Regular expressions  
This was a cool exercise to do! I've had experience in regular expressions from school and work since its a very handy way of getting specific data or selecting certain things. I think its interesting in the context of extracting formal data and information vs what the exercises done in the computer science classes that deal with arbitrary scenarios.  
Some good to know regular expressions that I didn't know of:  
- \< and \b is beginning of word (always thought it was ^)  
- \> and \b is end of word (always thought it was $)  
- sed 's/old text/new text/g' filename (identifies text that matches pattern and swaps it)  
- grep 'PATTERN WE WANT' inputfile > outputfile  (finds text and prints it to screen or to outputfile as it is done here)  
- grep '\bto\b' texas.txt  (finds results with the word "to" in it, exlusive)  
- sed -r -i.bak 's/(.+\bto\b.+)/~\1/g' texas.txt  (makes backup -i.bak, doesnt have to escape characters, finds all ones with to in it and adds tilde)  
- sed -r -i.bak 's/(,)( [0-9]{4})(.+)/\2/g' index.txt (makes it into csv format)   
- sed -r -i.bak 's/~//g' index.txt  (removes tilde!)  
- sed -r -i.bak 's/(\b to \b)/,/g' index.txt  (separates senders and receivers)  
- grep -r ".+,.+,.+," index.txt  (more cleanup regarding csv style)
- cp index.txt cleaned-correspondence.csv  (makes a csv out of the file)  
I found some of the specifics to be hard, even when trying things in the regex playground so it was fairly difficult even for someone who is familiar with regex beforehand!  

### Open Refine  
Nice that we are using a web server to run Open Refine! From the videos and examples, it seems to be an incredibly powerful tool to fix data and I might actually incorporate it in work as there are cases like this where things can and should be clustered due to different naming conventions and what not. Something I did notice while using the tool was that I was not able to reduce it to the number of Senders that he had - instead of reducing it from 189 to around 150, I could only get it to around 171. Similarly, I had the same for Recipients where it said from around 192 to 160 I only got it to around 179. I believe part of it was because some of the merging was not applicable so I skipped the merging of quite a few things but I think that I did my best judgment on that part.  
I also had some slight problems exporting the csv from the project in Chrome - it would just hang on the new page opened. To get around this, I just opened the same thing on Firefox and it worked fine there.  
Putting the final data into Palladio was interesting but to be honest, I didn't know what to make of it...the general shape of it was almost like a target, with a bunch of the names clustered in the middle and then a ring of other names outside of it. Nonetheles, it's cool to see what you can do with this kind of information.  

## Comments/Concerns  
As mentioned before, the regex was a bit challenging, especially in the context of "real" data and found some of the regex to be hard to figure out. I got some of them but in unorthodox ways and ended up using the solutions that were included at the end since they were cleaner and made more sense. Open Refine was a cool and useful tool outside of the course that I might be able to utilize since it seems like its a powerful way to organize and cluster similar data. OVerall, once again, found myself enjoying the module again and looking forward to another week of learning new ways to clean, use and organize data!  


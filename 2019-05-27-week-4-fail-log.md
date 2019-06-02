# Week 4 fail log

(Note: This is a scratch pad; record of commands, code written, memos to self of websites gone for help etc)

## Activities for this week:  
- Regular expressions  
This was a cool exercise to do! I've had experience in regular expressions from school and work since its a very handy way of getting specific data or selecting certain things. I think its interesting in the context of extracting formal data and information vs what the exercises done in the computer science classes that deal with arbitrary scenarios.  
Some good to know regular expressions that I didn't know of:  
- \< and \b is beginning of word (always thought it was ^)  
- \> and \b is end of word (always thought it was $)  
- sed 's/old text/new text/g' filename
- grep 'PATTERN WE WANT' inputfile > outputfile  
- grep '\bto\b' texas.txt  
- sed -r -i.bak 's/(.+\bto\b.+)/~\1/g' texas.txt  
- sed -r -i.bak 's/(,)( [0-9]{4})(.+)/\2/g' index.txt  
- sed -r -i.bak 's/~//g' index.txt  
- sed -r -i.bak 's/(\b to \b)/,/g' index.txt  
- grep -r ".+,.+,.+," index.txt  
- cp index.txt cleaned-correspondence.csv  
I found some of the specifics to be hard, even when trying things in the regex playground so it was fairly difficult even for someone who is familiar with regex beforehand!  

- Refine



## Comments/Concerns  
As mentioned before, the regex was a bit challenging, especially in the context of "real" data and found some of the regex to be hard to figure out. I got some of them but in unorthodox ways and ended up using the solutions that were included at the end since they were cleaner and made more sense.  


# Week 3 Reflections:

## Reflection on exercises:

Activities for this week:  
- The Dream Case  
- Wget  
- Writing a program to extract data from a webpage  
- Encoding transcribed text  
- Collecting data from Twitter  
- Coverting images to text with Tesseract  

The Dream Case was a straightforward section - search keywords in a database, export them and record them in a file.

Wget was an interesting one! I've played around with this before for scraping things but I really didn't know it was this powerful! The only downside seems to be that it is single threaded but even so the ability to put delays and restrict download speed to not overload servers are very cool options that I didn't know existed. I also liked using Python and look forward to potentially learning and using it more for retrieving data, especially when used in conjunction with wget!

TEI

*Questions*  
http://www.recoveredhistories.org/  
What makes you believe this site is a trustworthy provider of historical texts?  
- Contact information is explcitly listed and linked to a trustworthy site (antislavery.org) as well as a number of other reputable organizations
- Going through some of the source texts looks legitimate and not made up
What makes you believe this site is NOT a trustworthy provider of historical texts?  
- It looks a bit "ghetto" since its old fashioned
- Information can be faked out although they would have taken great effort to do so  

APIS

Overall, a good exercise! I've dealt with third party APIs for other projects and work (Youtube, Paypal, etc) and so I'm familiar with the concepts that were trying to be taught. The last activity to get the data csv from a medieval search is taking too long (have been trying to wait for it to get out of the loop for about 30 minutes now) so I'm skipping it

Mining Twitter

This was probably one of the more troublesome parts due to trying to get a consumer key. It's a bit more difficult to get a consumer key on your own (have to apply for it and get it approved) so I opted to ask the professor for his. When he  replied, I tried it out but it redirected to a page that said "Your PHP installation appears to be missing the MySQL extension which is required by WordPress.". Looking into this a bit more, it looks like its redirecting to the base site of the professors site...which is strange. In either case, I cannot get the PIN that is needed to move forward so will ask the Slack thread and see if anyone can help.  
Update: This is a bit of a fumbled on my end - he tells you what exactly to look in the next section. It is actually the oauth_verifier parameter not the oauth_token key that you are looking for however  

Tesseract  

It was interesting using Tesseract from the command line and then in R and seeing the differences between how they process the data and either get drastically or gradually different.  I especially liked being able to batch convert the images!  

Ask yourself: what are some of the key dangers? Reflect: how have you used digitized resources uncritically in the past? Remember: To digitize doesn't — or shouldn't — mean uploading a photograph of a document.  
I've used digitized resources probably pretty irresponsibly in the past (and likely here and there). I've actually done a couple speeches at things like Toastmasters where I've disseminated (or tried to) information that I thought was interesting such as space, theology, health, etc. I've never gone too far into properly giving credit or sourcing where I got the information or pictures in my presentations simply due to the somewhat informal nature of it all and perhaps my overtrust on the sources where I got this information from. I think trying to be more mindful of how these digitized resources and sources should be used moving forward is something that I need to work on and likely needs a bit more thought for others as well.

## Reflection on readings: 

*Questions*  
Have you ever sat down with one of the librarians to get help finding something?  

Consider the knowledge and labour involved not just with finding materials, but in making materials findable in the first place. Make an entry in your blog that reflects on these questions in the light of your annotations.

The article I chose to talk about is [Seams and edges: Dreams of aggregation access discovery in a broken world](http://discontents.com.au/seams-and-edges-dreams-of-aggregation-access-discovery-in-a-broken-world/).

In regards to the questions, I don't think I ever explicitly sat down with a librarian for finding books at any point in my life. In elementary and early high school life, I already looked upon libraries as old vestigial remnants of physical data archives since I was introduced into technology and, frankly, spoiled by Google. Therefore, I regarded a lot of librarians as keepers/overseerers of the institution rather than a source of knowing where things are, since they also did not always know where to find things and I didn't blame them. In large libraries, it's almost impossible to expect an individual to know where things belong and if they were currently checked out or not which is why the library catalogue exists. In the odd case I didn't know what to look for, there were usually self library catalogues kiosks that would tell me if books were checked out or not, which in a sense, functioned as the real "librarians". I dont mean to disparage librarians and their function but there is an increasing, if not already established, need to move to digital forms of keeping track of assets so that it can be properly and efficiently. 

To try and convey my respect to librarians a bit mroe, with respect to the second statement and question, the librarians ensure that everything gets put into the proper place from a physical point of view: primarily by managing the systems that keep track of the information and putting data entities into their respective locations. In the context of a well functioning library, staying on top of materials and putting them back into place is an important piece of the puzzle and ultimately makes finding materials easily (can almost be the "indexing" equivalent of search engines). Without a proper indexing and traversing backend, a search engine will fall flat.

Now, with respect to the above metaphors, I think a segway into Google is in place as that was the focus of my annotations. I thought it was relevant to this topic when considering searchability and our [reliance](https://hyp.is/keaGRnwIEemZCz_Kt_3dJQ/discontents.com.au/seams-and-edges-dreams-of-aggregation-access-discovery-in-a-broken-world/) on it. Unless it's a proprietary book of some sort, you can almost ubiquitously find whatever you want on Google: tutorials, history, images, people, etc. This is all fueled by a top notch search algorithms and indexing methodologies but I also like the take the article took on how the data is displayed. The somewhat [flat, minimalistic](https://hyp.is/ClagZnwJEemDt9t-Jr7bfw/discontents.com.au/seams-and-edges-dreams-of-aggregation-access-discovery-in-a-broken-world/) can be a limiting aspect to how we can ultimately consume the information and make connections - it functions on one level but can't it be done in more dimensions to stimulate other ways of thinking and interpreting the data? 

In either case, the amount of work and effort to do this manually is staggering and even from Google's digital point of view, they have invested millions and will continue to do so as the methods to make search even more powerful become increasingly complex and sophisticated. 

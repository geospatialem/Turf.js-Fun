# Lyzi's Turf Exercise

Hi Lyzi,

Thanks for sharing the <a href="http://lyzidiamond.com/turf-exercise/">Turf.js exercise</a>, it was a lot of fun to work with! :-) Overall, I am a fan of Turf.js but I would definitely not recommend it to anyone who is new to JavaScript or development as it wasn't as intuitive as I was expecting. Hopefully my comments below help in providing more context into why I believe that is the case but if not, feel free to shoot me a message back and I'd be happy to discuss in greater detail. 
Again, thank you for sharing this with others in the community, I see this as a great asset with the work I do everyday. :-)

Regards,

Kitty

In response to your questions:

__*1. Which prompt did you attempt?*__

Number 4, kind of. I used Minnesota's counties and classified them using some data I help serve up in my office: asthma hospitalizations' age-adjusted rate per 10,000 people. I calculated both the quantiles and jenks data classifications.

__*2. What turf modules did you use?*__

 - Jenks
 - Quantile

__*3. What was helpful about the documentation?*__

text

__*4. What was not great about the documentation?*__

- While the documentation was great it only showed some examples that helped to get started but didn't go over any advanced information. It also did not give details on the back-end or under the hood issues which made it difficult for me to troubleshoot what the issue was when they presented themselves.

- Another issue I encountered was although I could get the values I was unsure of how to apply them to the JSON file once the values were created. For instance, I was unable to understand how to apply the classifications to the JSON file as the documentation only lists how to get the values but doesn't specify how to apply them back to the JSON file. Of course, this is also a limitation of my understanding of JavaScript, so this may not effect all users but as a new developer it made things difficult. An improvement could be providing a few more detailed examples in addition to the smaller snippets of code that help users get started. :-)

__*5. How can we improve it?*__

One of the first questions I had was, 'What can I do with a point? What about a line? polygon?' It would be cool to be able to see what capabilities exist for each right away (in addition to clicking on each module to check if it works with the type) if there is a specific data type the user would like to utilize.

__*6. What other resources did you use for help?*__

Lots of JSON resources as that was one of my biggest hurdles. While I could get the JSON file to load just fine I was unable to import the JSON file using Turf.js without manually entering it in as seen in the examples provided in the documentation.

__*7. Other Notes*__

When running on the field values with 'null' seem to throw off the classifications, or breaks. Since the data I see everyday has to be suppressed, since it includes private information, this would pose a problem. Knowing a little bit more of the back-end and how Turf.js runs would be helpful to troubleshoot, or at least, help those with specific datasets' understand what is going on 'under the hood'.

# Lyzi's Turf Exercise

Hi Lyzi,

This Github project includes a README.md file (that includes all of my answers below), the JSON file (.js) utilized and all of the code in the index.html page. I've also got a working copy of the <a href="http://geospatialem.github.io/Turf.js-Fun/">final map</a> on Github.

Thank you for sharing the <a href="http://lyzidiamond.com/turf-exercise/">Turf.js exercise</a>, it was a lot of fun to work with! :-) Overall, I am a fan of Turf.js but I would definitely not recommend it to anyone who is new to JavaScript or development as it wasn't as intuitive as I was expecting. Hopefully my comments below help in providing more context into why I believe that is the case but if not, feel free to shoot me a message back and I'd be happy to discuss in greater detail. 
Again, thank you for sharing this with others in the community, I see this as a great asset with the work I do everyday. :-)

Thanks,

Kitty

In response to your questions:

__*1. Which prompt did you attempt?*__

Number 4, kind of. I used Minnesota's counties and classified them using some data I help serve up in my office: asthma hospitalizations' age-adjusted rates, calculated per 10,000 people between 2009-2011. I used Turf to calculate the quantiles and Jenks (natural breaks) data classifications.

__*2. What turf modules did you use?*__

 - Jenks (natural breaks)
 - Quantile

__*3. What was helpful about the documentation?*__

It was clear how to get started and get going with the code. I tried to understand a few examples before coding and everything listed was intuitive. There wasn't as much documentation on what Turf's overall purpose is but I think that would be really helpful for those getting started or looking to use Turf as a tool. :-)

__*4. What was not great about the documentation?*__

- While the documentation was great it only showed some examples that helped to get started but didn't go over any advanced information. It also did not give details on the back-end or what was going on 'under the hood' which made it difficult for me to troubleshoot any issues that were presented.

- Although I could get the classification values when calling Turf I was unsure of how to apply them back to the JSON file once the values were created. In particular, the documentation only lists how to get the classification values but doesn't specify how to apply them back to the JSON file for styling. Of course, this is also a limitation of my understanding of JavaScript, so this may not effect all users but as a new developer it made things difficult. If I wanted to apply the classifications I would still need to manually enter in the numbers Turf provided into the JavaScript. An improvement could be providing a few more detailed examples in addition to the smaller snippets of code that help users get started. :-)

__*5. How can we improve it?*__

One of the first questions I had was, 'What can I do with a point? What about a line? polygon?' It would be cool to be able to see what capabilities exist for each right away (in addition to clicking on each module to check if it works with the type) if there is a specific data type the user would like to utilize.

__*6. What other resources did you use for help?*__

I haven't used the Mapbox API much so I utilized other Mapbox API library resources and samples, all of which were fantastic!! Additionally, many JSON resources as that was one of my biggest hurdles. While I could get the JSON file to load into the application I was unable to assign Turf's values back to the JSON file.

__*7. Other Miscellaneous Notes*__

It seemed Turf had issues with field values containing 'null' when determining the classification levels (breaks). Since the data I see everyday has to be suppressed, since it includes private information, this would pose a problem for me utilizing Turf while at work. Knowing a little bit more of the back-end and how Turf runs would be helpful to troubleshoot, or at least, help those with specific datasets understand what is going on 'under the hood'.

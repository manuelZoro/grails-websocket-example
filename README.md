This project is based on the example :

###WebSocket (Tutorial 01 - Java Server + JavaScript Client + GlassFish 4.0 + JDK 1.7)
###ZA Software Development Tutorials

http://www.youtube.com/watch?v=_Fi4vz6oUio

+

https://www.youtube.com/watch?v=BikL52HYaZg

I have ported over the concept into Grails and it does appear to be working fine, the additions was the Listener which is in src/groovy and dynamically added to web.xml using the _events.groovy in scripts folder...

Besides this everything else is as was on the tutorial 

I will also add the chat example into this so its the complete example as per instructions but now working under Grails :)


#### Chat has now been added too chat.gsp which interacts with MyServletChatListenerAnnotated Endpoint
 

### Please note  this is using Grails 2.3.7 with Java 1.7 - no additional libraries was required - Glasshfish etc not installed into grails.


 
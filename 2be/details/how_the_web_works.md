## How The Web Works

### Background:

Review the materials below.

* First let's read [MDN HOW WEB WORKS](https://developer.mozilla.org/en-US/Learn/Common_questions/How_does_the_Internet_work)
* Next let's watch a few quick examples of [how the internet works](https://www.youtube.com/watch?v=7_LPdttKXPc).
* And [how IP addresses work](https://www.youtube.com/watch?v=KFooN7Mu0IM   - how IP addresses work).
* Finally let's tie these things together and watch a video about [DNS - what happens when you type an address into a web browser](https://www.youtube.com/watch?v=72snZctFFtA).
* Lastly, let's read a little about [the anatomy of a URL](https://doepud.co.uk/blog/anatomy-of-a-url)

### Questions:

Now we have a better grasp about the internet, and how some of the things are working. Now, let's answer a few questions to check our understanding. Don't be afraid to do additional research (googleing) for an answer. Fork this gist and answer the following questions:

1. Describe, step by step, what happens when I type `www.example.com` into my browser and try to go to the page? The browser and operating system will both try to determine whether they know the IP address already. If not, the OS asks a resolving name server for the IP address it doesn't know. The RNS stores that information in cache and then takes that information to the root name server.  The root name server then finds the top level domain servers, and the TLD name servers direct the RNS to the authoritative name servers. The correct ANS is determined by the domain's registrar.  The right ANS will recognize the domain name and produce the correct IP address, which the RNS will then return to the operating system, which will point the browser to the right IP address. 
1.  What does HTTP stand for? Hypertext Tranfer Protocol
1. 	What protocol does the World Wide Web use?-http
1. 	Each computer on the Internet is assigned an IP address, what does IP stand for? Internet protocol
1. 	What does DNS stand for?
  * A. Domain Name System

1. 	How are text domain names matched to their respective numeric IP addresses. Through the domain registry--when a domain is purchased, the registrar is told which authoritative name server to use.  The registrary notifies the registry to update the TLD servers to point to the correct ANS. 

1. 	What is the client?

  * E. The computer which the IP address belongs to
  
1. 	What does URL stand for? Uniform Resource Locator

1. 	What are protocols

 * D.	The standardised method for transferring data or documents over a network
 
1. What does DNS stand for?- Domain Name System
1. what is the `www` portion of a url? part of the domain name
1. What is The markup language used for all web documents? html
1. What is the organization that monitors web technologies? W3C--World Wide Web Consortium
1. What is the Protocol for transferring web documents on the Internet? hypertext transfer protocol
1. What matches the domain names with numeric IP addresses? The authoritative name server, identified through the domain registry







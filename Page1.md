# **History of the Internet**
---
## **Early Visions and Breakthroughs (1950s – 1960s)**
* J.C.R. Licklider, a psychologist in the 1950s and 1960s, envisioned a global communication network. In a 1968 paper, he described a network that “unites communities of common interest and collaboration without regard to location.”
* In the early 1960s, Leonard Kleinrock, a graduate student at MIT, began to outline a decentralized communication network design and devised a methodology to quantify its performance
    *	Applied queuing theory to data transmission or packages of data to determine overall speed and performance of the network
    *	Conceived the concept of Demand Access, whereby computing resources are shared across the network and Distributed Control, whereby there is no central control of the data flow across the network
*	Paul Baran, working for ARPA (Advanced Research Projects Agency) a US Department of Defense agency, designed a network with emphasis on reliability. The motivation was to build a communication network that would be reliable during a nuclear war. Specifically, the challenge was to design a network that would still function even after parts of it were destroyed. Baran’s network design was modelled after mice going through a maze. He named it a ‘Hot Potato’ network and it had the following attributes: 
    *	The network chops data into equally sized packets with ‘from’ and ‘to’ addresses. 
    *	Each packet finds its way independently through the network. 
    *	Each node keeps a copy of the packet and resends it until it has arrived at the next node.
    *	Once all the packets arrive at the destination, the packets are reassembled into the full message that was sent. 

## **Early Development of the Internet – The ARPANET (1970s)**
* Bob Taylor and Lawrence Roberts worked for ARPA and in 1969 were given a small budget to build a network in which heterogenous mainframe computers could communicate on a common network. They applied the network design that had been proposed years earlier by Paul Baran to build what came to be known as the ARPANET.
    * Computers could share files and be accessed from several terminals. The resources of a computer could be shared across different terminals. This became known as Time Sharing. 
	* Through a process termed Packet Switching, Data messages to be sent across the network were first broken into smaller packets that would be sent independently and through non-deterministic paths across the network. The messages would be reassembled at the destination.
    * Lawrence Roberts developed the idea of creating identical special minicomputers, called Interface Message Processors (IMP) for each mainframe computer to facilitate communication between mainframes. With the IMPs the network did not require for a specific communication to be setup between each of the mainframe computers. 
    * Bob Taylor hired a small company named Bolt Beranek and Newman Inc. to build the network of mainframe computers that would communicate over phone lines. At each site of a supercomputer in the network an IMP had to be built. 
    * The initial network of mainframes that successfully communicated by the end of 1969 consistent of the following mainframes: UCLA (Sigma 7), Stanford SDS 940 SRI, UCSB IBM 360/75, and University of Utah PDP-10 Utah. By 1971 18 mainframe computers were in this network, called the ARPANET.
* The 1971 Killer App
    * Once the ARPANET was in place, Raymond Tomlinson invented a way to send messages across the network. This functionality was first called “Killer app” and later came to be known as “email.” 
* The ARPANET continued to grow and evolve throughout the Western World in the 1970s. Local Area Networks and Wide Area Networks continued to be developed. 
* In 1973 Vinton Cerf and Bob Kahn designed Transmission Control Protocol/Internet Protocol (TCP/IP) which allowed disparate networks to communicate through a Gateway computer. 
* TCP/IP was built on the information contained in the front of packets that described the information they contained.
  
## **1980s and early 1990s - Birth of the Internet and World Wide Web**
* In 1983 TCP/IP was adopted as the universal standard, creating a single common network of interconnected networks. This meant that there would be only one single Internet, rather than several Internets that do not readily communicate with each other.
* In 1983, Paul Mockapetris proposed the Domain Name System (DNS), which translates domain names (e.g. ibm.com) into Internet Protocol (IP) addresses and vice versa. With DNS an internet user does not have to know the IP address of the server where a web site resides; DNS does the translation from domain name to IP address. The IP address itself is assigned dynamically by individual networks through Dynamic Host Configuration Protocol (DHCP).  For individual computers at home, the internet service provider assigns through the router an IP address from a set it has been given to allocate.
* In 1992 Tim Bernes-Lee, a physicist in Switzerland, developed software to more easily follow threads of knowledge within the information stored throughout the internet. Bernes-Lee developed Hypertext Transfer Protocol (HTTP), which facilitated the creation of hyperlinks through which the user could follow associated knowledge across the internet. Bernes-Lee called this weblike linking of information World Wide Web.
* As with Moore’s law, which states that the speed and power of integrated circuit from microprocessors to memory chips doubles every 18 months, network connectivity began to grow exponentially. Metcalfe’s law describes the exponential growth of connectivity. One additional node on a network increases the networks value by a number much greater than one.
* In 1992, legislation was passed took the Internet out of governmental control. This spurred a log of new uses of the Internet, most notably commercial use. 
* In 1993 Marc Andreesen create the Mosaic web browser at the University of Illinois
    * Made surfing the web user friendly through text, scroll bars, links, etc
    * In 1992 there were only 50 web pages on the internet. This grew by 341,000% growth in 1993.

## **1990s The Browser War**
* In 1994 Jim Clark a wealthy former Stanford professor became interested in Marc Andreesen Mosaic web browser and the explosion of internet users in 1993.
* Jim Clark created Netscape Communications with Marc Andreesen and some of Andreesen’s former friends at the University of Illinois.
* At the end of 1994 Netscape released the Navigator web browser, which could easily be downloaded by anyone around the world with access to the Internet. It spurred further explosive growth in internet use around the world.
* After Navigator’s enormous success, Bill Gates recognized that the Internet had to be prioritized above all else in Microsoft’s strategy. He wrote a memo to his staff entitled the Internet Tidal Wave: “The single most development in computing since the PC.” He viewed Netscape as a new competitor born on the Internet that had to be matched and beaten:
* According to Netscape, Microsoft offered to buy the company for only $1 million. If they refused, Microsoft would copy all of their products and drive them out of business.
* The Netscape Initial Public Offering (IPO) in August of 1995 was wildly successful. This arguably ignited the internet stock market boom that was to follow.
* In 1995 Microsoft created Microsoft Explorer to compete with Netscape Navigator. By leveraging its Operating System dominance, Microsoft was eventually able to cut into Navigator’s dominance. Microsoft bundled Explorer into its operating system at seemingly no cost to the customer.
* In September 1997 it became clear that Microsoft had won the browser war with 80% market share. Netscape was acquired by AOL in 1998.
The Search Engines - Google
* In 1994 Jerry Yang and David Filo at Stanford University began working on creating Yahoo. Initially, the idea of a search engine was to manually categorize information on the Internet to make it more useful for potential Internet users.
* Yahoo began to accept advertisers, as a pioneer in the commercial use of the internet.
* By 1996, other web browser came on the market. Notably Excite, revolutionized the search engine functionality through automated searches of the Internet. However, the search technology was not sophisticated.
* The first sophisticated search engine was Google, created by Stanford students Larry Page and Sergey Brin. The technology was based on an innovative metric, which counted the number of links a given web page has pointing to it. That is, if a web page had a lot of links to it would be ranked higher in the search.
* Google Advertising – Unlike its predecessors, Google did not sell advertisement space on its page. Rather, it let advertisers would come up in search results. This targets advertising to a targeted group of potential customers. This is much more valuable to the company advertising than to advertise to the overall population.   

## **1990s e-commerce**
* A main theme throughout the late 1990s was to use the Internet to sell products. 
* Amazon created an online bookstore.
* Ebay created an online market place to buy and sell products through an auction system.
* Craigslist

## **2000s The Birth of Social Media**
* In the 2000s Internet innovation moved beyond simply finding new ways of marketing and selling old products.
* The 2000s saw the spawning of social media with novel ways in which groups or individuals could connect, interact, and communicate over the internet.
* Mark Zuckerberg applied social graph theory to build Facebook. A social graph is a way to describe an individual in a social web. Zuckerberg recognized that people enjoy receiving and sharing information (e.g. news, political opinions, music reviews) more from people within their social networks than from official sources (e.g. news organizations, governments, and educational institutions.)
* Traditional media (e.g. The New York Times and NBC) have had to adapt not only in terms of the medium or format with which they deliver their product. The content of their products has also drastically changed with interactive forums (e.g. blogs), live content, timeliness, and continuity of reporting. 
* The Internet has become central to political discussion and debate. It has drastically changed how news and other information is provided. Examples of platforms that facilitate this are Twitter and Facebook. Starting with the 2008 Presidential race Social Media became part of the central cores of political campaign strategies. This included the dissemination of data and, perhaps more importantly, the collection of data of online users and potential voters. The internet has created a new commodity: massive amounts of potentially useful data.
* In addition to the advent of social media the relatively unregulated Internet and free access to data and information has posed new challenges to intellectual property protections. In particular, services such as Napster have sprung up, that let users freely share entertainment (e.g. music and movies). Naturally, this has been met with heavy resistance from the entertainment industry and artists themselves (e.g. opposition Metallica, Dr. Dre).



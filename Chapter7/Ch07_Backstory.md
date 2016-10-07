##Chapter 7 - Backstory ![Flashlight](https://raw.githubusercontent.com/robertriordan/2400/master/Images/icons/32/time_mach_1.png)


### Design Trends 

Here's a great infographic on 2016 design trends:

**Figure MJBJ: 2016 Design Trends**

![Design trends 2016](https://raw.githubusercontent.com/robertriordan/2400/master/Images/CC_Design_Trends_2016.jpg)

<a class="underlined-link" href="http://www.dailyinfographic.com/2016-design-trends?utm_source=feedburner&utm_medium=email&utm_campaign=Feed%3A+DailyInfographic+%28Daily+Infographic%29" target="_blank">Infographic source</a>

###Designer Skills

Here's some copy from the Careers page of a cutting-edge local (Ottawa) software house. The first ad is for a UX Designer. Note how many of the skills and responsibilities mesh with what we're talking about in this book:

>**Roles and responsibilities:**
>
*Helping the UX teams harness their creativity, realize their confidence to deliver and to mobilize behind collaborative inspirations*

>*You will articulate design reasoning to all levels of the organization – so communication skills are a must*

>*You will establish the creative direction and will monitor the health of project timelines for multiple programs*

>*You will help attract talent and grow the UX design team*

>**Skills and experience:**

>*8 years of experience working with product/design teams, ideally through the full lifecycle development process*

>*2+ years working experience in a UX Lead or UX Manager capacity*

>*Previous experience with agile development processes and a understanding of how to integrate into this environment*

And here, same company, an add for a Visual Designer:

>**Roles and responsibilities:**

>*You will be responsible for the pixel-perfect visual appearances and design styles of our projects*

>*You will work on the development of innovative navigation systems, interface designs, typography, iconography and screen or page layouts for software, application, web sites, and other interactive media*

>*You will work on pushing the state-of-the-art with every creation with a meticulous and uncompromising eye*

And finally, here for a Software Developer:

>**Roles and responsibilities:**

>*You have a strong sense of curiosity and are excited about learning new technologies*

>*You believe in iterating quickly and improving the performance of existing features*

>*You are a proven software developer and have a strong command of object-oriented principles*

>*If you have worked on open sourced projects, have a Github account or portfolio that represents your work, we would love to see it!*

>**Skills and experience:**

>*Strong programming skills in C++*

>*Experience or strong interest in developing 2D and 3D video games*

>*Experience or strong interest in developing apps for Android and iOS*

>*Experience in manipulating assets (geometry, images, sounds)*

>*Experience in building innovative user interfaces using popular toolkits*

Interesting to note that this textbook was written primarily using an open-source tool called *GitBook* which rests on the *GitHub* infrastructure mentioned in the ad. It's a small world...  

### How the internet works (a very brief introduction)

The internet is a *network of networks*. In any organisation, large or small, there are likely multiple devices capable of communication with each other. Think desktops, laptops, smart devices, tablets, printers, modems and a wide variety of smaller devices such as sensors and beacons. But how does this communication take place? Let's start at the very beginning, with the original switched network, the telephone system.  

####Circuit Switching - the early era of electronic communication
In the old days, every telephone was connected to every other telephone by wire. They weren't all simultaneously connected mind you. But if you had a phone, it was physically connected to the phone company network. When you wanted to make a call from phone number 5 to phone number 7, you requested the assistance of an operator - by either spinning a crank on the phone to spool up an electrical charge that, when sent over the wire, alerted the operator to your request or (later) clicking the receiver cradle to send a request signal down the line. 

**Image EBTB. A crank-operated phone**

![Crank](https://raw.githubusercontent.com/robertriordan/2400/master/Images/crank.jpg)

*Image credit: http://d2ydh70d4b5xgv.cloudfront.net/images/9/3/vintage-swedish-american-oak-hand-crank-wall-telephone-early-1900s-06583d8a0509b2a8fd776a64e64679fa.jpg*

The operator would connect with your line and ask you which number you wanted to reach. The operator would them *physically* connect your line with the destination line by plugging a wire into a large what was called *switchboard*. When the call ended, the operator disconnected the lines. Much of this was automated in the 1950s and onward, where mechanical switches were used to *disintermediate* operators. They were all out of work, and 95% (my estimate) were women.

**Image LTDG. A switchboard operator back in the day**

![Operator](https://raw.githubusercontent.com/robertriordan/2400/master/Images/operator.jpg)

*Image credit: https://influxis.com/app/uploads/2014/06/switchboard-operator.jpg*

 There were still *long distance* operators into the 1970s. Long distance (out of your Area Code) calls were initiated by dialing the number "0" and asking for a long distance operator. Here, different networks were connected together and you could hear the operators talking to each other. "Hello 312? This is 416 long distance operator requesting local number..." and so on. It was fun to listen. The numbers 312 and 416 were, of course, the Area Codes (AC) of Chicago and Toronto, respectively. An interesting tidbit is that, when area codes were assigned in North America in the late 1940s,  according to the North American Numbering Plan (NANP) states and provinces with only one AC were given numbers with a "0" in the middle, and those with more than one AC were assigned numbers with a "1" in the middle. So Illinois and Ontario had more than one AC. Furthermore, the numbers were assigned based on population, with the smallest numerical sums going to more densely populated areas. Chicago was big (and still is) thus their numbers summed to 6. Toronto summed to 11. Since "1" was never used as the first number in an area code, the lowest possible AC was 211. But all the *n11* ACs were reserved for future use (anticipating 411 - directory assistance and 911 etc.), the lowest AC was 212. Guess who got that? New York City, of course! The next lowest, 213, went to Southern California, including Los Angeles. This was to reduce wear and tear on the equipment as when a number was dialed (when direct dialing was introduced), the phone had a rotary dial. The dial had to be spun around to indicate the number (see the rotary handset below), and the actual physical clicking you heard (called *pulses*) was a signal to the network of the number you were dialing. It used the pulses to crank the mechanical switches to make the proper connection. There would obviously be more calls going to larger population areas, thus there was an effort to reduce the number of clicks required (both for wear and tear and ease of use - lower numbers required less effort to dial). If you can see it on your device, note the wear pattern on the numbers on the rotary dial phone image below.

**Image EBSS. An early rotary phone**

![Rotary](https://raw.githubusercontent.com/robertriordan/2400/master/Images/phone.jpg)

*Image credit: https://s-media-cache-ak0.pinimg.com/564x/5c/df/a0/5cdfa0cec1c3a31cd91c5f98cd0229f0.jpg*

Early phone numbers were assigned on a first-come, first-served basis. So my grandfather's dairy was the 7th phone on his local exchange. Later, when phones became more popular and small phone exchanges amalgamated, they needed better addressing. There was obviously a phone number 7 in Oshawa, and Whitby and Ajax and Pickering and Scarborough and so on. I assume this began with a reassignment of numbers within amalgamated exchanges, so phone number 7 in Oshawa might have become 23 when Oshawa and Whitby amalgamated and so on according to some rule. Even this became unwieldy when numbers of phones grew, and local exchanges were assigned, in anticipation of changes to come, with alphanumeric identifiers. At my house, our identifier was *Randolph* shortened to RA. Our proper phone number was RA 5-1805. Neighbouring Whitby had a prefix of GR (I don't recall what GR stood for). If you watch the old *Honeymooners* TV series from the 1950s, you will note that Ralph Cramden's phone number was *Bensonhurst* (or BE) 0-7741 (they lived at 328 Chauncey Street in the Bensonhurst section of Brooklyn, New York. [Interested?](http://www.tv.com/shows/the-honeymooners/the-babysitter-104367/) in an explanation of why Ralph's phone number started with a "0" - none ever do).

All this to say that eventually, the Randolph RA became 72, so our phone number was 416-725-1805. Check out the very large dialpad from the iPhone below to map how the RA became 72.  Adding a country code (Canada and the US share the country code "1") gives us, finally, 1.416.725.1805. *Et voila!* Very similar to an IP address, which we talk about below. If you were to dial that number from Germany, for example, the first digit would get you North America, the next three the 416 AC, the 72 gives the local sub-exchange and the 51805 the actual phone line into the house. Note that in 1993, the 416 AC was split into the 905 (ring around Toronto) and 416 (Toronto core). So that old phone number of mine in Oshawa now belongs to someone in Toronto. 

If you need a break, you can watch some old Honeymooners here: 

{% youtube %}https://www.youtube.com/watch?v=Nb8ulccRP_E{% endyoutube %}

More trivia. The later, animated sitcom *The Flintstones* (you may have seen the much more recent movie starring John Goodman, Rosie O'Donnell, Rick Moranis and Halle Berry, among many others) was based on the Honeymooners.

**Image RDIT. Contemporary dialpad (huge!)**

![Dialpad](https://raw.githubusercontent.com/robertriordan/2400/master/Images/dialpad.png)

*Image credit: My iPhone*

I know the above is totally useless information, but it might come in handy some day in a game of trivia. With an old person. 

 So the connected world was physically connected with wires and switchboards to connect one device with another. Like a road system, you had to follow the wire to make the connection. We can still use this metaphor to describe the internet. Just as every phone had a number associated with it, every device attached to the internet has an address. Read on.
 
####IP Addresses
Everything that is connected to the internet has an *Internet Protocol address*, usually referred to simply as an IP address or just an IP. Originally, IP addresses were made up of 4, 3-digit numbers separated by a dot. The form was xxx.xxx.xxx.xxx. Many devices still use this standard, called IPv4. The newer standard (IPv4 addresses were running out by 1995) is IPv6 (v5 is never mentioned - maybe it was that incident at the wedding reception last year?). The format of IPv6 addresses is considerably longer. Our friends at Wikipedia have this to say:

>"The rapid exhaustion of IPv4 address space prompted the Internet Engineering Task Force (IETF) to explore new technologies to expand the addressing capability in the Internet. The permanent solution was deemed to be a redesign of the Internet Protocol itself. This new generation of the Internet Protocol was eventually named Internet Protocol Version 6 (IPv6) in 1995. The address size was increased from 32 to 128 bits (16 octets), thus providing up to 2128 (approximately 3.403×1038) addresses. This is deemed sufficient for the foreseeable future."

[Interested?](https://en.wikipedia.org/wiki/IP_address)

Just to reiterate: every device both great and small, if it's connected to the internet, has an IP address, either v4 or v6. That's how devices on the network communicate. Every communication across the net must be addressed to some other device, otherwise, why bother communicating? Devices would simply be whistling in the wind with no one to hear the tune. That's fine for humans, but we expect more from our machines. 

####DNS - Domain Name Servers
At very low levels, when machines are talking to machines, they use IP address exclusively. But if we type the address *www.carleton.ca* into a browser, how does it get the address of the web server at Carleton? When we type that address into the browser's address box, we're asking to contact a web server at the school and for it to send back to our machine the contents of the home page for Carleton. But we're not typing an IP address, but a name. This is where *Domain Name Servers* come in. DNS' hold tables of IP addresses with associated names (like *carleton.ca*) and when a request is made over the World Wide Web service, the DNS does the translation of the name we type to the machine's IP address. Simple.

**Table YTDS. Internet Protocols**

| Protocol Layer | Description |
| :-: | :- |
| Applications Protocol Layer | Protocols specific to particular applications which use the Internet. For example: the World-Wide Web (WWW), email (Post Office Protocol - POP), File Transfer Protocol (FTP), Voice over IP (VOIP), etc.|
| Transmission Control Protocol (TCP) Layer | TCP directs packets to a specific application on a computer using a port number. |
| Internet Protocol (IP) Layer | IP directs packets to a specific computer using an IP address. |
| Hardware Layer | Converts binary packet data to network signals and back. For example: Ethernet network card, modem for phone lines, WiFi adapter, etc.)

Source: Based on https://web.stanford.edu/class/msande91si/www-spr04/readings/week1/InternetWhitepaper.htm (Accessed August 21, 2016)

**Figure TBRT. Network Protocols and Communication**

![Protocols](https://raw.githubusercontent.com/robertriordan/2400/master/Images/protocols.png)

Figure TBRT depicts communication between two machines over a network (likely the internet). Each machine (left one has the IP address 1.2.3.4 and the right one has the address 5.6.7.8) has, in addition to its address, a *stack* of software/hardware consisting of four layers: *Application, TCP, IP* and *Hardware*. Below, the process of communicating a simple email between the two machines is explained in light detail. 

The (somewhat dated but still quite valid) [Stanford University article](https://web.stanford.edu/class/msande91si/www-spr04/readings/week1/InternetWhitepaper.htm) explains what's going on in Figure TBRT (edited for context and clarity):

1. Let's imagine that you want to send an email from your computer on the left, with an IP address of 1.2.3.4, to computer 5.6.7.8 on the right. The user types the message ("Hello computer 5.6.7.8!") into an email client (the application on the top layer) to start the process.  
2. If the message to be sent is long, each stack layer that the message passes through may break the message up into smaller chunks of data. This is because data sent over the Internet (and most computer networks) are sent in manageable chunks. On the Internet, these chunks of data are known as *packets*.
3. The packets are passed on by the Application Layer and continue to the TCP layer. Here, each packet is assigned a *port number*. Ports will be explained later, but suffice to say that many programs may be using the TCP/IP stack (at the same time) and sending messages. We need to know which program on the destination computer needs to receive the message because it will be listening on a specific port, thus we need to send to that port. One of the jobs of the TCP layer is to include the port number in the contents of each packet it passes to the IP layer below it. 
4. The packets now proceed down to the IP layer. This is where each packet receives it's destination address, in this case the IP number *5.6.7.8.* It is important to note also that sequencing information is also added to the packets so that they can be reassembled in the proper sequence on the destination machine. We don't want our message to come out as "8pHll7..rc" etc. (These are some of the characters in the original message, but in the wrong order.) 
5. Now that our message packets have a port number and an IP address and a sequence number, they are ready to be sent over the Internet. The hardware layer takes care of turning our packets containing the alphabetic text of our message into electronic signals and transmitting them over the internet.
6. On the other end of the modem in your home, your ISP has a direct connection to the Internet. The ISPs router examines the destination address in each packet and determines where to send it. Often, the packet's next stop is another router. The message zips around from router to router, following the least busy electronic pathway, until all pieces are received at the destination computer. 
7. Eventually, the packets reach computer 5.6.7.8. Here, the packets start at the bottom of the destination computer's TCP/IP stack and work upwards.
8. As the packets go upwards through the stack, all routing data that the sending computer's stack added (such as IP address, port number and sequence) is stripped from the packets.
9. When the data reaches the top of the stack, the packets have been re-assembled into their original form, "Hello computer 5.6.7.8!" appears as an email in the destination computer. 

But how do all those addresses get handled efficiently. There's a massive number of connected devices, and the number is growing exponentially. The answer is division of labour and knowing your neighbourhood. A very simple example will do here. Imagine your home. Likely you have Internet service from one of the big providers in Canada (Bell, Rogers, Telus, Cogeco, Videotron, etc.). Along with that service, comes a modem. A modem is an interface from your home to the internet. All internet traffic in your home runs through the modem. Likely you connect to it wirelessly, but it doesn't matter if you use a wireless or wired connection. This *port* to the internet *knows* the IP addresses of each device that connects to it. 

As promised, here's what [Techopedia](https://www.techopedia.com/definition/3659/computer-port) has to say about *ports:*

>"A computer port is a connection point or interface between a computer and an external or internal device. Internal ports may connect such devices as hard drives and CD ROM or DVD drives; external ports may connect modems, printers, mice and other devices."

Thus a port is simply a place that accepts incoming communication, just like a seaport or a door. It's the *delivery door* for machine communication. When an email is sent, it's sent from a port. WHen an email arrives, it's sent to the email port, where the machine is *listening* for email. 

###Communication Types

All manner of communication protocols like Bluetooth, etc. 


- Bluetooth - According to Wikipedia (accessed October 2, 2016) "Bluetooth is a wireless technology standard for exchanging data over short distances (using short-wavelength UHF radio waves in the ISM band from 2.4 to 2.485 GHz[4]) from fixed and mobile devices, and building personal area networks (PANs). Invented by telecom vendor Ericsson in 1994, it was originally conceived as a wireless alternative to RS-232 data cables. It can connect several devices, overcoming problems of synchronization." Bluetooth is primarily used to connect devices such as speakers, headphones and other short-range devices to smart phones. <a class="underlined-link" href="https://www.bluetooth.com/" target="_blank">Interested in where Bluetooth is going?</a>
- RFID (Radio Frequency Identification). RFID provides unique identification for an object.. Much like a bar code or the magnetic strip on the back of a credit card, RFID scanners can retrieve basic information about an object from a distance of about 6 metres (20 feet) for high-frequency scanners. And unlike bar code scanners for exaple, orientation doesn't matter for RFID. Theoretically, you could put all your grocery purchases in a bag and set it on an RFID scanner and all would be scanned without the troublesome swiping and aligning that's necessary with bar code readers. <a class="underlined-link" href="http://www.technovelgy.com/ct/Technology-Article.asp?ArtNum=2" target="_blank">Interested?</a>
- NFC (Near Field Communication) NFC descended from RFID technology and is the "magic" behind "tap-and-go" technology found in payment cards, for example. NFC does not require a "pairing handshake" as does Bluetooth and has a very low power requirement. All that is necessary to exchange data is to being an NFC device close to a reader. <a class="underlined-link" href="http://www.techradar.com/news/phone-and-communications/what-is-nfc-and-why-is-it-in-your-phone-948410" target="_blank">Interested?</a>  
- Client-server. The largest implementation of client-server architecture is the Internet. Clients (that's you and me) can make requests for services (data) from servers (machines that hold the data we want). We make requests of those machines, which *serve* the data back to us. Various specialised machines and architectures provide a wide range of services. There are specialised machines for database, video, voice, email and a range of others. <a class="underlined-link" href="https://en.wikipedia.org/wiki/Client%E2%80%93server_model" target="_blank">Interested?</a>
- P2P - Peer-to-Peer networks. According the Wikipedia "Peer-to-peer (P2P) computing or networking is a distributed application architecture that partitions tasks or work loads between peers [machines of equal standing on the network - unlike the client-server model where servers have more power and privilege]. Peers are equally privileged, equipotent [same power] participants in the application. They are said to form a peer-to-peer network of nodes." Early file-sharing networks (Napster, for example) used P2P to their advantage. <a class="underlined-link" href="https://en.wikipedia.org/wiki/Peer-to-peer" target="_blank">Interested?</a>

For a comprehensive treatment of networks (not required reading but pretty interesting anyway) see [this Wikipedia article](https://en.wikipedia.org/wiki/Computer_network). 

That's it for Chapter 7!
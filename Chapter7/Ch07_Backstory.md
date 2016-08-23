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

IP Addresses
DNS
The internet as the telephone lines or highways

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

The (somewhat dated but still quite valid) Stanford University article explains what's going on in Figure TBRT (edited for context and clarity):

1. Let's imagine that you want to send an email from your computer on the left, with an IP address of 1.2.3.4, to computer 5.6.7.8 on the right. The user types the message ("Hello computer 5.6.7.8!") into an email client (the application on the top layer) to start the process.  
2. If the message to be sent is long, each stack layer that the message passes through may break the message up into smaller chunks of data. This is because data sent over the Internet (and most computer networks) are sent in manageable chunks. On the Internet, these chunks of data are known as *packets*.
3. The packets are passed on by the Application Layer and continue to the TCP layer. Here, each packet is assigned a *port number*. Ports will be explained later, but suffice to say that many programs may be using the TCP/IP stack (at the same time) and sending messages. We need to know which program on the destination computer needs to receive the message because it will be listening on a specific port, thus we need to send to that port. One of the jobs of the TCP layer is to include the port number in the contents of each packet it passes to the IP layer below it. 
4. The packets now proceed down to the IP layer. This is where each packet receives it's destination address, in this case the IP number *5.6.7.8.* It is important to note also that sequencing information is also added to the packets so that they can be reassembled in the proper sequence on the destination machine. We don't want our message to come out as "8pHll7..rc" etc. (These are some of the characters in the original message, but in the wrong order.) 
5. Now that our message packets have a port number and an IP address and a sequence number, they are ready to be sent over the Internet. The hardware layer takes care of turning our packets containing the alphabetic text of our message into electronic signals and transmitting them over the internet.
6. On the other end of the modem in your home, your ISP has a direct connection to the Internet. The ISPs router examines the destination address in each packet and determines where to send it. Often, the packet's next stop is another router. The message zips around from router to router, following the least busy electronic pathway, until all pieces are received at the destination computer. 
7. Eventually, the packets reach computer 5.6.7.8. Here, the packets start at the bottom of the destination computer's TCP/IP stack and work upwards.
8. As the packets go upwards through the stack, all routing data that the sending computer's stack added (such as IP address, port number and sequence) is stripped from the packets.
9. When the data reaches the top of the stack, the packets have been re-assembled into their original form, "Hello computer 5.6.7.8!" appears as an email in the destination computer. 

Ports and more ports.

NADS

All manner of communication protocols like Bluetooth, etc. 

<div>
<iframe src="http://www.itu.int/net4/ITU-D/idi/2015/#idi2015map-tab" allowfullscreen></iframe>
</div>



Stuff
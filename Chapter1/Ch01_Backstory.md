##Chapter 1 - Backstory ![Clock](https://raw.githubusercontent.com/robertriordan/2400/master/Images/icons/32/time_mach_1.png)

### Measurement
<a name="measure"></a>
When considering data, we first need to carefully consider what is meant by the term *measurement* as measurement is necessary in order for data to be useful. Measurement makes data tangible and gives it value. Under the topic of *Accuracy and precision*, Wikipedia (accessed June 17, 2015) offers the following discussion seedlings:

#### Accuracy
<a name="accuracy"></a>
“In the fields of science, engineering, industry, and statistics, the accuracy of a measurement system is the degree of closeness of measurements of a quantity to that quantity's actual (true) value."

#### Precision
<a name="precision"></a>
"The precision of a measurement system, related to reproducibility and repeatability, is the degree to which repeated measurements under unchanged conditions show the same results. Although the two words precision and accuracy can be synonymous in colloquial use, they are deliberately contrasted in the context of the scientific method."

They continue that, “A measurement system can be accurate but not precise, precise but not accurate, neither, or both. For example, if an experiment contains a systematic error, then increasing the sample size generally increases precision but does not improve accuracy. The result would be a consistent yet inaccurate string of results from the flawed experiment. Eliminating the systematic error improves accuracy but does not change precision."

Furthermore, “A measurement system is considered valid if it is both accurate and precise. Related terms include bias (non-random or directed effects caused by a factor or factors unrelated to the independent variable) and error (random variability).

#### Another view
According to ISO 5725-1, Accuracy consists of Trueness (proximity of measurement results to the true value) and Precision (repeatability or reproducibility of the measurement). Furthermore, the terms *trueness* and *precision* are both used to describe the accuracy of a measurement. Trueness refers to the closeness of the mean of the measurement results to the actual (true) value and precision refers to the closeness of agreement across individual results. Therefore, according to the ISO standard, the term "accuracy" refers to both trueness and precision.

**Figure SMC. Low accuracy: poor precision, good trueness**  

![](http://upload.wikimedia.org/wikipedia/commons/thumb/1/10/High_accuracy_Low_precision.svg/200px-High_accuracy_Low_precision.svg.png)

Looking at the *target practice* image above, we immediately see that no one shot is exactly dead centre. This is to be expected and might even be considered a random outcome. It's pretty hard to hit dead centre on any attempt. So we can't give any of these attempts good marks for *precision* - the degree to which they hit the centre of the target. But all is not lost. We next observe that the four attempts are, in general, at about the same distance from dead centre. So none is a great shot, but considered together, they seem to have some consistency. So while not completely accurate, they are at least *true to each other*. This gives them marks for *trueness*. They err by the same amount in different directions. So, *on average*, a good set of results, though no one was accurate. For why this is important, see the *old joke* below.  

**Figure BFHC. Low accuracy: good precision, poor trueness**

![](http://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/High_precision_Low_accuracy.svg/200px-High_precision_Low_accuracy.svg.png)

Here we have a different situation. While again not even one attempt was dead centre, all four were clustered closely to the left and below the *pay dirt* area. Still a situation of *low accuracy* but not for the same reason as above. In this case, the *precision* is excellent. The attempts are very closely clustered together and are thus very precise. But they are *consistently* wrong. As if some technical difficulty is introducing bias into the process (a crooked site perhaps?) causing an otherwise great set of attempts to be consistently wrong. But unlike the first low accuracy situation we looked at above, the attempts are not considered to be *true* on the whole. This is because their *average* distance from dead centre is considered to be large. 

Note in the first case above if you were to calculate an average difference from the centre, you would note that they are all at least touching the first outer ring of the target (though it is enticing to note, it doesn't matter that they are nearly at the 12, 3, 6 and 9 o'clock positions). Calculating an average distance for all four would yield a mean very close to 1 (one) if we were calibrating the rings as 1, 2, 3, etc.  

Now consider the second case. All are clustered in one spot AND two of the attempts are clearly farther away than any in the first example. The average difference would, therefore, be greater. It appears to be splitting hairs, but it's the best I've got. I'll try to photo some of my own for the next edition of this text. 

*Source: [Wikipedia accuracy and precision](http://en.wikipedia.org/wiki/Accuracy_and_precision). Image sources: Credit DarkEvil (public domain)*

This might clear up some of the confusion: "According to ISO 5725-1, the general term *accuracy* is used to describe the closeness of a measurement to the true value. When the term is applied to sets of measurements of the same *measurand* [see this reference to understand the term *measurand*](http://en.wiktionary.org/wiki/measurand), it involves a component of random error and a component of systematic error. In this case *trueness* is the closeness of the mean of a set of measurement results to the actual (true) value and *precision* is the closeness of agreement among a set of results." 

**Figure SR. Precision and trueness of measurement**

![Accuracy](https://raw.githubusercontent.com/robertriordan/2400/master/Images/accuracy_new.png)

Figure SR might help in that it clearly shows precision as being *how close a measure is to the true value* whereas trueness is how closely each measure in a set of measures agrees with the others. And maybe it doesn't help. I'm doing my best. I'm sure you will LMK if you don't get this.   

The Wikipedia article continues that, “The terminology is also applied to indirect measurements—that is, values obtained by a computational procedure from observed data. In addition to accuracy and precision, measurements may also have a measurement resolution, which is the smallest change in the underlying physical quantity that produces a response in the measurement. In numerical analysis, accuracy is also the nearness of a calculation to the true value; while precision is the resolution of the representation, typically defined by the number of decimal or binary digits.”

Each of these will become important at different junctures in our study. Measurement resolution will appear again when we discuss *sensors* and resolution of representation when we talk about the shrinking divide between *digital and binary*. 
 
[Interested?](http://en.wikipedia.org/wiki/Accuracy_and_precision)  

#### An old joke
*All this measurement talk reminds me of the great old joke about a doctor, a lawyer and a statistician who are obviously starving or else they wouldn't be on a hunting trip. While hiding in the bushes, they spot a big buck deer at a distance of 25 metres directly in front of them. The doctor sizes up the distance and wind speed, then aims and fires an arrow at the deer. His shot zooms one metre to the rear of the unsuspecting creature. The lawyer notes the doctor's outcome, does some quick calculations, then aims and fires. His shot zips one metre in front of the deer. Our statistician friend jumps up, raises his hands in victory and shouts "GOT ‘IM!!"  (No animals were hurt in the process of creating this book.)* 

<a name="types">
### Levels (types) of data
In using statistical methods, for example, the determination of level of measurement is critical. Certain statistical tests and methods require certain levels of measurement of the data under analysis. Level of measurement is also important when data scientists plan what data to collect for a particular purpose. Imagine a firm needing to know the exact year in which a person was born in order to provide an age-based discount but having only collected customer age data in 5-year age brackets. So rather than asking a customer to provide the year of their birth, instead asking them to indicate whether they were born in the 1970-1974 or 1975-1979 period, etc. That's a lot of guessing and a lot of unnecessary sloppiness in the precision of their data. Thus, level of measurement is critical in some contexts. 

In general, the closer one can get to ratio / hierarchical data level, the more powerful is the measurement. But some data simply doesn't exist at that level. Gender, for example, is a nominal-level measurement no matter how you slice it. Thought needs to be put into data capture schemes so that the collected data can be used to generate value for the firm. We will return to this later.

The *NOIR* and *LATCH* taxonomies assist in categorising and determining what can be done with data. Each is discussed and cross-referenced between taxonomies below. 

#### NOIR taxonomy

The NOIR taxonomy allows data to be categorised in four broad groups, as follows:

1. Nominal
2. Ordinal
3. Interval
4. Ratio

Each is described in turn.

##### Nominal 

Means *in name only*. Data measured using the nominal scale do not represent any intrinsic value. Measurement at this level simply names things such as Chevrolet, Ford, Ferrari or Male and Female. One might have an opinion on some characteristic of the named thing (such as the difference in value between a Ferrari and a Chevrolet) but there is nothing in the measurement itself that would allow one to accurately measure any value difference between these categories of automobile. In some contexts, a Chevrolet pickup truck would be superior to a Ferrari (on a farm or a construction site for example). But there is nothing in the *naming* of them that would allow one to accurately determine whether one is better than the other. They simply have different names. 

Nominal-level data have the lowest information *affordance*, meaning there is little or nothing hidden in the variable that is not shown (suggested) by its name. There is no implicit scale or indicator of value. Just a name. 

Nominal data can only be reported or used as a category for bins (as in throwing things in bins for counting and then that count becomes Ratio (see below). For example you can say that “35,000 times more people own a Chevrolet than a Ferrari but that’s a *count* of the number of things in a bin and not an attribute of *Chevyness* or *Ferraritude*. Thus there are no algebraic operations possible - no math can be done on such variables other than comparing frequencies between categories as in Chevy vs. Ferrari ownership numbers. 

Nominal data on the NOIR scale roughly corresponds to either *Attribute* or *Location* (except if the location is expressed as GPS coordinates which would be Interval-level rather than Nominal-level data) in LATCH. 

##### Ordinal 

Ordinal data afford an intrinsic (implied) ordering but cannot specify the *exact increment/decrement* implied by changes from one category to the next. A *Likert* scale in a survey for example - "On a scale of 1 to 5, how happy are you?" Is someone who answers *2* only *half* as happy as someone who answers *4*? The scale is not sensitive enough, or well enough *calibrated*, to make these determinations. We can report *frequencies* along latent dimensions only - for example "Twice as many people in our survey reported being somewhat or very *happy* as opposed to those reporting being somewhat or very *unhappy*." But honestly, we haven't even *operationalised* the concept of *happy* here.   

Another example: "How satisfied are you with this book?" There is no real objective way to measure the underlying dimension of *satisfaction*. We can ask if you are *Not at all, Somewhat, Neither satisfied nor dissatisfied,* etc. This gives us an indication and we can compare person to person at one point in time or with the same person over time. We just can't say that we've measured *satisfaction* in a truly rigorous way.

[Interested in Likert?](https://en.wikipedia.org/wiki/Likert_scale)

Researchers call these underlying states *latent dimensions*. We often look for things that *act like the latent variable* and measure it, instead, as a *proxy* for the unmeasured variable. These *indicator variables* are *correlated* with our variable of interest - so they vary in a known way with our latent variable - but are not exact measures of the dimension that we are interested in measuring. (Don't leave me yet, it's just getting good.) So if we're measuring *happiness* we might measure the number of times a sample of people smiles in a day along with the number of laughs and warm embraces, etc. These things, are not *exactly* the same as happiness, but together, they can make a compelling argument for being able to tap into the underlying river of emotions that are expressed as happiness, sadness, anger, etc.

Finally, with ordinal variables, we cannot do algebraic operations on categories except to report frequencies/counts, which are then Ratio. Ordinal-level variables correspond to Hierarchical in LATCH.

##### Interval 
Data measurable with the interval level are similar to Ordinal data, but the exact difference in increments between categories can be specified. Interval data have an arbitrary zero value. 

Take temperature for example: 23 degrees Celsius is exactly one degree warmer than 24C but 0C is arbitrarily simply the temperature at which fresh water freezes at sea level. We cannot say that 12C is *twice as warm* as 6C for example. Nonetheless, one can do some algebra, such as addition/subtraction with interval data, but not division, multiplication or exponentiation. 

Interval data using the NOIR taxonomy corresponds to Time and Hierarchical in LATCH.

##### Ratio 

This is the highest level of measurement and affords the most opportunity to understand the underlying dimensions captured therein. Examples of variables measured at the ratio level include age, dollar values, counts of discrete items (number of events, purchases, people, goods, etc. either when counting or when expressed as a ratio to each other or to a total). Interval data are exact and have a real zero, thus any and all algebraic operations are possible (addition, subtraction, multiplication, division and exponentiation). Finally, we can say that $2 is twice as much as $1. 

Ratio data in NOIR corresponds to Hierarchical data in LATCH.

### LATCH taxonomy

Just as in NOIR, all data can be categorised according to one of the LATCH descriptors. Table XYZ shows the correspondence between NOIR and LATCH. NOIR is more technical than LATCH and considerably more homogeneous, but any data can be expressed using one or both taxonomies. 

**Table XYZ. Comparing measurement taxonomies** 

| **LATCH** | **NOIR equivalent** |
| :- | :- |
| **L**ocation | **N**ominal |
| **A**lphabetical | **N**ominal |
| **T**ime | **O**rdinal, **I**nterval |
| **C**ategorical | **N**ominal, **O**rdinal |
| **H**ierarchical | **O**rdinal, **I**nterval, **R**atio |

##### L -  Location data

Maps, broadly defined (from a location on the body for a surgeon to a room in a building for a delivery all the way up to quadrant in the universe), can be neatly categorised as Location data in LATCH. GPS devices make use of data tagged with *geo-locale* information (latitude by longitude and elevation). 

Location data can be either Nominal data in NOIR (as in the name of a city such as Kamloops, for example) or as Ratio data if expressed in GPS latitude/longitude coordinates such as 45.4165315, -75.65170139999998 or as Degrees, Minuters and Seconds as in N45° 24 59.513', W75° 59 6.125'. These are the coordinates of the Ottawa ViaRail station around 200 Tremblay Road. 

[Interested in the GPS coordinates of some place?](http://www.gps-coordinates.net/)

##### A - Alphabetic data

Alphabetisation is very frequently used, often as a secondary attribute. Alpha data are good for categorising enormous datasets such as a phone directory or an employee directory or a social media *friend* list. Since virtually everyone understands alphabetical order, this method is often used when consumers of data are not familiar with the subtle nuances of other methods of categorisation - *"When all else fails, alphabetise!"*

Alphabetic data under the LATCH taxonomy corresponds to Nominal data in NOIR. 

##### T - Time data

Anything that is tracked chronologically and has either a measurable start point and/or end point can be expressed in terms of time. The Vietnam Memorial in Washington DC, for example, is ordered by time, affording viewers the added information of seeing others who died at roughly the same time, and allowing context with other events in the news. Interesting to note that within time segments (days for example) US Vietnam casualties are then listed alphabetically to assist in finding them. Thus alphabetical listing is secondary to chronological. 

Time data corresponds to either Ordinal or Interval data in the NOIR system. 

##### C - Categorical data

That which falls into mutually-exclusive categories such as:

- Gender
- Paint colour
- Options group on a website
- Degree programme

Categorical data works well when trying to make sense of information of similar importance without an implied order or rank. Red is no better a colour than blue, but we distinguish between them nonetheless. We can, however, distinguish between different *Tints, Tones* and *Shades* of a colour and categorise them as more or less intensely red, for example. 

Red is nominal in the NOIR taxonomy, whereas the various tints, tones and shades might be considered Ordinal in NOIR. Splitting hairs indeed.

##### H - Hierarchical Data

Hierarchical data is that which is measured in comparison with others and which can be compared in terms of quantity and/or quality, such as:

- Temperature
- Weight
- Dollar value

Any and all mathematical operation can be done using such data. It is the highest data categorisation and corresponds to Interval data in the NOIR system.

<a name="communication">
## Communication

How pervasive is information communication? What's the *coverage* in Canada? Take a look at this simple interactive map:

**Figure FMAP. Cellular coverage in Canada**

<iframe src="https://www.google.com/maps/d/embed?mid=ziiXzGEk59_I.kvJPNhGl3KKk" width="640" height="480"></iframe>

*Source: http://www.itbusiness.ca/news/interactive-map-inside-canadas-wireless-landscape/56833*

An excellent introduction to the history of communication is available in Wikipedia. 

[Interested?](https://en.wikipedia.org/wiki/History_of_communication)

Speaking of the importance of communication, here is an interesting depiction of the [Internet Exchange Points](http://www.internetexchangemap.com/) in the world. Find the one closest to you. What is an internet exchange you ask? [Interested?](https://en.wikipedia.org/wiki/Internet_exchange_point)

And here is an interactive map of the [submarine cables](http://www.submarinecablemap.com/) in the world. Why is this important? [Interested?](http://www.cbc.ca/news/technology/submarine-cables-explainer-1.3289954)


Take a look at Figure DVTP below.

**Figure DVTP. A brief history of communication**
![Communication history](https://raw.githubusercontent.com/robertriordan/2400/master/Images/hist_comm.png)

Let's now consider this in some detail (I know it will render small and there's lots of detail. I recommend viewing this on a desktop machine if you can, or printing it. Any way to see the detail.) For important context, note that time is represented top to bottom in the figure, shown by the green arrow on the left, topped by a *Dali-like* melting clock to indicate that time here is relative and not absolute. I have, for example, grouped TV and radio together (#4 and #5) because they are examples of *broadcasting* whereas in reality, telephone (#6 and #7) predated TV. With this in mind, note we start with cave-dwellers (#1) at the top and end with the modern internet at the bottom (#8 & #9). Much of history is missing here (such as the telegraph and still photography and then moving pictures, for example). Note also that when I created this figure, I searched for an image of a cave-dweller and was so enamoured with the little guy I found that I used him to represent people right up to the modern era. He's a little Luddite cave dude and I'm attached to him. He just represents people. 

Next note that no matter which era or breakthrough we examine from top to bottom in the figure, the little cave dude appears on both ends of the transaction - this is all about person-to-person communication. The arrows (there are two colours of arrow) indicate directionality of communication. Blue arrows indicate bi-directional communication; that is, messaging that flows both ways, from sender to receiver and back. Note that the earliest communication (simple speech) was bi-directional but despite eons of progress, we didn't return to bi-directionality until the invention of the telephone (and the earlier telegraph - which was not synchronous - which is not shown in the figure). It took us a long time to replicate real-time (synchronous) chatting. Red arrows indicate one-way communication.

Next note that there are sometimes other *ghosted* images clustered around a darker image (as is the case with the cave dudes in Form #3). On the right, there is one principal and several secondary dudes. This indicates that there could be more than one person on this end of the communication emanating from  the *printing press* and *newspaper* modes of communication. One source (an author, for example) can produce many copies of a book or a paper. The message is the same in each case, but there can be many recipients with a copy, and the copy can be shared with others. It's important to note that each on the many side are looking at *their own unique copy of the message* be it a book or a magazine or a newspaper. So the *Mode* of communication (see the column just to the right named *Mode*) is 1:m, meaning *one source* but *many destinations* are possible (this is referred to as *monologic* transmission). The other two possibilities for Mode are 1:1 (one-to-one or *dialogic*) and m:m (many-to-many or *multilogic*). There is some confusion among specialists on the three terms (monologic, dialogic and multilogic). I prefer to refer to one-way communication (as in a piece of art or a radio broadcast) as *monologic* (as in *monologue*), one-to-one communication as *dialogic* (same root as dialogue) and many-to-many as *multilogic* (logically *multilogue*) but you will find this isn't universal. 

The same can be said for the clusters of televisions and radios. A broadcaster sends a signal that many can receive, but the signal, and therefore the message, is the same in each case. What is slightly different is that, while the receiver is easily replicated (many tvs and radios), so can there be many people watching and listening to the message simultaneously. So that's why the dudes are all solid. Many people looking at the same TV or streaming event or movie is different from many people, each looking at their own book because when many people are together, it creates a real-time community. We have moved from one source (a newspaper) producing many copies, to one source (a radio station) producing one copy of a program that many listen to simultaneously. There are no *ghosts* here in #4 or #5. Each person who receives the message is listening to or watching the same broadcast. 

You might want to argue that a cave dude might be talking to one among the cohort, but others might well be passively listening or even in a rudimentary *audience* as it were. But I consider such other listeners to be incidental to the basic communication here. Likely the first couple of millions of years of communication were *predominantly* one-on-one affairs. Dude could be talking to one person or to a crowd, but the message is the same for all. Much like when we get to the internet around #8 in the figure. The original internet (often called Web 1.0) featured servers *serving up* the same content to all, much like TV or radio. With Web 2.0, not only is much of the content crowd-sourced, but configuration allows us to customise the messages we receive in infinite ways. 

Finally, generally note that the tools we are using to communication are becoming increasingly sophisticated and layered. We increasingly need intermediary technology in order send and receive messages.

Table IMPT explains each column in Figure DVTP.

**Table IMPT. Description of the elements in Figure DVTP.** 

| Column | Description |
| :-: | :- | 
| Form |The pictographs show the type or form of communication that is under consideration. There are always people (cave dudes) on each end of the communication. The channel or medium is depicted with images. Both people and media are *actors*. The direction of communication is represented by red or blue arrows. Red arrows indicate one-way (monologic) communication whereas blue arrows represent two-way (dialogic) communication. Ghosted images indicate the potential for multiple occurrences of the actor. |
| Mode | Represents the multiplicity of the communication. There are three possible types: 1:1 = one-to-one messaging where one actor is communicating with one actor as in a private conversation; 1:m = one-to-many where one actor is communicating with many other actors as in a person giving a speech or a radio broadcast; finally, m:m = many-to-many where many actors are communicating with many other actors.  |
| Latency | Refers to the lag between the sending and the receipt of the message. Latency is *potentially* high where the message persists (as in cave art, photography, cinema, etc.) or is sent over long distances with multiple actors or technological layers intervening, and low where actors are present in the same time and place. |
| Synch | Synchronicity of the communication refers to whether the sender and receiver are engaging in communication at relatively the same time. This is related to Latency but whereas latency can be measured on an analogue scale from zero to infinity, Synchronicity is binary; either the actors are actively communicating at the same time or they are not. There can still be latency where there is synchronicity. The two states of Synchronicity are A (asynchronous = not same time) or S (synchronous = same time). |
| Persists | Persistence of the message. How long it lasts. A spoken word disappears nearly immediately upon uttering unless recorded in some way. A sculpture persists until it erodes or is destroyed by some immediate force. |
| Solves | This column suggests which of the barriers faced by communicators in getting their message sent and received is removed by the media actors in the scenario. In number 1 for example, the most basic of all challenges, that of verbal, synchronous, zero-latency one-to-one communication is solved by speech and a vocabulary. Other challenges include persistence of the message, the distance between the sender and the recipient, how many exact copies can be sent and received and the notion of the creation of a community of actors. Each form normally contains the solution to previous forms, and introduces a new solution unique to its actors. |

Let's now dissect Figure DVTP in detail. Starting at Form #1, with the cave dudes talking. The communication tool they are using is the mouth. The *mode* is one-to-one. *Latency* refers to the lag in time between the sender of a message formulating and sending that message and the receipt of that message by the recipient. In face-to-face (f2f) communication, the lag is nearly zero; imperceptible; negligible; nada; nuttin. Next we consider *synchronicity*, or whether the communication occurs in real-time or is subject to pooling or spooling and perhaps storage at one or the other end of the message. In-person, f2f communication is synchronous. Email (not considered in detail here), however, is asynchronous. It can take a good deal of time to compose an email and even if composed quickly, email can be saved as a draft and sent later. It's also subject to latency issues as mail travels through several servers on its journey to the recipient. On the recipient side, mail can sit in one's inbox for days or weeks. When read, it can be responded to immediately or after some time has passed. And in a lot of cases, email, like snail mail, can be trashed or ignored and *never* read. Thus communication never occurred despite a message being sent. 

Next we consider *persistence*, or whether the communication can be preserved in some usable format. Face-to-face conversation cannot be so preserved, except in the leaky and subject-to-bias memory of those who hear the message. Thus f2f does not persist in a valuable way. Finally we move to the *Solves* column where, for f2f conversation, we deem that this breakthrough (and the first time we communicated was an incredible breakthrough) solves the very fundamental problem of communication itself. There was (and is) plenty of *natural* communication (DNA for example) through hormones and touch and likely posture and physical intervention (shoving someone away has been and still is a form of communication) but when language developed - allowing us to *abstract* the physical from the mental - the breakthrough happened. 

Let's move on to #2, which is really a special case of #1. Same cave dude, but now the communication is being created through a physical artifact - a cave painting. First, take a look at the cartoon below:

** Figure ZDHL. 'Twas ever thus.**

![I've been framed!](https://raw.githubusercontent.com/robertriordan/2400/master/Images/golden_age.jpg)

*Source: http://www.toonpool.com/user/99530/files/cave_painting_2094475.jpg*

Funny eh? Believe me, it works on a lot of levels :) The tool in #2 is a paintbrush (I know it's a house painting brush -  Figure ZDHL is small and I wanted you to get the idea). Note what has changed from #1. First, there are several dudes looking at the painting. Each is seeing the same original. In addition, the *latency* has changed from Nil to High. There can be considerable time elapsed between the artist's conception and the viewer's viewing. In addition, *Synch* is now asynchronous, owing to the fact that the viewer (recipient of the message) likely isn't in the same place at the same time in which the sender (artist) is creating the message. Next, we have persistence. Cave paintings are still being viewed today. And finally, cave paintings solved three things: Mode (changed from 1:1 to 1:m), synchronicity (it was no longer necessary to be in the same place and time as the sender in order to receive the message) and persistence. A message could now be preserved in its original form.

The advent of the printing press (Form #3) solved the problem of replication (which is really about *portability*). A cave painting stays where it was created. To view it, you must travel to where it is. Books and magazines (and works of art on canvas for that matter) solved this portability problem. Now the message could be delivered to the recipient's location through replication. Original works of art excluded, the printing process also allowed multiple versions of the exact same object to exist, and copies of original work to be distributed. Ditto camera technology (not considered here). A picture can exist simultaneously in many places. But latency remained an issue. While some forms could be rapidly edited and republished (such as the evening edition of a newspaper with all the late-breaking news of the day included). Others, such as books, took a long time to prepare. Finally, asynchronicity remained an issue.

On to breakthrough #4 and #5, the *broadcast era.* Latency was defeated with live feeds and synchronicity could be either live or taped for later broadcast. The best of both worlds. Follow the aside below for an in-depth discussion of this advancement.



Back to Figure DVTT where we left off at item 6 and 7. This was a huge step forward for communications: the telephone. Whether, as Canadians contend, it was invented, produced and first tested in Canada (at Brantford Ontario where AG Bell lived and worked for a time) on in Boston Massachusetts, where a better infrastructure existed, is moot. What the telephone did was to allow synchronous communication over great distance, thus defeating *distance*. The sender and receiver of a communication could now be half a planet away yet still communicate in near perfect synchronicity. The cell phone then defeated the challenge of *location*. Early land lines were tethered (tied) to the wall and a system of physical wires in order the make the circuit. We had to go where the phones were. Cell phones allowed us to *cut the cord* and roam anywhere with an available the cell infrastructure. 

Hand-in-hand with the telephone revolution was the phenomenon we know as the internet. A *network of networks* allowed near real-time, distributed, person and group communication in any combination. Person-to-person, group-to-group, person-to-group, etc. All possibilities were attainable. The internet revolution Phase 1 defeated dialogicity (allowing many people to communicate synchronously with many people) and the wireless revolution allowed the defeat of location, just as the cell phone did for verbal communication. 

## Systems and process
<a name="systems">
**Figure SG. A simple system**

![Process](https://raw.githubusercontent.com/robertriordan/2400/master/Images/simple_system.png)

A simple system or a complex system, any system, has only four pieces. First, input is required. Once input is present, work (a process) then transforms that input into output. Feedback is then provided to the Input end (with a message that processing should continue, increase, decrease, stop or change in some way). That's it. Input --> Process --> Output --> Feedback. All four are necessary. No work process without input, no output without work, no input and work without something coming out the other side. And every system needs to report on how it's doing. Make sure to understand that a system also requires a *trigger*: something to set it in motion. Systems don't just start of their own volition (if they had any) or momentum. Something must spur them into action. Furthermore, and equally important, a system must have a *goal*; a reason for its existence; a purpose. We don't just do things because we can.

Our simple graphic above depicts a system, the goal of which is to make dairy products -- something my family did 100 years ago when their telephone number in Oshawa, Ontario was *7*. Yup, that’s it. Seven. Talk about getting in on the ground floor! 

![Riordan’s Dairy](https://raw.githubusercontent.com/robertriordan/2400/master/Images/riordans_dairy_cap.jpg)

To make dairy products, plenty of inputs are required, including hay, corn and grass to feed the cows, milk from those cows, scientific know-how, elbow grease and muscle, expertise, time, land and, of all things, data, information and accumulated knowledge. And lots more such as a farm infrastructure such as barns and storage silos to nurture the cows and a dairy with machinery to bring it all together and a supply chain to move stuff in and out. The message is that in order to produce dairy, plenty of input is required.

These inputs are fed to the dairy process, and this work process yields the output: cheese and milk and yogurt and ice cream. It’s pretty clear that our little graphic represents a very high-level view of the dairy system. There are literally hundreds of other systems, linked in chains, that actually account for the production here. But each is the same; a simple process, flanked by inputs and outputs. How then, and where, is value added and profit realised? 

Let’s look at our system again, this time in light of value add. 

**Figure Z. Value creation**

![Process](https://raw.githubusercontent.com/robertriordan/2400/master/Images/value_creation.png)

We shall see that while value is *added in the process part* it's measured at the boundaries - at the input and output sides of the system. 
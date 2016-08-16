##Chapter 1 - Backstory ![Flashlight](https://raw.githubusercontent.com/robertriordan/2400/master/Images/icons/32/time_mach_1.png)

### Measurement
<a name="measure"></a>
We first need to carefully consider what is meant by the term *measurement* as measurement is necessary in order for data to be useful. Measurement makes data tangible and gives it value. Under the topic of *Accuracy and precision*, Wikipedia (accessed June 17, 2015) offers the following discussion seedlings:

#### Accuracy
<a name="accuracy"></a>
“In the fields of science, engineering, industry, and statistics, the accuracy of a measurement system is the degree of closeness of measurements of a quantity to that quantity's actual (true) value."

#### Precision
<a name="precision"></a>
"The precision of a measurement system, related to reproducibility and repeatability, is the degree to which repeated measurements under unchanged conditions show the same results. Although the two words precision and accuracy can be synonymous in colloquial use, they are deliberately contrasted in the context of the scientific method."

They continue that, “A measurement system can be accurate but not precise, precise but not accurate, neither, or both. For example, if an experiment contains a systematic error, then increasing the sample size generally increases precision but does not improve accuracy. The result would be a consistent yet inaccurate string of results from the flawed experiment. Eliminating the systematic error improves accuracy but does not change precision."

Furthermore, “A measurement system is considered valid if it is both accurate and precise. Related terms include bias (non-random or directed effects caused by a factor or factors unrelated to the independent variable) and error (random variability).

#### Another view
According to ISO 5725-1, Accuracy consists of Trueness (proximity of measurement results to the true value) and Precision (repeatability or reproducibility of the measurement). Furthermore, the terms *trueness* and *precision* are both used to describe the accuracy of a measurement. Trueness refers to the closeness of the mean of the measurement results to the actual (true) value and precision refers to the closeness of agreement within individual results. Therefore, according to the ISO standard, the term "accuracy" refers to both trueness and precision.

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

Means *in name only*. Data measured using the nominal scale do not represent any intrinsic value. Measurement at this level sinmply names things such as Chevrolet, Ford, Ferrari or Male and Female. One might have an opinion on some characteristic of the named thing (such as the difference in value between a Ferrari and a Chevrolet) but there is nothing in the measurement itself that would allow one to accurately measure any value difference between these categories of automobile. In some contexts, a Chevrolet pickup truck would be superior to a Ferrari (on a farm or a construction site for example). But there is nothing in the *naming* of them that would allow one to accurately determine whether one is better than the other. They simply have different names. 

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

This is the highest level of measuerment and affords the most opportunity to understand the underlying dimensions captured therein. Examples of variables measured at the ratio level include age, dollar values, counts of discrete items (number of events, purchases, people, goods, etc. either when counting or when expressed as a ratio to each other or to a total). Interval data are exact and have a real zero, thus any and all algebraic operations are possible (addition, subtraction, multiplication, division and exponentiation). Finally, we can say that $2 is twice as much as $1. 

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
| **H**ierchical | **O**rdinal, **I**nterval, **R**atio |

##### L -  Location data

Maps, broadly defined (from a location on the body for a surgeon to a room in a building for a delivery all the way up to quadrant in the universe), can be neatly categorised as Location data in LATCH. GPS devices make use of data tagged with *geo-locale* information (latitude by longitude and elevation). 

Location data can be either Nominal data in NOIR (as in the name of a city such as Kamloops, for example) or as Ratio data if expressed in GPS latitude/longitude coordinates such as 45.4165315, -75.65170139999998 or as Degrees, Minuters and Seconds as in N45° 24 59.513', W75° 59 6.125'. These are the coordinates of the Ottawa ViaRail station around 200 Tremblay Road. 

[Interested in the GPS coordinates of some place?](http://www.gps-coordinates.net/)

##### A - Alphabetic data

Alphabetisation is very frequently used, often as a secondary attribute. Alpha data are good for categorising enormous datasets such as a phone directory or an employee directory or a social media *friend* list. Since virtually everyone understands alphabetical order, this method is often used when consumers of data are not familiar with the subtle nuances of other methods of categorisation - *"When all else fails, alphabetise!"*

Alphabetic data under the LATCH taxonomy corresponds to Nominal data in NOIR. 

##### T - Time data

Anything that is tracked chronologically and has either a measurable start point and/or end point can be expressed in terms of time. The Vietnam Memorial in Washington DC, for example, is ordered by time, affording viewers the added information of seeing others who died at roughly the same time, and allowing context with other events in the news. Interesting to note that within time segments (days for example) US Vietnam casulaties are then listed alphabetically to assist in finding them. Thus alphabetical listing is secondary to chronological. 

Time data correspponds to either Ordinal or Interval data in the NOIR system. 

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

Let's now consider this in some detail (I know it will render small and there's lots of detail. I recommend viewing this on a dektop machine if you can, or printing it. Any way to see the detail.) For important context, note that time is represented top to bottom in the figure, shown by the green arrow on the left, topped by a *Dali-like* melting clock to indicate that time here is relative and not absolute. I have, for example, grouped TV and radio together (#4 and #5) because they are examples of *broadcasting* whereas in reality, telephone (#6 and #7) predated TV. With this in mind, note we start with cave-dwellers (#1) at the top and end with the modern internet at the bottom (#8 & #9). Much of history is missing here (such as the telegraph and still photography and then moving pictures, for example). Note also that when I created this figure, I searched for an image of a cave-dweller and was so enamoured with the little guy I found that I used him to represent people right up to the modern era. He's a little Luddite cave dude and I'm attached to him. He just represents people. 

Next note that no matter which era or breakthrough we examine from top to bottom in the figure, the little cave dude appears on both ends of the transaction - this is all about person-to-person communication. The arrows (there are two colours of arrow) indicate directionality of communication. Blue arrows indicate bi-directional communication; that is, messaging that flows both ways, from sender to receiver and back. Note that the earliest communication (simple speech) was bi-directional but despite eons of progress, we didn't return to bi-directionality until the invention of the telephone (and the earlier telegraph - which was not synchronous - which is not shown in the figure). It took us a long time to replicate real-time (synchronous) chatting. Red arrows indicate one-way communication.

Next note that there are sometimes other *ghosted* images clustered around a darker image (as is the case with the cave dudes in Form #3). On the right, there is one principal and several secondary dudes. This indicates that there could be more than one person on this end of the communication emanating from  the *printing press* and *newspaper* modes of communication. One source (an author, for example) can produce many copies of a book or a paper. The message is the same in each case, but there can be many recipients with a copy, and the copy can be shared with others. It's important to note that each on the many side are looking at *their own unique copy of the message* be it a book or a magazine or a newspaper. So the *Mode* of communication (see the column just to the right named *Mode*) is 1:m, meaning *one source* but *many destinations* are possible (this is referred to as *monologic* transmission). The other two possibilities for Mode are 1:1 (one-to-one or *dialogic*) and m:m (many-to-many or *multilogic*). There is some confusion among specialists on the three terms (monologic, dialogic and multilogic). I prefer to refer to one-way communication (as in a piece of art or a radio broadcast) as *monologic* (as in *monologue*), one-to-one communication as *dialogic* (same root as dialogue) and many-to-many as *multilogic* (logically *multilogue*) but you will find this isn't universal. 

The same can be said for the clusters of televisions and radios. A brodacaster sends a signal that many can receive, but the signal, and therefore the message, is the same in each case. What is slightly different is that, while the receiver is easily replicated (many tvs and radios), so can there be many people weatching and listening to the message simultaneously. So that's why the dudes are all solid. Many people looking at the same TV or streaming event or movie is different from many people, each looking at their own book because when many people are together, it creates a real-time community. We have moved from one source (a newspaper) producing many copies, to one source (a radio station) producing one copy of a program that many listen to simultaneously. There are no *ghosts* here in #4 or #5. Each person who receives the message is listening to or watching the same broadcast. 

You might want to argue that a cave dude might be talking to one among the cohort, but others might well be passively listening or even in a rudimentary *audience* as it were. But I consider such other listeners to be incidental to the basic communication here. Likely the first couple of millions of years of communication were *predominantly* one-on-one affairs. 

Dude could be talking to one person or to a crowd, but the message is the same for all. Much like when we get to the internet around #8 in the figure. The original internet (often called Web 1.0) featured servers *serving up* the same content to all, much like TV or radio. With Web 2.0, not only is much of the content crowd-sourced, but configuration allows us to customise the messages we receive in infinite ways. 

Finally, generally note that the tools we are using to communication are becoming increasingly sophisticated and layered. We increasingly need intermediary technology in order send and receive messages.

Table IMPT explains each column in Figure DVTP.

**Table IMPT. Description of the elements in Figure DVTP.** 

| Column | Description |
| :-: | :- | 
| Form |The pictographs show the type or form of communication that is under consideration. There are always prople (cave dudes) on each end of the communication. The channel or medium is depicted with images. BOth people and media are *actors*. The direction of communication is represented by red or blue arrows. Red arrows indicate one-way (monologic) communication whereas blue arrows represent two-way (dialogic) communication. Ghosted images indicate the potential for multiple occurences of the actor. |
| Mode | Represents the multiplicity of the communication. There are three possible types: 1:1 = one-to-one messaging where one actor is communication with one actor as in a private conversation; 1:m = one-to-many where on actor is communication with many other actors as in a person giving a speach or a radio broadcast; finally, m:m = many-to-many where many actors are communications with many other actors.  |
| Latency | Refers to the lag between the sending and the receipt of the message. Latency is *potentially* high where the message persists (as in cave art, photography, cinema, etc.) or is sent over long distances with multiple actors intervening, and low where actors are present in the same time and place. |
| Synch | Synchronicity of the communication refers to whether the sender and receiver are present in the same time an place. This is related to Latency but whereas latency can be m,easured on an analogue scale from zero to infinitiny, Synchnonicity is binary; either the actors are same place and time or not. There can still be latency where there is synchronicity. The two state of Synchronicity are A (asynchronous = not same time and palce) or S (synchronous = same time ans place). |
| Persists | Persistence of the message. How long it lasts. A spoken word dissapears nearly immediately upon uttering unless recorded in some way. A sculpture persists intil it erodes or is destroyed by some immediate force. |
| Solves | This column suggests which of the barriers faced by communicators in getting their message out and received is removed by the media actors in the scenario. In number 1 for example, the most basic of all challenges, that of verbal, synchronous, zero-latency one-to-one communication is solved by speach and a vocabulary. Other challenges include persistence of the message, the distance between the sender and the recipient, how many exact copies can be sent and received and the notion of the creation of a community of actors. Each form normally contains the solution to previous forms, and introduces a new solution unique to its actors. |

Let's now disect Figure DVTP in detail. Starting at Form #1, with the cave dudes talking. The communication tool they are using is the mouth. The *mode* is one-to-one. *Latency* refers to the lag in time bewtween the sender of a message formulating and sending that message and the receipt of that message by the recipient. In face-to-face (f2f) communication, the lag is nearly zero; imperceptible; negligible; nada; nuttin. Next we consider *synchronicity*, or whether the communication occurs in real-time or is subject to pooling or spooling and perhaps storage at one or the other end of the message. In-person, f2f communication is synchronous. Email (not considered in detail here), however, is asynchronous. It can take a good deal of time to compose an email and even if composed quickly, email can be saved as a draft and sent later. It's also subject to latency issues as mail travels through several servers on its journey to the recipient. On the recipient side, mail can sit in one's inbox for days or weeks. When read, it can be responded to immediately or after some time has passed.

Next we consider *persistence*, or whether the communication can be preserved in some useable format. Face-to-face conversation cannot be so preserved, except in the leaky and subject-to-bias memory of those who hear the message. Thus f2f does not persist in a valuable way. Finally we move to the *Solves* column where, for f2f conversation, we deem that this breakthrough (and the first time we communicated was an incredible breakthrough) solves the very fundamental problem of communication itself. There was (and is) plenty of *natural* communication (DNA for example) through hormones and touch and likely posture and physical intervention (shoving someone away has been and still is a form of communication) but when language developed - allowing us to *abstract* the physical from the mental - the breakthrough happened. 

Let's move on to #2, which is really a special case of #1. Same cave dude, but now the communication is being created through a physical artifact - a cave painting. First, take a look at the cartoon below:

** Figure ZDHL. 'Twas ever thus.**

![I've been framed!](https://raw.githubusercontent.com/robertriordan/2400/master/Images/golden_age.jpg)

*Source: http://www.toonpool.com/user/99530/files/cave_painting_2094475.jpg*

Fynny eh? Believe me, it works on a lot of levels :) The tool in #2 is a paintbrush (I know it's a house painting brush -  Figure ZDHL is small and I wanted you to get the idea). Note what has changed from #1. First, there are several dudes looking at the painting. Each is seeing the same original. In addition, the *latency* has changed from Nil to High. There can be considerable time elasped between the artist's conception and the viewer's viewing. In addition, *Synch* is now asynchronous, owing to the fact that the viewer (recipient of the message) likely isn't in the same place at the same time in which the sender (artist) is creating the message. Next, we have persistence. Cave paintings are still being viewed today. And finally, cave paintings solved three things: Mode (changed from 1:1 to 1:m), synchronicity (it was no longer necessary to be in the same place and time as the sender in order to receive the message) and persistence. A message could now be preserved in its original form.

The advent of the printing press (Form #3) solved the problem of replication (which is really about *portability*). A cave painting stays where it was created. To view it, you must travel to where it is. Books and magazines (and works of art on canvas for that matter) solved this portability problem. Now the message could be delivered to the recipient's location through replication. Original works of art excluded, the printing process also allowed multiple versions of the exact same object to exist, and copies of original work to be distributed. Ditto camera technology (not considered here). A picture can exist simoultanelously in many places. But latency remained an issue. While some forms could be rapidly edited and republished (such as the evening edition of a newspaper with all the late-breaking news of the day included). Others, such as books, took a long time to prepare. Finally, asynchronicity remained an issue.

On to breakthrough #4 and #5, the *broadcast era.* Latency was defeated with live feeds and synchronicity could be either live or taped for later broadcast. The best of both worlds. Follow the aside below for an in-depth discussion of this advancement.

###Disassociation of content, time and support
<a name="disassociation">
We live in an increasingly digitised world. Consider a simple example: a hockey game. Time was, the only one way to enjoy the event was in person. Consider the myriad ways such an event can be enjoyed today, both *synchronously* (in real time both in person and offsite) and *asynchronously* (not in real time – stored for later consumption).  See Figure TT below.

**Figure TT. Disassociation of content, time and support**

![Disassociation](https://raw.githubusercontent.com/robertriordan/2400/master/Images/disassociation.png)

Let’s unpack this busy figure. The event is a hockey game. In the early days of such games, they were played on local frozen ponds and then on makeshift rinks, and only when the temperature was below freezing. The teams were made up mostly of locals, and the fans, if there were such hardy souls, were locals rooting for the local boys (it was a man’s game back in the day). In order to experience the spectacle, it was necessary to attend in person. There wasn’t often any press to report on the match. The only artifacts produced by the games were in the memories of those in attendance, and any anecdotal scribblings of a local historian or scribe. Those were the days indeed.

As the cities and towns grew, so too did the rivalries. More and more attention was paid to sporting events and more archival material became available in the form of photographs and perhaps even some grainy film. Players began to receive small *rewards* for their efforts. Firms became interested in having their name associated with a winning side (as brand management). When real money enters the picture, interest picks up. More people attend the games. More widespread interest in the outcomes is aroused. This spiral of interest and investment leads to capacity problems at the arenas. Not enough seats for willing purchasers, and the widespread interest leads to the inability for *fans* to attend due to long travel times and cost.

Enter new support systems. The dawn of commercial radio, and then television, led to the ability for remote fans to enjoy at least some of the *in-person* experience of a sporting event in the comforts of their own home. This revolution required what Goldfinger calls *supports* and what we might think of as technology (which includes print media). Supports are the things that allow us to have a *near-real-time* experience of an event occurring in some other place. 

I remember back to the 1965-66 Junior “A” hockey season, the last where legendary Bobby Orr played for my hometown *Oshawa Generals*, and I was all of 13 years old. There was no TV coverage at all but I owned a gorgeous little compact transistor radio, powered by the very first 9-volt batteries, that I hid under my pillow so I could listen to the games as the Generals travelled to exotic (to me) locations around the country to beat first the *St. Catherine’s Black Hawks*, then the *Montréal Junior Canadiens* (at that time playing in the Ontario Hockey League) and finally the *Kitchener Rangers* to win the J. Ross Robertson trophy emblematic of OHA (not yet called the OHL) supremacy. The Oshawa side then went on to best the *North Bay Trappers* (by a combined score of 43-9 over four games) and finally the *Shawinigan Bruins* in three straight in a best-of-five to earn the right to represent the eastern provinces in the Memorial Cup.  

Oshawa lost to the *Edmonton Oil Kings* in that national final, with Orr playing hurt and finally reputedly being benched on orders from his new masters, the *Boston Bruins*, who had drafted and signed him to an NHL contract. Orr’s bad knees were legendary, even at 17 years of age. 

While the pain of losing that Memorial Cup series to the Oil Kings is still palpable, so is the sheer excitement of listening in near real-time as the games unfolded in faraway places. That little Japanese *Candle* transistor radio was my support. By the same token, I remember well watching the Toronto Maple Leafs (my dad’s team – I was a Bruin’s fan as Oshawa was a Boston feeder team) win their last ever (and maybe final ever) Stanley Cup, in 1967, when I was the tender age of 14... alas. This was the golden age of *broadcasting*, or sending a single signal to many receivers, in this case, most of the TV sets in Canada.  

This explains the first two spheres on Figure TT, numbered 1 and 2, extending the in-person experience to the home, through early radio and then TV.  Sphere number three is a bit more complex, as it introduces the confounding influence of *synchronicity* to the equation. Attending the game, or listening via radio or watching on TV are all *synchronous* events – experienced in real time (or very near real time taking *latency* into account). Sphere number three, labelled *Anywhere*, shows that it’s not necessary to be *tethered* to a location in order to experience an event. The automobile radio and the portable transistor radio were the first to *cut the cord* as it were, allowing the very first *roaming* experience. And make no mistake - it was big at the time. The ability to bring music to the beach or on a walk or to a ball game on a summer's eve was truly liberating. 

Today the ability to consume anything, anywhere, in real time is taken for granted. Thus we have a myriad of ways to experience the game, including streaming services available wherever the internet is available, on devices such as desktop and laptop computers, tablets, smart phones and smart TVs, most of which are quite portable. Commercial providers offer services varying from streamed audio, streamed audio/video, to instant, *bite-sized* updates in various forms depending on the device in use.  All these are on the synchronous side of the equation. Asynchronous media include newspaper reports, news media on radio and TV reporting (which are nothing new at all), as well as our own capacity, with a Personal Video Recorder (PVR), to *tape* an event and dissect it at any time later in all its stop and start, slow-motion glory. Time is no longer in the equation. 

And that covers the commercial providers. Increasingly important, however, is our own ability to report (share) the real-time experience for both synchronous and asynchronous consumption. Witness the rise of social media and the concept of *narrowcasting*. Twitter and Facebook are narrowcasting technologies, narrow being defined relatively. Twitter supports narrow communities of *followers* and Facebook the same concept, referred to as *friends*. I don’t need to explain these platforms to you. 

Let’s think about what could happen at a public event, such as our hockey game. With social media, you could easily narrowcast through any number of platforms. Your followers and friends could consume, in near synchronicity (real time), your experience of the game. But let’s go farther afield and consider that you could also narrowcast a live stream of the event through technologies such as *Periscope*, and *Meerkat* (who are now concentrating on video networking) and Facebook Live which allow anyone with a camera and a connection to the internet to live stream any event. You are the new CBC. An emerging *Sportsnet*. A nascent *Hockey Night in Canada*. 

Ok so cool enough. But consider that you can be Tweeting, Facebooking and *Periscoping* in real time *inside the venue* where the event is happening. Others in your sphere could well be consuming your narrowcasts, and by the same token you could be consuming theirs.  This adds a whole new dimension to the model. Finally, you could also be live narrowcasting the game to anyone on the other end of a cell phone call, or recording your play-by-play on a voicemail recorder for later consumption and analysis. 

Alas, just two days after my writing the above paragraph, The NHL itself officially banned livestreaming of its property (games) by anyone. [Mashable.com reported](http://mashable.com/2015/04/22/periscope-meerkat-banned-nhl/) that NHL Deputy Commissioner Bill Daly announced on April 21, 2015 that: 
>“... any streaming of footage in violation of the NHL’s Broadcast Guidelines (including, for example, live-streaming inside the arena less than 30 minutes before the start of the game) and Media Access Policy is expressly prohibited." 

The Mashable piece concludes with: 
>“... the branding opportunities for organizations like the NHL seem pretty limitless: rinkside live streams of team warm-ups, exclusive interviews with players and coaches, the list goes on. So it figures: Why cede those opportunities (and future dollars) to fans?”

[Interested?](http://yhoo.it/1dkOJFp)

All of this represents a wrinkle in the space-time continuum of synchronicity and location. But what’s the bottom line here? Why does this matter other than being really cool and other than actually making it considerably less likely that we will enjoy an in-person, synchronous event? (Next time you either attend or watch a major event such as the opening or closing of the Olympic Games, note how many people are recording it, watching the pageantry through a tiny camera screen, to be played back... never?). Recently (May 2016), pop star Adele (only needs one name), called out a fan for recording her concert. Or perhaps the fan was live-streaming? Hard to tell, but Adele shut her down anyway. Check out the video:

{% youtube %}https://www.youtube.com/watch?v=Gg0pSgrtQJo{% endyoutube %}

But in an odd twist, and back to the future for sure, take a look at this *[Economist Espresso](https://espresso.economist.com/30d454f09b771b9f65e3eaf6e00fa7bd)* story from June 4, 2016. Seems that live broadcasting of events isn't quite dead yet, and may in fact enjoy a resurgence. 

####Some thoughts on the media

There is no denying that the majority of the *weightless* or the *digital* or the *intangible economy* is if not driven by, at least facilitated by, information and communication technology. So to fully participate, it’s necessary to be well versed in the technology – not necessarily to be able to *create* new technology but clearly to be able to *leverage* it. To understand it well enough to be able to see how it can solve problems or create opportunities for competitive advantage. 

And it’s also important because of ownership. And ownership is all about business because business sells access to events such as hockey games. This is why it’s a revolution. The ownership model is completely upside-down now. The ability to participate in (consume) an event is now available to any and all with a support mechanism (technology) and an internet connection (technology). So ownership of that event is now widely dispersed. Who, for example, owns the rights to a Tweet or a FB post or indeed to a live stream via *Periscope* of a hockey game? And the pricing for consumption is now multi-tiered. In fact, one could argue that the price to consume many events (or movies or broadcasts of any kind – indeed at the time of writing there have been numerous reports of live-streaming feature films) has been reduced to the hit you take on your data plan. So how to generate revenue from events? How do you pay your hockey players or your screen actors? 

This at least partly explains the consolidation among entertainment providers and also why the former content *purveyors* (such as Rogers and Bell) are now content *producers*, owning major league sports teams for example, and buying up sports broadcasting properties (while Bell owns at least part of TSN, for example, and Rogers owns the Blue Jays as well as their ball park, and at the time of writing, they together hold a nearly 80% share in Maple Leaf Sports and Entertainment, which owns major league teams in three leagues as well as considerable prime real estate). So the folks who formerly *brought you* the product (via cable, satellite and the internet), now own the venues, the product and the distribution channels. And in a market such as Canada, where people live and die hockey, having the purveyors of content own the competition is particularly problematic.  

[Interested in media consolidation?](http://www.dailyinfographic.com/wp-content/uploads/2015/04/IllusionofChoice.jpg)

But if they don’t follow this model, they risk being shoved aside by the content producers. They’ve become the creators rather than the purveyors. *Shomi* is a Rogers – Telus joint response to *Netflix* (isn’t it fun when competitors get in bed with each other – this is the definition of a strategic partnership). Bell’s *CraveTV* is the same. As of the writing of this paragraph, Rogers/Telus has announced that, just like Netflix, Shomi will be available to all as a streaming service to anyone (not just their customers). It’s the only way to compete in this world of intangible products. And it’s due in large part to the *digital revolution*. Netflix is a *disruptor*. We will return to disruptors later in this text.
 
Netflix has impacted network TV to the point of near extinction.

[Interested?](http://www.dailyinfographic.com/wp-content/uploads/2015/09/watta.jpg)

Back to Figure DVTT where we left off at item 6 and 7. This was a huge step forward for communications: the telephone. Whether, as Canadians contend, it was invented, produced and first tested in Canada (at Brantford Ontario where AG Bell lived and worked for a time) on in Boston Massacheutsetts, where a better infrastrcture existed, is moot. What the telephone did was to allow synchronous communication over great distance, thus defeating *distance*. The sender and receiver of a communication could now be half a planet away yet still communicate in near perfect synchronicity. The cell phone then defeated the challenge of *location*. Early land lines tethered (tied) to the wall and a system of physical wires in order the make the curcuit. We had to go where the phones were. Cell phones allowed us to *cut the cord* and roam anywhere with an available the cell infrastructure. 

Hand-in-hand with the telephone revolution was the phenomenon we know as the internet. A *network of networks* allowed near real-time, distributed, person and group communication in any combination. Person-to-person, grouo-to-group, person-to-group, etc. All possibilities were attainable. THe internet revolution phase I defeated dialogicity (allowing many people to communicate synchronously with many people) and the wireless revolution allowed the efeat of location, just as the cell phone did for verbal communication. 

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


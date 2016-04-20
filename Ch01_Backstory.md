### Measurement
<a name="measurement"></a>
We first need to carefully consider what is meant by the term *measurement* as measurement is necessary in order for data to be useful. Measurement makes data tangible and gives it value. Under the topic of *Accuracy and precision*, Wikipedia (accessed June 17, 2015) offers the following discussion seedlings:

#### Accuracy
“In the fields of science, engineering, industry, and statistics, the accuracy of a measurement system is the degree of closeness of measurements of a quantity to that quantity's actual (true) value."

#### Precision
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
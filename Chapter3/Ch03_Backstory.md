Week 7 Chapter 6 slides for relationship between SDLC and Project Management. 

##Risk and Risk Management

Everything is risky. Getting out of bed in the morning is risky (you could slip and fall). But so is staying put (you wouldn't last long without food and exercise). So once again, nothing is free. There is risk attached to action and to inaction. This might remind you of our discussion n Chapter 2 regarding how decisions arise from information. Given the right information in the right context, one can decide whether to act or not.This is nicely illustrated by the notion of risk. Given the right information, we can decide to do something about risk or not. That's where we're going in this discussion. 

What is risk? Our friends at [Wikipedia define risk](https://en.wikipedia.org/wiki/Risk) as "... the potential of gaining or losing something of value. Values (such as physical health, social status, emotional well-being or financial wealth) can be gained or lost when taking risk resulting from a given action or inaction, foreseen or unforeseen." People takes risks all the time (some more than others - teenage males are the biggest risk takers). Firms and organisation also take risks. To not take risk is to perish. For example, Bernard Myerson (VP Global Innovation, IBM), in a speech at GTEC 2012 in Ottawa, said ”You can never save your way to greatness. If you shut that engine [innovation] off, it can take 35 years to restart. You have to be willing to gamble. Safe and conservative gets you nowhere!” (Source: Ottawa Citizen, November 9, 2012, pages F1 and F2). Innovation is risk. Changing what works is risky. Not changing what doesn't work is riskier still. But how to know which risk to take, and what the consequences will be. That's the hard part. 

What are the sources of risk? Among others, there are:

- Credit and financing
- Internal sabotage
- Project/product failures
- Political
- Legal liabilities
- Supply chain difficulties
- Accidents
- Natural causes and disasters
- Malicious attacks from a competitor/adversary
- Others may arise and/or are specific to particular industries...

###Managing Risk

To mitigate risk, the following methods are performed more or less in the following order:

- Identify, characterise, and assess threats
- Assess the vulnerability of critical assets to specific threats
- Determine the risk (i.e. the expected consequences of specific types of attacks on specific assets)
- Identify ways to reduce those risks
- Prioritise risk reduction measures *based on a strategy*

A simple measure of risk is the *Composite Risk Index* which is calculated by multiplying the *impact of a risk event* by the *probability of occurrence for each potential risk event*. The impact of the risk event is assessed on a scale of 1 (no or small financial impact) to 5 (total ruin). The probability of occurrence is likewise assessed on a scale from 1 (highly unlikely) to 5 (inevitable – but if inevitable it’s not a risk but a structural fact so let’s say 5 is just shy of inevitable... almost certain?). The resultant *Composite Index* thus ranges from 1 through 25 *for each factor*. This risk score is then arbitrarily divided into three sub-ranges:

- Low (score of 1 to 8)
- Medium (9 to 16)
- High (17 to 25)

But note that the probability of risk occurrence is difficult to estimate since past data on frequency of occurrence are not always readily available.
Furthermore, the impact of the risk is not easy to assess since it is often difficult to estimate the potential financial loss in the event of a risk turns into an event. So indeed, this is a risky business. 

Here is a simple risk profiler.

**Figure JPHB. Risk profiler**

![Risk Profiler](https://raw.githubusercontent.com/robertriordan/2400/master/Images/risk_profiler.png)

This is a picture of the risk profile of a project. The project could be anything from building a deck to architecting a complex information system. In the particular (fictional) project, there are 11 identified risk factors - count each *x*. These factors were identified by either business process (domain) experts, or systems analysts, designers or project managers - most likely *all* these players played a role in identifying the risk factors. As outlined above, each was then assigned, based on the best available information, an *impact* score (how much it would hurt if the risk were realised) and a *likelihood* score (the probability that this risk will actually happen). We then simply sum the product of the two scores for each factor. This project has a total risk profile of 65. The total score is of nothing more than passing interest unless comparing projects with the same number of risk factors. A better measure is the *average* risk score, here calculated as 65/11 (the total score / the number of factors). This will allow better comparison over time and between projects. But that's not the *whole* story. The *distribution* of risk is also important. If factors are clustered in one zone, for example, a score can be misleading. *Ergo* the distribution is important.  Whatever the distribution however, the risks in the upper, right must be addressed. These are potentially damaging and likely to happen. They can lead to disaster if not managed. 

[Interested in risk profiling?](https://raw.githubusercontent.com/robertriordan/2400/master/resources/risk_profiler.xlsx) Download this Excel spreadsheet and see what different hypothetical projects would look like in terms of risk profile. You can enter two project profiles side by side and compare the statistics derived from them. Enter values in the green areas. (You will need Excel installed on whatever device you choose to use.)

**Table STTA. Risk reduction methods**

| Risk response | Potential action |
| :-| :-|
| Risk transfer | Move the risk to a department, organisation or person who can better handle the risk |
| Risk deferral | Postpone exposure to the risk until circumstances are more favourable or resources are available to address the risk |
| Risk reduction | Either reduce the probability of the risk occurring or lessen the impact |
| Risk acceptance | Realise that some risks are unavoidable and make sure that contingency plans are in place |
| Risk avoidance | Eliminate the possibility of the risk occurring; however, that may close the doors on some business opportunities as well |

You can't make risk disappear, but you can manage around it. Table STTA outlines five ways in which risk can be managed, ranging from transferring the risk to someplace else (this is what insurance does, but at a cost relative to the severity and probability of the risk), through changing the project schedule to some future time when the risk is reduced (this is deferral), through changing the context of the risk (this is a vague action as it would mean changing either the project or the circumstances of the project, which really changes everything - this is my least favourite method), down to just biting the bullet and accepting that risk occurs to finally just not doing the project because the risk is too great. 

###Project Management

Perhaps the best, and certainly the most popular, method to deal with risk is through Project Management. Project Management is an accredited discipline regulated by the [Project Management Institute](https://www.pmi.org/). Accreditation is akin to becoming a CPA, for example, with rigorous training, testing and regular and continuous re-training and re-certification. 

Managing an ICT development (or other) project is a balancing act. A project manager simultaneously oversees three main project elements: 

- The scope of the project
- The required resources
- The time to complete it

The project scope defines what the project is intended to accomplish. Resources can include people, equipment, material, and money. Time estimates consider project activity time requirements and how they depend on each other (for example it's not wise to begin coding until there is some understanding of what the system requirements are). Management of these elements, and their intricate interplay, is a balancing act. Project Managers (PMs) often make decisions to actively set the levels of two elements, and then calculates the third accordingly while always realizing that all three are important and must be accomplished. This is often expressed (or visualised) as the *Project Management Triangle.* 

**Figure YTPT. The Project Management Triangle (revisited)**

![Risk Profiler](https://raw.githubusercontent.com/robertriordan/2400/master/Images/pmt.png)

Let's take a minute of two unpacking this figure. The Project Management Triangle (PMT) is most often seen as, guess what, a triangle. There is a faint tirangle in the background of the figure, with the three corners pointing at the three constraints in project management: Quality, Speed and Economy. You will likely have seen (*or will see) *economy* expressed as *cost*. The idea is the same, but calling it economy makes the *opposite* of it easier to express with arrows (as we will see). 
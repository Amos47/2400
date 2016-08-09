Week 7 Chapter 6 slides for relationship between SDLC and Project Management. 

###Risk and Risk Management

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

####Managing Risk

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

This is a picture of the risk profile of a project. The project could be anything from building a deck to architecting a complex information system. In the particular (fictional) project, there are 11 identified risk factors - count each *x*. These factors were identified by either business process (domain) experts, or systems analysts, designers or project managers - most likely *all* these players played a role in identifying the risk factors. As outlined above, each was then assigned, based on the best available information, an *impact* score (how much it would hurt if the risk were realised) and a *likelihood* score (the probability that this risk will actually happen). We then simply sum the product of the two scores for each factor. This project has a total risk profile of 65. The total score is of nothing more than passing interest unless comparing projects with the same number of risk factors. A better measure is the *average* risk score, here calculated as 65/11 (the total score / the number of factors). This will allow better comparison over time and between projects. But that's not the *whole* story. The *distribution* of risk is also important. If factors are clustered in one zone, for example, a score can be misleading. A project would have the same average score if it has 10 risk factors judged to be low probability (1) and high impact (5) as a project with 10 factors judged high probability but low impact. But these can be very different projects with very different consequences. *Ergo* the distribution is important.  

Try [this](https://raw.githubusercontent.com/robertriordan/2400/master/resources/risk_profiler.xlsx) download of a profiler in Excel. See what different projects look like in terms of risk profile.  
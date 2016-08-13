### Fixing the siloed organsiation

What to do? As a first step, some rationalisation of data stores is in order. Looking at the organisation from a *process viewpoint*, we realise that the Sales, Marketing and Customer Service functions all relate to the *customer interface* and share more in common with each other than they do with Manufacturing or Finance, for example. So we might think to rationalise around an enterprise system that has a customer focus. And there's just such a beast: the *Customer Relationship Management* or CRM system. 

Take a look at Figure ESO below. Note the only real change? Functions under the same VP now share databases, making reporting much easier at that level. The databases are bigger, more sophisticated in terms of reporting and relationships and allow for data to be stored and formatted in compatible ways for reporting purposes in this management structure. That’s a great first step. But really, we have only *reduced* the pain. It’s not a cure. Note the CFO (Chief Financial Officer) and CPO (Chief Privacy Officer) would experience the same problem getting compatible and timely reports as before, as they must cross systems boundaries to get rolled-up data. Not a complete solution at all.

Examples of enterprise systems include: 

- *CRM* (Customer Relationship Management) - manages customer-related processes
- *PLM* (Product Lifecycle Management) - handles creation and implementation of new products
- *SCM* (Supply Chain Management) - deals with procurement, inventory, and other supply chain processes
- *SRM* (Supplier Relationship Management) - works with suppliers, vendors and service providers

Each of these types of ES concentrate on a particular aspect of the value chain. Note they are *managing* some process or aspect, such as *Customers* or *Suppliers* or *Products*. Using such systems, while productive (efficient and effective) in and of themselves, does not get us to the truly integrated enterprise stage that we seek. Read on.

**Figure ESO. An enterprise systems organisation**

![An ES organisation](https://raw.githubusercontent.com/robertriordan/2400/master/Images/es.png)

You are probably already guessing what the ultimate fix might be, and that is the enterprise system to beat all enterprise systems -- the mother of all ESs - the *Enterprise Resource Planning*, or ERP, system. The ERP organisation is a medium to large (to enormous) operation with enough functional complexity and cash to warrant such a comprehensive and expensive solution. ERP (Enterprise Resource Planning systems) automate and rationalize key business functions such as financials, human capital, operations, and corporate services, and also provide complete *snap-in* solutions for a wide variety of industries (such as pharma, auto, defence, agriculture, retail, etc…) which integrate and automate all functions of an organisation. Take a look at Figure ERP below and spot the change.  

<a name="erp_org"></a>
**Figure ERP. An ERP organisation**

![An ERP organisation](https://raw.githubusercontent.com/robertriordan/2400/master/Images/erp.png)

While this is a *massive* oversimplification of all the benefits or ERP, it serves to illustrate its most basic principle: that a transaction should be *atomic*, that is, there should only ever be one instance of a thing such as a *sale*. The sale, as an *entity*, should make its way through the organisational value chain but should never exist anywhere other than in the value area in which it resides. So there should not be an instance of the sale in Accounting, and in Finance, and in Sales and in Shipping. There is only ever *one* sale. We can track its position but never copy it. Because a sale, like any other object in an organisation, has a lifetime. We can watch it and interact with it and query it to ask what it's up to through its lifetime but we must never clone it to fulfil the siloed needs of functional areas. And enterprise database *backends* help to fulfil this very basic requirement. We will discuss *backends* in Chapter 7.

What are the benefits of Enterprise Systems (such as ERP)? According to Rick Mullin, *ERP Users Say Payback is Passé*, (Chemical Week, Feb. 24, 1999) as quoted in CGA stuff waiting for permission, they are plenty: 

- Inventory reduction 
- Personnel reduction 
- Productivity improvement 
- Order management improvement 
- Financial close cycle reduction 
- Procurement cost reductions 
- Cash management improvements 
- Revenue increases 
- Transportation/logistics cost reduction 
- Maintenance reduction 
- On-time delivery improvements 
- Information visibility 
- Improved processes 
- Customer responsiveness 
- Cost reduction 
- Integration 
- Standardization 
- Flexibility 
- Globalization 
- Improved business performance 
- Supply chain management

What's not to love? 

Note the major change – one massive database has replaced all functional and MIS systems. While this is the most *obvious* change, it is by no means the *only* change that organisations undergo when adopting an ERP.  Next in line in terms of significance following the integration of all company data stores into a single, transaction-oriented database, the largest impact that an ERP has on an organisation is the requirement that the firm examine and alter all its business processes to match the *best practice* standards enforced by the ERP system. Don’t want to do business our way? Then you won’t be running SAP or Oracle or Microsoft ERP systems. You play by the rules or you don’t play. This is the most common reason cited for failed ERP installations – the inability (or unwillingness) of the organisation to change the way it does business to match the ERP’s standards.

Let's take a quick look at role-based visibility and scope as it applies to organisations using ERP-type software. Figure KT shows the breadth of visibility of data and information corresponding to position in the organisational hierarchy. 

**Figure KT. Role-based scope of visibility**

![An ERP organisation](https://raw.githubusercontent.com/robertriordan/2400/master/Images/scope.png)

The *visibility* of data/information refers to the reporting structure. Starting at the very top, note the great, grey pyramid radiating downward from the CEO position. The CEO *sees* all data and their Executive Information System software ensures that they have complete visibility of all data because their *role* as Chief, demands it. So their role-based visibility is 100% wide in scope. Others in the hierarchy have different visibility of, and responsibility for, more restricted domains. Not all the roles are scoped out on this Figure. You can see what the others would be by simply tracing the functional responsibilities up to each successive level of reporting. Such *role-based* visibility is easily effected in enterprise software.    

#### When ERP fails

What happens when organisations can't make the necessary adjustments to their business processes to allow the ERP to run their business? There are several high profile cases. In the Canadian context, the biggest splash was made in 2001 when grocery giant Sobey's has a very public spat with SAP over a database failure (Sobey's was using IBM's DB2 software as their enterprise database system) [Interested?](http://www.computerdealernews.com/news/sobeys-fires-sap-over-erp-debacle/22906) and [Interested in a slightly different perspective?](http://www.itworldcanada.com/article/sobeys-says-goodbye-sap/29540). But they apparently kissed and made up, as Sobey's implemented an SAP system a few years later. [Interested?](http://www.itbusiness.ca/news/sobeys-gives-sap-a-second-chance/10471)

In 2008, Mountain States Entertainment made the news for a big ERP flop [Interested?](http://www.erpsoftwareblog.com/2011/01/erp-implementation-failure-you-be-the-jury-part-1/), and in 2004 Marin County California's failed implementation led to a lawsuit against Deloitte [Interested?](http://www.computerworlduk.com/news/it-business/20575/deloitte-sued-over-failed-erp-project/).  A more academic treatment is found in a Harvard business case written by A. McAfee, entitled *Rich-Con Steel*, (Harvard Business School Case 9-699-133, HBS Press, January 27, 1999).

But the knife cuts both ways. ERP business process is based on best practices (extensive research, testing and proof from the field that the ERP-recommended way to do business is the most efficient and effective way). The opportunity for an organisation to actually stop and look at its processes – which may have grown up over years in a patchwork quilt of expediency and become inefficient and redundant – is an amazing opportunity. 

###Is your IT operating at two speeds?

Is this in the right place? It could go several places in the text. 

"It’s hard — perhaps impossible — to undergo a digital transformation with a legacy IT architecture. While the integrity of transaction-focused systems with sensitive data must be protected, IT needs to build out a separate system that can provide nimble customer-facing capabilities. New apps and databases can then be added as needed without touching the underlying systems that run the rest of the business. This second high-speed system supports agile development and prototyping, with weekly or even daily releases and an experimental “fail faster” mind-set.

"In developing high-speed systems, digital leaders put in place the analytics and intelligence needed to provide near-real-time insights into customer needs and behaviors, which then determine the personalized messages and offers delivered to individual customers. Being digital involves establishing a cyclical dynamic in which processes and capabilities are constantly evolving in response to inputs from the customer. Supporting this give-and-take process across multiple platforms at scale requires extensive automation."

http://www.mckinsey.com/business-functions/organization/our-insights/nine-questions-to-help-you-get-your-digital-transformation-right

(TK) The hybrid cloud: http://searchcloudcomputing.techtarget.com/definition/hybrid-cloud

###Shadow IT, BYOD and cloud computing

An Information Week [article](http://www.informationweek.com/strategic-cio/it-strategy/shadow-it-8-ways-to-cope/d/d-id/1319535) on Shadow IT begins this way: 

>"f your employees and business departments are bypassing internal IT resources to acquire their own systems, software, and other technologies without your explicit permission, take heart: You are not alone.

>For many organizations, so-called Shadow IT grew out of pure necessity, as increasingly tech-savvy employees sought out their own solutions to specific
line-of-business problems."

Here's how Wikipedia defines Shadow IT:

>"Shadow IT is a term often used to describe information-technology systems and solutions built and used inside organizations without explicit organizational approval. It is also used, along with the term "Stealth IT", to describe solutions specified and deployed by departments other than the IT department.

>Shadow IT is considered by many an important source for innovation and such systems may turn out to be prototypes for future approved IT solutions. On the other hand, shadow IT solutions are not often in line with the organization's requirements for control, documentation, security, reliability, etc., although these issues can apply equally to authorized IT solutions."

[Interested?](https://en.wikipedia.org/wiki/Shadow_IT)

BYOD (Bring Your Own Device) id often credited with being the start of Shadow IT. BYOD was and is a strategy popular in organisations both large and small whereby employees brought their own, personal computing devices and smart tech to work, and the organisation supported their use of it to access and create data on the corporate network. Most IT organisations aren't nimble enough the handle the rapid pace of change in technology - see Governance in Chapter 4 Backstory - <a class="underlined-link" href="Ch04_Basics.md\#governance" target="_blank">(take me there)</a>. Coupled with cloud computing and the wide range of *as-a-service* services available (such as *Software-as-a-Service* (SaaS) and *Platform-as-a-Service* (PaaS). 

Cloud computing has allowed and supported the connection of almost any kind of device to remote resources for storage, computing and transmission of data. You are probably using a cloud email service, examples of which are Hotmail, Gmail, Outlook web access and even Cmail - which is Outlook web access from Microsoft. 
---
layout: page
title: "For your eyes only...?"
category: managing-data
date: 0000-03-03 13:20:10
---

##Who can access the data?

The person ultimately responsible for the data will need to have both physical and digital control over the data. Physical access control means having control over the documents, computers, servers and working areas where data is kept. On the digital side, check that are you doing all you reasonably can to secure your data - for example, using strong passwords, encrypted connectons, VPN, logging, two factor authentication etc.

To work out what kinds of permissions and controls others in your team might need, mapping the types of users and what kind of access they will need is a useful exercise to undertake early in project planning.

>CASE STUDY: “Human Trojans”

>Many NGOs work on areas that involve high stakes and powerful interests, such as when it comes to operations in natural resource issues (oil, diamonds, gas). This often involves collecting information on the ground in countries where those resources are extracted (sourced from governments, companies, local people) and then transferring this information to an international office in another country – often in the Global North – for analysis and reporting. In this case, it was a company that was adversely affected by one of the NGO’s reports that started wondering about the source of leaks that caused negative information about their practices to end up in the NGO reports. It then hired private intelligence services to specifically find ways to get people working at the international offices on their payroll. This time, the attempt to infiltrate the international office to locate the sources was unsuccessful since some of the targeted employee reported it. The assumed intention of the attempt was to locate embarrassing information on the NGO to use as leverage, potentially embarrass their donors, bug their offices and place trojans on their computers.

>Lessons:

> * Human beings are the biggest risk
> * Provide access to information on a need-to-know basis only
> * Even if local operations are secure, complacency in international offices may increase vulnerability

>Mitigation:

>* Strong vetting of staff is crucial
>* Conduct and continuously update a threat assessment, especially when new data is released
>* Understand your potential adversary
>* Think also about physical access control of offices

##Setting permissions

A general security principle is to **limit user access to only the minimum amount of data** that they need to be able to do their work effectively - and **only have access for as long as they need it**. This ensures the privacy of people who have had their data stored by your organisation, and also reduces the potential impact of security incidents such as a data breach or data loss. Put otherwise: if only very few people have access to the whole database, then there is less chance of them accidentally deleting all of it.

People should also **only have the minimum permissions that they need to do their job**. To do this, you must identify the broad categories of users and what information they will need to work with. For example, a role such as a remote medical clinic worker on a short term project might only need to access data relevant to the area they are travelling in for a few weeks of their deployment. This means they only need to have access to office files and IT systems which are relevant to that specific area. However, someone working as a country researcher tasked with identifying trends across the country might need access permissions to all of the data in the country for a longer period. Although it might be less work for you to simply give out the widest possible permissions to people, to avoid them having to come back to you and hve them adjusted.  The easy route is not always the most sensible, and doing so could create a lot more work for you in the future.

Access permission also includes items like auditing and controlling who can manipulate, manage and delete data. The person with responsibility for managing and creating access should schedule regular times to audit the users types and remove people who no longer need access - for example, temporary workers such as contractors and interns. Unfortunately this is particularly important for potentially digruntled staff such as workers who are fired - a number of examples exist of people using their old job credentials to illegally access data at their previous roles.

Example of access control and permissions:



HUMAN RESOURCES: Bear in mind that if you are introducing people to a new set of tools or methods for accessing the data, they will likely require ongoing training sessions and follow up.  

>CASE STUDY: “Donor Data Danger”

>In a project involving sensitive human rights work, two of the donors involved insisted collecting a huge amount of data on operations, including names of people involved and receipts for all activities. Within three months of the project, however, both of those donors discovered inside threats. In each case, some of their employees had become disgruntled with their working conditions and subsequently left the organisations, taking with them a large amount of data – not only on one project, but all the NGOs and individuals the donor had been working with and/or had funded. In some instances, this information was even channelled to the country’s intelligence services directly or indirectly, exposing a large number of people to high risk (including employees, sources, beneficiaries, as well as their connections and networks). At the high point of this crisis, even the regional director of one of those donors said we should stop passing sensitive information to his employees, as he couldn't trust those in the organisation. While it is impossible to prove causality, a considerable increase in attacks and disruption of those NGOs’ work that had linkages with those particular donors was reported.

>Lessons:

* Be aware and prepared to actively disagree with your stakeholders, even if they are your funders
* International actors can be just as much a threat as anybody else – secure your info from the bottom up, but also all the way up
* Don’t think because an organisation has an international reputation, they are automatically responsible data holders – in the end, you will be responsible for your data and the people it reflects!
* Encourage a culture of responsible access controls and permissions, not just within your organisation, but also in organisations you share your data with.

##Collaboration

Controlling access effectively means selecting the right choice of methods and tools which balance the need to keep information secure, and also allowing effective collaboration in the field. A number of things which need to be considered in this area include:

* **Types of data** that people are collecting, and where they are putting it.
* **Tool choice:** suitability, usability, support, updates, cost, local vs network, network vs online access, mobile vs desktop, open source vs proprietry.
* **Levels of verification for the data:** how many people should be looking at and checking the data?
* **Speed of internet connections for users accessing data:** eg. if users are collecting data on their mobile devices in the field, the mechanism chosen for collaboration will need to be able to cope with receiving from such devices. Depending on phone signal, this may mean collecting and sending video from remote locations is not possible. This should be thought about **prior** to committing to any technical infrastructure.  
* **Access points:** Collaboration often requires remote access which can occasionally decrease security, as it opens up a number of less easily secured access points to a network. As such, tools and methods such as forcing regular password changes, two factor authentication, network logging, VPN only access, etc. are important to help mitigate such risks. (see: Security Resources)
* **Layered access:** Having appropriate access permissions is pivotal to ensuring that strategies for separating information will work. Note that it can also be an option to only allow access when several people co-sign, that is, certain data is only accessible when more than one person unlocks it.

##But don't overdo it!

It's important to make sure that there are rigorous controls on how data is accessed, but you don't want to lock it up so tight that you are unable to access the data when needed. In fact, projects should take active steps to make sure that the data can be accessed by the right people at the right times. Below are some concrete steps to take that will ensure data integrity, while also making sure that it's available only for the right people at the right time.

* Backing up your data: regularly back up your files, and test these procedures on a regular basis.

* Building **redundant systems** in case of failure: For example, it can happen that hard drives or essential equipment can completely fail without warning. Without redundancy like alternate data servers, this can completely disrupt your operations.

* Building architecture with extra capacity: data collection can be disrupted when space runs out on storage or collection platforms. You should try to ensure any system you have can be easily and cheaply expansible.

* Emergency situations: unexpected interruptions like natural disasters or internet shut downs can interupt data collection and transmission. Having a plan for such occurrences (for example, to shift to satellite links) can minimize the damage such interruptions may cause.

* Targeted disruption: sometimes someone, or something, may target your data specifically.  Ideally, threats such as this will be identified in a risk assessment, allowing you to build extra capacity into your architecture to deal with such problems. If hosting on your own, fighting against malicious attacks (such as Deliberate Denial of Service) can be very expensive. However, services exist which specialise in absorbing such attacks and using these is recommended best practice - such as Deflect (https://deflect.ca/) and the commercial provider Cloudflare (https://www.cloudflare.com)

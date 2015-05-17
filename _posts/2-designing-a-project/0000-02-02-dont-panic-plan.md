---
layout: page
title: "Don't panic, plan: assessing risks and threats"
category: "designing-a-project"
published: true
---


When working with data, there are many things that can go wrong, but that does not mean they actually will, or that the consequences will be catastrophic. Taking the time to do a risk assessment can save you a lot of time, and save you from future panics! It will help you identify what is likely and what is consequential, and thereby come up with a rational response. By carrying out a risk assessment, you'll preemptively come up with a number of preventative measures, as well as a back up plan to limit potential harm.

This section focuses on risk assessment practices specifically with regards to data, beyond digital and physical security risks, to include questions about the social impacts of data collection and publication, or how data can be reused towards objectionable ends. This does not, however, remove the need for a risk assessment to also be conducted for the entire environment of the project as part of standard planning.

##Threat Modelling

Threat modelling is a type of risk assessment and part of a broader risk assessment framework. It is a useful process to help uncover specific threats to existing assets. To conduct a threat modelling exercise, discuss the following issues and identify how they manifest themselves for your project. (See the matrix template below these definitions).

###Assets

These are the types of data that the project will create or use (for examples of different types of data, see the introductory chapter, **Are you Working With Data?**). What data is being created? Where does the data exist and how do you interact with it? Map the types of data and the data flow. Does the data fall into clusters, such as public, internal, or confidential? If so, this already gives you a clue that different procedures may be needed for different types of data. (See section: The Sharing Spectrum)

###Risks

These are the vulnerabilities identified in the data flow, including access, sharing, storage and management of the various types of data.

###Adversaries

There are individuals and groups that may be interested in making the threats to your assets a reality. In other terms, they are the ones who you are up against. *Research their capabilities*, but don't let fear take over: when you know who they are, you will already have a clear idea of what you can do to stop malicious action. Also, do not forget that "adversaries" may be internal: the disgruntled former employee who goes rogue, or the lazy systems administrator who forgets to do the backup.

###Threats

These are potential risks to your assets, to people or to the project. Threats to data assets can often be grouped into three generic categories: (a) loss, (b) illegitimate access, (c) manipulation. Threats to people can be sorted according to: (a) direct harm and (b) social effects. Threats to the project generally have to do with (a) sustainability and efficiency or (b) reputations and relationships. These generic categories can be made a lot more concrete for your given project, so use them as a guide, not an exhaustive list. Map out potential threats, paying specific attention to who or what you are working with. Remember that not all threats have adversaries or malicious intent.

###Likelihood

What are the chances that the above threats become real? Put differently, what is more probable to happen: an unidentified hacker who breaks into your highly secured systems only to prove a point, or you forgetting to budget for data hosting after the end of the project period?

###Mitigation Strategy

Responsible data practices also require safety planning. This identifies actions you can take to address the threats. Questions that may help formulate your plan include:

What risks can be eliminated entirely and how?
Based on their likelihood and significance, which risks should be addressed first?
How can risks be reduced or better managed?
It is assumed that practitioners and managers won’t be able to address all threats at once. They should be prepared to schedule work on project risk assessment and safety planning, alongside project design, implementation, and monitoring and evaluation activities.

The threat model can be organized into a matrix such as this:

![]({{site.baseurl}}/assets/2.3.threat-modeling.png)

Writing these out, and thinking them through at the very start will help you to consider whether you have the resources you need to prevent the most probable risks, as well as the most consequential threats. It also helps you to work out your priorities and how you can meet the most urgent tasks, while being aware of disaster scenarios that might be catastrophic, but are less likely to occur.

Feed your findings back into your project lifecycle diagram. Does this leave any critical gaps? Do you need additional resources? Should you reconsider the project in its entirety? Asking these questions will help you focus on finding the right responses.

Clearly, you can't 'prioritise' or focus on every single scenario here: each organisation will have its own sense of whether it makes sense to focus on the more probable and less disastrous scenarios, or the less likely but potentially catastrophic ones. It may also help to develop a strategy for weighing different scenarios and allocating organizational resources accordingly. Either way, being aware of the spectrum of risks can help to arrive at a position and strategy that is tailored to your project's particular context.

Some risks are more avoidable than others. Data loss is a common and highly avoidable harm. Regular systems for back up are both accessible and affordable, and represents a type of basic data awareness that projects should review even in low-threat environments.

##Contingency planning

Prevention is only half of what you can do. There will always be residual risk and threats you cannot foresee. This is why it is important to prepare for incidents to happen, so you can contain them or mitigate their impact.

- Talk through the different kinds of risks, and make sure there is a clear, step-by-step plan of action to highlight incidents to the relevant people within the organisation if or when they happen.
- Encourage a culture of openness and learning from mistakes, not blame; reporting incidents within your project team should be seen as a positive, not a negative.
- Stress that the consequences of covering up or hiding in-house mistakes will always be much more serious than coming clean: mistakes happen, and it's good to learn from them.
- Keep a list of people to call in times of emergency in areas in which you lack internal expertise - for example, lawyers, crisis communications, data forensics. Building those connections before you really need them will save you time if/when a crisis hits.
- For all projects, have an emergency plan of action to prepare for immediate shutdown or project termination.

##External Providers

Relying on external providers is often a necessity. It may actually be desirable to work with someone who is an expert in what they are doing, rather than spending your time on learning something that is hard to master and is outside of your core skills. However, ask yourself to what extent you can trust them, what mechanisms are available to you to verify this trust, and what you need to know to evaluate what they are doing. If you're hiring external consultants to work directly with vulnerable populations to collect data, for example, make sure they come with strong references, or from within your trusted network. Consider the option of independent audits or external references from organisations that you do trust, too, as well as the role of such providers over time, and establish safety mechanisms in case they become unavailable or their position or reliability changes.

##Holistic Security

This is a way of thinking of all of the various security threats or risks that are faced: digital information security, physical and operational security, and psycho-social well being required for good security implementation. All three of these should be considered within technology projects, not just digital security, and there are many strong tools and support organisations who can help conduct security assessments - see Further Resources for a list of organisations working in this space. On the topic of holistic security, Tactical Technology Collective have put together a note with further discussion- https://tacticaltech.org/holistic-security.

---
layout: page
title: "Legal Considerations"
category: managing-data
---

All steps of the data lifecycle are subject to legal requirements, and managing  data securely requires understanding and meeting these requirements adequately. It's better to be proactively aware of the legal restrictions on your work, than to realise after the fact that you've been breaking the law and face monetary fines as a consequence, or that you can't legally do what you were planning to do. With the growth of cheap cloud computing (ie. data stored on servers not owned by your organisation), it is often difficult to know exactly where your digital data is being held. Popular providers of email and storage such as Google, Amazon, Facebook, Yahoo, DropBox, GitHub make use of infrastructure spread across a number of international sites. For example, Google stores data in the US, Ireland, Belgium, Finland, Chile, Taiwan and Singapore; so, which country's laws affect your data? It's not always easy, but you need to understand the legal ramifications of where you store your data.

##What types of laws and procedures apply to your data project?

###Jurisdiction

It can be challenging to understand how management of your data is affected by the laws of the countries in which the data is stored. Some common grounds for jurisdiction include:

* The countries where your organization is registered
* The countries where your organization operates
* The countries where your data is stored (for cloud storage, this can quickly become complicated and involve multiple countries)
* The countries where your users, participants or subjects are

Sometimes the terms of service or specific policies will determine which law applies, but often not, and other jurisdictional claims can supercede these. As a point of departure, it's worth assuming that all of these jurisdictions apply. Talk to your technical and legal team to determine which don't.

###Data protection laws

A number of countries have strong data protection laws which place limits on the types of data which may be collected from individuals. They also often include specific legal requirements about the methods used to store such data, along with mandatory reporting and monetary fines for breaches. Individuals about whom data is stored are often granted a number of rights, such as access to their information and the right to have their data correction and/or removed.

For an overview of data protection laws in different countries, you can browse http://www.forrestertools.com/heatmap/ and http://www.dlapiperdataprotection.com/#handbook/world-map-section.

It might require some careful thinking, but granting people rights to access data in which they are reflected is crucial, especially for organisations which collect sensitive data, such as witnesses of human rights violations and perperators.

>CASE STUDY: Data protection laws
>
>Organization X was a human rights organisation in sub-Saharan Africa collecting and publishing data about human rights abuses by the local government. The government was embarrassed by this and wanted to stop the organisation from functioning effectively. Rather than attack the organisation physically, which they knew would draw international attention, they decided to disrupt its work by tying them up in nefarious legal cases. For example, the organsation was severely punished for poorly protecting data, minor health and safety violations, and accounting malpractices. While the cases were all eventually thrown out, this caused harmful disruptions to the organisation's work and caused them to spend their limited resources on lawyers' fees. Adhering to relevant data protection laws may not prevent this kind of legal tactic to be used against you, especially if the law-makers are targeting you specifically, but it may limit their techniques.

###Encryption technology laws

Local laws in a number of countries (such as Sudan, Yemen and Pakistan) place limits upon the nature of encryption software allowed for the communication and storage of data. System architecture and tool choice must incorporate these concerns. Other laws which effect the use of encryption include:

* mandatory handing over of encrypted data if requested by government authorities
* mandatory metadata collection by specific industries, eg. telecommunications (and potentially their subsequent sharing with government authorities)
* laws requiring the weakening of encryption software, such as programmes for export: some countries (eg. Pakistan) won't allow the use of programmes which contain certain levels of encryption. Other countries (like the US) try to control the distribution of programmes with high-strength cryptographic controls - this originated from countries not wanting to share their
* high-strength cryptographic software with potential adversaries.
* those which require individuals to disclose their passwords (such as the UK) upon government request.
NGO registration laws

An increasing trend in many countries has been the introduction of strong laws which regulate the presence, funding and/or activities of NGOs in their countries (for example, Russia, Ethiopia, Egypt, Hungary, Kenya and South Sudan). Projects initiated in the country must consider these when building data management infrastructure, and when thinking about different country presences.

###Jurisdictional issues

Organisations should be aware of laws that would give governments access to information stored on servers hosted in their countries. For example, Boston College was forced to give interview information (tapes) to the Police Service of Northern Ireland after they were subpoenaed. Cite: http://www.timeshighereducation.co.uk/features/oral-history-where-next-after-the-belfast-project/2013679.article

It is very difficult to protect digital information from subpoenas (for example, see this map on US extradition treaties http://qz.com/97428/map-how-to-stay-out-of-reach-of-us-extradition-treaties/) so it is important to adhere to a minimalist approach to collecting or storing sensitive digital data (or don't store it all) - see section on Getting Data.

Organisations must also be aware of cross-jurisdictional issues in relation to their data management. It is not unusual for data to be collected in a country office, transferred to a regional office in another country, then onwards to the organisation's headquarters in a third country. Also, some states or regional groups place strict conditions on where their citizens' data may be transfered to - for example, the EU/US Safe Harbour law.

###Copyright and Patent

Copyright and patent issues related to the collection, storage and dissemination of your data are important laws to consider. Ensuring you have the correct licensing for your projects and infrastucture can help reduce unexpected restrictions and costs further into your project. Open licencing such as Creative Commons options, and open source code such as MIT or BSD licences provide tested and off-the-shelf solutions for your data, and open the door to your peers being able to verify your data, or mixing it with other datasets that you might not have collected yourself, but which would strengthen your project. (See section: Disseminating Data for more information on licensing and advantages of open licensing)

###Procedures on presentation of evidence

If you intend on using your data in legal cases, you should understand the requirements used in court for the presenting of evidence. Approaches to digital data differ significantly in each jurisdiction. However, some standard basic requirements are that data management systems:

* Allow for an auditable chain of custody (ie. make it possible to know who has had access to the data at all times)
* Ensure the integrity and authenticity of the data. For example, a number of technical processes (such as hashing and forensic examination) allow a comparison between original and other versions. Authenticity can be enhanced through the collection of extra information such as metadata. However this must be balanced against the extra risk this may pose to collectors - as often it is not clearly understood by the people involved.
* Ensure that data is verifiable. The data content itself in many cases should be verifiable. For example, the massive growth of online video posted to sites such as Youtube, Vimeo and LiveLeak has driven the development of methodologies to verify what is shown in the footage - is it showing what it says it is showing?

##Further resources

NGO Law Monitor - http://www.icnl.org/research/monitor/
Maps of Data Protection Laws - http://www.forrestertools.com/heatmap/ & http://www.dlapiperdataprotection.com/#handbook/world-map-section
Choosing an Open Source Licence for Code - http://choosealicense.com
Creative Commons - https://creativecommons.org

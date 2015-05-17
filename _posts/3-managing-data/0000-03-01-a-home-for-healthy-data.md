---
layout: page
title: A home for healthy data
category: "managing-data"
published: true
---


![chapter-image]({{site.baseurl}}/assets/icons/icon-managing.png)

##Give your data a safe space

Data occupies physical space, even if in our imagination the bits and bytes are ephemeral. We store data on hard drives, and these drives have a physical presence, which brings a number of responsibility and privacy implications.

The most obvious issue to address is about data **access**: who can physically (or digitally) reach that hard drive and copy data from it, or simply take the drive away with them? Another one is **location**: there are many different places in which we can store our data. It can be on a laptop, on a USB stick, on a remote server in some other country, or even distributed throughout different geographic locations (interestingly, this is probably one of the most common cases). Location issues also bring with them **legal implications**, especially if we don't know in which country our data is being stored, and which laws govern digital property there.

This section provides an overview of approaches you can implement to ensure your information is stored, managed and accessed in a responsible, secure and protected manner. To begin with, it's worth reviewing the general principles of data integrity, and how to manage risks surrounding data storage.

##Data integrity

Data integrity is a term used to describe the validity, authenticity and security of information. It includes aspects of both information security and information quality, including how information systems and processes for sharing information are designed. As such, it has some overlap with confidentiality and availability, but is a useful frame of analysis for considering the interaction of technical and human influences on data responsibility.

* Is the data checked for changes at key points (upload, migration across servers, migration from data collection devices to the main server)?
* Are changes to the data flagged and are there mechanisms for version control?
* Are there granular permissions for making changes to the data during analysis?
* Is the data collection process well-documented? For example, through a codebook or other document that allows newcomers to the project to make sense of the data and understand the relationships between data structure, variables and the data collection process.
* Does the data include contextual information (potentially in metadata) that is necessary to understand the data?
* Are data collection notes (eg. on ambiguity, potential duplication, variations, or more contextual information such as notes made during personal interviews) provided together with the data in an accessible format, and the relationship between the two made clear?
* Are appropriate backup mechanisms in place in case of blackouts or system failures?
* Is the software used to manage and store the data fully up to date and licensed?
* Is the data interoperable? Can it be accessed by all the people and platforms that it needs to be? If people who might need to access the data don't have technical training, is the data available in common file formats (such as csv files)?
* Have you future-proofed your data by anticipating changes in institutional and contextual factors which could make the data difficult to access or use?

##Assessing and managing risks

A thorough discussion of risk assessments is included in the chapter on project design. When planning data storage, there are some specific risks and mitigation strategies that are worth considering.

Some data storage risks and harms:

* Loss of information (deliberate or accidental)
* Confiscation of information
* Data breach
* Legal threats
* Malicious attack

Some mitigation strategies:

* Speak to other organisations in your community who have conducted data projects successfully. Ask them about their storage practices.
* For bonus points, adapt or use standards for benchmarking your information security procedures, such as ISO 27001 or PCI DSS.
* Only store the minimal amount of data necessary to complete the task.
* De-identify data by default (though this approach has its limitations, see the chapter on anonymisation).
* Encrypt your data at all stages of its collection, usage, transmission and storage.
* Use secure tools (ideally open source tools which are more transparent) for communication (for a listing of secure tools, see https://www.prismbreak.org)
* Delete and destroy data safely when it has become insecure.
* Conduct regular audits and penetration tests of your security measures.
* Ensure your organisation is capable of managing and updating the system and tools on a long-term basis - as technology becomes outdated and easier to breach

For more information on protecting your information in a physical space, see Tactical Tech's Security in a Box chapter on this topic https://securityinabox.org/chapter-2

##Separate storage for sensitive data

You can store some information separately from the rest. For example, if you have a database with case files, you can replace the names with codes and create a spreadsheet with the codes and their resolution to real names. You can then store this spreadsheet on another, highly-protected computer. This method alone will in most cases not lead to true anonymisation because the case files are easily linkable to real persons.

>CASE STUDY: Hacked and then fined!

>In 2014, the UK Information Commissioner's Office (ICO) imposed a £200,000 fine on a charity called the British Pregnancy Advisory Service. The organisation's website had been hacked by an anti-abortion activist who threatened to publish the names, addresses, dates of birth and telephone numbers of women using the service. The ICO determined that considering the sensitivity and risk of the information, the website did not have adequate security and left a vulnerability which could be exploited by the attacker. The organisation also breached the Data Protection Act by keeping data on callers for five years longer than was necessary.
Reference:
"Abortion service to appeal against £200,000 fine over hacked website" http://www.theguardian.com/world/2014/mar/07/abortion-service-website-hacker-information-commissioner-fine

##Further resources

* The Frontline SMS Users' Guide to Data Integrity http://www.frontlinesms.com/wp-content/uploads/2011/08/frontlinesms_userguide.pdf
* Deflect https://deflect.ca/
* Cloudflare https://www.cloudflare.com
* For a listing of secure tools, see https://www.prismbreak.org

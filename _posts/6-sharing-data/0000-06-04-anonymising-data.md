---
layout: page
title: "Anonymising data"
category: sharing-data
---
Data can have real consequences for real people, and often these consequences are as unintended as they are harmful. This is regularly the case when Personally Identifiable Information (PII) is published, or when seemingly innocuous data is mashed and collated with other data sets. This is why it is very important to try and anonymise information before publishing in any way at all.  However, there are many cases where efforts to anonymise have also failed.

At the end of the day, there might be no such thing as perfect anonymisation. Removing all personally identifiable information from a data set isn't necessarily enough to protect identities in that data set. With the increasing sophistication of analytical techniques and algorithms, "de-identified" data sets can be combined with other supposedly anonymous data to re-identify individuals and the data associated with them. This phenomenon, known as the Mosaic Effect, is particularly challenging because evaluating the risk of it occuring requires one to anticipate all the different types of data that exist or may be produced, and which could be combined with that data set, which simply isn't possible.

As such, this chapter will talk about strategies for de-identification, because that word doesn't have the "magic bullet" feeling that is often associated with anonymisation, and because the word itself implies that it can be undone.

It's also important to underscore that de-identification is a complicated and imperfect science. This chapter aims to help you navigate different techniques, but be careful: Don't take decisions on publishing lightly, seek expert advice, and err on the side of caution.

Once the data is published, there is no turning back.

##What data should be de-identified?

The short answer is, any and all data that has any potential to identify a person  But it is still important to conduct a thorough risk assessment of the possible consequences of data release during project design and update it before release. Once the data is out, it's too late. Consider the following:

* Can an individual be identified from the data, or, from the data and other relatively accessible information?
* Does the data ‘relate to’ the identifiable individual, whether in personal or family life, business or profession?
* Is the data ‘obviously about’ a particular individual?
* Is the data ‘linked to’ an individual so that it provides particular information about them?
* Is the data used, or is it to be used, to inform or influence actions or decisions affecting an identifiable individual?
* Does the data have any biographical significance in relation to the individual?
* Does the data focus or concentrate on the individual as its central theme rather than on some object, transaction or event?
* Does the data impact or have the potential to impact on an individual, whether in a personal, family, business or professional capacity?

If the answer is "yes" or even "maybe" to any of these, you need to anonymize!

##Common types of personally identifiable data

Information that at first glance seems not-identifiable may become so, especially when combined with other data and subjected to powerful algorithmic analysis. This list gives examples, but is nowhere near comprehensive. Do evaluate for your context.

* Age
* Ethnicity
* Gender
* District/County
* Highest Level of Education
* Medications prescribed
* Geo-location of login

##Thinking about risk

Once you have done your data sensitivity assessment, you need to do a risk assessment of the context. This gives you an idea of how dangerous the data could be for the data subjects if it got out, and how much danger there is for that.  Some of the things you should think about are:

* What might be the consequences be for individuals or groups in the de-identified data if it is reversed?
* What people or groups may have an interest in trying to re-identify your data? (Intelligence agencies, hackers, curious data scientists etc.)
* What other data sets are available that may result in re-identifying the data you are releasing?
* What is your release strategy for your data? (For example, how is it being released to media? Is it possible that they may accidentally/deliberately add identifiable data?)
* What technical and version control methods are you going to use? (For example, to ensure you release the correct anonymised version of your data)

###Anonymisation Techniques

These are some techniques that help in anonymising data, once the process above has yielded that it may be advisable to to do so. For more detailed descriptions of these techniques, their limitations and in which contexts they are most appropriate, see the anonymisation guide produced by the UK Information Commissioner's Office (http://ico.org.uk/~/media/documents/library/Data_Protection/Practical_application/anonymisation-codev2.pdf).

* Data masking: This describes supplying only part of a data set (e.g.. taking out columns from a spreadsheet) or deleting these parts from the data set completely.
* Pseudonimisation: This describes the exchange of values for codes - this way, for example a name might be replaced with a number, but the same number will show up in every instance where the name was.
* Aggregation: Instead of providing the raw data, this would aggregate especially small amounts of information; rounding large numbers, or providing only small samples of larger data sets.
* Derived data: This describes a process where the original intent is kept, but the output changed. An example would be to provide the age of a person instead of the exact date of birth.

>CASE STUDY: New York Taxis

>In 2014, New York City released data under a Freedom of Information Request on 192 million taxi trips and fares made the year before. It held data on items such as pickup and drop off points. This potentially had a lot of useful research benefits, such as city planning. It also contained personally identifiable information about the name of the driver, taxi license and taxi plate number - this information was supposed to be anonymised. However, this anonymisation was very soon worked around, leading to a lot of intimate information being available online, about both drivers and passengers.

>While an effort had been made to hide these pieces of information using a method known as “hashing,” it was undermined by a poor understanding of how it works. For example, due to the fact that taxi license numbers are assigned using a specific six or seven digit method, the anonymising method was weakened because it was limited to only three million possible combinations. It then took only minutes using a modern computer to reverse the anonymising method and reveal taxi license numbers. Due to the fact that the NYC Taxi and Limousine commission also provides data linking real names to taxi license numbers, researchers could get to the name of the driver.

>The result was that it was possible to figure out who was the driver of nearly every one of the 192 million journeys. From this it was possible to determine how much money each driver made, where they lived, the dates and times when they were working and in what areas they worked. In some cases, it was also possible to infer journeys made by members of the public, in particular celebrities, or visitors of strip clubs.

>Sources:
On Taxis and Rainbows: Lessons from NYC’s improperly anonymized taxi logs
https://medium.com/@vijayp/of-taxis-and-rainbows-f6bc289679a1
NYC Taxi Data Blunder Reveals Which Celebs Don't Tip—And Who Frequents Strip Clubs
http://www.fastcompany.com/3036573/fast-feed/nyc-taxi-data-blunder-reveals-which-celebs-dont-tip-and-who-frequents-strip-clubs

##Get Help

It can be helpful during this process to create an expert group of advisors who have experience with your project and with releasing data in a safe manner. Ideally some of these people will be outsiders, with a good knowledge of the areas in which you work but without potentially biased connections to the project. The overall objective of such a pre-release review is to review all possible negative scenarios that might occur because of the data.

Judging by many previous failures, it makes sense to also seek advice from people who have skills relevant to de-anonymising and de-identification, such as data scientists, open data experts and ethical hackers. Pre-release reviews should also include increasing your protection methods in light of the potential increase in attention you may be subject to afterwards. For example, if original data sets are still not secured properly (physically or digitally), now is the time to ensure you do this. After release, you may find it becomes harder to do this, especially if adversaries are technically adept.

##Further Resources

* The UK Anonymisation Network provides consultation and training for NGOs.
* Anonymisation guide produced by the UK Information Commissioner's Office (https://ico.org.uk/media/1061/anonymisation-code.pdf).

#Vision Statement
##Table of contents
- [Introduction](#Introduction)
- [Positioning](#Positioning)
- [Stakeholder and User Descriptions](#Stakeholder_and_User_Descriptions)
- [Product Overview](#Product_Overview)
- [Product Features](# Product_Features)
- [Other Product Requirements](#Other_Product_Requirements)

<a name="Introduction"/>
##Introduction
The purpose of this document is to collect, analyze and define high-level needs and features of the Exceed vote application.
###Definitions, Acronyms and Abbreviations
See [Glossary](Glossary.md)
###References
None.

<a name="Positioning"/>
##Positioning
| | |
|:------------- |:---------------------------------- |
| The problem of | Users are uncomfortable and not cheatable |
| Affects | People who join the eXceed camp |
| The impact of which is | The old method is unreliability, slowly, uncomfortable and unsecure  |
| A successful solution would | Support more users, access the appication easily and be more simple |

###Product Position Statement
| | |
|:------------- |:---------------------------------- |
| For | Kasetsart University students, professors |
| Who | SKE and CPE students and professors who join this camp |
| The Exceed camp vote System | Is a tool |
| That | Enables online voting and access the information each teams |
| Unlike | The old method is  out-of-date |
| Our product | Provides the real time result, online voting and update the information of your team |

<a name="Stakeholder_and_User_Descriptions"/>
##Stakeholder and User Descriptions
- This section describes the users of Exceed camp vote system. There are 3 types of user of the Exceed-Vote System; the Organizers, the Participants, and Guests.

###Stakeholder Summary
| | | |
|:------------- |:---------------------------------- |:---------------------------------- |
| Name | Description | Responsibilities |
| Organizer | Staff of the Exceed camp | Manage and monitor vote system, an attend on presentation of each group and vote for them |
| Participant | Student | Create or join group, Do and present project, and vote for other group |
| Guest | Anybody else who join the Exceed camp | Attend on presentation of each group and vote for them |


###User Summary
| | | | |
|:------------- |:---------------------------------- |:---------------------------------- |:---------------------------------- |
| Name | Description | Responsibilities | Stakeholder |
| Participant | Student | Create or join group, Do and present project, and vote for other group | self-represented |
|Guest | Anybody else who join the Exceed camp | Attend on presentation of each group and vote for them | self-represented |


###User Environment
- lidividual will regis to vote system. After that their duty is to visit all group and verify themself to each group to have a permission to vote for that group. Verify method is to exchange QR Code or PIN with that group.
- Users will be expected to have a browser-enabled device for viewing content. If they have devices capable of viewing video or audio clips, this content will also be available to the user.
- Paticipant will be expected to have a browser-enabled device for manage their own team page.
- Organizer will require a browser-enabled device for manage system and viewing system status.


###Key Stakeholder or User Needs
| Need | Priority | Concerns | Current Solution | Proposed Solutions |
| ------- | ------ | ---------------| ------------------ | ------------------ |


###Alternatives and Competition

<a name="Product_Overview"/>
##Product Overview
###Product Perspective
###Assumptions and Dependencies
- It is assumed that the server support Play framework (Java)

<a name="Product_Features"/>
##Product Features
This section defines and describes the features of the Exceed camp vote system.

###Register
User have to regis by use student code.

###Login
The system allow user who regised.

###Achievement
The system shows the teams which user voted. 

###Check point
The system confirm that user visited that team by using QR code or PIN. They have to exchange each other.   

###Voting
The system record user's vote. User can change your votes by voting again.

###Result of voting
The sysem allow user who is admin only to access the result.

###Description
The system allow user who is member of that team can edit team's description.

<a name="Other_Product_Requirements"/>
##Other Product Requirements
###Usability
- Have tutorial for user.

###Reliability
- Backup data every 10 second.

###Performance
- Can supports more than 100+ users in the same time.
- Can use in local server.

###Supportability
- Data will be remain when camp ended.
- Application can use in other year after camp ended.
- Have two languages: Thai and English.



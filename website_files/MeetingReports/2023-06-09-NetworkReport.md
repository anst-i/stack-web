# 2nd STACK Network meeting report, June 2023

The 2nd STACK Network meeting took place on the 9th of June 2023 online. The purpose of the meeting was to discuss that issues that raised during the recent International meeting of the STACK Community (April 2023). It was also a good opportunity to welcome new members.

## Topics Discussed:

**New STACK Release:**
Chris presented the new STACK release, STACK 4.4.3, and demonstrated its new features. The key features of this release included improved cleaning of Unicode from students' input strings, descriptions to the question (castext), the PRT nodes, and the question tests. Additionally, an input extra option [validator](https://docs.stack-assessment.org/en/CAS/Validator/) was introduced to allow user-defined validation functions. A new [reveal block](https://docs.stack-assessment.org/en/Authoring/Question_blocks/Dynamic_blocks/#reveal-block) in questions was also added. It was emphasized that users should check their existing questions after updating to STACK 4.4.3, especially in relation to the changes in JSX graphs. Further details about the new features can be found in the documentation provided at [https://docs.stack-assessment.org/en/Developer/Development_history/](https://docs.stack-assessment.org/en/Developer/Development_history/).


**Bulk Testing for STACK Update:**
It was recommended that everyone who is updating to the new STACK version should perform bulk testing of their questions. However, not everyone has admin privileges on their local servers, making it necessary to seek assistance from the local IT team. To support colleagues who lacked admin privileges, Maciej volunteered to write guidelines for testing quizzes, which will be shared with the team.
Note, for moodle users there is a capability `qtype/stack:usediagnostictools`.  If you don't have admin rights at your university you can make a case for a group of STACK users to be granted this capability, which is needed for the bulk test, and other STACK maintenance functions.

**API, Managing Questions Outside Moodle:**
The meeting included a discussion on exploring API options for managing questions outside Moodle. While the topic proved to be highly technical, it generated interest among some participants. Santiago expressed willingness to assist in putting together a funding application if there is genuine interest from the team. It was proposed to organize a dedicated meeting specifically focused on this topic to ensure a detailed discussion with interested members.
_Update on 2023-07-07:_ Tim and Andreas made a start with this new Moodle tool: [https://github.com/maths/moodle-qbank_importasversion](https://github.com/maths/moodle-qbank_importasversion) which allows you to import a question from a Moodle XML file as a new version of an existing question.

**Github training**
All of the STACK sourcecode, documentation and the community website can be found in the Github repository [https://github.com/maths](https://github.com/maths). However, since not everyone is familiar with using Github, this can serve as a barrier for contributing to the documentation. To address this issue, we decided to organize a Github training. The aim of this training is to assist people in becoming more familiar with Github and to boost their confidence in contributing to the STACK website [https://stack-assessment.org/](https://stack-assessment.org/) (Github repository [https://github.com/maths/stack-web](https://github.com/maths/stack-web)) by adding case studies, advertising events, and updating documents.

**Funding Opportunities, Grant Opportunities:**
The possibility of securing funding for professional networks was discussed. A stream was created in Zulipchat to coordinate efforts in writing grant applications.

**Communications:**
Zulipchat was identified as the preferred communication platform for the organization, providing a centralized space for discussions and issue reporting. Github was emphasized as the primary platform for reporting code-related issues. [https://stack-assessment.zulipchat.com/](https://stack-assessment.zulipchat.com/#)

## Next Meetings:
Despite the approaching summer season, it was suggested to schedule another meeting in July and another in early September. This would ensure continued progress and provide opportunities for further discussions and updates.


## List of participants:

* Chris Sangwin - University of Edinburgh, UK
* Ruth Reynolds - University College London, UK
* Stephen Nulty - National University of Ireland Maynooth, Ireland
* Jonas Lache - HRW University of Applied Scieces, Germany
* Kim Kneher - DHBW Mannheim, Germany
* Marc Peterfi - DHBW Mannheim, Germany
* Steffi Zegowitz - TU Clausthal, Germany
* Andreas Steiger - ETH Zürich, Switzerland
* George Ionita -  ETH Zürich, Switzerland
* Kinga Sipos - Bern University, Switzerland
* Sam Fearn - Durham University, UK
* Maciej Matuszewski - Durham University, UK
* Santiago Borio - IDEMS International, UK
* Konstantina Zerva - University of Edinburgh, UK 
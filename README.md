# APPCorp: A Corpus for Android Privacy Policy Document Structure Analysis

## Introduction

we propose a novel task of categorizing the topical structures of privacy policies for Android Apps.

There are in total **231** privacy policies labelled, which consists of **7,748** natural paragraphs and **19,708** sentences.

With the above considerations, we consolidate the topic information (Sarne et al., 2019) summarized through unsupervised learning techniques, the GDPR regulations as well as and expert knowledge (which is mostly consistent with the labels in OPP-115 (Wilson et al., 2016)), and propose a label scheme with 11 labels. We introduce the details of our label scheme in the following:

1.  **Policy Introductory (PI):** The general descriptions of the privacy policy document, including definitions on the referential pronouns used in the document.
2.  **First Party Collection and Use (FPCU):** What, when and how the first party (the controller) collects, uses and processes the users’ information5 . [GDPR Art.13.1]
3.  **Cookies and Similar Technologies (CT):** How to collect and use the cookies and other similar technologies (e.g., beacons), and descriptions about those techniques.
4.  **Third Party Share and Collection (TPSC):** How the controller shares and discloses the information with third parties, which include corporate affiliates, service providers or advertising partners.
5.  **User Right and Control (URC):** The right of user, guaranteed by GDPR and the options which users have in order to control their personal information, such as the settings on users’ privacy and safety. For example GPDR requests that the data subject has the right to access, rectify and erase the data.[GDPR Art.13.2 (b-f)]
6.  **Data Security (DS):** The security facilities/methods that the controller implements to protect users’information. [GDPR Art.32.1]
7.  **Data Retention (DR):** Descriptions on the retention period about users’ information. [GDPR Art.13.2 (a)]
8.  **International Data Transfer (IDT):** Descriptions of how is the information stored and transferred internationally. [GDPR Art.13.1 (f)] 
9.  **Specific Audiences (SA):** Specific terms for specific audiences, e.g., children, or data subjects from a specific area/country, which usually has privacy protection laws in power. [GDPR Art.40.2 (g)]
10.  **Policy Change (PC):** Descriptions of changes of the privacy policy and how is the data subject notified if changes happen.
11.  **Policy Contact Information (PCI):** The contact information of the data controller (i.e., first party). [GDPR Art.13.1 (a)]


## References
[1] David Sarne,  Jonathan Schler,  Alon Singer,  Ayelet Sela,  and Ittai Bar Siman Tov.   2019.   Unsupervised topicextraction from privacy policies.  InCompanion Proceedings of The 2019 World Wide Web Conference, pages563–568.

[2] Shomir  Wilson,  Florian  Schaub,  Aswarth  Abhilash  Dara,  Frederick  Liu,  Sushain  Cherivirala,  Pedro  GiovanniLeon, Mads Schaarup Andersen, Sebastian Zimmeck, Kanthashree Mysore Sathyendra, N Cameron Russell,et al.  2016.  The creation and analysis of a website privacy policy corpus.  InProceedings of the 54th AnnualMeeting of the Association for Computational Linguistics (Volume 1: Long Papers), pages 1330–1340.
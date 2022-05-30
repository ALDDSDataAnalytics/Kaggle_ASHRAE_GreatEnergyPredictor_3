# Kaggle_ASHRAE_GreatEnergyPredictor_3

## Description

Q: How much does it cost to cool a skyscraper in the summer? A: A lot! And not just in dollars, but in environmental impact.  Thankfully, significant investments are being made to improve building efficiencies to reduce costs and emissions. The question is, are the improvements working? That’s where you come in. Under pay-for-performance financing, the building owner makes payments based on the difference between their real energy consumption and what they would have used without any retrofits. The latter values have to come from a model. Current methods of estimation are fragmented and do not scale well. Some assume a specific meter type or don’t work with different building types.  In this competition, you’ll develop accurate models of metered building energy usage in the following areas: chilled water, electric, hot water, and steam meters. The data comes from over 1,000 buildings over a three-year timeframe. With better estimates of these energy-saving investments, large scale investors and financial institutions will be more inclined to invest in this area to enable progress in building efficiencies.  About the Host   Founded in 1894, ASHRAE serves to advance the arts and sciences of heating, ventilation, air conditioning refrigeration and their allied fields. ASHRAE members represent building system design and industrial process professionals around the world. With over 54,000 members serving in 132 countries, ASHRAE supports research, standards writing, publishing and continuing education - shaping tomorrow’s built environment today.  Banner photo by Federico Beccari on Unsplash

## Evaluation 
Evaluation Metric
The evaluation metric for this competition is Root Mean Squared Logarithmic Error.

The RMSLE is calculated as

![A1](https://github.com/ALDDSDataAnalytics/Kaggle_ASHRAE_GreatEnergyPredictor_3/blob/main/Screenshots/A1.PNG)


Where:

 is the RMSLE value (score)
 is the total number of observations in the (public/private) data set,
 is your prediction of target, and
 is the actual target for .
 is the natural logarithm of 
Note that not all rows will necessarily be scored.

Notebook Submissions
You can make submissions directly from Kaggle Notebooks. By adding your teammates as collaborators on a notebook, you can share and edit code privately with them.

Submission File
For each id in the test set, you must predict the target variable. The file should contain a header and have the following format:

 id,meter_reading
 0,0
 1,0
 2,0
 etc.

## Prizes

1st place - $10,000
2nd place - $7,000
3rd place - $5,000
4th place - $2,000
5th place - $1,000

Because this competition is being hosted in coordination with the ASHRAE Organization and its Winter or Annual meetings in 2020, winners will be invited and strongly encouraged to attend the conference, contingent on review of solution and fulfillment of winners' obligations.

Note that in addition to the standard Kaggle Winners' Obligations (open-source licensing requirements, solution packaging/delivery, presentation to host), the host team also asks that you create a short video (under 5 minutes) summarizing your solution.
## Timeline 
December 12, 2019 - Team Merger deadline. This is the last day participants may join or merge teams.
December 12, 2019 - Entry deadline. You must accept the competition rules before this date in order to compete.
December 19, 2019 - Final submission deadline.

All deadlines are at 11:59 PM UTC on the corresponding day unless otherwise noted. The competition organizers reserve the right to update the contest timeline if they deem it necessary.
## Prior Competitions
History of Great Building Energy Predictor Shootout I and II Competitions

ASHRAE has previously hosted two data competitions, called the "Great Building Energy Predictor Shootout I" (1993) and "Great Building Energy Predictor Shootout II" (1994). If you are interested in seeing how the field has changed over the years, we have rehosted a copy of the first competition here with a leaderboard. It's entirely for fun and does not award points, medals, etc.

For both of these competitions, participants were asked to develop empirical models for predicting building energy data from data sets and compare how those models could be used to forecast energy usage (Shootout I) and calculate energy conservation retrofit savings (Shootout II).

The 1994 competition asked participants to retrieve the competition training data set via an FTP server. Teams were required to submit their empirical models along with predictions via floppy disks. The submitted package included predictions of energy savings and a sufficient explanation of how the specific method (calculation method, data removal, etc.) was applied. Submissions using black-box, or proprietary methods, were disqualified. A combination accuracy metric of CV-RMSE (Coefficient of Root Mean Square Error) and MBE (Mean Bias Error) was used to evaluate prediction accuracy.

While the 1994 competition awarded no monetary prizes, over 150 teams competed. Six winning teams were formally recognized, all participants were asked to write an ASHRAE paper to document their efforts and to present at ASHRAE conferences. As a part of these efforts, over a dozen peer-reviewed papers were published and several software vendors incorporated the algorithms described in these papers.

Haberl, J. (1994, July 1). Instructions - "The Great Building Energy Predictor Shootout II: Measuring Retrofit Energy Savings".

## Acknowledgments

In addition to the Data Driven Modeling (DDM) Subcommittee of ASHRAE Technical Committee 4.7: Energy Calculations, the following organizations have generously contributed to data collection, travel and resources to host this competition:

Singapore Berkeley Building Efficiency and Sustainability in the Tropics
BUDS Lab
Engineering Experiment Station Texas A&M University

#Rules

One account per participant
You cannot sign up to Kaggle from multiple accounts and therefore you cannot submit from multiple accounts.

Use of Automated Machine Learning Tools (AMLT)
As further described in the Rules, this Competition permits the use of automated machine learning tool(s) (“AMLT”) in the creation of Submissions. AMLT Teams (as defined in the Rules) are not eligible to win any prizes.

No private sharing outside teams
Privately sharing code or data outside of teams is not permitted. It's okay to share code if made available to all participants on the forums.

Team Mergers
Team mergers are allowed and can be performed by the team leader. In order to merge, the combined team must have a total submission count less than or equal to the maximum allowed as of the merge date. The maximum allowed is the number of submissions per day multiplied by the number of days the competition has been running. AMLT Teams are not permitted to enter into a Team merger.

Team Limits
The maximum team size is 5.

Submission Limits
You may submit a maximum of 2 entries per day.

You may select up to 2 final submissions for judging.

Competition Timeline
Start Date: October 15, 2019

Merger Deadline: December 12, 2019 11:59 PM UTC

Entry Deadline: December 12, 2019 11:59 PM UTC

End Date (Final Submission Deadline): December 19, 2019 11:59 PM UTC

COMPETITION-SPECIFIC TERMS
COMPETITION TITLE: Great Energy Predictor III

COMPETITION SPONSOR: American Society of Heating, Refrigerating and Air-Conditioning Engineers

COMPETITION SPONSOR ADDRESS: 1791 Tullie Circle, N.E., Atlanta, GA 30329

COMPETITION WEBSITE: https://www.kaggle.com/c/ashrae-energy-prediction

TOTAL PRIZES AVAILABLE: $25,000

First Prize: $10,000

Second Prize: $7,000

Third Prize: $5,000

Fourth Prize: $2,000

Fifth Prize: $1,000

WINNER LICENSE TYPE: Open-Source

DATA ACCESS AND USE: Competition Use , Non-Commercial Purposes & Academic Research, Commercial Purposes

Competitions are open to residents of the United States and worldwide, except that if you are a resident of Crimea, Cuba, Iran, Syria, North Korea, Sudan, or are subject to U.S. export controls or sanctions, you may not enter the Competition. Other local rules and regulations may apply to you, so please check your local laws to ensure that you are eligible to participate in skills-based competitions. The Competition Sponsor reserves the right to award alternative Prizes where needed to comply with local laws.

ENTRY IN THIS COMPETITION CONSTITUTES YOUR ACCEPTANCE OF THESE OFFICIAL COMPETITION RULES.

The Competition named above is a skills-based competition to promote and further the field of data science. You must register via the Competition Website to enter. Your competition submissions ("Submissions") must conform to the requirements stated on the Competition Website. Your Submissions will be scored based on the evaluation metric described on the Competition Website. Subject to compliance with the Competition Rules, Prizes, if any, will be awarded to participants with the best scores, based on the merits of the data science models submitted. See below for the complete Competition Rules.

A. COMPETITION-SPECIFIC RULES
In addition to the provisions of the General Competition Rules below, you understand and agree to these Competition-Specific Rules required by the Competition Sponsor:

1. WINNER LICENSE.
Under Section 11 (Winners Obligations) of the General Rules below, you hereby grant and will grant Competition Sponsor the following license(s) with respect to your Submission if you are a Competition winner:

Open Source: You hereby license and will license your winning Submission and the source code used to generate the Submission under an Open Source Initiative-approved license (see www.opensource.org) that in no event limits commercial use of such code or model containing or depending on such code. For generally commercially available software that you used to generate your submission that is not owned by you, but that can be procured by the Competition Sponsor without undue expense, you do not need to grant the license in the preceding sentence for that software

2. AUTOMATED MACHINE LEARNING TOOLS (AMLT).
This competition permits the use of automated machine learning tool(s) (“AMLT”) in the creation of Submissions. Except as described in this section, AMLT are not permitted to be used in the creation of a Submission.

A. Submission as an AMLT

An individual or team may make a Submission as an AMLT (each individual or team making a submission as an AMLT, a “AMLT Team”). The AMLT Team must be authorized to make such Submission by the owner(s) of the AMLT (including all rights in the AMLT). AMLT Teams must declare themselves as such by submitting the following form prior to making a Submission: https://www.kaggle.com/amlt-registration. Submissions made by an AMLT Team will be marked as benchmarks (highlighted and named to match the AMLT Team name) on the Competition’s public leaderboard and, like all Submissions, cannot be removed or revoked once submitted.

The following provision is added to the end of Section 2 of the General Competition Rules below: “AMLT Teams may enter and participate in the Competition, but are not eligible to win any Prizes.”

The following provision is added to the end of Section 6 of the General Competition Rules below: “D. AMLT Teams. If you submit a Submission to this Competition as an AMLT Team, you cannot also submit as an individual user or as a team. Violation may result in your disqualification from the Competition and removal from the Competition leaderboard, at Kaggle's sole discretion. AMLT Teams are not permitted to enter into a Team merger.”

B. Using an AMLT to create a submission

Individual participants and Teams may also use an AMLT to create a Submission, provided that the participant ensures that they have an appropriate license to the AMLT and are able to comply with the Rules. An individual participant’s or Team’s use of an AMLT to create a Submission does not require that individual or team declare itself as an AMLT Team as described in Subsection A (Submission as an AMLT Team) above.

The following provision is added to the end of Section 11 of the General Competition Rules below: “Individual participants and Teams who have not declared themselves as an AMLT Team, but who create a Submission using an AMLT may win a Prize. However, for clarity, the potential winner’s Submission must still meet the requirements of these Rules, including but not limited to Section A.1 (Winners License), Section B.11 (Winners Obligations), and Section B.17 (Warranty, Indemnity, and Release). Additionally, as this Competition requires [an open source] license, a participant may only use AMLTs in the creation of their Submission if they have the unrestricted right to grant the open source license to source code used to generate the Submission, including the AMLT code. Associated disqualification and other consequences as specified in these Rules will apply if this requirement is not met.”

B. GENERAL COMPETITION RULES
1. BINDING AGREEMENT.
To enter the Competition, you must agree to these Official Competition Rules, which incorporate by reference the provisions and content of the Competition Website and any Specific Competition Rules above (collectively, the "Rules"). Please read these Rules carefully before entry to ensure you understand and agree. You further agree that submission of an entry in the Competition constitutes agreement to these Rules. You may not submit an entry to the Competition and are not eligible to receive the prizes associated with this Competition (“Prizes”) unless you agree to these Rules. These Rules form a binding legal agreement between you and the Competition Sponsor with respect to the Competition.

2. ELIGIBILITY. 
A. To be eligible to enter the Competition, you must be: (i) a registered account holder at Kaggle.com; (ii) the older of 18 years old or the age of majority in your jurisdiction of residence (unless otherwise agreed to by Competition Sponsor and appropriate parental/guardian consents have been obtained by Competition Sponsor); (iii) not a resident of Crimea, Cuba, Iran, Syria, North Korea, or Sudan; and (iv) not a person or representative of an entity under U.S. export controls or sanctions (see https://www.treasury.gov/resource-center/sanctions/Programs/Pages/Programs.aspx).

If you are entering as a representative of a company, educational institution or other legal entity, or on behalf of your employer, these rules are binding on you, individually, and the entity you represent or are an employee. If you are acting within the scope of your employment, as an employee, contractor, or agent of another party, you warrant that such party has full knowledge of your actions and has consented thereto, including your potential receipt of a Prize. You further warrant that your actions do not violate your employer's or entity's policies and procedures.

The Competition Sponsor reserves the right to verify eligibility and to adjudicate on any dispute at any time. If you provide any false information relating to the Competition concerning your identity, residency, mailing address, telephone number, email address, ownership of right, or information required for entering the Competition, you may be immediately disqualified from the Competition.

B. Unless otherwise stated in the Specific Competition Rules above or prohibited by internal policies of the Competition Entities, employees, interns, contractors, officers and directors of Competition Entities may enter and participate in the Competition, but are not eligible to win any Prizes. "Competition Entities" means the Competition Sponsor, Kaggle Inc., and their respective parent companies, subsidiaries and affiliates. If you are such a participant from a Competition Entity, you are subject to all applicable internal policies of your employer with respect to your participation.

3. SPONSOR AND HOSTING PLATFORM.
The Competition is sponsored by Competition Sponsor named above. The Competition is hosted on behalf of Competition Sponsor by Kaggle Inc. ("Kaggle"). Kaggle is an independent contractor of Competition Sponsor, and is not a party to this or any agreement between you and Competition Sponsor. You understand that Kaggle has no responsibility with respect to selecting the potential Competition winner(s) or awarding any Prizes. Kaggle will perform certain administrative functions relating to hosting the Competition, and you agree to abide by the provisions relating to Kaggle under these Rules. As a Kaggle.com account holder and user of the Kaggle competition platform, remember you have accepted and are subject to the Kaggle Terms of Service at www.kaggle.com/terms in addition to these Rules.

4. COMPETITION PERIOD.
For the purposes of Prizes, the Competition will run from the Start Date and time to the End Date and time (such duration the “Competition Period”). The Competition Timeline is subject to change, and Competition Sponsor may introduce additional hurdle deadlines during the Competition Period. Any updated or additional deadlines will be publicized on the Competition Website. It is your responsibility to check the Competition Website regularly to stay informed of any deadline changes. YOU ARE RESPONSIBLE FOR DETERMINING THE CORRESPONDING TIME ZONE IN YOUR LOCATION.

5. COMPETITION ENTRY. 
NO PURCHASE NECESSARY TO ENTER OR WIN. To enter the Competition, you must register on the Competition Website prior to the Entry Deadline, and follow the instructions for developing and entering your Submission through the Competition Website. Your Submissions must be made in the manner and format, and in compliance with all other requirements, stated on the Competition Website (the "Requirements"). Submissions must be received before any Submission deadlines stated on the Competition Website. Submissions not received by the stated deadlines will not be eligible to receive a Prize.

Submissions may not use or incorporate information from hand labeling or human prediction of the validation dataset or test data records.

If the Competition is a multi-stage competition with temporally separate training and/or test data, one or more valid Submissions may be required during each Competition stage in the manner described on the Competition Website in order for the Submissions to be Prize eligible.

Submissions are void if they are in whole or part illegible, incomplete, damaged, altered, counterfeit, obtained through fraud, or late. Competition Sponsor reserves the right to disqualify any entrant who does not follow these Rules, including making a Submission that does not meet the Requirements.

6. INDIVIDUALS AND TEAMS.
A. Individual Account. You may make Submissions only under one, unique Kaggle.com account. You will be disqualified if you make Submissions through more than one Kaggle account, or attempt to falsify an account to act as your proxy. You may submit up to the maximum number of Submissions per day as specified on the Competition Website.

B. Teams. If permitted under the Competition Website guidelines, multiple individuals may collaborate as a team (a "Team"); however, you may join or form only one Team. Each Team member must be a single individual with a separate Kaggle account. You must register individually for the Competition before joining a Team. You must confirm your Team membership to make it official by responding to the Team notification message sent to your Kaggle account. Team membership may not exceed the Maximum Team Size stated on the Competition Website.

C. Team Merger. Teams may request to merge via the Competition Website. Team mergers may be allowed provided that: (i) the combined Team does not exceed the Maximum Team Size; (ii) the number of Submissions made by the merging Teams does not exceed the number of Submissions permissible for one Team at the date of the merger request; (iii) the merger is completed before the earlier of: any merger deadline or the Competition deadline; and (iv) the proposed combined Team otherwise meets all the requirements of these Rules.

7. COMPETITION DATA.
"Competition Data" means the data or datasets available from the Competition Website for the purpose of use in the Competition, including any prototype or executable code provided on the Competition Website. The Competition Data will contain private and public test sets. Which data belongs to which set will not be made available to participants.

A. Data Access and Use. You may access and use the Competition Data for any purpose, whether commercial or non-commercial, including for participating in the Competition and on Kaggle.com forums, and for academic research and education. The Competition Sponsor reserves the right to disqualify any participant who uses the Competition Data other than as permitted by the Competition Website and these Rules.

B. Data Security. You agree to use reasonable and suitable measures to prevent persons who have not formally agreed to these Rules from gaining access to the Competition Data. You agree not to transmit, duplicate, publish, redistribute or otherwise provide or make available the Competition Data to any party not participating in the Competition. You agree to notify Kaggle immediately upon learning of any possible unauthorized transmission of or unauthorized access to the Competition Data and agree to work with Kaggle to rectify any unauthorized transmission or access.

C. External Data. You may use data other than the Competition Data (“External Data”) to develop and test your models and Submissions. However, you will (i) ensure the External Data is available to use by all participants of the competition for purposes of the competition at no cost to the other participants and (ii) post such access to the External Data for the participants to the official competition forum prior to the Entry Deadline.

8. SUBMISSION CODE REQUIREMENTS.
A. Private Code Sharing. Unless otherwise specifically permitted under the Competition Website or Competition Specific Rules above, during the Competition Period, you are not allowed to privately share source or executable code developed in connection with or based upon the Competition Data or other source or executable code relevant to the Competition (“Competition Code”). This prohibition includes sharing Competition Code between separate Teams, unless a Team merger occurs. Any such sharing of Competition Code is a breach of these Competition Rules and may result in disqualification.

B. Public Code Sharing. You are permitted to publicly share Competition Code, provided that such public sharing does not violate the intellectual property rights of any third party. If you do choose to share Competition Code or other such code, you are required to share it on Kaggle.com on the discussion forum or kernels associated specifically with the Competition for the benefit of all competitors. By so sharing, you are deemed to have licensed the shared code under an Open Source Initiative-approved license (see www.opensource.org) that in no event limits commercial use of such Competition Code or model containing or depending on such Competition Code.

C. Use of Open Source. Unless otherwise stated in the Specific Competition Rules above, if open source code is used in the model to generate the Submission, then you must only use open source code licensed under an Open Source Initiative-approved license (see www.opensource.org) that in no event limits commercial use of such code or model containing or depending on such code.

9. DETERMINING WINNERS. 
Each Submission will be scored and ranked by the evaluation metric stated on the Competition Website. During the Competition Period, the current ranking will be visible on the Competition Website's public leaderboard. The potential winner(s) are determined solely by the leaderboard ranking on the private leaderboard, subject to compliance with these Rules. The public leaderboard will be based on the public test set and the private leaderboard will be based on the private test set.

In the event of a tie, the Submission that was entered first to the Competition will be the winner. In the event a potential winner is disqualified for any reason, the Submission that received the next highest score rank will be chosen as the potential winner.

10. NOTIFICATION OF WINNERS & DISQUALIFICATION.
The potential winner(s) will be notified by email.

If a potential winner (i) does not respond to the notification attempt within one (1) week from the first notification attempt or (ii) notifies Kaggle within one week after the End Date that the potential winner does not want to be nominated as a winner or does not want to receive a Prize, then, in each case (i) and (ii) such potential winner will not receive any Prize, and an alternate potential winner will be selected from among all eligible entries received based on the Competition’s judging criteria.

In case (i) and (ii) above Kaggle may disqualify the participant. However, in case (ii) above, if requested by Kaggle, such potential winner may provide code and documentation to verify the participant’s compliance with these Rules. If the potential winner provides code and documentation to the satisfaction of Kaggle, the participant will not be disqualified pursuant to this paragraph.

Competition Sponsor reserves the right to disqualify any participant from the Competition if the Competition Sponsor reasonably believes that the participant has attempted to undermine the legitimate operation of the Competition by cheating, deception, or other unfair playing practices or abuses, threatens or harasses any other participants, Competition Sponsor or Kaggle.

A disqualified participant may be removed from the Competition leaderboard, at Kaggle's sole discretion. If a Participant is removed from the Competition Leaderboard, additional winning features associated with the Kaggle competition platform, for example Kaggle points or medals, may also not be awarded.

The final leaderboard list will be publicly displayed at Kaggle.com. Determinations of Competition Sponsor are final and binding.

11. WINNERS OBLIGATIONS.
As a condition to being awarded a Prize, a Prize winner must fulfill the following obligations:

(a) deliver to the Competition Sponsor the final model's software code as used to generate the winning Submission and associated documentation. The delivered software code should follow these documentation guidelines, must be capable of generating the winning Submission, and contain a description of resources required to build and/or run the executable code successfully; For generally commercially available software that you used to generate your submission that is not owned by you, but that can be procured by the Competition Sponsor without undue expense, you do not need to grant the license in the preceding sentence for that software

(b) grant to the Competition Sponsor the license to the winning Submission stated in the Competition Specific Rules above, and represent that you have the unrestricted right to grant that license;

(c) sign and return all Prize acceptance documents as may be required by Competition Sponsor or Kaggle, including without limitation: (i) eligibility certifications; (ii) licenses, releases and other agreements required under the Rules; and (iii) U.S. tax forms (such as IRS Form W-9 if U.S. resident, IRS Form W-8BEN if foreign resident, or future equivalents).

12. PRIZES. 
Prize(s) are as described on the Competition Website and are only available for winning during the time period described on the Competition Website. The odds of winning any Prize depends on the number of eligible Submissions received during the Competition Period and the skill of the participants.

All Prizes are subject to Competition Sponsor's review and verification of the participant’s eligibility and compliance with these Rules, and the compliance of the winning Submissions with the Submissions Requirements. In the event that the Submission demonstrates non-compliance with these Competition Rules, Competition Sponsor may at its discretion take either of the following actions: (i) disqualify the Submission(s); or (ii) require the potential winner to remediate within one week after notice all issues identified in the Submission(s) (including, without limitation, the resolution of license conflicts, the fulfillment of all obligations required by software licenses, and the removal of any software that violates the software restrictions).

A potential winner may decline to be nominated as a Competition winner in accordance with Section 10.

Potential winners must return all required Prize acceptance documents within two (2) weeks following notification of such required documents, or such potential winner will be deemed to have forfeited the prize and another potential winner will be selected. Prize(s) will be awarded within approximately 30 days after receipt by Competition Sponsor or Kaggle of the required Prize acceptance documents. Transfer or assignment of a Prize is not allowed.

You are not eligible to receive any Prize if you do not meet the Eligibility requirements in Section 2 above.

If a Team wins a monetary Prize, the Prize money will be allocated in even shares between the eligible Team members, unless the Team unanimously opts for a different Prize split and notifies Kaggle before Prizes are issued.

13. TAXES.
ALL TAXES IMPOSED ON PRIZES ARE THE SOLE RESPONSIBILITY OF THE WINNERS. Payments to potential winners are subject to the express requirement that they submit all documentation requested by Competition Sponsor or Kaggle for compliance with applicable state, federal, local and foreign (including provincial) tax reporting and withholding requirements. Prizes will be net of any taxes that Competition Sponsor is required by law to withhold. If a potential winner fails to provide any required documentation or comply with applicable laws, the Prize may be forfeited and Competition Sponsor may select an alternative potential winner. Any winners who are U.S. residents will receive an IRS Form-1099 in the amount of their Prize.

14. GENERAL CONDITIONS.  
All federal, state, provincial and local laws and regulations apply.

15. PUBLICITY.
By accepting a Prize, you agree that Competition Sponsor, Kaggle and its affiliates may use your name and likeness for advertising and promotional purposes without additional compensation, unless prohibited by law.

16. PRIVACY.
You acknowledge and agree that Competition Sponsor and Kaggle may collect, store, share and otherwise use personally identifiable information provided by you during the Kaggle account registration process and the Competition, including but not limited to, name, mailing address, phone number, and email address (“Personal Information”). Kaggle acts as an independent controller with regard to its collection, storage, sharing, and other use of this Personal Information, and will use this Personal Information in accordance with its Privacy Policy <www.kaggle.com/privacy>, including for administering the Competition. As a Kaggle.com account holder, you have the right to request access to, review, rectification, portability or deletion of any personal data held by Kaggle about you by logging into your account and/or contacting Kaggle Support at <www.kaggle.com/contact>.

As part of Competition Sponsor performing this contract between you and the Competition Sponsor, Kaggle will transfer your Personal Information to Competition Sponsor, which acts as an independent controller with regard to this Personal Information. As a controller of such Personal Information, Competition Sponsor agrees to comply with all U.S. and foreign data protection obligations with regard to your Personal Information. Kaggle will transfer your Personal Information to Competition Sponsor in the country specified in the Competition Sponsor Address listed above, which may be a country outside the country of your residence. Such country may not have privacy laws and regulations similar to those of the country of your residence.

17. WARRANTY, INDEMNITY AND RELEASE.
You warrant that your Submission is your own original work and, as such, you are the sole and exclusive owner and rights holder of the Submission, and you have the right to make the Submission and grant all required licenses. You agree not to make any Submission that: (i) infringes any third party proprietary rights, intellectual property rights, industrial property rights, personal or moral rights or any other rights, including without limitation, copyright, trademark, patent, trade secret, privacy, publicity or confidentiality obligations, or defames any person; or (ii) otherwise violates any applicable U.S. or foreign state or federal law.

To the maximum extent permitted by law, you indemnify and agree to keep indemnified Competition Entities at all times from and against any liability, claims, demands, losses, damages, costs and expenses resulting from any of your acts, defaults or omissions and/or a breach of any warranty set forth herein. To the maximum extent permitted by law, you agree to defend, indemnify and hold harmless the Competition Entities from and against any and all claims, actions, suits or proceedings, as well as any and all losses, liabilities, damages, costs and expenses (including reasonable attorneys fees) arising out of or accruing from: (a) your Submission or other material uploaded or otherwise provided by you that infringes any third party proprietary rights, intellectual property rights, industrial property rights, personal or moral rights or any other rights, including without limitation, copyright, trademark, patent, trade secret, privacy, publicity or confidentiality obligations, or defames any person; (b) any misrepresentation made by you in connection with the Competition; (c) any non-compliance by you with these Rules or any applicable U.S. or foreign state or federal law; (d) claims brought by persons or entities other than the parties to these Rules arising from or related to your involvement with the Competition; and (e) your acceptance, possession, misuse or use of any Prize, or your participation in the Competition and any Competition-related activity.

You hereby release Competition Entities from any liability associated with: (a) any malfunction or other problem with the Competition Website; (b) any error in the collection, processing, or retention of any Submission; or (c) any typographical or other error in the printing, offering or announcement of any Prize or winners.

18. INTERNET.
Competition Entities are not responsible for any malfunction of the Competition Website or any late, lost, damaged, misdirected, incomplete, illegible, undeliverable, or destroyed Submissions or entry materials due to system errors, failed, incomplete or garbled computer or other telecommunication transmission malfunctions, hardware or software failures of any kind, lost or unavailable network connections, typographical or system/human errors and failures, technical malfunction(s) of any telephone network or lines, cable connections, satellite transmissions, servers or providers, or computer equipment, traffic congestion on the Internet or at the Competition Website, or any combination thereof, which may limit a participant’s ability to participate.

19. RIGHT TO CANCEL, MODIFY OR DISQUALIFY.
If for any reason the Competition is not capable of running as planned, including infection by computer virus, bugs, tampering, unauthorized intervention, fraud, technical failures, or any other causes which corrupt or affect the administration, security, fairness, integrity, or proper conduct of the Competition, Competition Sponsor reserves the right to cancel, terminate, modify or suspend the Competition. Competition Sponsor further reserves the right to disqualify any participant who tampers with the submission process or any other part of the Competition or Competition Website. Any attempt by a participant to deliberately damage any website, including the Competition Website, or undermine the legitimate operation of the Competition is a violation of criminal and civil laws. Should such an attempt be made, Competition Sponsor and Kaggle each reserves the right to seek damages from any such participant to the fullest extent of the applicable law.

20. NOT AN OFFER OR CONTRACT OF EMPLOYMENT.
Under no circumstances will the entry of a Submission, the awarding of a Prize, or anything in these Rules be construed as an offer or contract of employment with Competition Sponsor or any of the Competition Entities. You acknowledge that you have submitted your Submission voluntarily and not in confidence or in trust. You acknowledge that no confidential, fiduciary, agency, employment or other similar relationship is created between you and Competition Sponsor or any of the Competition Entities by your acceptance of these Rules or your entry of your Submission.

21. GOVERNING LAW.
Unless otherwise provided in the Competition Specific Rules above, all claims arising out of or relating to these Rules will be governed by California law, excluding its conflict of laws rules, and will be litigated exclusively in the Federal or State courts of Santa Clara County, California, USA. The parties consent to personal jurisdiction in those courts. If any provision of these Rules is held to be invalid or unenforceable, all remaining provisions of the Rules will remain in full force and effect.

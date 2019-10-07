# Problem Set 2 (out of 120 points)

# Problem 1 (20 points)

Pretend that you are an IRB reviewer and you have received the experimental protocol described below.

> Proposed protocol: We will follow a two-part protocol to study the usability of fingerprint readers on ATMs. This experiment is particularly timely since many Washington-area banks have recently installed fingerprint scanners on their ATMs to make sure that only verified account owners can withdraw money. The first part will be an observational field study. We will conduct this field study at the First Bank of GW branch on 'Eye' St. because there is a coffee shop located across the street. We will sit at an outdoor table at the coffee shop and watch everyone who goes to the ATM across the street. To make sure we don't miss anyone, we will also have a video camera at our table pointed at the ATM. The camera will be recording continuously. For each person who comes up to the ATM, we will record how many attempts are necessary for them to successfully authenticate to the fingerprint reader, as well as approximately how much money they take out. From the video recording, we will also estimate their height, weight, and ethnicity to see if those impact success using the fingerprint reader. To make it easier on our research team, we will crowdsource the estimation of height/weight/ethnicity by posting screencaptures on Amazon's Mechanical Turk platform and letting crowdworkers vote.

> The second part of our study will be a between-subjects, in-lab experiment comparing the usability of different brands of fingerprint readers commonly used on ATMs. Participants will come to our lab, and we will begin by giving them a detailed demographics survey (age, occupation, annual income, sexual orientation, and past experience using biometric systems). Afterwards, they will use each fingerprint scanner on the market in randomized order. To understand the tolerance of the fingerprint reader at accepting partial matches of the fingerprints, we will retain participants' fingerprint readings from each device so that undergraduate students in a security class at our institution can analyze the tolerance as part of a class project. We will then administer a survey about participants' perceptions of the usability and comfort of each fingerprint scanner. To make sure our participants have enough free time to do our study, we will try to recruit students in grades 6-12 by posting flyers for the study in front of local schools. To reflect the amount of free time participants have, we will compensate students $5.00 for the study. Any non-student participants will receive $10.00 for the study.

1. Task 1-A: Create a bulleted list of potential ethics concerns raised by this protocol.
2. Task 1-B: Write at least one paragraph describing positive steps the researchers appear to have taken to minimize some of these ethics concerns.
3. Task 1-C: Write two paragraphs suggesting modifications to the study protocol that would better protect human subjects. The first paragraph should cover the first part of the protocol, and the second paragraph should cover the second part of the protocol.
4. Task 1-D: Based on accepting your modifications, which IRB determination (non-research, exempt, expedited, full-board) would this study fall into? Provide a one paragraph justification. 

*Submission*: Submit a single file `review.md` that contains all your information for this problem set to github classroom.

*Github Classroom Link*: https://classroom.github.com/a/BKydnxIW



# Problem 2 (20 points)

You are to conduct an IRB-esc ethics review of another project. You will be provided (and should provide to a classmate) materials related to your class project, including

* Project proposal
* IRB Document
* Survey Instrument / Scripts
* Recruitment material
* Informed Cosent

You should make an IRB determination justification, e.g., non-research, exempt, expedited, or full-board, based on the review criteria. You should do so in a *four* paragraph essay which you submit to your classmate and for grading. 

1. First paragraph should summarize the research and the protocol
2. Second paragraph should described the risks, benefits, and methods used to protect subjects of the experiment.
3. Third paragraph should offer suggestions for improving the protocol from both a research and ethics perspective. 
3. Fourth paragraph should offer a determination justification with clear reasoning. 


Note your justification should touch on the following IRB review criteria:

* Risks to subjects are minimized
* Risks to subjects are reasonable in relation to anticipated benefits
* Selection of subjects is equitable
* Informed consent was sought, or with justifiable waivers
* Proper monitoring of data collection to ensure safety, where appropriate
* Participant privacy and confidentiality is well maintained within the data set

*Submission*: You will use "teams" in github classroom to communicate about your review. The reviewee will upload to the repository all necessary review material, and the reviewer will upload a single file `review.md` with the necessary review material. 

*Github Classroom Link*: https://classroom.github.com/g/Y3zwou0e



# Problem 3 (40 Points)

The past few years have seen a number of privacy controversies related to transportation apps like Uber. For instance, Uber has made the news about [God View mode](https://motherboard.vice.com/en_us/article/ubers-god-view-was-once-available-to-drivers), the [broad tracking of customers' location data](https://www.eff.org/deeplinks/2016/12/uber-should-restore-user-control-location-privacy), and [tracking users after rides have ended](https://consumerist.com/2016/12/07/uber-tracks-you-even-after-your-ride-invasion-of-privacy-or-necessary/), [among other issues](https://www.revealnews.org/blog/why-privacy-advocates-are-worried-about-ubers-security-problems/).

Design a short (no more than 15-minute long) interview study exploring one or more research questions of interest to you in the area of security or privacy related to so-called "ride-sharing" apps. Potential topics include the convenience versus privacy trade-off users perceive; awareness of these controversies; physical security concerns related to driving, or being driven around by, strangers; etc.

Turn in a 1 paragraph description of your research question(s), and your interview script, including iterations thereon as you practice the interview.  Include in your script everything you will say to the participant at any point in the interview, such as welcoming them at the beginning or thanking them and telling them the purpose of the study.

Finally, actually conduct this interview with 3 pilot participants (and, if applicable, improve your script in between interviews). While you would not want to have your friends participate in a real study, it's perfectly fine to have your friends participate in a pilot study like this. Then, using the qualitative analysis techniques we've discussed in class, turn in 3 or 4 paragraphs describing the results.


*Submission*: To submit problem 3 and 4, on github classroom, you should submit the following files: 
* `research-questions.md`: one paragraph description of your research questions
* `script-v0.md`: your initial script used before interviews
* `script-v1.md`: your final script used by the end of your interviews as iteration and improvement
* `report.md` : the final report based on your interviews

*Github Classroom Link*: https://classroom.github.com/a/W9AS9WVM

# Problem 4 (40 points)

Facebook has a feature on its [settings page](https://www.facebook.com/settings?tab=account) with which users can "download their data" as an archive (see https://www.facebook.com/help/1701730696756992/?helpref=hc_fnav). Using whatever language/frameworks you prefer, write a script that, given such an archive, automatically generates an information visualization that summarizes what you deem important for the archive's owner to know about their Facebook privacy. 

(If you don't use Facebook, choose another "social media" application that has a similar feature for you to download your archive of information.)

Submit a one paragraph describing your goals in creating this visualization, as well as an example of your script's output running on either a real Facebook archive (feel free to manually sanitize the output) or synthetic test data. However, also upload your script(s) and instructions for running it so that the course staff can test it out on our own Facebook data.


*Submission*: Submit on github classroom the following files:
* program file called `analyze.py` if python (or in the correct format for the language of your choice)
* A single PDF file *report.pdf* that self contains your visualization and report

*Github Classroom Link*: https://classroom.github.com/a/8Wsfh4DQ

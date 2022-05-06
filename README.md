# Smart Machines Spring 2022 - Final Project
A client intake app for Prosody Law that screens clients who may qualify was aggreived employees under the Massachusetts Paid Family and Medical Leave Act. This interview was created in fulfillment of Suffolk Law's Smart Machines Spring 2022 final project requirement.

# Research 
This app guides those who believe they may have been retaliated against due to taking paid leave as allowed under the [Massachusetts Paid Family and Medical Leave Act](https://malegislature.gov/Laws/GeneralLaws/PartI/TitleXXII/Chapter175M) (PFML). While passed in 2018, the substance of the act - including protections for employees against retaliatory actions by their employer - went into effect on January 1, 2021. This app uses Chapter 175M Sections 9(c) and 9(d) to form the framework of the app. I also included language found in the [poster](https://www.mass.gov/service-details/notice-and-acknowledgement-for-the-paid-family-and-medical-leave-pfml-law-for-executive-department-employees) covered employers are legally required to post conspicuously in the workplace.

# Completeness
The app attempts to screen potential clients who may have been retaliated against by their employer for taking family or medical leave afforded by PFML. Prosody Law, a solo practitioner firm, has faced difficulty in finding potential clients who fit this narrow population, as the law (and his firm) are fairly new. This app allows for Prosody Law to host a guided interview on their website, where they can point both external users and SEO traffic to their website. After the user completes the interview, it allows them to send their responses directly to Prosody Law.

Definitions and examples are provided to the user with either green words or help bubbles; this is particularly necessary when describing defined language within the statute (e.g., "serious health condition", "covered individual"). Guidance is given along the way in the form of a progress bar, detailed questions, a page that displays their responses, and an end screen letting the user know the email was sent successfully.

# Polish and refinement
To ensure the app's question flow was complete, I created a [flowchart](https://beantownbrit.github.io/litlab/decisionmodel.png) (text found [here](https://beantownbrit.github.io/smartmachines/decisionmodel.md)) that displays the logic of the app. Appropriate radio buttons were used on yes/no questions, with JavaScript enabled when a condition was met and required additional information from the user to continue. This was key as some leave conditions (e.g., if user didn't give notice to their employer) made the potential client ineligible based on the narrow target population as descibed by Prosody Law.

# Iteration and use of feedback
I had initially wanted the app to screen for potential clients under the whole of PFML (as described in my initial [project proposal](https://beantownbrit.github.io/litlab/PFMLproposal.html), but feedback from Prosody Law narrowed the scope by explaining they were seeking potential clients who: (1) had taken leave under PFML; (2) had given notice to their employer; and (3) had been retaliated against by their employer due to taking leave. I had also originally formatted the app to produce a client intake form, but this was condidered unnecessary additional paperwork by Prosody Law; thus, I coded the app to only produce the user's responses on screen to be sent via email to both Prosody Law and the user.

The app went through three rounds of live user testing by Prosody Law. This does not inclusive of numerous short conversations confirming goal of app, ensuring correct interpretation of statute provisions, and revisiting stylistic choices of question format. The final iteration generated extremely positive user feedback and satisfied the goals set by Prosody Law.

# Next steps and handoff
As I am pretty much the creative director and IT admin for Prosody Law, next steps and handoff will happen in-house (literally). I would have liked to embed the questionnaire in the stand alone website I have planned, so I'll explore options for that this summer. Upon completion of this project, I thought of how it may be easiest to take this app's framework and translate it to a QnA Markup format. This would be similar to my [Coding the Law final project](http://chatbot.masmallclaims.org/) for Harvard's Small Claims Advisory Service, which is now hosted directly on their website. This may help in adding more directory services and external aids for those who do not quite fit into the potential client pool but may still need additional help.

Overall, I enjoyed exploring the capabilities of DocAssemble and hope to use it for future projects - maybe if I can squeeze in another LIT Lab rotation next spring!

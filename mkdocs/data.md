# Data. Like... all of it. Kind of.

All data we collected. 

 > In some cases we had to anonymize, to protect participant identity. But you can still replicate all results. Cheers.

## Video Observations

We collected more than 72 hours of video onscreen recordings throughout the experiment. Participants were asked to avoid capturing personal information or identifiers. Unfortunately this request was widely ignored. To preserve participant anonymity, **we cannot provide the original video material**. Bummer.
We can however provide all information, extracted ***from*** the video material.

 * Task solving and task preparation times: We measured how much time every participant spent on the actual project conversion tasks and the instructions and provide precise information on their time spendings.
 * Task deviations, difficulties, remarkable observations: We provide for each participant and each refactoring task a transcript of all noteworthy events. This includes problems with specific task phases, problems with software used, even information on their task solving activity itself.
 * Participant methodology feedback preferences

Here's the actual data, in various file formats:

 * [Mac Numbers File](extrafiles/observations/video-observations.numbers)
 * [Microsoft Excel File](extrafiles/observations/video-observations.xlsx)
 * [CSV File](extrafiles/observations/video-observations.csv)


## Participant Feedback

Participant issued comments on the study, issues, preferences after study conclusion.

We crunched it all for you, in various file formats:

 * [Mac Numbers File](extrafiles/feedback/participant-feedback.numbers)
 * [Microsoft Excel File](extrafiles/feedback/participant-feedback.xlsx)
 * [CSV File](extrafiles/feedback/participant-feedback.csv)  

We also created an [informal meta summary](extrafiles/feedback/participant-feedback-summary.csv) of most common issues observed in task solving.


## Code / Model Submissions

Everything the participants actively produced on their endevour to migrate the provided legacy applications:

 * [All raw code and all models (anonymized)](https://www.cs.mcgill.ca/~mschie3/restify/submissions/02-uploads-anonymized-sources-models.zip) (and the corresponding generated code), provided by participants.
 * [All patched code and all models (anonymized)](https://www.cs.mcgill.ca/~mschie3/restify/submissions/03-uploads-sanitized-sources-models.zip) (and the corresponding generated code), provided by participants.

 > We patched some submissions before testing, i.e. in some cases a minimal configuration mistake prevented testing. See our publication for the details on the patches performed.
 
## Participant Test Results

We tested all submissions against the requested REST API interface description.

Here's a [CSV with all the results](extrafiles/observations/tests.csv). You can reproduce the CSV using the above code / model submissions and our [provided tester](analyzer.md).
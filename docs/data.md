# Collected Data

This page lists data we *collected* in preparation, or throughout the experiment.  
There are two limitations to consider:

 * The data is anonymized, i.e. we wiped or replaced any information related to participant identity.
 * This page contains no *interpretation results*, i.e. statistical insights, or conclusions. If you are interested in replicating our interpretation results (as presented in our paper submission), we kindly refer you to the dedicated [result replication](replication.md) page.

## Video Observations

We collected more than 72 hours of video onscreen recordings throughout the experiment. Participants were asked to avoid capturing personal information or identifiers. Unfortunately this request was often ignored. To preserve participant anonymity, **we do not provide original video material**.

However, we do provide a lot of information, carefully extracted ***from*** the video material:

 * Task solving and task preparation times: We measured how much time every participant spent on the actual project conversion tasks and the instructions and provide precise information on their time spendings.
 * Task deviations, difficulties, remarkable observations: We provide for each participant and each refactoring task a transcript of all noteworthy events. This includes problems with specific task phases, problems with software used, even information on their task solving activity itself.
 * Participant methodology feedback preferences

Below are direct links to the described data, in various file formats:

 * [Mac Numbers File](extrafiles/observations/video-observations.numbers)
 * [Microsoft Excel File](extrafiles/observations/video-observations.xlsx)
 * [CSV File](extrafiles/observations/video-observations.csv)


## Participant Feedback

Participant provided a plethora of comments on the study, regarding issues, personal preferences, and general feedback. The comments were collected as final step of their study participation.

Below are direct links to the described data, in various file formats:

 * [Mac Numbers File](extrafiles/feedback/participant-feedback.numbers)
 * [Microsoft Excel File](extrafiles/feedback/participant-feedback.xlsx)
 * [CSV File](extrafiles/feedback/participant-feedback.csv)  

We also created an [informal meta summary](extrafiles/feedback/participant-feedback-summary.csv) of most common issues observed in task solving.


## Code / Model Submissions

Each participant produced two software artifacts: One raw code submission, where the participant manually migrated an application to REST - and one model submission, where the migration was performed by help of modelling. Note that in the latter case the provided models were used to directly generate corresponding code.

Below are direct links to download all participant software submissions.

 * [{--All raw code and all models (anonymized)--}](https://github.com/m5c/RestifyAnalyzer/blob/master/02-uploads-anonymized-sources-models.zip) [{==local snapshot of all patched code and all models (anonymized)==}](../../RestifyAnalyzer/02-uploads-anonymized-sources-models.zip) (and the corresponding generated code), provided by participants.
 * [{--All patched code and all models (anonymized)--}](https://github.com/m5c/RestifyAnalyzer/blob/master/03-uploads-sanitized-sources-models.zip) [{==local snapshot of all patched code and all models (anonymized)==}](../../RestifyAnalyzer/03-uploads-sanitized-sources-models.zip) (and the corresponding generated code), provided by participants.

 > *Patched* refers to minimal changes done to participant submissions. In rare cases minimal project configuration mistakes prevented us from testing a submission. In these cases we minimally modified the participant submission. All study interpretations are based on the patched version. We describe the modifications applied in more detail in our paper submission.
 
## Participant Test Results

We determined *correctness* of all submissions, by testing against a stipulated REST API interface description. The process is described in more detail in the dedicated [analyzer section](analyzer.md).

 * For your convenience, we provide a [direct link with the test results in CSV format](extrafiles/observations/tests.csv). 
 * You can reproduce the test results by following the instructions on the [analyzer documentation page](analyzer.md).
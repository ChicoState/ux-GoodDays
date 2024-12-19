# Phase III: Prototypes and User Testing

## Introduction

Good Days is a mood tracking and journaling app which features a calendar style interface and activity tracking capabilities. For this final sprint, the UX team focused primarily on integrating feedback from users on our wireframes, as well as preparing for live user testing. We developed a live prototype with user interaction capabilities with a color scheme. We received certification to conduct user testing as an independent research group working from the university. Furthermore, we prepared protocols designed for user testing and then conducted these tests and analyzed the data. Although we drifted apart from our software team, we ended the sprint with a solid prototype that is ready for further development if chosen to continue.

## Methods

To perform a formative study on our UX prototype, we conducted a usability evaluation with participants selected from CSCI 431 (N=6) and structured the evaluation into a background information section, our main task session and a final debrief.

We started by asking some questions about the participants’ previous journaling experiences to compare our test participants with our personas.
1. _Do you regularly keep a journal, or have you ever done so in the past?_
2. _Which aspects of journaling are particularly important for you?_
3. _What aspects of your current/previous journal did you not like?_

Our usability evaluation centers around six tasks using our interactive Figma prototype:

_T1_ _Looking through the activity options, you feel like something is missing. Try to open the create activity dialog._</br>
_T2_ _Try to delete the Gym activity._ </br>
_T3_ _Today is October 26th, and you want to make a new entry. Try to access the journal entry for October 26th, then select a mood._</br>
_T4_ _You are curious about how your month has been. Find a way to see your most common mood throughout October._</br>
_T5_ _You want to keep your journal secure. Find a way to set a password so you can lock the application._</br>
_T6_ _Now that you have added a password, lock the app._

After they attempted each task, we asked the following question: “On a scale from 1 to 5, where 1 is “very difficult” and 5 is “very easy”, how would you rate your experience completing this task?” We also asked them to explain the reasoning behind their choice.

Participants were asked to “think out loud”, explaining their thought process as they carried out each task.

_T1_ is meant an easy task to make the user comfortable with the Figma prototype setup. </br>
_T2_ builds upon T1 in a more sophisticated way, letting the user complete a more complex flow.</br>
_T3_ explores the possibility of multiple pathways of accessing the current day (pressing on the today button or using the calendar view) as well as using the mood slider, which is one of our core capabilities. </br>
_T4_ tries to explore the statistical features of the application. </br>
_T5_ and T6 round up the usability evaluation by testing out the security features of the application. </br>

Finally, we asked the participants a few closing questions about their overall experience:
1. _How would you rate your experience completing the tasks? Use the same 1 to 5 scale, where 1 is “terrible” and 5 is “great”._
2. _Why do you feel that way?_
3. _Could you see yourself using GoodDays?_
4. _Are there any features that you felt were missing?_
5. _Do you think GoodDays would work better as a mobile app?_
The last question was particularly important for us, since we envisioned GoodDays initially as a mobile application. The desktop application resulted as a compromise with the development team.

Overall, we tried to archive a balance between quantitative data points such as ratings and completion ratios as well as qualitative insights such as user feedback.

## Findings

The quantitative task scores (1 indicating high difficulty and 5 indicating low perceived difficulty) averaged around 4.72 across all tasks and can be summarized in the following table: 

| Task | Average Score | Standard Deviation |
| ---- | ------------- | ------------------ |
| T1   | 4.83          | 0.41               |
| T2   | 4.67          | 0.52               |
| T3   | 5.00          | 0.00               |
| T4   | 4.00          | 0.63               |
| T5   | 4.83          | 0.41               |
| T6   | 5.00          | 0.00               |

*Table 1: Average task scores.*

<img src="https://github.com/user-attachments/assets/73d03d5f-f795-4eb3-96ef-44893df5ddc6" width="400px"/>

*Figure 1: Task score bar chart.*

We observed a 100% completion across all tasks.
The qualitative feedback can be summarized in the following table:


| Task | Reaffirmed                                     | Improvement                                                                                       |
| ---- | ---------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| T1   | Obvious navigation patterns.                   | Highlighting the activities section.                                                              |
| T2   | Good error prevention.                         | Adding more feedback after the deletion of an activity (e.g., animations).                        |
| T3   | Good mood color choice.                        | Better wording: “How are you feeling today?”                                                      |
| T4   | N/A                                            | Not immediately obvious that “Statistics” is a button.  <br>Making the “October”-Label clickable. |
| T5   | Easy to navigate and logical process.          | N/A                                                                                               |
| T6   | Good navigation with a familiar settings page. | Not immediately obvious that “Lock” is a button.                                                  |

*Table 2: Task feedback summery.*

The background information section revealed that 50% of the participants kept a previous journal and were using it primarily to organize their thoughts and reflect on their day.
The biggest drawback of journaling was the time-consuming aspect. 

The debrief had an average, general score of 4.83 with many participants highlighting the clean UI design and easy to use interface layout.

5 out of 6 participants could imagine themself using GoodDays as a real product, while also requesting additional features such as more statistical insights and planning options.

Additionally, 5 out of 6 participants reported that they would think that GoodDays would be better suited as a mobile app.

Our raw evaluation data can be obtained using the following URL:
[https://docs.google.com/spreadsheets/d/1oWIWQ_Cr6HeE1DWeM4rKTfVSt_U-HavfuOCL68SdR3s/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1oWIWQ_Cr6HeE1DWeM4rKTfVSt_U-HavfuOCL68SdR3s/edit?usp=sharing)


## Conclusions

The overall task average, of 4.72, strongly indicates a positive experience. The only major deviation was task 4, scoring 4.0. Three test participants independently said that it would be better if they could click “October” on the calendar to see metrics for October, so that is one of the most obvious and pressing changes to make.

Participants also reported that some buttons could have been more obvious, particularly those in the navigation sidebar at the left.
Additionally, the general Feedback of the application could be improved by including animations or toast popups after actions like deleting an activity. These are usually difficult to archive using our Figma prototype, but present vital insights for the software implementation of the UI.

Ultimately, the feedback we received was quite positive, and we feel comfortable with many of the choices we’ve already made. Most of the tasks were completed quickly and painlessly. Of the six participants, when asked if they could see themselves using GoodDays in the future, five said “yes” and one said “maybe”.

## Caveats

Unfortunately, there are a few factors that somewhat reduce our confidence in our findings.

The pool of participants consisted solely of students in our class, so the demographics among them were limited in some ways. For example, they are all college students at CSU Chico, and many of them are majoring in Computer Science or a related field. The small sample size of N=6 was also a limiting factor.

In addition, our app is relatively simple and has few unique screens, so our tasks were also simple. Some were as simple as identifying and clicking a single button. We asked users to “think out loud”, but in some cases they completed the tasks so quickly that there was little for them to explain. It may have been better to combine some tasks into larger ones, with multiple steps involved.

It’s also possible that the wording of some tasks influenced our users’ behavior. For example, in task 4, we asked participants to find out how to see their most common mood “throughout October”. That wording may have led some of them to believe that clicking “October” would bring them to the appropriate metrics page.

Finally, for one of the tasks, you delete an activity by clicking it. In the actual application, we envisioned that clicking an activity would add it to the current entry, and you would right click it to delete it. We were unable to reflect this in Figma, so unfortunately the prototype’s behavior does not entirely reflect the final app’s.

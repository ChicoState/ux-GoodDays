# Phase II: Refining interaction and designing wireframes

## Introduction

GoodDays in our personal, desktop journaling app.

At the end of the last sprint, we gave the software engineering team a handful of user stories to focus on. We also gave them several paper sketches of a few ways they could implement the UI, but there were still many unanswered questions. Our sketches were quite different, and we didn’t know which elements of each we wanted to move forward with.

Now, we have a much clearer idea of what the UI should look like. We started by making wireframes. Then, we did a cognitive walkthrough to gather feedback, and used what we learned to improve the wireframes. Now that the software engineering team has an interactive, fleshed-out prototype of the user interface, they should have a much clearer idea of how to implement it.


## Methods

Cognitive Walkthroughs and Informal Feedbacks provided feedback that we used to improve our wireframes. 

> “A cognitive walkthrough is a technique used to evaluate the learnability of a system from the perspective of a new user.” </br>
>  ̶ [nngroup.com](https://www.nngroup.com/articles/cognitive-walkthroughs/)

This exercise exposed areas of improvement. We posted our wireframes into Slack and received feedback from external evaluators (other UX teams). There were three users total (n=3). Users noted down the clarity of each step. Unclear areas were identified and improved upon. Through this feedback, our wireframes now provide a holistic view of our application.

Our Software Development team demoed the first iteration of Good Days to their fellow CSCI 430 students (n=65). Our teammates asked for informal feedback from the audience at the conclusion of the demo. Informal feedback is given by external evaluators without structure. Instead of providing rigid feedback guidelines, we listen to our evaluators personal opinion of our application design. Through this informal feedback, we gained a wide variety of perspectives which aided our understanding of our user's needs.

See the results of these methods in the findings section.

## Findings

The positive aspects mentioned throughout the Cognitive Walkthroughs primarily highlighted the good discoverability and overview of day logs, which assured us in the current design of our calendar view.

However, three major problems were identified thought the three Cognitive Walkthroughs. 
(1) The user does not know if his information has been saved due to a lack of feedback. Our design proposes an auto save system, which does not require a specific save button. To increase the learnability and feedback of this system, we propose to instantly update the color of the day entry in the calendar based on the slider value. This enables the user to directly see his changed reflected in the separate calendar view.
(2) “The slider on the top of the notes doesn’t have an immediate purpose, since neutral doesn’t give an immediate thought” was a common quote thought the walkthroughs. The word “neutral” should be a label for an emotion. In the final product, this would be better identified with the emoji displayed above the label. To avoid any misunderstanding, we added the label “How was your mood?” to the slider input, as well as additional symbols at the different ends of the emotion spectrum.
(3) The users could not complete certain tasks, since some wireframes were not conceptualized. We solved this problem by full fleshing out our wireframes.


![image](https://github.com/user-attachments/assets/bb47408a-2ac1-4f68-a392-8d94bf74cd43)
<p style="text-align: center;"><i>The initial wireframe for evaluation vs. the refined new log entry screen.</i></p>

The feedback gathered towards the software engineering team prototype mentioned the importance of a statistics screen. Additionally, the focus should be put on the color schema, which is currently out of scope for our wireframes. The identification of a balanced color schema for our spectrum of emotions will be a major task for the following sprint.

## Conclusions

Our initial wireframes felt partially incomplete. The main page was essentially done, and we received positive feedback on it, but many of the other pages and features were missing. Since then, we’ve come a long way, adding a settings page, a metrics page, and interactivity. However, we haven’t done any research since improving the wireframes. Gathering more feedback would be a logical next step.


We’re happy with the progress we’ve made on our wireframes, but unfortunately they have diverged somewhat from the software engineering team’s prototype. Moving forward, we should prioritize inter-team communication so we can bridge the gap.

## Caveats

Unfortunately, there are several factors that detract somewhat from our research. Our cognitive walkthrough gave us a lot of valuable feedback, but it still wasn’t as comprehensive as it could have been. There were only a handful of respondents (n=3), and they were not professional UX designers. In addition, our personas are theoretical, rather than being informed by market research, so it’s possible that they fail to accurately represent our users. Finally, the cognitive walkthrough was performed a few weeks ago, and our wireframes have come a long way since then. We would really benefit from having structured feedback on the current iteration of the wireframes.


The informal feedback conducted by the software engineering team has its share of issues as well, making it difficult for us to act on what they learned. The sample size was large (n=65), but the audience consisted of students in the software engineering class, who may or may not have UX experience. Also, many of the responses were feature requests, rather than feedback on the SE team already had. However, the biggest issue by far is that the SE team’s prototype is very different from our wireframes. It’s likely that this


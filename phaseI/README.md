# Phase I: Analyzing Users, Competitors, and Initial Designs

## Introduction

GoodDays is a minimalist daily journaling app that allows users to log their feelings on a scale from 1 to 5 at the end of each day. Users can also record daily activities and optionally add written notes or comments. Additionally, they have the flexibility to add and remove custom activities to reflect on their daily habits and moods.

## Methods

In order to gain a better understanding of how to facilitate the best user experience possible, we used several research methods.

First, we used competitive analysis[^competitive-analysis], personally using several competing apps and recording our experiences. Unfortunately, the competitors we analyzed initially were mobile apps, and our software engineering team later decided to make a desktop app, so many of our early findings no longer apply. We accounted for this with further research, using heuristic evaluation to analyze Notion, a desktop notes/journaling app. We used Nielsen’s list of 10 heuristics[^nielsen-1994], rating Notion on a scale of 1-10 for each, to identify strengths that we can learn from and weaknesses where improvements could be made.

We also analyzed several personas and scenarios to learn more about our users’ needs. Though we believe that GoodDays is appealing to a very wide audience, we focused on a few of the biggest reasons why users would be drawn to GoodDays, rather than another journaling method. A key advantage of GoodDays is its convenience, so people who feel busy or overwhelmed could definitely benefit from it. We also believe that users who are struggling with a personal issue could get a lot out of GoodDays, since it would give them a way to organize their thoughts and track their progress over time. Our personas were chosen to reflect these two key groups.

To conclude this phase of research, we made some preliminary UI sketches for a minimum viable product.

## Findings

Two of our personas[^personas] are busy with school or work and are simply looking for an easy journaling experience, while the third is struggling with a recent breakup and looking for a way to organize his thoughts. Our personas and scenarios taught us that sometimes our users will want to include lots of detail in their entries, while others are pressed for time and will just want to include their mood and maybe an activity or two. We should ensure that the UI caters to both of these use cases.

We identified that a good app has…
- easy to understand UI 
- zero confusion between system and real world

App to research: [Custom Notion Board](https://gres.notion.site/10b16469034880e590e9e7024b08de15?v=9569263f9390427290fbf03037c3dc3f&pvs=4) (Our board can be accessed via this link for replication purposes.)

<p align="center">
  <img src="https://github.com/user-attachments/assets/61d28f5a-c7f8-4895-9743-c40635079736" />
  Figure 1: Calendar overview of the custom Notion board
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cd9e4fd6-8476-4888-a6c0-0a827940edf5" />
  Figure 2: Journal entry featuring custom activities and mood selection
</p>


Findings from heuristic evaluation:

|                                                         |                   |                                                                                                                                                                                  |
| ------------------------------------------------------- | ----------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Heuristic                                               | Score (out of 10) | Reasoning                                                                                                                                                                        |
| Visibility of System Status                             | 5                 | no preview of the mood of the day in the calendar view (e.g. having every day colored by the selected mood) - the general UI however feels responsive and provides good feedback |
| Match between system and real world                     | 9                 | There are no "custom words" that would be confusing. Uses real world analogies like calling new note entities "pages"                                                            |
| User control and freedom                                | 8                 | Clearly visible cancel buttons and actions. It would be hard to have an accident. The menu drops down and it's very clear what each button does.                                 |
| Consistency and standards                               | 9                 | Follows standard UI patterns for note apps. There is not much room for confusion                                                                                                 |
| Error prevention                                        | 10                | perfect undo/redo implementation                                                                                                                                                 |
| Recognition rather than recall                          | 8                 | Clear use of iconography                                                                                                                                                         |
| Flexibility and efficiency of use                       | 7                 | Requires a bit of customization to make it compatible with our use case                                                                                                          |
| Aesthetic and minimalist design                         | 8                 | Clean design language with modern UI elements 8                                                                                                                                  |
| Help users recognize, diagnose, and recover from errors | 7                 | Good error highlighting, however it is not possible to enforce constraints on page properties (e.g. having to choose a mode)                                                     |
| Help and documentation                                  | 8                 | Notion AI feature to ask questions, create drafts, brainstorm ideas, summarize...                                                                                                |

## Conclusions

Through our heuristic evaluation, we identified the need for simplicity and clarity in our desktop app, focusing on ease of use and intuitive flow. Our goal is to design an app that lets users access what they need while minimizing unnecessary elements. We aim to make our desktop app a smooth experience and prevent frustrations.

Key priorities:
System Status Visibility: Ensure the app is clear and easy to understand, reducing user confusion as much as possible.

Next sprint we will take feedback from the Software Team’s presentation to modify our website to improve these areas.


## Caveats

Our research methods make sense given the time and resource constraints, but unfortunately they’re mostly based on theory, rather than the experiences of actual users. Our analysis would be more comprehensive if we had the opportunity to do research involving potential users other than ourselves.


## References

[^competitive-analysis]: “5.3 Competitive Analysis - Entrepreneurship | OpenStax.” Accessed September 5, 2024. https://openstax.org/books/entrepreneurship/pages/5-3-competitive-analysis.

[^nielsen-1994]: Nielsen, Jakob, and Robert L. Mack, eds. Usability Inspection Methods. New York: Wiley, 1994.

[^personas]: “Personas.” In The Encyclopedia of Human-Computer Interaction, 2nd ed. Accessed September 12, 2024. https://www.interaction-design.org/literature/book/the-encyclopedia-of-human-computer-interaction-2nd-ed/personas.

Step 1: Interface Task Selection & Empirical Problem Framing
Target System Flow
I will test the appointment booking flow on the Utah DMV website. Participants will be asked to schedule an appointment to register a vehicle from out of state. This will include selecting the right service, finding an office, choosing a date and time, and completing the booking. 
Empirical Rationale
In my original usability study for the DMV website, all three participants reported booking an appointment was the hardest task. A large bottleneck was finding an office that actually offered appointments.
My redesign uses very easy, plain-language service names and a searchable office list with clear notes if an office does not offer appointments. I think these changes will help users set up an appointment faster and with fewer mistakes.  


Step 2: Hypothesis Formulation

I will be comparing Interface A, the original Utah DMV appointment booking flow, with Interface B, my redesigned booking flow. Both conditions will use the same task to schedule an appointment to register a vehicle from out of state. 

Directional Hypotheses (H1)
1. Time to complete the task
Participants using Interface B will finish the booking task in less time (on average) than participants using Interface A. 
2. Number of errors
Participants using Interface B will make fewer mistakes during the booking task than participants using Interface A. Errors will include choosing the wrong service, not knowing what to select next, or attempting to book at an office that does not offer appointments.
Null Hypotheses (H0)
1. Time to complete the task
The avg booking completion time for Interface B will be equal or higher than the average for Interface A. 
2. Number of errors
The avg booking errors for Interface B will be equal or higher than the average for Interface A. 


Step 3: Variable Formulation & Operationalization
Independent Variables (IVs)
Interface A (control): the original appointment booking flow
Interface B (treatment): my redesigned booking flow 

Dependent Variables (DVs)
Operationalize at least three measurable quantitative metrics to capture effectiveness, efficiency, and user satisfaction:
Efficiency Metric: Time-on-task measured in seconds (Task_Completion_Time_sec).
The timer will start when the user gets to the DMV booking home page, and will stop when the participant reaches the appointment confirmation screen with the correct service and an available office. 
I will compare completion times and report if any participants did not complete the task without errors.
Effectiveness Metric: Error frequency, discrete slip count, or successful task completion rate (Task_Success_Binary / Error_Count_Total).
I will count one error for each time a participant tries to select the wrong service or attempts to search for/book an office that does not offer appointments. Errors count even if the participant corrects them. 
Subjective Satisfaction Metric: Standardized post-task scale, such as the System Usability Scale (SUS_Score) or Single Ease Question (SEQ_Rating).
After each attempt I will ask, “Overall, how difficult or easy was the task to complete?” Participants will use a scale 1-7 to rate the overall difficulty. 

Confounding Variables & Controls
Identify potential confounds (e.g., prior system familiarity, input hardware variations, ambient glare, fatigue effects) and specify precise control strategies (e.g., standardized screen resolutions, fixed browser environments, pre-study screening surveys).

Prior experience with the DMV website
Before testing, I will ask if participants have booked a Utah DMV appointment online before and record their response. 
Device 
Each participant will use the same laptop, browser, and screen zoom % for each session.
Differences in instructions
I will give each participant the same instructions, provide the same demo information, and will not give hints during the task. 
Data to enter
I will give each participant sample data. Sample data will be the same for all participants. 



Step 4: Experimental Design Architecture & Counterbalancing
Subject Design Selection
I will be using a Between-Subjects design. Each participant will either use Interface A or Interface B and complete the booking task only once. This prevents participants from learning the system well enough to get a faster or more accurate result on a second try and skewing results. 

I will recruit 10 participants and randomly assign five to each interface. Before assigning groups, I will sort participants by whether they have booked a Utah DMV appointment online in the past. In each group, I will shuffle participants and assign them alternately to A and B, so they are randomly chosen for their group.

Participant Sampling Plan
Target users: Utah adults with a drivers license.

Inclusion criteria: Participants must be at least 18, live in Utah, and agree to participate. I will include people with and without prior experience with the DMV website booking flow. Assistive technology may be used. 

Exclusion criteria: people who participated in my original usability study or have already seen my redesign are excluded. 

Sample size rationale: this is a small exploratory study for a very specific screen flow, so five per interface will give me enough results to find patterns or common roadblocks between participants. 

Step 5: Ethical Protocol Safeguards
Informed Consent & Ethics
Draft a participant briefing script adhering to ethical research standards, ensuring participants understand that the software interface is being evaluated—never the user's intelligence or capability.
Thank you for helping with my Human-Computer Interaction exploratory study. I am evaluating the overall usability of the Utah DMV appointment booking system. This is a test of the website on a computer. If anything feels confusing or difficult, that will help me understand what steps could use improvement. 
I will ask you to use one version of the booking flow to schedule an appointment. Your goal is to book an appointment to register a vehicle from out of state. I will give you sample information to enter. After you are finished, I will ask you to rate how easy or difficult the task was. 
I will be recording your completion time. Any booking errors, and your rating under an anonymous Participant ID. The results will be summarized for my class assignment without using your name. You can use any assistive technology or accommodations you need. 
This is a voluntary study. You can skip the rating, take a break, or stop any time. Do you have any questions before we start and do you agree to participate? 




Post-Mortem Reflection
Why is it critical in HCI empirical research to distinguish between statistical significance (P < .05) and practical significance (real-world clinical or operational impact) when evaluating interface performance metrics?


Statistical significance helps judge whether the results actually provide enough evidence of a difference between the two interfaces. Practical significance has us consider if that difference is even large enough to matter to users overall. 

In my example, if my redesigned DMV booking flow saves 2 seconds on average, that difference could be technical statistically significant, but wouldn’t make much of a difference to a user. If the redesign were to save two minutes or reduces errors like selecting the wrong service, that would be a meaningful difference for the user. 


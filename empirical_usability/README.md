## Step 1: Study Scope & Participant Screener Formulation
Target System & Task Selection

1. Locate where you can book an appointment to register your vehicle after moving to Utah.
   You recently moved to Utah and brought a car with you. You live near ogden and work in the morning. Find a weekday afternoon appointment for registering your out of state vehicle. State the office, date, and time chosen.

   The task is complete when:
   - The participant identifies an available time slot that meets the given requirements.

2. Check if you can walk in for an appointment or not
   You need to replace a damaged license plate. You'll be near a DMV office during your lunch break in Ogden and want to know if you can walk in or need to find a different office. Use the website to figure out if you can walk in for this service.

   The task is complete when:
   The participant indentifies a walk in office for that specific service.


## Step 2: Participant Screener

I will recruit 3-5 adults living in Utah who own a vehicle. I will try to gather a mix of ages, comfort levels navigating online, and accessibility needs. 

1. **What is your age range?**
   Under 18 / 18-29 / 30-49 / 50-64 / 65+ / Prefer not to say 

2. **Do you currently live in Utah and own a vehicle?**
   Yes, both / I live in Utah but do not own a vehicle / I own a vehicle but do not live in Utah / Neither

3. **When you last used a website to fill out a form or schedule something, how did you do it?**
   On my own / With help from someone else / I have never done this

4. **Have you used the Utah DMV website before?**
   Yes / No / Not sure

5. **What tools, settings, or accomodations do you use when browsing websites, if any?**
   Optional short answer. Examples: text zoom, screen reader, voice input, or keyboard navigation.


**Selection criteria:** Participants must be 18 or older and answer "yes, both" to Question 2. Anyone who prefers to keep their age range can confirm that they are at least 18 in private. I will use questions 3-5 to recruit people with different experience levels and let participants use their own accessibility tools during the session.

## Moderator Script and Informed Consent

## Before the tasks
Read the following to each participant before starting any recording.

> Thank you for helping me test the Utah DMV website. I'm evaluating how the website works for different people.
> This session is about the website, and your personal ability and performance are not included in the study.
>
> Participating is voluntary. You may skip a question, take a break, or withdraw at any point.
>
> I will be taking notes during the session. With your permission, I will also record your test window and voice.
> You can decline recording and still participate. I will label notes and recordings with a participant code.
> These codes are anonymous. Your name and other identifying characteristics will not be noted.
> A recording may still contain your voice, so I will keep recordings private and delete it after I finish my review of the session.
>
> Do you agree to participate?
> May I record your test window and voice?

Record both answers separately. Start the session only after the participant agrees to participate. Start recording only if they agree to be recorded. 
Ask participants to keep personal information off screen and stop before reserving a real appointment. 

### Think-aloud instructions
> As you use the website, please say what you are looking for, what you expect the result to be, and anything you find confusing.
> Tell me when you think you've finished the task or when you'd like to stop.

Use the task scenarios above as the participant handouts and read each one exactly as written. 
If a participant is quiet for at least 15 seconds, say "Please keep thinking out loud." 
If they ask where to click, say "what would you try if I weren't here?"
Read the scenario again if requested. 
Keep your tone and body language neutral throughout the task, and give feedback after both tasks are finished. 


## Step 3: Performance Metrics and Observation Log
Use one row per participant, per task in the [observation log][usability_logging_sheet.csv]
Use participant codes (e.g. P01, P02, etc)

| Metric | How to record |
|---|---|
| Time on Task ('Task_Time_sec') | Start the timer as soon as you finish the instruction prompt. For Task 1, stop when the participant gives their final office, date, and time selection. For Task 2, stop when they give their answer about what office they could walk in. If they give up, stop the timer and record the reason. |
| Task success ('Task_Success') | **1** = completed with correct results, no help required. **0.5** completed with correct results, but hint required. **0** = incorrect results or participant gives up. |
| Error count ('Error_Count') | Count each distinct wrong turn, click that produces no response, or incorrect entry. Record what happened and at what point in the process. Count a repeated error only if the participant makes a separate attempt. |
| Single Easy Question ('SEQ_1_to_7') | After each task attempt, before any feedback or further hints, ask "Overall, from 1-7 how easy or difficult was this task to finish?" Record one rating from 1 (very difficult) to 7 (very easy). 4 is the midpoint. |

Record any hints and when they are given. 
If the participant withdraws or a technical interruption occurs that ends the session, record the reason and leave the success score blank.

Record visible facial expressions, participant's verbal notes about what confused them, physical hesitation, or changes in posture. Be descriptive. Leave fields blank if no observation noted. 


## System Usability Scale (SUS

After both tasks and their overall ratings, I will ask each participant to complete the 10-item System Usability Scale.
I will ask them to rate their overall experience with the Utah DMV website.

The survey will use the 10 statements outlined in the Lab 5 assignment details.

Scale:
1. Strongly disagree
2. Disagree
3. Neither agree nor disagree
4. Agree
5. Strongly agree

### Scoring

- For odd-numbered items (1, 3, 5, 7, and 9), subtract 1 from the response.
- For even-numbered items (2, 4, 6, 8, and 10), subtract the response from 5.
- Add the 10 adjusted values and multiply the total by 2.5

Form Link: [https://docs.google.com/forms/d/e/1FAIpQLSd1vd_H2oEg2arj5LddQ_k8qCbFrzFEd6g0-8VxSxnAvcS2Gw/viewform?usp=publish-editor](url)



## Step 5: Accessibility Audit
- **Explicit Labels - Pass** In Chrome's DevTools, I confirmed that the 1 - Strongly Disagree option uses a '<label for="i6">' that matches the radio input 'id="i6"'
- **Keyboard Navigation with Visible Focus - Pass** I used tab to move between questions and arrow keys to move between answer options. I could see which option had keyboard focus.
- **Text contrast - Pass** The response label text had a contrast ratio of 8.5
- **Missing-response error markup - Pass** When I submitted with a required question left blank, Google Forms displayed "This is a required question." In Chrome's DevTools, I confirmed that the message's parent element uses 'role="alert"'



## Post =Mortem Reflection
### 1. Why does the SUS alternate positive and negative statements?
The SUS alternates statements to help counter acquiescence bias. This is the tendency for the participant to agree with statements regardless of what they say. Alternating could also prevent users from trying to answer "correctly" by the form having no clear bias positive or negative. 

## 2. How can moderator cues affect think-aloud results?
If a moderator nods when a participant hovers near the correct option to move forward, this could help them choose it faster as well as prevent an error click. If the moderator frowns or adjusts when they take a valid path, they could backtrack which would add time and possible errors. To reduce this bias, each task is read as written, body language and tone neutral, and neutral reminders are given to encourage ongoing out loud thinking. Directional hints are recorded as such. 

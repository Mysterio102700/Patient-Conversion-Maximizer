# Patient Conversion Maximizer Interactive Demo - Updated Wireframes

## Overview

This document contains updated wireframe designs for the Patient Conversion Maximizer interactive demo, now supporting all three scenarios:
1. After-Hours Emergency Call (already implemented)
2. Busy Front Desk Missing Calls (new)
3. Patient Follow-up & Reactivation (new)

The wireframes follow the user flow outlined in the storyboard document and incorporate the copy from the updated copy deck.

## Scenario Selection Screen

```
+----------------------------------------------------------+
|                                                          |
|  [X] Close                                               |
|                                                          |
|  +------------------------------------------------------+|
|  |                                                      ||
|  |  Explore Practice Challenges Solved by AI            ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  [After-Hours Emergency Call]            |        ||
|  |  |  See how AI handles urgent patient calls |        ||
|  |  |  when your office is closed, ensuring no |        ||
|  |  |  emergency goes unaddressed and no       |        ||
|  |  |  opportunity is missed.                  |        ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  [Busy Front Desk Missing Calls]         |        ||
|  |  |  Your team is helping patients in-office |        ||
|  |  |  while calls pile up. See how AI ensures |        ||
|  |  |  every caller receives immediate         |        ||
|  |  |  attention without putting anyone on hold.|        ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  [Patient Follow-up & Reactivation]      |        ||
|  |  |  Patients who miss appointments or need  |        ||
|  |  |  follow-up often fall through the cracks.|        ||
|  |  |  See how automated sequences keep them   |        ||
|  |  |  engaged and on track with treatment plans.|      ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  +------------------------------------------------------+|
|                                                          |
|  [Back]                        [Start Selected Scenario] |
|                                                          |
+----------------------------------------------------------+
```

## Scenario 1: After-Hours Call (Already Implemented)

*Note: This scenario is already implemented in the current demo. Wireframes included for reference.*

### Scene 1: After-Hours Call Scenario

```
+----------------------------------------------------------+
|                                                          |
|  [X] Close                       Step 1 of 3 [Progress]  |
|                                                          |
|  +------------------------------------------------------+|
|  |                                                      ||
|  |  After Hours: When Patients Need You Most            ||
|  |                                                      ||
|  |  It's 8:45 PM on Saturday. Your practice is closed,  ||
|  |  but patient needs don't follow business hours.      ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  [Smartphone Interface]                  |        ||
|  |  |                                          |        ||
|  |  |  8:45 PM                      Saturday   |        ||
|  |  |                                          |        ||
|  |  |  [Incoming Call Animation]               |        ||
|  |  |  Jane Smith - Potential New Patient      |        ||
|  |  |                                          |        ||
|  |  |  [Answer] [Decline]                      |        ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  |  Without AI assistance, this call would go to        ||
|  |  voicemail. 87% of patients who reach voicemail      ||
|  |  will call your competitor next.                     ||
|  |                                                      ||
|  |  [Play AI Conversation] <-- Button                   ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  ✓ New Patient Lead Captured             |        ||
|  |  |                                          |        ||
|  |  |  Name: Jane Smith                        |        ||
|  |  |  Contact: (555) 123-4567                 |        ||
|  |  |  Concern: Tooth pain, possible infection |        ||
|  |  |  Urgency: High - Next day appointment    |        ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  +------------------------------------------------------+|
|                                                          |
|  [Try Another Scenario]         [See What Happens Next →]|
|                                                          |
+----------------------------------------------------------+
```

### Scene 2: Instant SMS Follow-up

```
+----------------------------------------------------------+
|                                                          |
|  [X] Close                       Step 2 of 3 [Progress]  |
|                                                          |
|  +------------------------------------------------------+|
|  |                                                      ||
|  |  Instant Follow-up: Converting Inquiries to          ||
|  |  Appointments                                        ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  [Smartphone Interface]                  |        ||
|  |  |                                          |        ||
|  |  |  8:47 PM                      Saturday   |        ||
|  |  |                                          |        ||
|  |  |  AI Assistant (8:47 PM):                 |        ||
|  |  |  Hi Jane, this is Amy from Bayside       |        ||
|  |  |  Dental confirming your emergency        |        ||
|  |  |  appointment for tomorrow (Sunday)       |        ||
|  |  |  at 9:00 AM with Dr. Roberts. Reply      |        ||
|  |  |  YES to confirm or suggest another       |        ||
|  |  |  time. Reply HELP for assistance.        |        ||
|  |  |                                          |        ||
|  |  |  Jane (8:49 PM):                         |        ||
|  |  |  YES, thank you! Can I fill out forms    |        ||
|  |  |  ahead of time?                          |        ||
|  |  |                                          |        ||
|  |  |  AI Assistant (8:49 PM):                 |        ||
|  |  |  Perfect! I've reserved your spot with   |        ||
|  |  |  Dr. Roberts. You can complete your      |        ||
|  |  |  intake forms here: [secure.link/intake] |        ||
|  |  |  This saves time tomorrow. Directions    |        ||
|  |  |  to our office: [maps.link/directions]   |        ||
|  |  |  Need to reschedule? Just text or call   |        ||
|  |  |  this number.                            |        ||
|  |  |                                          |        ||
|  |  |  Jane (8:52 PM):                         |        ||
|  |  |  Got it, thanks for the quick response!  |        ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  |  While your competitors send patients to voicemail,  ||
|  |  your practice converts them to appointments—even    ||
|  |  at 8:45 PM on a Saturday.                          ||
|  |                                                      ||
|  |  Emergency appointments average $1,250 in immediate  ||
|  |  revenue and $5,400 in lifetime value               ||
|  |                                                      ||
|  +------------------------------------------------------+|
|                                                          |
|  [Try Another Scenario]         [View Practice Dashboard]|
|                                                          |
+----------------------------------------------------------+
```

### Scene 3: Analytics Dashboard

```
+----------------------------------------------------------+
|                                                          |
|  [X] Close                       Step 3 of 3 [Progress]  |
|                                                          |
|  +------------------------------------------------------+|
|  |                                                      ||
|  |  Actionable Insights: After-Hours Conversion         ||
|  |                                                      ||
|  |  After-Hours Performance Dashboard - Weekly Summary  ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  [HIPAA Compliant Badge]                 |        ||
|  |  |                                          |        ||
|  |  |  +----------------+  +----------------+  |        ||
|  |  |  | Total Patient  |  | Average        |  |        ||
|  |  |  | Inquiries:     |  | Response Time: |  |        ||
|  |  |  |                |  |                |  |        ||
|  |  |  | 127            |  | 0.8 minutes    |  |        ||
|  |  |  | (+34%)         |  | vs 3.2 hours   |  |        ||
|  |  |  +----------------+  +----------------+  |        ||
|  |  |                                          |        ||
|  |  |  +----------------+  +----------------+  |        ||
|  |  |  | Conversion     |  | After-Hours    |  |        ||
|  |  |  | Rate:          |  | Conversions:   |  |        ||
|  |  |  |                |  |                |  |        ||
|  |  |  | 78%            |  | 31 new         |  |        ||
|  |  |  | vs 43% avg     |  | patients       |  |        ||
|  |  |  +----------------+  +----------------+  |        ||
|  |  |                                          |        ||
|  |  |  [Chart: Call Volume by Hour of Day]     |        ||
|  |  |  [Shows significant after-hours volume]  |        ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  |  Revenue Impact Calculator                           ||
|  |                                                      ||
|  |  New Patients Captured After-Hours: 31               ||
|  |  Average Patient Value: $3,200                       ||
|  |  Estimated Monthly Revenue Impact: $99,200           ||
|  |                                                      ||
|  +------------------------------------------------------+|
|                                                          |
|  [Try Another Scenario]    [Book Your Personalized Demo] |
|                                                          |
+----------------------------------------------------------+
```

## Scenario 2: Busy Front Desk Missing Calls (New)

### Scene 1: Busy Office Hours Call

```
+----------------------------------------------------------+
|                                                          |
|  [X] Close                       Step 1 of 3 [Progress]  |
|                                                          |
|  +------------------------------------------------------+|
|  |                                                      ||
|  |  Office Hours: When Every Call Counts                ||
|  |                                                      ||
|  |  It's 11:30 AM on Tuesday. Your front desk staff is  ||
|  |  helping in-office patients while calls are piling up.||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  [Smartphone Interface]                  |        ||
|  |  |                                          |        ||
|  |  |  11:30 AM                     Tuesday    |        ||
|  |  |                                          |        ||
|  |  |  [Incoming Call Animation]               |        ||
|  |  |  Michael Johnson - Potential New Patient |        ||
|  |  |                                          |        ||
|  |  |  3 calls in queue • Average wait: 4:30   |        ||
|  |  |                                          |        ||
|  |  |  [Answer] [Decline]                      |        ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  |  Without AI assistance, this call would go to        ||
|  |  voicemail or be placed on a long hold. 68% of       ||
|  |  patients will not call back if their first call     ||
|  |  goes unanswered.                                    ||
|  |                                                      ||
|  |  [Play AI Conversation] <-- Button                   ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  ✓ New Patient Lead Captured & Scheduled |        ||
|  |  |                                          |        ||
|  |  |  Name: Michael Johnson                   |        ||
|  |  |  Contact: (555) 987-6543                 |        ||
|  |  |  Concern: Back pain, new patient referral|        ||
|  |  |  Preference: This week appointment       |        ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  +------------------------------------------------------+|
|                                                          |
|  [Try Another Scenario]         [See What Happens Next →]|
|                                                          |
+----------------------------------------------------------+
```

### Scene 2: Instant Appointment Scheduling

```
+----------------------------------------------------------+
|                                                          |
|  [X] Close                       Step 2 of 3 [Progress]  |
|                                                          |
|  +------------------------------------------------------+|
|  |                                                      ||
|  |  Seamless Scheduling: From Call to Confirmation      ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  [Calendar Interface]                    |        ||
|  |  |                                          |        ||
|  |  |  Finding optimal appointment slot based  |        ||
|  |  |  on patient needs and provider availability       ||
|  |  |                                          |        ||
|  |  |  [Calendar Animation with Available Slots]        ||
|  |  |                                          |        ||
|  |  |  Appointment confirmed:                  |        ||
|  |  |  Thursday, 2:00 PM with Dr. Williams     |        ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  |  Comprehensive follow-up automatically initiated:    ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  ✓ Appointment confirmation email sent   |        ||
|  |  |  ✓ New patient intake forms attached     |        ||
|  |  |  ✓ Office location and parking info      |        ||
|  |  |  ✓ Insurance verification request        |        ||
|  |  |  ✓ Reminder scheduled for 24h before     |        ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  |  Your AI assistant handles appointment scheduling    ||
|  |  and sends all necessary information automatically,  ||
|  |  freeing your staff to focus on in-office patients.  ||
|  |                                                      ||
|  |  Each captured call during busy periods represents   ||
|  |  an average of $2,100 in new patient revenue that    ||
|  |  would otherwise be lost.                            ||
|  |                                                      ||
|  +------------------------------------------------------+|
|                                                          |
|  [Try Another Scenario]         [View Practice Dashboard]|
|                                                          |
+----------------------------------------------------------+
```

### Scene 3: Analytics Dashboard

```
+----------------------------------------------------------+
|                                                          |
|  [X] Close                       Step 3 of 3 [Progress]  |
|                                                          |
|  +------------------------------------------------------+|
|  |                                                      ||
|  |  Actionable Insights: Front Desk Efficiency          ||
|  |                                                      ||
|  |  Front Desk Efficiency Dashboard - Weekly Summary    ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  [HIPAA Compliant Badge]                 |        ||
|  |  |                                          |        ||
|  |  |  +----------------+  +----------------+  |        ||
|  |  |  | Simultaneous   |  | Average        |  |        ||
|  |  |  | Calls Handled: |  | Hold Time:     |  |        ||
|  |  |  |                |  |                |  |        ||
|  |  |  | 47             |  | 0.5 seconds    |  |        ||
|  |  |  | (would be missed) | vs 1.5 minutes |  |        ||
|  |  |  +----------------+  +----------------+  |        ||
|  |  |                                          |        ||
|  |  |  +----------------+  +----------------+  |        ||
|  |  |  | Staff Time     |  | Patient        |  |        ||
|  |  |  | Saved:         |  | Satisfaction:  |  |        ||
|  |  |  |                |  |                |  |        ||
|  |  |  | 14.2 hours/week|  | 4.9/5         |  |        ||
|  |  |  |                |  | vs 4.2/5 before|  |        ||
|  |  |  +----------------+  +----------------+  |        ||
|  |  |                                          |        ||
|  |  |  [Chart: Call Volume vs. Staff Availability]      ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  |  Revenue Impact Calculator                           ||
|  |                                                      ||
|  |  Weekly Calls Handled During Peak Hours: 47          ||
|  |  Conversion Rate to Appointments: 72%                ||
|  |  Average New Patient Value: $2,100                   ||
|  |  Estimated Monthly Revenue Impact: $71,064           ||
|  |                                                      ||
|  +------------------------------------------------------+|
|                                                          |
|  [Try Another Scenario]    [Book Your Personalized Demo] |
|                                                          |
+----------------------------------------------------------+
```

## Scenario 3: Patient Follow-up & Reactivation (New)

### Scene 1: Missed Appointment Follow-up

```
+----------------------------------------------------------+
|                                                          |
|  [X] Close                       Step 1 of 3 [Progress]  |
|                                                          |
|  +------------------------------------------------------+|
|  |                                                      ||
|  |  Patient Reactivation: Recovering Lost Opportunities ||
|  |                                                      ||
|  |  It's 5:30 PM on Wednesday. Your staff has left for  ||
|  |  the day, but 12 patients need follow-up.            ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  [Practice Management Dashboard]         |        ||
|  |  |                                          |        ||
|  |  |  5:30 PM                     Wednesday   |        ||
|  |  |                                          |        ||
|  |  |  12 patients require follow-up          |        ||
|  |  |  Staff availability: None until tomorrow |        ||
|  |  |                                          |        ||
|  |  |  [Patient Selection Interface]           |        ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  |  Without automated follow-up, 42% of missed          ||
|  |  appointments are never rescheduled, resulting in    ||
|  |  incomplete treatment plans and lost revenue.        ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  Patient: Robert Garcia                  |        ||
|  |  |  Status: Missed appointment on Tuesday   |        ||
|  |  |  History: Regular patient for 3 years    |        ||
|  |  |  Last Visit: 3 months ago                |        ||
|  |  |  Treatment Plan: Physical therapy,       |        ||
|  |  |                  8/12 sessions completed |        ||
|  |  |  Insurance: Coverage active              |        ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  |  AI analyzing patient history, preferred             ||
|  |  communication channels, and optimal contact times   ||
|  |                                                      ||
|  |  Optimal channel selected: SMS                       ||
|  |  Optimal time: Now (high response probability)       ||
|  |                                                      ||
|  +------------------------------------------------------+|
|                                                          |
|  [Try Another Scenario]     [View Patient Communication] |
|                                                          |
+----------------------------------------------------------+
```

### Scene 2: Intelligent Patient Reactivation

```
+----------------------------------------------------------+
|                                                          |
|  [X] Close                       Step 2 of 3 [Progress]  |
|                                                          |
|  +------------------------------------------------------+|
|  |                                                      ||
|  |  Smart Reengagement: Personalized Patient Outreach   ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  [Smartphone Interface]                  |        ||
|  |  |                                          |        ||
|  |  |  5:32 PM                     Wednesday   |        ||
|  |  |                                          |        ||
|  |  |  AI Assistant (5:32 PM):                 |        ||
|  |  |  Hi Robert, we noticed you missed your   |        ||
|  |  |  physical therapy appointment on Tuesday.|        ||
|  |  |  You've completed 8 of 12 recommended    |        ||
|  |  |  sessions. Would you like to reschedule  |        ||
|  |  |  to continue your progress? We have      |        ||
|  |  |  openings tomorrow at 10:00 AM or 3:30 PM.|       ||
|  |  |                                          |        ||
|  |  |  Robert (5:35 PM):                       |        ||
|  |  |  Sorry about that, I had a work emergency.|       ||
|  |  |  3:30 PM tomorrow works for me.          |        ||
|  |  |                                          |        ||
|  |  |  AI Assistant (5:35 PM):                 |        ||
|  |  |  Great! I've rescheduled your appointment|        ||
|  |  |  for tomorrow at 3:30 PM with Dr. Martinez.|      ||
|  |  |  You'll receive a reminder 1 hour before.|        ||
|  |  |  Would you like me to send you the       |        ||
|  |  |  exercises Dr. Martinez recommended for  |        ||
|  |  |  home practice?                          |        ||
|  |  |                                          |        ||
|  |  |  Robert (5:37 PM):                       |        ||
|  |  |  Yes, that would be helpful. Thanks!     |        ||
|  |  |                                          |        ||
|  |  |  AI Assistant (5:37 PM):                 |        ||
|  |  |  Perfect! I've sent the exercises to your|        ||
|  |  |  email. See you tomorrow at 3:30 PM.     |        ||
|  |  |  Reply HELP if you need anything else.   |        ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  ✓ Patient Reactivated: Robert Garcia    |        ||
|  |  |  ✓ Appointment Rescheduled: Thursday, 3:30 PM     ||
|  |  |  ✓ Treatment Plan: Back on track (9/12)  |        ||
|  |  |  ✓ Additional Value: Home exercise plan  |        ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  |  Your AI assistant proactively reengages patients    ||
|  |  who might otherwise drop out of their treatment     ||
|  |  plans, improving outcomes and practice revenue.     ||
|  |                                                      ||
|  |  Completing treatment plans increases patient        ||
|  |  satisfaction by 47% and boosts lifetime patient     ||
|  |  value by 28%.                                       ||
|  |                                                      ||
|  +------------------------------------------------------+|
|                                                          |
|  [Try Another Scenario]         [View Practice Dashboard]|
|                                                          |
+----------------------------------------------------------+
```

### Scene 3: Analytics Dashboard

```
+----------------------------------------------------------+
|                                                          |
|  [X] Close                       Step 3 of 3 [Progress]  |
|                                                          |
|  +------------------------------------------------------+|
|  |                                                      ||
|  |  Actionable Insights: Patient Retention              ||
|  |                                                      ||
|  |  Patient Engagement & Retention Dashboard            ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  [HIPAA Compliant Badge]                 |        ||
|  |  |                                          |        ||
|  |  |  +----------------+  +----------------+  |        ||
|  |  |  | Missed Appts   |  | Treatment Plan |  |        ||
|  |  |  | Recovered:     |  | Completion:    |  |        ||
|  |  |  |                |  |                |  |        ||
|  |  |  | 87%            |  | 92%            |  |        ||
|  |  |  | vs 43% avg     |  | vs 68% before  |  |        ||
|  |  |  +----------------+  +----------------+  |        ||
|  |  |                                          |        ||
|  |  |  +----------------+  +----------------+  |        ||
|  |  |  | Patient        |  | Avg Response   |  |        ||
|  |  |  | Reactivation:  |  | Time:          |  |        ||
|  |  |  |                |  |                |  |        ||
|  |  |  | 76%            |  | 2.4 minutes    |  |        ||
|  |  |  | vs 31% avg     |  | (24/7)         |  |        ||
|  |  |  +----------------+  +----------------+  |        ||
|  |  |                                          |        ||
|  |  |  [Chart: Treatment Plan Completion Rates]|        ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  |  Revenue Impact Calculator                           ||
|  |                                                      ||
|  |  Monthly Recovered Appointments: 64                  ||
|  |  Average Value Per Completed Treatment Plan: $3,800  ||
|  |  Reduction in Patient Churn: 47%                     ||
|  |  Estimated Monthly Revenue Impact: $83,200           ||
|  |                                                      ||
|  +------------------------------------------------------+|
|                                                          |
|  [Try Another Scenario]    [Book Your Personalized Demo] |
|                                                          |
+----------------------------------------------------------+
```

## Technical Implementation Notes

1. **Scenario Selection:**
   - The scenario selection screen will be accessible from any point in the demo via the "Try Another Scenario" button
   - Each scenario card will have a unique data attribute to identify it (data-scenario="1", "2", or "3")
   - When a scenario is selected, the demo will reset all state variables and load the appropriate content

2. **Shared Components:**
   - All scenarios will share the same modal framework, progress indicators, and navigation buttons
   - The "Try Another Scenario" button will be hidden in Scene 1 of each scenario and visible in Scenes 2 and 3
   - The final CTA button will be consistent across all scenarios in Scene 3

3. **Responsive Design:**
   - All scenario screens will adapt to mobile devices using the same responsive design principles
   - On smaller screens, two-column layouts will collapse to single columns
   - Touch targets will be at least 44×44px for mobile accessibility

4. **Accessibility Considerations:**
   - All interactive elements will be keyboard navigable
   - Focus management will be maintained when switching between scenarios
   - ARIA roles and labels will be used appropriately
   - Color contrast will meet WCAG AA standards (4.5:1 for normal text)

5. **Animation and Transitions:**
   - Transitions between scenarios will use fade effects for smooth user experience
   - Animations will respect the prefers-reduced-motion setting
   - Loading states will be shown when switching between scenarios

6. **State Management:**
   - Each scenario will have its own set of state variables
   - The current scenario will be tracked in a global state variable
   - Progress through each scenario will be tracked independently

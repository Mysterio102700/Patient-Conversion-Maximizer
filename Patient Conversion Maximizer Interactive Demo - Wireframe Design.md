# Patient Conversion Maximizer Interactive Demo - Wireframe Design

## Overview

This document contains wireframe designs for the Patient Conversion Maximizer interactive demo. The wireframes follow the user flow outlined in the storyboard document and incorporate the copy from the copy deck. The design prioritizes accessibility, performance, and a clear path to the "Book a Call" CTA.

## Widget Trigger Design

```
+------------------------------------------+
|                                          |
|  +------------------------------------+  |
|  |                                    |  |
|  |  [Phone Icon with Notification]    |  |
|  |                                    |  |
|  |  Never Miss Another Patient Call   |  |
|  |  — Try the AI Demo                 |  |
|  |                                    |  |
|  |  See how our AI answers calls,     |  |
|  |  sends follow-ups, and books       |  |
|  |  appointments while you focus on   |  |
|  |  patient care.                     |  |
|  |                                    |  |
|  |  [Experience the Demo] <-- Button  |  |
|  |                                    |  |
|  |  Quick 60-second interactive       |  |
|  |  experience                        |  |
|  |                                    |  |
|  +------------------------------------+  |
|                                          |
+------------------------------------------+
```

### Widget Trigger Specifications:
- Position: Fixed bottom-right of viewport
- Initial state: Collapsed to phone icon with notification badge
- Expanded state: Card with headline, subcopy, and CTA button
- Animation: Subtle pulse effect on notification badge
- Responsive behavior: Adapts to mobile as bottom banner

## Demo Modal Framework

```
+----------------------------------------------------------+
|                                                          |
|  [X] Close                       Step X of 3 [Progress]  |
|                                                          |
|  +------------------------------------------------------+|
|  |                                                      ||
|  |  [Scene Header]                                      ||
|  |                                                      ||
|  |  [Scene Content Area]                                ||
|  |                                                      ||
|  |                                                      ||
|  |                                                      ||
|  |                                                      ||
|  |                                                      ||
|  |                                                      ||
|  |                                                      ||
|  +------------------------------------------------------+|
|                                                          |
|  [Try Another Scenario]         [Primary Action Button]  |
|                                                          |
|  [Skip to booking a call →]                              |
|                                                          |
+----------------------------------------------------------+
```

### Modal Framework Specifications:
- Size: 80% of viewport width (max 900px), 70% of viewport height
- Position: Centered with overlay background
- Accessibility: Focus trap within modal when open
- Close behavior: "X" button and ESC key
- Animation: Fade in/out with subtle scale effect

## Scene 1: After-Hours Call Scenario

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
|  [Skip to booking a call →]                              |
|                                                          |
+----------------------------------------------------------+
```

### Scene 1 Specifications:
- Phone visualization: Realistic smartphone frame
- Call animation: Ringing effect with vibration indication
- Audio player: Appears after clicking "Play AI Conversation"
- Audio transcript: Expandable below audio player
- Patient card: Appears after audio completes or is skipped

## Scene 2: Instant SMS Follow-up

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
|  [Skip to booking a call →]                              |
|                                                          |
+----------------------------------------------------------+
```

### Scene 2 Specifications:
- Text message animation: Messages appear sequentially with typing indicators
- Timing: Realistic delays between messages
- Links: Styled as clickable but with tooltips explaining they're demo links
- Value proposition: Highlighted box or different background color

## Scene 3: HIPAA-Compliant Analytics Dashboard

```
+----------------------------------------------------------+
|                                                          |
|  [X] Close                       Step 3 of 3 [Progress]  |
|                                                          |
|  +------------------------------------------------------+|
|  |                                                      ||
|  |  Actionable Insights: Measure What Matters           ||
|  |                                                      ||
|  |  Practice Performance Dashboard - Weekly Summary     ||
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

### Scene 3 Specifications:
- Dashboard style: Clean, professional with Orange Carrot brand colors
- Charts: Simple, clear visualizations with minimal animation
- HIPAA badge: Prominent with tooltip on hover
- Calculator: Pre-filled with example values
- Final CTA: Largest, most prominent button in the entire flow

## Alternative Scenario Selection Screen

```
+----------------------------------------------------------+
|                                                          |
|  [X] Close                                               |
|                                                          |
|  +------------------------------------------------------+|
|  |                                                      ||
|  |  Explore More Practice Challenges                    ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  [After-Hours Emergency Call]            |        ||
|  |  |  Default scenario showing how AI handles |        ||
|  |  |  patient calls when your office is       |        ||
|  |  |  closed.                                 |        ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  [Busy Front Desk Missing Calls]         |        ||
|  |  |  Your team is helping patients in-office |        ||
|  |  |  while calls pile up. See how AI ensures |        ||
|  |  |  no inquiry goes unanswered.             |        ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  |  +------------------------------------------+        ||
|  |  |                                          |        ||
|  |  |  [Patient Follow-up & Reactivation]      |        ||
|  |  |  Patients who need follow-up often fall  |        ||
|  |  |  through the cracks. See how automated   |        ||
|  |  |  sequences keep them engaged.            |        ||
|  |  |                                          |        ||
|  |  +------------------------------------------+        ||
|  |                                                      ||
|  +------------------------------------------------------+|
|                                                          |
|  [Back]                        [Book Your Demo Call]     |
|                                                          |
+----------------------------------------------------------+
```

### Alternative Scenario Specifications:
- Selection cards: Equal size, clickable areas
- Visual indicators: Icons representing each scenario
- Selection behavior: Clicking card starts that scenario from Scene 1

## Mobile Adaptations

### Widget Trigger (Mobile)
```
+------------------------------------------+
|                                          |
|  [Phone Icon] Never Miss Another Call    |
|  Try the AI Demo                         |
|                                          |
+------------------------------------------+
```

### Demo Modal (Mobile)
```
+------------------------------------------+
|                                          |
|  [X]                      Step X of 3    |
|                                          |
|  [Scene Header]                          |
|                                          |
|  [Full-width Content Area]               |
|                                          |
|  [Primary Action Button]                 |
|                                          |
|  [Try Another Scenario]                  |
|                                          |
+------------------------------------------+
```

### Mobile-Specific Notes:
- Full-screen modal on mobile devices
- Simplified layouts with vertical stacking
- Touch-friendly tap targets (min 44x44px)
- Reduced animations for performance
- Orientation guidance for optimal experience

## Accessibility Considerations

1. **Color Contrast:**
   - All text meets WCAG AA 4.5:1 contrast ratio
   - Interactive elements have 3:1 contrast against backgrounds
   - No information conveyed by color alone

2. **Text Sizing:**
   - Base font size: 16px
   - Minimum text size: 14px
   - Headings properly hierarchical (H1, H2, etc.)

3. **Keyboard Navigation:**
   - All interactive elements focusable
   - Focus order follows logical reading order
   - Focus styles visible and prominent

4. **Screen Reader Support:**
   - All images have alt text
   - ARIA roles and landmarks where appropriate
   - Dynamic content changes announced

5. **Reduced Motion:**
   - Respects prefers-reduced-motion setting
   - Essential animations only
   - No flashing content

## Technical Implementation Notes

1. **Performance Optimization:**
   - Lazy load scenes as needed
   - Preload next scene assets
   - Optimize images and animations

2. **Browser Compatibility:**
   - Support latest Chrome, Safari, Firefox, Edge
   - Graceful degradation for older browsers
   - Polyfills for ES6+ features

3. **Mobile Considerations:**
   - Touch events for mobile interactions
   - Viewport meta tag configuration
   - Media queries for responsive layouts

4. **Embedding Requirements:**
   - Self-contained bundle
   - No external dependencies where possible
   - Namespace isolation to prevent conflicts

This wireframe design document provides a comprehensive visual guide for implementing the Patient Conversion Maximizer interactive demo, ensuring alignment with the user flow, copy deck, and technical requirements.

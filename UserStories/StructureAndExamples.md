User Stories: Structure and Examples
====================================

| 172: Add Item to Basket             |
|-------------------------------------|
| **AS A** customer                   |
| **I WANT** to add items to a basket |
| **SO THAT** I can review them later |
|                                     |
| Priority: 8                         |
| Points: 5                           |


Key:

172                - unique ID for the story  
Add Item to Basket - title for the story  
**AS A**           - phrase to define the user whose needs this story serves  
**I WANT**         - phrase to describe the action to be taken or goal to be accomplished  
**SO THAT**        - phrase to describe the value to the user that results from completing the action  
Priority           - the priority estimate for the story  
Points             - the estimated amount of work (in points) for the story  

The **SO THAT** phrase drives the acceptance criteria.

One way to derive acceptance criteria from the story is to rework each phrase element, substituting:

- a **GIVEN** phrase for the **AS A** phrase
- a **WHEN** phrase for the **I WANT** phrase
- a **THEN** phrase for the **SO THAT** phrase


Example: User Device Switch With Sync
-------------------------------------

AS A live streaming sports watcher
I WANT to start watching a video on one device then be able to switch to another device while preserving my play position
SO THAT I don't miss a moment of the big game

### Acceptance Criteria ###

- user starts a new app session (while an existing app session was active (with a stream) within the last 60 minute) and system prompts if user wants to continue where left off, user selects yes. App should take user to previously watched stream. If user selects no, app should take user to main menu.
- user starts a new app session (last live stream played has now finished). System should not attempt to resume playback and should go straight to main menu.
- user selects a stream that is unavailable, system should present error message then take user to main screen.
- System should update stream position information at least every five seconds.


Example: Email Attachments
--------------------------

Here we see the card -> conversation -> confirmation flow (remember that this is bidirectional: any of the activities may change our understanding of the problem and can lead to reworking the content of the card/confirmation, or altering our conversation).

### Card ###

AS AN email sender I WANT emails with attachments to send faster SO THAT I can get on with my work.

### Conversation ###

- "What if the attachment is already compressed?"
- "What if the file is already small?"
- "Should we store a compressed version?"
- "Should the user be able to select compression options?"
- "Is up to 100 attachments enough?"
- "Can each attachment be up to 10 MB?"

### Confirmation ###

- User notices emails with attachments send twice as fast
- Works with attachments up to 10 MB
- Works with up to 50 attachments


Example: Hotel Reservation Cancellation
---------------------------------------

### Card ###

AS A traveler I WANT to cancel a reservation SO THAT I avoid being charged full rate.

### Conversation ###

- "What if I am a premium member, do I get charged?"
- "When is a non-premium member charged, and how much?"
- "How do these vary depending on when the cancellation occurs?"
- "Do we need to send the user confirmation by email?"
- "When does the hotel need to be notified?"
- "What if the user paid a deposit?"

### Confirmation ###

- Verify a premium member can cancel same-day with no charge
- Verify a non-premium member is charged 10% for same-day cancellation, but otherwise not charged
- Verify an email confirmation sent to user with appropriate info
- Verify hotel is notified within 10 minutes

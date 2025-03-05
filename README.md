# A11y Demo

This project demonstrates key accessibility principles. 
Each page showcases different accessibility features and best practices.

## Setup

1. Clone this repository
2. Open `index.html` in your browser
3. Navigate through different pages to learn about accessibility features


# WCAG 2.2 Understanding Docs

_source: https://www.w3.org/WAI/WCAG22/Understanding/_

# Perceivable

"Perceivable" refers to the principle that all information and user interface components must be presented to users in ways they can perceive.
This means that content should be available to at least one of their senses, such as sight or hearing.
For example, providing text alternatives for non-text content, ensuring that videos have captions, and making sure that content can be adapted to different sensory modalities are essential practices.

## 1.1 Text Alternatives

Provide text alternatives for any non-text content so that it can be changed into other forms people need, such as large print, braille, speech, symbols or simpler language.

###    1.1.1 - Non-text Content (Level A)

- Goal: Non-text information is available to more people.
- What to do: Create a text alternative for visual and auditory content.
- Why it's important: People who can’t fully see or hear content can understand it.

## 1.2 Time-based Media

Provide alternatives for time-based media

### 1.2.1 Audio-only and Video-only (Prerecorded) (Level A)

- Goal: Audio and video-only content can be understood by more people.
- What to do: Provide an alternative when content is perceivable with only one sense.
- Why it's important: People who can’t fully see or hear content can understand it.

### 1.2.2 Captions (Prerecorded) (Level A)

- Goal: Videos can be played with captions.
- What to do: Provide synchronized text for audio content in existing videos.
- Why it's important: People who are deaf or hard of hearing can understand audio in videos.

### 1.2.3 Audio Description or Media Alternative (Prerecorded)  (Level A)

- Goal: Prerecorded videos can be understood by more people.
- What to do: Provide a description of the visual content in videos.
- Why it's important: People who are blind or who cannot understand the visual content can have it described.

### 1.2.4 Captions (Live) (Level AA)

- Goal: Live videos have captions.
- What to do: Provide synchronized text for audio content in real-time videos.
- Why it's important: People who are deaf or hard of hearing can understand audio in real-time video content.

### 1.2.5 Audio Description (Prerecorded) (Level AA)

- Goal: Videos can be played with audio descriptions.
- What to do:Provide a synchronized spoken description of the visual content in videos.
- Why it's important:People who cannot see or understand the visual content can hear about it while playing videos.

### 1.2.6 Sign Language (Prerecorded) (Level AAA)

- Goal: Videos can be accompanied by sign language.
- What to do: Provide sign language interpretation for audio content in existing videos.
- Why it's important: People who are deaf or hard of hearing have more ways to understand multimedia content.

### 1.2.7 Extended Audio Description (Prerecorded) (Level AAA)

- Goal: Videos can be played with more detailed audio descriptions.
- What to do: Provide extended spoken descriptions of the visual content in videos.
- Why it's important: People who are blind or who cannot understand the visual content can have it described to them while playing videos.

### 1.2.8 Media Alternative (Prerecorded) (Level AAA)

- Goal: Precorded videos can be understood by more people.
- What to do: Provide a text equivalent for all content in videos.
- Why it's important: More people, including those who are deaf-blind, can better understand the content at their own pace.

### 1.2.9 Audio-only (Live) (Level AAA)

- Goal: Live audio can be understood by more people.
- What to do: Provide a text equivalent for live audio-only content.
- Why it's important: People who cannot hear or understand real-time audio can read an equivalent.

## 1.3 Adaptable

Create content that can be presented in different ways (for example simpler layout) without losing information or structure.

### 1.3.1 Info and Relationships (Level A)

- Goal: Information about content structure is available to more people.
- What to do: Use code to reinforce relationships and information conveyed through presentation.
- Why it's important: People can adapt the presentation to suit their needs while preserving the original meaning.

###  1.3.2 Meaningful Sequence (Level A)

- Goal: The order of content can be understood by more people.
- What to do: Use code to preserve meaningful content order.
- Why it's important: Assistive technology can present content to users in the proper order.

### 1.3.3 Sensory Characteristics (Level A)

- Goal: Instructions are understandable by more people.
- What to do: Describe controls by name, not just by appearance or location.
- Why it's important: People who are blind or have low vision need non-visual instructions.

### 1.3.4 Orientation (Level AA)

- Goal: Devices can be used in any orientation.
- What to do: Don't lock content to either portrait or landscape presentation.
- Why it's important: Wheelchair users and others may have devices mounted in a fixed orientation.

### 1.3.5 Identify Input Purpose (Level AA)

- Goal: It is easier to fill out forms.
- What to do: Use code to indicate the purpose of common inputs, where technology allows.
- Why it's important: Some people with cognitive disabilities may not understand the input's purpose from the label alone.

### 1.3.6 Identify Purpose (Level AAA)

- Goal: It is easier to operate and navigate content.
- What to do: Use code to indicate the meaning of all controls and other key information, where available.
- Why it's important: Some people with cognitive disabilities may not understand a control's purpose from the name alone.

## 1.4 Distinguishable

Make it easier for users to see and hear content including separating foreground from background

### 1.4.1 Use of Color (Level A)

- Goal: Color is not the only way of distinguishing information.
- What to do: Use information in addition to color, such as shape or text, to convey meaning.
- Why it's important: Not everyone sees colors or sees them the same way.

### 1.4.2 Audio Control (Level A)

- Goal: A page that plays music or sounds doesn't disrupt people.
- What to do: If you play audio content automatically, let people turn it down or off.
- Why it's important: Sound distracts some people, and also interferes with screen readers.

### 1.4.3 Contrast (Minimum) (Level AA)

- Goal: Text can be seen by more people.
- What to do: Provide sufficient contrast between text and its background.
- Why it's important: Some people cannot read faint text.

### 1.4.4 Resize Text (Level AA)

- Goal: Text can be enlarged.
- What to do: Ensure text can be doubled in size.
- Why it's important: Some people can only read text when it is bigger.

### 1.4.5 Images of Text (Level AA)

- Goal: Users can adjust how text is presented.
- What to do: Use text instead of pictures of text.
- Why it's important: People cannot alter how text looks in images.

### 1.4.6 Contrast (Enhanced) (Level AAA)

- Goal: Text can be seen by people who need strong contrast.
- What to do: Strongly contrast text against its background.
- Why it's important: Some people cannot read text with minimum contrast.

### 1.4.7 Low or No Background Audio (Level AAA)

- Goal: Prerecorded speech is not disrupted by background sound.
- What to do: Avoid or lessen background sound, or let users turn it off.
- Why it's important: People who are hard of hearing may have difficulty distinguishing speech from music and other sounds.

### 1.4.8 Visual Presentation (Level AAA)

- Goal: Text appearance can be altered by users to meet preferences.
- What to do: Meet text display requirements or allow users to adjust them.
- Why it's important: Some text formats are more readable for people with cognitive disabilities and low vision.

### 1.4.9 Images of Text (No Exception) (Level AAA)

- Goal: Users can always adjust how text is presented.
- What to do: Do not use pictures of text unless there is no other way to present information.
- Why it's important: People cannot alter how text looks in images.

### 1.4.10 Reflow (Level AA)

- Goal: Content can be enlarged without increasing line length.
- What to do: Make lines of text reflow within the viewport.
- Why it's important: People who need bigger text find it difficult if they must scroll to read long lines.

### 1.4.11 Non-text Contrast (Level AA)

- Goal: Important visual information meets the same minimum contrast required for larger text.
- What to do: Ensure meaningful visual cues achieve 3:1 against the background.
- Why it's important: Some people cannot see elements with low contrast.

### 1.4.12 Text Spacing (Level AA)

- Goal: Users can adjust text spacing to make it easier to read.
- Author task: Ensure content adapts to user-defined text settings.
- Why it's important: Some people need text with different spacing or font characteristics.

### 1.4.13 Content on Hover or Focus (Level AA)

- Goal: More users can perceive and dismiss non-persistent content.
- What to do: If hover or focus causes content changes, ensure interaction is predictable.
- Why it's important: Unpredictable temporary content can be hard for some to consume and may disrupt others.

# Operable

"Operable" refers to the principle that all user interface components and navigation must be operable by everyone.
This means that users should be able to interact with and navigate the content using various methods, such as a keyboard, mouse, or assistive technologies.
The aim is to ensure that all users can easily operate and interact with web content.

2.1 Keyboard Accessible

Make all functionality available from a keyboard.

### 2.1.1 Keyboard (Level A)

- Goal: Everything can be done with a keyboard except freehand movements.
- What to do: Ensure pointer actions have a keyboard equivalent.
- Why it's important: Many people rely on the keyboard interface, including blind and some mobility impaired people.

### 2.1.2 No Keyboard Trap (Level A)

- Goal: Keyboard users don't get stuck.
- What to do: Ensure users always know how to navigate away from components.
- Why it's important: People who rely on the keyboard often have no other means to navigate.

### 2.1.3 Keyboard (No Exception) (Level AAA)

- Goal: Everything can be done with a keyboard.
- What to do: Ensure all pointer actions have a keyboard equivalent.
- Why it's important: People who can only use the keyboard interface need to be able to accomplish everything.

### 2.1.4 Character Key Shortcuts (Level A)

- Goal: Reduce accidental activation of keyboard shortcuts.
- What to do: Ensure character-only shortcut keys can be turned off or modified.
- Why it's important: Character-key shortcuts are easy to accidentally trigger, especially with speech input.

## 2.2 Enough Time

Provide users enough time to read and use content.

### 2.2.1 Timing Adjustable (Level A)

- Goal: Users have adequate time to complete tasks.
- What to do: Let users turn off, adjust, or extend time limits.
- Why it's important: People with disabilities may need more time to complete activities.

### 2.2.2 Pause, Stop, Hide (Level A)

- Goal: Fewer users are distracted by content that updates or moves.
- What to do: Let users control content changes that occur in parallel with other content.
- Why it's important: Some people with cognitive disabilities and attention deficits are distracted by continuous movement.

### 2.2.3 No Timing (Level AAA)

- Goal: Users do not face time limits.
- What to do: Do not use time limits, except for video and live events.
- Why it's important: People with disabilities often need more time to complete actions.

### 2.2.4 Interruptions (Level AAA)

- Goal: Users are not interrupted.
- What to do: Let people delay or turn off updates, except in emergencies.
- Why it's important: Updates distract and disrupt assistive technology users and people with attention deficits.

### 2.2.5 Re-authenticating (Level AAA)

- Goal: Users do not lose information or context due to reauthentication.
- What to do: Preserve users' prior activity and data through reauthentication.
- Why it's important: Some people may require additional time to complete an activity.

### 2.2.6 Timeouts (Level AAA)
- 
- Goal: Users do not lose data due to unknown timeouts.
- Author task: Tell users how long their session can be inactive before they may lose information.
- Why it's important: People with disabilities may need more time to complete actions.

## 2.3 Seizures and Physical Reactions

Do not design content in a way that is known to cause seizures or physical reactions.

### 2.3.1 Three Flashes or Below Threshold (Level A)

- Goal: Content does not trigger seizures.
- What to do: Avoid content that flashes, or keep it under thresholds.
- Why it's important: Flashing content can cause migraines, dizziness, nausea, and seizures.

### 2.3.2 Three Flashes (Level AAA)

- Goal: Content does not trigger seizures.
- What to do: Do not flash content more than 3 times a second.
- Why it's important: Flashing content can cause migraines, dizziness, nausea, and seizures.


### 2.3.3 Animation from Interactions (Level AAA)

- Goal: Users are not harmed or distracted by motion.
- What to do: Support user preferences for motion, and eliminate unnecessary motion effects.
- Why it's important: People can get sick from motion effects.

## 2.4 Navigable

Provide ways to help users navigate, find content, and determine where they are.

### 2.4.1 Bypass Blocks (Level A)

- Goal: Users can more easily navigate by keyboard.
- What to do: Provide a means of skipping repeating content.
- Why it's important: Users reliant on the keyboard interface can move around pages efficiently.

### 2.4.2 Page Titled (Level A)

- Goal: Each web page has a meaningful title.
- What to do: Provide a descriptive page title using appropriate technology.
- Why it's important: Page titles help users identify and distinguish different pages.

### 2.4.3 Focus Order (Level A)

- Goal: Keyboard users navigate content in a correct order.
- What to do: Elements receive focus in an order that preserves meaning.
- Why it's important: Navigating a site or application with only the keyboard will make sense.

### 2.4.4 Link Purpose (In Context) (Level A)

- Goal: Users understand what each link will do.
- What to do: Provide descriptive names or context for all links.
- Why it's important: People with visual and cognitive disabilities can navigate more easily.

### 2.4.5 Multiple Ways (Level AA)

- Goal: Users can get to content in multiple ways.
- What to do: Provide at least two options for reaching the same content.
- Why it's important: Not everyone can navigate content in the same way.

### 2.4.6 Headings and Labels (Level AA)

- Goal: A page's content is described in headings and labels
- What to do: Provide descriptive headings and labels
- Why it's important: People can orient themselves, especially those with cognitive or visual disabilities.

### 2.4.7 Focus Visible (Level AA)

- Goal: Users know which element has keyboard focus.
- What to do: Ensure each item receiving focus has a visible indicator.
- Why it's important: Without a focus indicator, sighted keyboard users cannot operate the page.

### 2.4.8 Location (Level AAA)

- Goal: Users know where they are in a set of pages.
- What to do: Use breadcrumbs, site maps, or other indicators to give context.
- Why it's important: Location indicators reduce confusion for people with cognitive disabilities.

### 2.4.9 Link Purpose (Link Only) (Level AAA)

- Goal: Users understand what each link will do.
- What to do: Provide descriptive names for all links.
- Why it's important: Descriptive link text is more understandable for all users, especially when using assistive technology.

### 2.4.10 Section Headings (Level AAA)

- Goal: Users understand how content is organized in sections.
- What to do: Where content is organized in sections, provide section headings.
- Why it's important: People can orient themselves, especially those with cognitive or visual disabilities.

### 2.4.11 Focus Not Obscured (Minimum) (Level AA)

- Goal: Keep the focused item visible.
- What to do: Ensure when an item gets keyboard focus, it is at least partially visible.
- Why it's important: People who can't use a mouse need to see what has keyboard focus.

### 2.4.12 Focus Not Obscured (Enhanced) (Level AAA)

- Goal: Don't cover any part of the item with focus.
- What to do: Ensure when an item gets keyboard focus, it is fully visible.
- Why it's important: People who can't use a mouse need to see what has keyboard focus.

### 2.4.13 Focus Appearance (Level AAA)

- Goal: Make it easier to spot the keyboard focus.
- What to do: Use a focus indicator of sufficient size and contrast.
- Why it's important: Many people can't see small changes in visual appearance, including older people.

## 2.5 Input Modalities

Make it easier for users to operate functionality through various inputs beyond keyboard.

### 2.5.1 Pointer Gestures (Level A)

- Goal: Let users operate touchscreens with one finger and reduced gestures.
- What to do: Provide single-point operation for all functions.
- Why it's important: Not everyone can perform complex and multi-touch gestures.

### 2.5.2 Pointer Cancellation (Level A)

- Goal: Reduce accidental activation of controls by mouse or touch.
- What to do: Make pointer cancellation predictable and consistent.
- Why it's important: Make it easier for anyone to recover from something they didn’t mean to do.

### 2.5.3 Label in Name (Level A)

- Goal: The visual label for controls is a trigger for speech activation.
- What to do: Where practical, make the control’s text label and name match.
- Why it's important: People who operate with voice interaction use the visible labels in their commands.

### 2.5.4 Motion Actuation (Level A)

- Goal: Content is not dependent on a user's ability to move a device.
- What to do: Don't rely solely on device motion to control page content.
- Why it's important: Some people cannot hold or move a device steadily.

### 2.5.5 Target Size (Enhanced) (Level AAA)

- Goal: Controls can be operated more easily, especially on touch screens.
- What to do: Make custom targets at least 44 by 44 pixels.
- Why it's important: Some people cannot tap small objects.

### 2.5.6 Concurrent Input Mechanisms (Level AAA)

- Goal: Users can choose different ways of inputting content.
- What to do: Do not prevent users from switching their mode of input.
- Why it's important: People may not be able to work using just one input method.

### 2.5.7 Dragging Movements (Level AA)

- Goal: Don’t rely on dragging for user actions.
- What to do: For any action that involves dragging, provide a simple pointer alternative.
- Why it's important: Some people cannot use a mouse to drag items.

### 2.5.8 Target Size (Minimum) (Level AA)

- Goal: Make controls easier to activate.
- What to do: Ensure targets meet a minimum size or have sufficient spacing around them.
- Why it's important: Some people with physical impairments cannot click small buttons that are close together.

# Understandable

"Understandable" refers to the principle that information and the operation of the user interface must be clear and comprehensible to all users.
This involves ensuring that text is readable and understandable, making content appear and operate in predictable ways, and helping users avoid and correct mistakes.
For example, using clear and simple language, providing consistent navigation, and offering error messages that help users understand and fix input errors are essential practices.

## 3.1 Readable

Make text content readable and understandable.

### 3.1.1 Language of Page (Level A)

- Goal: Assistive technology can determine the language of a page.
- What to do: Indicate the predominant language on a page.
- Why it's important: People using assistive technology get information in the correct language.

### 3.1.2 Language of Parts (Level AA)

- Goal: Assistive technology can identify the languages used within a page.
- What to do: Indicate when words are in a different language.
- Why it's important: People using assistive technology get information in the correct language.

### 3.1.3 Unusual Words (Level AAA)

- Goal: Users can identify and learn what unusual words mean.
- What to do: Provide definitions for technical jargon and unusual terms.
- Why it's important: More people, especially those with cognitive disabilities, can understand the meaning of content.

### 3.1.4 Abbreviations (Level AAA)

- Goal: Users can identify and learn what abbreviations mean.
- What to do: Provide the expanded form of abbreviations to users.
- Why it's important: Some people, including those with cognitive disabilities, may not understand the shortened form of words.

### 3.1.5 Reading Level (Level AAA)

- Goal: Users can get a simplified version of complex information.
- What to do: When text information becomes complex, create a more easily understood version.
- Why it's important: More people, especially those with cognitive disabilities, can understand the meaning of content.

### 3.1.6 Pronunciation (Level AAA)

- Goal: Users can identify the pronunciation of ambiguous words.
- What to do: Indicate how to pronounce a word, where its meaning is otherwise unclear.
- Why it's important: Some people, including those with cognitive disabilities, may not understand the meaning of content.

## 3.2 Predictable

Make web pages appear and operate in predictable ways.

### 3.2.1 On Focus (Level A)

- Goal: Content can be navigated more predictably.
- What to do: Do not change a user's context when items get focus.
- Why it's important: Content that behaves predictably is especially important to people with disabilities.

### 3.2.2 On Input (Level A)

- Goal: Content can be operated more predictably.
- What to do: Forewarn users if their context will change based on their input.
- Why it's important: Content that behaves predictably is especially important to people with disabilities.

### 3.2.3 Consistent Navigation (Level AA)

- Goal: Content can be navigated more predictably.
- What to do: Consistently order navigation that repeats across multiple pages.
- Why it's important: Content that behaves predictably is especially important to people with disabilities.

### 3.2.4 Consistent Identification (Level AA)

- Goal: Actions are more predictable across pages.
- What to do: Identify repeating functions consistently.
- Why it's important: Consistently identified actions are especially important to people with disabilities.

### 3.2.5 Change on Request (Level AAA)

- Goal: Users have full control of major content changes.
- What to do: Provide ways for users to trigger or turn off changes of context.
- Why it's important: Content that behaves predictably is especially important to people with disabilities.

### 3.2.6 Consistent Help (Level A)

- Goal: Make it easier to find help and support.
- What to do: Put help in the same place when it is on multiple pages.
- Why it's important: People who need help can find it more easily if it's in the same place.

## 3.3 Input Assistance

Help users avoid and correct mistakes.

## 3.3.1 Error Identification (Level A)

- Goal: Users know an error exists and what is wrong.
- What to do: Provide descriptive notification of errors.
- Why it's important: Flagging errors helps people with reduced sight and cognitive disabilities resolve them.

### 3.3.2 Labels or Instructions (Level A)

- Goal: Users know what information to enter.
- What to do: Provide labels or instructions for inputs.
- Why it's important: Everyone, especially those with cognitive disabilities, will know how to respond.

### 3.3.3 Error Suggestion (Level AA)

- Goal: Users get suggestions on how to resolve errors.
- What to do: Where errors are detected, suggest known ways to correct them.
- Why it's important: People can address errors faster and with reduced effort.

### 3.3.4 Error Prevention (Legal, Financial, Data) (Level AA)

- Goal: Users can avoid submitting incorrect important information.
- What to do: Provide ways for users to confirm, correct, or reverse important submissions.
- Why it's important: People with disabilities may be more likely to make mistakes, or not notice them.

### 3.3.5 Help (Level AAA)

- Goal: Users can avoid making mistakes.
- What to do: Provide help to users on the function currently being performed.
- Why it's important: People with cognitive or other disabilities can complete their tasks more easily.

### 3.3.6 Error Prevention (All) (Level AAA)

- Goal: Users can avoid submitting incorrect information.
- What to do: Provide ways for users to confirm, correct, or reverse any submissions.
- Why it's important: People with disabilities may be more likely to make mistakes, or not notice them.

### 3.3.7 Redundant Entry (Level A)

- Goal: Make it easier for users to complete multi-step processes.
- What to do: Don't ask for the same information twice in the same session.
- Why it's important: Some people with cognitive disabilities have difficulty remembering what they entered before.

### 3.3.8 Accessible Authentication (Minimum) (Level AA)

- Goal: Make logins possible with less mental effort.
- What to do: Don't make people solve, recall, or transcribe something to log in.
- Why it's important: Some people with cognitive disabilities cannot solve puzzles, memorize a username and password, or retype one-time passcodes.

### 3.3.9 Accessible Authentication (Enhanced) (Level AAA)

- Goal: Make logins possible with less mental effort.
- What to do: Don't make people recognize objects or user-supplied images and media to login.
- Why it's important: Some people with cognitive disabilities can't do puzzles, including identifying objects and non-text information they previously supplied.

# Robust

"Robust" refers to the principle that content must be robust enough to be reliably interpreted by a wide variety of user agents, including assistive technologies.
This means ensuring that web content is compatible with current and future technologies. Key practices include using clean, standard-compliant code and providing proper markup so that assistive technologies can accurately interpret and interact with the content.

## 4.1 Compatible

Maximize compatibility with current and future user agents, including assistive technologies.

### 4.1.1 Parsing (Obsolete and removed)

### 4.1.2 Name, Role, Value (Level A)

- Goal: People using assistive technology understand all components.
- What to do: Give components correct names, roles, states, and values.
- Why it's important: Assistive technology only works well when code is done properly.

### 4.1.3 Status Messages (Level AA)

- Goal: Make users aware of important changes in content.
- What to do: Let assistive technology notify users about status changes that don't take focus.
- Why it's important: People who do not see messages need to be informed about them.
    

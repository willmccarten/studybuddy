
# Mac Cat Companion Study Buddy

A lightweight, always-on macOS app that features a pixel-art calico cat on your desktop. The cat provides gentle motivational prompts, study reminders, and comforting messages—helping med students (and anyone in need of a boost) stay focused, balanced, and emotionally supported. The design marries nostalgic pixel art with a dreamy, pastel-colored “purple cloud world” background for a soothing yet engaging experience.

---

## Table of Contents

1. [Problem Statement](#problem-statement)
2. [Product Overview](#product-overview)
3. [User Stories](#user-stories)
4. [Wireframes & Mockups](#wireframes--mockups)
5. [MVP Feature Scope](#mvp-feature-scope)
6. [Feature Roadmap](#feature-roadmap)
7. [Setup & Installation](#setup--installation)

---

## Problem Statement

Many medical students face long, intense study sessions that can lead to stress and burnout. In particular, my girlfriend—who is a med student—sometimes struggles with motivation. In addition, she misses the comforting presence of her childhood cat.  
**The goal of this project** is to create an emotionally engaging tool that:
- Provides gentle encouragement and timely study reminders.
- Evokes nostalgic comfort through a pixel-art representation of her childhood calico cat.

---

## Product Overview

**Mac Cat Companion** is a self-contained macOS app that sits on your desktop in a small, floating window. It offers:
- **Motivational Prompts:** Timed and context-based messages to encourage study and healthy habits.
- **Interactive Dialogues:** Simple choices (e.g., “Study now” vs. “Snooze”) that affect the cat’s mood.
- **Mood-Responsive Animations:** The cat’s expression and animations change based on user interaction and time-of-day.
- **Dreamy Aesthetics:** A pastel “purple cloud world” background creates a relaxed, calming atmosphere, complementing the detailed pixel art of a calico cat.

---

## User Stories

| **User Type**     | **Story**                                                                                 | **Benefit**                                  |
|-------------------|-------------------------------------------------------------------------------------------|----------------------------------------------|
| Med Student       | As a med student, I want a cute cat on my screen so that I feel emotionally supported.     | Reduces stress and adds personal comfort.    |
| Motivated User    | As a user, I want the cat to remind me to study so that I stay on track with my goals.       | Keeps me accountable and focused.            |
| Interactive User  | As a user, I want to respond to the cat’s prompts so that it feels like an engaging dialogue. | Increases interaction and personalization.   |
| Nostalgic User    | As a user, I want the cat to reflect my childhood pet so that it evokes warm memories.       | Enhances emotional connection and nostalgia. |
| Efficiency Seeker | As a user, I want the app to run unobtrusively in the background so that it doesn't distract me. | Allows focus on work with subtle reminders.  |

---

## Wireframes & Mockups

### Wireframe Sketch

```
+------------------------------------------------+
| [⚙️]                                       [X] |
|                                                |
|                   [Cat Sprite]                 |
|                                                |
|            "Time to study, friend!             |
|             Would you like to begin?"          |
|                                                |
|             [Study Now]   [Snooze]             |
|                                                |
+------------------------------------------------+
```

### Artistic Design Notes

- **Pixel Art Style:** Small, detailed pixels for retro charm and expressiveness.
- **Background:** Pastel purple "dreamy cloud world" aesthetic.
- **Color Palette:** Calico cat colors with muted, soft background tones.
- **Mood Animations:** Idle, Studious, Sleepy, Excited, Pouty.

---

## MVP Feature Scope

| **Category**       | **Feature**                                                                 |
|--------------------|------------------------------------------------------------------------------|
| Window & Layout    | Fixed 400x300 px window, always-on floating                                |
| Cat Display        | Idle animation, mood state changes based on interaction                    |
| Motivational Prompts | Scheduled prompts, 2-button interactions                                |
| State Persistence  | Store mood, last prompt, interactions using `UserDefaults`                 |
| Offline Use        | No network access needed; all data bundled                                |

---

## Feature Roadmap

### v1.0 – MVP

| **Category**         | **Feature**                                                                 |
|----------------------|------------------------------------------------------------------------------|
| Window & Layout      | Fixed-size window, always-on floating                                       |
| Cat Display          | Idle animation, basic mood system                                           |
| Motivational Prompts | Timed prompts, 2-button interactions                                        |
| State Persistence    | `UserDefaults` for local state                                              |
| Offline Use          | Fully offline; no external dependencies                                     |

### v1.1 – Quality of Life Improvements

| **Category**         | **Feature**                                                                 |
|----------------------|------------------------------------------------------------------------------|
| Moods & Animations   | Expanded mood system and animations                                         |
| Prompt Logic         | Improved scheduling based on activity                                       |
| UX Enhancements      | Settings button, keyboard shortcut support                                 |

### v1.2 – Seasonal & Emotional Touches

| **Category**         | **Feature**                                                                 |
|----------------------|------------------------------------------------------------------------------|
| Seasonal Content     | Special messages for holidays or events                                     |
| Art Variations       | Holiday outfits and accessories                                             |
| Customization        | Personalized greetings (e.g., “Welcome back, [Name]”)                      |

### v2.0 – Customization & Smart Behavior

| **Category**         | **Feature**                                                                 |
|----------------------|------------------------------------------------------------------------------|
| Theme & Style        | Custom backgrounds, outfit options                                          |
| Interaction Tracking | Response history and streaks                                                |

### v2.1+ – Network-Optional Stretch Features

| **Category**         | **Feature**                                                                 |
|----------------------|------------------------------------------------------------------------------|
| Weather Integration  | Optional prompts based on local weather via API                             |
| Update System        | Auto-updates using Sparkle or GitHub Releases                               |
| Dynamic Dialogue     | Load dialogue from local or online sources                                  |

---

## Setup & Installation

### For Developers
1. Clone the Repository:
   ```
   git clone https://github.com/yourusername/mac-cat-companion.git
   ```
2. Open the project in Xcode (`.xcodeproj` or `.xcworkspace`)
3. Build and run the app

### For Users
1. Unzip and drag the app into the `Applications` folder
2. Control-click to open if macOS warns about unidentified developer

---

## Conclusion

Mac Cat Companion is a relaxing, supportive tool designed to add joy, comfort, and encouragement to a busy academic lifestyle. By blending nostalgia with gentle guidance, it brings a smile to every study session.

---
title: Week 2: Horizon Worlds & VR Critique
revealOptions:
  transition: slide
---

# Week 2: Horizon Worlds
## Platform Introduction & VR Critique Setup
DIG 4633C - Multi-Modal Design  
Monday, August 25, 2025

---

# Today's Agenda

- 3:30-3:45 — Seat Selection & Setup
- 3:45-4:00 — VR Critique Assignment Introduction
- 4:00-4:15 — Horizon Worlds Overview
- 4:15-4:45 — Desktop Editor Tutorial
- 4:45-5:20 — Hands-on Creation Time

---

# Quick Hardware Update

> ⚠️ **Temporary Desktop Development**
>
> Our Quest 3 headsets are being provisioned this week. Today we'll work with Horizon's desktop tools to get started!

✅ **What This Means**
- Start building today using desktop editor
- Test in VR on Wednesday when headsets are ready
- No impact on assignment deadlines
- Great opportunity to learn the tools first

**Seat Selection:**
Choose your seat for the semester - I'll create a seating chart for attendance.

---

# VR Critique Assignment

## 20% of Your Grade (2 Critiques)

### Critique 1 - Week 5
- 8% of grade
- 5-7 minute video essay
- Analyze a VR experience
- Focus on design decisions
- Due Thursday 11:59 PM

### Critique 2 - Week 9
- 12% of grade
- More advanced analysis
- Compare multiple experiences
- Apply course concepts
- Due Thursday 11:59 PM

**Key Requirements:**
- Include gameplay footage (screen recording)
- Professional narration and editing
- Peer review 2 classmates' critiques
- Document any AI assistance used

---

# What Makes a Good VR Critique?

## VR-Specific Analysis Points

- **Presence & Immersion**
    - How convincing is the virtual world?
    - What breaks immersion?
    - Environmental storytelling
- **Comfort & Accessibility**
    - Motion sickness mitigation
    - Comfort options provided
    - Physical accessibility
- **Interaction Design**
    - Hand tracking vs controllers
    - Gesture recognition
    - UI/UX in 3D space
- **Spatial Design**
    - Use of scale and perspective
    - Navigation methods
    - Audio spatialization

> ⚠️ **Avoid Generic Game Reviews!** Focus on what makes this experience unique to VR, not general game design principles.

---

# Critique Structure Example

- **0:00-0:30 — Hook & Introduction:** Grab attention, introduce the experience, state your thesis
- **0:30-2:00 — Context & Overview:** What is this experience? Platform, genre, developer background
- **2:00-4:30 — Deep Analysis:** 3-4 specific VR design elements with footage examples
- **4:30-5:30 — Comparative Analysis:** How does it compare to similar VR experiences?
- **5:30-6:30 — Recommendations:** What works? What could improve? Who is this for?
- **6:30-7:00 — Conclusion:** Summarize key points, final thoughts

---

# Recording Your Critique

## Capture Tools

**Quest Recording**
- Built-in recording (share button)
- Oculus Developer Hub
- SideQuest screen recording

**PC VR Recording**
- OBS Studio (recommended)
- NVIDIA Shadowplay
- Windows Game Bar

## Editing Software (Free Options)
- DaVinci Resolve — Professional free editor
- OpenShot — Simple and beginner-friendly
- Clipchamp — Built into Windows 11
- iMovie — Mac users

> **Pro Tip:** Record your narration separately for better audio quality. Use Audacity (free) for audio editing.

---

# Horizon Worlds Overview

## What is Horizon Worlds?
Meta's social VR platform for creating and sharing virtual worlds without coding.

**Key Features:**
- Visual scripting system
- Built-in multiplayer
- Cross-platform (Quest/PC)
- Instant publishing
- Social features built-in

**Limitations:**
- Meta ecosystem only
- Limited asset library
- Performance constraints
- Simplified physics
- No custom code

> **Perfect for:** Rapid prototyping, social experiences, event spaces, and learning VR design principles.

---

# Horizon World Assignment

## "Dreamscape" - Due Week 3 (7% of grade)

> **Create an Impossible Space**
> Design a world that could only exist in VR - defy physics, play with scale, or create surreal environments.

### Requirements
- Minimum 3 distinct areas/zones
- At least 5 interactive elements
- Use of visual scripting for 2+ behaviors
- Clear navigation/wayfinding
- 3-5 minute experience
- Published and accessible to classmates

### Inspiration Themes
- M.C. Escher-inspired geometry
- Gravity-defying spaces
- Scale transitions (shrinking/growing)
- Time manipulation areas
- Nested realities
- Synesthetic environments
- Dream logic navigation
- Emotional landscapes

---

# Getting Started with Horizon

## Today's Setup
1. Create Meta Account (if needed)
2. Download Horizon Worlds on lab PC
3. Launch Desktop Mode
4. Complete Tutorial
5. Start Your World

> **Account Setup Tips**
> - Use any email you prefer (not required to use UCF)
> - Enable 2-factor authentication
> - Set privacy to "Friends Only" initially
> - Use consistent username across platforms

**Download Link:** horizonworlds.com/download

---

# Desktop Editor Interface

## Main Panels

**Build Mode**
- Library: Objects and shapes
- Properties: Object settings
- Hierarchy: Scene structure
- Viewport: 3D workspace

**Script Mode**
- Script Graph: Visual coding
- Variables: Data storage
- Events: Triggers
- Actions: Behaviors

## Navigation Controls (Desktop)

| Action         | Mouse + Keyboard      |
| --------------| ---------------------|
| Move Camera   | WASD + Mouse         |
| Rotate View   | Right Click + Drag   |
| Pan View      | Middle Click + Drag  |
| Select Object | Left Click           |
| Multi-Select  | Ctrl + Click         |

---

# Basic Building Tutorial

## Step 1: Create Your Foundation
1. Open the **Library** panel
2. Drag a **Platform** into the scene
3. Scale it using the transform tools (R for scale)
4. Apply a material from the Materials library

## Step 2: Add Basic Geometry
Shortcuts:
- Q - Select tool
- W - Move tool
- E - Rotate tool
- R - Scale tool
- F - Focus on selected
- Ctrl+D - Duplicate
- Delete - Remove object

## Step 3: Create Your First Interaction
1. Select an object
2. Open **Script Mode**
3. Add event: "When player enters trigger volume"
4. Add action: "Play sound" or "Change color"
5. Test in Play Mode (P key)

---

# Visual Scripting Essentials

## Core Concepts

**Events (Green):**
- Player enters area
- Object is grabbed
- Timer completes
- World starts

**Actions (Blue):**
- Move object
- Play sound
- Change color
- Spawn object

## Your First Script: Color Change on Approach
1. Create a cube
2. Add a **Trigger Volume** around it
3. Script: When Player Enters → Set Color (cube) to Random
4. Add second action: Play Sound Effect

> **Challenge:** Make the cube also rotate when triggered!

---

# Common Horizon Patterns

## Teleportation Pads
- Use invisible trigger volumes
- Action: "Teleport Player To" target object
- Add particle effects for feedback

## Collectibles
- Object + Trigger Volume
- When collected: Destroy self + Add to variable
- Update UI counter

## Moving Platforms
- Use "Move To" action with loop
- Set waypoints with empty objects
- Adjust speed for comfort

## Day/Night Cycle
- Rotate directional light over time
- Lerp sky color values
- Trigger events at specific times

> **Remember:** Start simple! Get one mechanic working before adding complexity.

---

# Tips for Your Dreamscape

## Design Principles

**✨ Make it Impossible**
- Waterfalls flowing upward
- Infinite corridors
- Nested spaces
- Impossible geometry

**🎯 Guide the Player**
- Use lighting as wayfinding
- Create visual landmarks
- Sound cues for direction
- Clear sight lines

## Performance Tips
- Keep object count under 1000
- Use instances for repeated objects
- Limit particle effects
- Test frequently in Play Mode

## Avoid These Pitfalls
- Overcomplicating your first world
- Forgetting player comfort (avoid spinning rooms!)
- Making spaces too large and empty
- Not testing before publishing

---

# Hands-On Workshop

## Your Tasks for Remaining Class Time

- Task 1: Account & Download — Get Horizon Worlds running on your lab computer
- Task 2: Complete Tutorial — Finish the built-in Horizon tutorial (15 min)
- Task 3: Create Test World — Build a simple room with 1 interaction
- Task 4: Experiment — Try 2-3 different object types and scripts
- Task 5: Plan Your Dreamscape — Sketch or write ideas for your assignment

> **Goal:** Leave today comfortable with the basic tools and with a plan for your Dreamscape world!

---

# Resources & Support

## Official Documentation
- [Horizon Worlds Creator Guide](https://creator.horizonworlds.com)
- Script Reference: In-app documentation (F1 key)
- Community Forums: forums.oculusvr.com/horizon

## Video Tutorials
- Meta's Official YouTube Channel
- VR Game Development playlist on Webcourses
- Discord community tutorials channel

## Getting Help
**In Class:**
- Ask during workshop time
- Pair up with classmates
- Wednesday lab session

**Outside Class:**
- Teams/Discord channels
- Office hours (Wed 2-3pm)
- Document issues for class discussion

---

# Wednesday's Class

## What We'll Do
- Test your desktop creations in VR
- Learn VR-specific building techniques
- Explore comfort settings
- Collaborative building exercise
- Continue Dreamscape development

## Come Prepared
- Bring headphones! (Required)
- Bring external hard drive
- Have your Dreamscape concept ready
- Questions from today's desktop work

## Assignment Timeline
| Date         | Task                        |
| ------------|-----------------------------|
| Today (Mon) | Learn tools, start planning |
| Wed 8/27    | VR testing, continue building|
| Mon 9/1     | Labor Day - No class (work time!)|
| Wed 9/3     | Final polish in lab         |
| Thu 9/4 11:59 PM | Dreamscape DUE         |

---

# Let's Start Building!

## Workshop Time
I'll circulate to help with setup and answer questions

**First:** Choose your seat for the semester  
**Then:** Get Horizon Worlds running

_Remember: Creativity > Complexity_

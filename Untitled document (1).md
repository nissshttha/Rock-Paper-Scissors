Pixathon Ai Log

# **AI\_LOG.md**

## **1\. Project Information**

**Game Name:** ROCK PAPER REVERSE SHOOT\!

**Team Name:** Tapu Sena

**Challenge Statement:** Puzzle With A Twist

## **2\. AI Tools Used**

| AI Tool | Purpose |
| ----- | ----- |
| Google Stitch | Designing the game's interface and visual prototype |
| Google Antigravity | To be updated based on actual usage |
| Gemini  | For AI chat |

## **3\. Key Prompts Used**

**Prompt:** You are an award-winning game UI/UX designer and creative director specialising in original indie games, interactive experiences, and polished game interfaces.

Your task is to design a visually outstanding, interactive prototype for my hackathon project.

PROJECT NAME: ROCK PAPER SCISSORS — BEYOND THE RULES

THE CONCEPT

Reimagine the classic Rock Paper Scissors game as a visually distinctive, strategic, multi-level gaming experience.The game must remain instantly recognisable as Rock Paper Scissors. However, it should feel like a fresh, modern interpretation rather than a basic recreation of the original game.

The player should encounter new challenges, unexpected rule changes, and progressively more interesting decisions as they advance.

The game must have at least four distinct levels.

YOUR CREATIVE DIRECTION

Create a memorable visual identity that feels playful, intelligent, slightly surreal, and premium.

Use a sophisticated pastel palette featuring:

\* Lavender and lilac.

\* Powder blue.

\* Pale mint.

\* Butter yellow.

\* Warm cream.

\* Muted peach.

\* Deep navy for readable text and contrast.

Avoid harsh neon colours, overly saturated backgrounds, generic gaming interfaces, and excessive visual effects.

The interface should feel thoughtfully designed, not like a generic AI-generated website.

Use the uploaded reference prototype as the primary design reference. Preserve its strongest design elements and improve the execution without unnecessarily replacing its visual identity.

DESIGN THE COMPLETE GAME EXPERIENCE

Create a cohesive set of screens covering the entire player journey.

Screen 1: Welcome screen

\* A distinctive game title.

\* A memorable visual treatment of rock, paper, and scissors.

\* A clear Play button.

\* A concise introduction to the game’s unique concept.

\* A visually engaging first impression.

Screen 2: Instructions

\* Explain the classic rules in a simple, visual format.

\* Explain how the player progresses through the game.

\* Use illustrations or diagrams where useful.

\* Keep instructions short and accessible.

Screen 3: Level selection

\* Display at least four levels.

\* Give every level a distinct name and visual identity.

\* Show locked, unlocked, and completed states.

\* Include a clear progression indicator.

\* Make the final level feel like an exciting challenge.

Screen 4: Main gameplay

Design this screen particularly carefully.

Include:

\* Current level and objective.

\* Player score and opponent score.

\* Opponent character or visual identity.

\* Three prominent choice buttons for rock, paper, and scissors.

\* Current round information.

\* A visible description of the active rule or modifier.

\* A clear progression indicator.

\* Restart, help, and sound controls where appropriate.

The three choices must be the most visually obvious interactive elements.

Screen 5: Round result

Create visually distinct feedback for:

\* Player victory.

\* Player defeat.

\* A tie.

Display both choices, explain the outcome, and show the updated score.

Screen 6: Special level challenge

Create a screen demonstrating how a level-specific rule changes the gameplay.

Make the special mechanic visually understandable before the player makes a choice.

Screen 7: Level completion

\* Celebrate the player’s achievement.

\* Display the result.

\* Show progression.

\* Provide a Continue button.

Screen 8: Final victory

Create a memorable ending with a celebratory animation concept, final score, and Replay button.

Also design a level-failure state with a Retry button.

FOUR-LEVEL VISUAL IDENTITY

Use the following initial direction:

LEVEL 1 — THE CLASSIC

A welcoming introduction to the original rules.

LEVEL 2 — THE UNPREDICTABLE

A special modifier changes one of the familiar interactions.

LEVEL 3 — THE STRATEGIST

The player observes previous opponent choices and uses that information.

LEVEL 4 — THE FINAL TWIST

A final challenge combines familiar rules with a more demanding modifier.

These are visual and thematic directions. The exact gameplay rules will be finalised separately, so do not invent complicated mechanics merely to fill the screens.

INTERACTION DESIGN

Make the prototype demonstrate the intended interactions wherever the tool supports them.

Include:

\* Play navigation.

\* Level selection.

\* Rock, paper, and scissors selection.

\* Result feedback.

\* Continue and Retry buttons.

\* Navigation between the relevant screens.

If the prototype tool cannot implement a particular gameplay mechanic, represent its intended interaction clearly in the design.

DESIGN QUALITY

Pay close attention to:

\* Typography.

\* Spacing.

\* Alignment.

\* Button hierarchy.

\* Card proportions.

\* Readability.

\* Visual consistency.

\* Micro-interactions.

\* Responsive layouts.

\* Accessibility.

\* The transition between different game states.

Use consistent design tokens and reusable visual components.

Design for both desktop and mobile.

Avoid clutter, unnecessary menus, excessive text, and decorative elements that compete with gameplay.

FINAL DELIVERABLE

Create a cohesive, polished prototype that can be handed to a developer for implementation.

The screens must look like parts of the same game.

The result should be distinctive enough to stand out in a hackathon while remaining easy to understand and play.

Prioritise originality, clarity, personality, and visual polish.

Do not settle for a generic Rock Paper Scissors layout. Give the game a recognisable visual identity of its own.

## **4\. When AI Got Something Wrong**

**Problem:** The AI-generated game logic did not handle identical actions correctly. During testing, the game displayed identical actions in 4 out of 6 attempts, suggesting that the opponent’s choices were not behaving as expected.

**How We Identified It:**We tested the game across six attempts and observed that the opponent repeatedly selected the same action. This raised concerns about whether the opponent’s decision-making logic was working as intended.

**How We Fixed :We reviewed the opponent’s choice-generation logic and checked whether the randomisation and round-reset mechanisms were functioning correctly. We then corrected the logic to ensure that the opponent’s choice was generated independently for each round, while preserving the standard Rock Paper Scissors rules.**

## **6\. Team Contributions**

* **Team Member 1:** Driver and Artist  
* **Team Member 2:** Puzzle Master and Bard 


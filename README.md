# AI Functionality Demo — Live Input Version

This is the **live-input** variant of your classroom demo. It is designed for inviting a volunteer to type on stage.

## What’s new vs the previous version?
- **Typing support**: When the student types a salary and presses **Enter**, the **AI** calculates immediately.
- **Prompt box**: A simple text prompt (mimicking Copilot) reacts to Enter if it includes the word **tax**.
- **Context dropdown**: Choose hidden context (`student`, `senior`, `non-resident`). AI ignores it until you **Reveal Context**.
- **Human Judgment** applies policy after context is revealed.

## How to run
- Open `index.html` in any modern browser. No install required.

## Suggested on-stage flow
1. Invite a volunteer as your **AI v1.0**.
2. Ask them to type a salary value (e.g., `100000`) and press **Enter**.  
   → **AI Output** shows `33%` calculation.
3. Select a hidden context (e.g., **Student (exempt)**) and click **Reveal Context**.  
   Ask the class: “Should the AI change its answer?”
4. Click **Human Judgment**.  
   → Human Output applies policy (e.g., tax becomes 0 for student).
5. End with: **“AI helps. Humans decide.”**

## Customization ideas
- Replace 33% with your country’s default rate.
- Add more contexts (e.g., low-income threshold, charity entity, GST zero-rated supplies).
- Localize the UI strings to Chinese or bilingual.

MIT License

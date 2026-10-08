# Nurse Voices Matter

A tool for bedside nurses to tell federal regulators what they see at the bedside.

**Now open: FDA's request for feedback on generative AI medical devices (docket FDA-2026-N-7874), due October 19, 2026.** The earlier CMS-1848-P campaign closed September 14, 2026; that version is in the git history.

## The Why

AI tools are already at the bedside: sepsis alerts, ambient scribes, patient chatbots, suggested orders. FDA is now deciding how generative AI medical devices should be tested before approval and watched after launch. Nurses are often the first clinicians to see an AI output and act on it, and the last check before it reaches a patient. FDA's discussion paper asks 26 questions, and it doesn't name nurses as users.

**The goal: unique nurse comments, in nurses' own words, by October 19, 2026.**

Not identical copy-paste letters. Real voices. From ICUs and ERs and clinics and home health and everywhere nursing happens. The kind of comment that says: "I am a nurse. Here is what I've seen these tools do. Here is what FDA should require."

## How It Works

**Nurse Voices Matter** is a single-file web tool that takes about 5 minutes:

1. **Tell us who you are** — two taps: who the letter is from, and where you work
2. **AI at your work** — pick the AI tools you actually see (scribes, sepsis alerts, patient chatbots…). Optionally add the patient-safety work those tools step into, from 46 nursing contributions across 14 settings.
3. **Answer FDA's questions** — the questions that match your tools come first. Search the rest by keyword ("alarm", "chatbot", "scribe") or theme. Sentence starters ("In my work, I have seen…", "FDA should require…") help each answer say what FDA can use. Answers go in the letter under FDA's question number.
4. **Sign and send** — add credentials (optional), read the letter, tick one confirmation, then paste into the web form. Print and share options are below.

No account. Your letter stays on your device until you paste it yourself into the FDA comment form. Google Analytics counts visits and copied letters; it never receives names or letter text.

## Three Ways to Use

- **Online:** Open `Nurse Voices Matter.html` in any browser
- **Print a flyer:** Break-room flyer with a QR code that opens the app
- **Worksheet:** Print a blank form to fill by hand, then type it in later

## Who It's Built For

- Bedside nurses at the top of their shift or on a break
- Nurses who don't usually do policy work but know their care drives outcomes
- Hospitals with firewalls that block regulations.gov
- Nurses who prefer to mail a physical letter
- Anyone who wants to multiply their voice by sharing with 10 other nurses

## The Framework

Your comment should cover four things:

1. **Who you are** — setting and credentials
2. **The AI tools you actually see** — alerts, scribes, chatbots, suggested orders
3. **What you've seen them do** — one real example, in your words, under FDA's question number
4. **What FDA should require** — testing in real nursing workflows, nurses named as users, a human check before AI acts

The tool walks you through all four, in about 5 minutes.

## Where to Submit

- **Online (easiest):** https://www.regulations.gov/docket/FDA-2026-N-7874 (choose Comment)
- **By mail:** not offered in the app. FDA's page for this request lists online submission only; confirm the docket's own instructions before mailing anything.
- **Deadline:** October 19, 2026
- **FDA's discussion paper:** https://www.fda.gov/medical-devices/digital-health-center-excellence/considerations-regulation-generative-ai-enabled-medical-devices-discussion-paper-and-request

## Share It

One comment is a voice. 100,000 comments is a movement. After you submit:

1. Text the link to this tool to 10 nurses you know
2. Print the flyer and post it by the time clock
3. Share it in your unit Slack or group chat

Identical letters get bundled as one comment. Yours counts because it's yours — in your words, from your setting, about your work.

## Technical

- **No dependencies:** Single HTML file, runs anywhere
- **Typeface:** Geist (SIL Open Font License), embedded in the page so it loads offline
- **Offline:** Works without internet once loaded (analytics simply doesn't run)
- **Private:** Everything you type stays in your browser. Google Analytics records visits and copy events (setting and counts only, never names or text). An optional, opt-in form sends specialty and a timestamp.
- **Saves automatically:** Your draft is saved locally as you type
- **Accessible:** WCAG 2.2 AA; works with keyboard only, screen readers, narrow screens, 200% zoom

## License

MIT License — you can use this, modify it, run it, or share it. Just keep the original attribution. See LICENSE file for details.

## Questions?

This tool was built to meet nurses where they are: busy, practical, focused on the bedside, and expert in what they see. If something doesn't work or could work better, let us know.

---

**Built by:** Sharonda Davis  
**For:** Bedside nurses everywhere  
**Goal:** 100,000 nurse voices

Nurse Voices Matter.

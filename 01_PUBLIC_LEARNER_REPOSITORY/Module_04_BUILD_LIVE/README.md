# 🛠️ Module 04 — AI Can Help Me Build

> **AI in Action: Learn • Create • Build**  
> **Theme:** Describe an application in everyday language, create a working prototype, test it and refine it.

![Module 4 — Build with AI](https://github.com/user-attachments/assets/bdd4789d-79e7-4a11-ab6c-fff39719ab92)

[🏠 Main programme](../README.md) · [⬅️ Create with AI](../Module_03_CREATE_LIVE/README.md) · [➡️ Reflect](../Module_05_REFLECT_LIVE/README.md)

## 🌟 Overview

A software project starts with a problem to solve. Generative AI can help turn a written requirement into interface designs, functional code and an interactive prototype. **You do not need prior programming experience to begin**, although testing, understanding and improving the result remain essential.

This module uses **My Smart Planner**, a responsive task-management application suitable for both study-related and professional work. It demonstrates the practical loop: **idea → requirements → prompt → working application → testing → refinement**.

## 🎯 Learning objectives

After exploring this module, you should be able to:

- Describe the users, main features and design requirements of a small application.
- Generate an interactive prototype using [Claude](https://claude.ai/) and an Artifact, where available.
- Test whether features, calculations, controls and data storage behave as expected.
- Request a focused enhancement using a follow-up prompt.
- Distinguish an application **built with AI assistance** from one that **uses an AI model at runtime**.
- Explore a functional offline backup without installing a development environment.

## 💻 Meet My Smart Planner

| Feature | What it does |
|---|---|
| ✅ Task actions | Add, edit, complete, reopen and delete tasks |
| 📅 Dates and priorities | Track due dates and organise tasks by importance |
| 📚 Study / 💼 Work | Switch between two everyday use contexts |
| 📊 Progress | Calculate completed tasks and display progress indicators |
| 🔎 Find tasks | Search, filter and sort the task list |
| 🎨 Theme | Switch between light and dark layouts |
| 💾 Data controls | Store locally, export data, back up and restore task data |
| 📱 Responsive design | Adapt the interface to desktop and mobile screens |

![My Smart Planner interface — repository screenshot](https://github.com/user-attachments/assets/141d645e-e4ad-40ef-95f4-2736e3e2d048)

*Example interface from the programme's existing screenshot gallery. Actual appearance may depend on browser and screen size.*

## 📂 Available learner resources

| File | Purpose |
|---|---|
| [💻 My Smart Planner — offline HTML](03_My_Smart_Planner_OFFLINE.html) | Download and open the working task planner locally. |
| [🎨 Clean audience presentation](04_AUDIENCE_PRESENTATION_CLEAN.pptx) | Review the app-building concepts and workflow. |
| This README | Follow the full build, improvement and test instructions. |

**Opening the HTML app:** On its GitHub file page, download the **raw `.html` file**, save it on your computer and open it in a current desktop browser. You do not need an API key or an internet connection to run the local version. The file is an interactive educational application; it does **not** connect to Claude or another AI model while you use it.

## 🧪 Practical activity — Build an app in natural language

### Step 1 — Define the problem

Imagine that you want one lightweight tool for daily tasks, deadlines and progress. The application should be simple enough for a new user, flexible enough for different contexts and usable on a phone or laptop.

Separate the idea into:

- **Who?** Students, professionals and general users.
- **What?** Manage tasks and track progress.
- **How?** Clear interface, helpful defaults, reliable controls.
- **Where?** A responsive browser-based experience.
- **Limits?** No paid API, account creation or confidential information required.

### Step 2 — Ask Claude to build the prototype

Open [Claude](https://claude.ai/) and use an available interactive Artifact capability. Paste the following prompt:

```text
Create an attractive, responsive, functional interactive application named
"My Smart Planner" as an Artifact.

Core features:
1. Add, edit, delete, complete and reopen tasks.
2. Assign task deadlines, priorities (High / Medium / Low) and categories.
3. Search, filter and sort tasks.
4. Automatically show completed and pending counts plus a progress bar.
5. Offer Study and Work modes with useful editable sample tasks.
6. Include a clear light/dark theme switch.
7. Show helpful messages for empty states and invalid inputs.

Visual style: modern, professional and welcoming, with strong contrast,
readable text, calm accent colours, rounded components and mobile-friendly
spacing. All buttons and calculations must work, not merely look clickable.

Use local application state or browser storage as appropriate for an
educational prototype. No login, payment, external APIs, remote database,
paid service or real personal data is required.

Make the application interactive, then explain its main functions briefly.
```

**Expected result:** An interactive task manager you can click, rather than a static screenshot or only a code listing. If an interactive preview is unavailable, use the provided offline HTML sample to explore the expected behaviour.

### Step 3 — Test the application

A visually pleasing interface is not enough. Try the following real actions:

| Test | Expected behaviour |
|---|---|
| Add a task | The task appears once and counts update |
| Edit its title or priority | The new values are displayed without duplication |
| Mark it complete | Status and progress indicators update consistently |
| Reopen it | Counts and progress return to the correct state |
| Delete a task | Confirmation or undo behaviour is clear, and the item is removed |
| Search and filter | Only matching tasks appear; reset restores the full list |
| Enter invalid data | The app shows helpful feedback instead of silently accepting errors |
| Change theme | Text remains readable in both themes |
| Switch Study / Work | Tasks appear in the intended context without accidental data mixing |
| Refresh or reopen | Persistence works as described by that particular build |

The standalone HTML backup also supports local browser storage and data export. Always test those behaviours in the browser where you intend to use it.

### Step 4 — Improve the application through a follow-up prompt

```text
Improve My Smart Planner without breaking its existing features.
Add a clear "Today's Focus" section showing up to three incomplete tasks,
selected by overdue status, priority and due date.
Explain the selection rule in simple language. Include an empty state
when no tasks qualify. Retest task counts, filters and completion behaviour.
Keep the responsive layout and accessible contrast.
```

A second simple enhancement is to ask for **dark mode** or a **celebration message** on completing all tasks. Ask for one change at a time and test it afterward.

### Step 5 — Explore the offline reference app

Download [My Smart Planner](03_My_Smart_Planner_OFFLINE.html), open it, and try Study and Work sample tasks. Explore search, filtering, task status and progress. Export a test backup, make a change and restore the backup to see how data portability works.

**Storage note:** The offline app stores task information on the local device/browser. Local storage is not a cloud sync service, and data can be lost if browser data is cleared. Avoid putting confidential work, health or financial details into a demonstration app.

![Additional Smart Planner screenshot from the repository](https://github.com/user-attachments/assets/06f72e47-450b-4c3f-b067-e7d9679743cd)

## 🧠 Understanding what AI did—and did not do

AI-assisted development may generate interface code and logic from prompts. Once an ordinary HTML/JavaScript application has been created, its buttons, progress bars and task filters can work **without calling an AI service**. That is the case for the supplied offline HTML app.

To make a planner genuinely AI-powered while running, a separate model integration would be required. That introduces extra design questions about privacy, cost, security, availability and testing. Those are **not** needed for this beginner project.

## ✅ Review and reflection

- Which requirement was easiest to describe clearly?
- Did the generated app actually match the prompt, or only resemble it visually?
- What happened when you entered unusual or incomplete data?
- How did a follow-up instruction change the behaviour?
- Which tests would be essential before allowing others to depend on the app?

## 🔗 Continue learning

- [Claude](https://claude.ai/) — try an interactive Artifact where supported.
- [MDN Web Docs: Web technologies](https://developer.mozilla.org/en-US/docs/Web) — learn more about the HTML, CSS and JavaScript behind browser applications.
- [Programme glossary](../AI_in_Action_Glossary.md) — review terms such as UI, UX, validation, CRUD and responsive design.

## 🌱 Key takeaway

> **AI can help you begin building software; real quality comes from clear requirements, testing and thoughtful refinement.**

[⬅️ Module 03](../Module_03_CREATE_LIVE/README.md) · [🏠 Main programme](../README.md) · [➡️ Module 05](../Module_05_REFLECT_LIVE/README.md)

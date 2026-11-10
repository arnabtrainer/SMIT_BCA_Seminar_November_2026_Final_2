# 🔐 Phase 3 — Publication and Private Archive Guide

**Project:** AI in Action: Learn • Create • Build  
**Repository:** https://github.com/arnabtrainer/SMIT_BCA_Seminar_November_2026  
**Status:** Local packages prepared. The GitHub repository has **not** been changed.

## The two packages

1. **PUBLIC_Repo_Ready** — Learner-facing root README, five module READMEs, existing learner PPTX files, four digital-safety source files, Smart Planner HTML, and glossary. Public PowerPoints have had notes/notesMasters removed from their internal package, including empty placeholders. Image references still point to the existing GitHub user-attachment URLs; no duplicate image files are included.
2. **PRIVATE_Trainer_Archive** — Presenter-master PowerPoints containing speaker notes, internal control cards/guides, quiz-answer delivery advice, and this publication checklist. **Never upload this directory/ZIP to a public repository.**

## Publish safely

1. Make a full backup of your current repository before edits.
2. Save the **PRIVATE** archive in a private, access-controlled place outside the learner-facing repository.
3. Upload the contents of **PUBLIC_Repo_Ready/** to the repository's `main` branch at the repository root, preserving paths. This adds five module-level READMEs and replaces the root README and public slides with sanitized copies.
4. After confirming the private archive is safely stored, **remove all nine previously public trainer files** listed below from the current GitHub branch. Uploading the public ZIP alone does *not* remove existing private files.
5. Review GitHub's rendered main README, each of the five module READMEs, cross-module navigation, image assets, slide downloads, offline HTML download, and glossary. Confirm no training durations or instructor-only directions appear in learner resources.
6. Keep an offline copy of all essential source files and an approved final video for delivery if services fail.

### Remove these nine trainer-only files from the public branch

- `Module_01_DISCOVER_LIVE/01_Module_01_Trainer_Master_WITH_NOTES.pptx`
- `Module_01_DISCOVER_LIVE/03_Module_01_LIVE_CONTROL_CARD_PRIVATE.md`
- `Module_02_LEARN_LIVE/05_Gemini_Notebook_LIVE_CONTROL_CARD_PRIVATE.md`
- `Module_03_CREATE_LIVE/01_PRESENTER_MASTER_WITH_NOTES.pptx`
- `Module_03_CREATE_LIVE/02_OPEN_WHILE_PRESENTING_ALL_PROMPTS.md`
- `Module_04_BUILD_LIVE/01_PRESENTER_MASTER_WITH_NOTES.pptx`
- `Module_04_BUILD_LIVE/02_ALL_IN_ONE_DEMO_GUIDE_PRIVATE.md`
- `Module_05_REFLECT_LIVE/01_PRESENTER_MASTER_WITH_NOTES.pptx`
- `Module_05_REFLECT_LIVE/02_ALL_IN_ONE_TRAINER_GUIDE_PRIVATE.md`


**Important history warning:** Deleting a file from the current GitHub branch does **not** erase it from old commits, forks or previously downloaded copies. If any document contained genuine secrets or sensitive personal/client data, revoke or rotate that data immediately and consider a repository-history remediation procedure. For ordinary lesson pacing and speaker notes, current-branch removal usually addresses routine future distribution, but does not guarantee confidentiality.

## Suggested command-line removal (only after making a private backup)

From a local checkout of the public repository:

```bash
git rm -- "Module_01_DISCOVER_LIVE/01_Module_01_Trainer_Master_WITH_NOTES.pptx"
git rm -- "Module_01_DISCOVER_LIVE/03_Module_01_LIVE_CONTROL_CARD_PRIVATE.md"
git rm -- "Module_02_LEARN_LIVE/05_Gemini_Notebook_LIVE_CONTROL_CARD_PRIVATE.md"
git rm -- "Module_03_CREATE_LIVE/01_PRESENTER_MASTER_WITH_NOTES.pptx"
git rm -- "Module_03_CREATE_LIVE/02_OPEN_WHILE_PRESENTING_ALL_PROMPTS.md"
git rm -- "Module_04_BUILD_LIVE/01_PRESENTER_MASTER_WITH_NOTES.pptx"
git rm -- "Module_04_BUILD_LIVE/02_ALL_IN_ONE_DEMO_GUIDE_PRIVATE.md"
git rm -- "Module_05_REFLECT_LIVE/01_PRESENTER_MASTER_WITH_NOTES.pptx"
git rm -- "Module_05_REFLECT_LIVE/02_ALL_IN_ONE_TRAINER_GUIDE_PRIVATE.md"
git commit -m "Separate learner resources from private presenter materials"
git push origin main
```

If using GitHub's web interface, delete the same nine files individually, then commit the changes. Make sure you do not inadvertently upload the private archive.

## Audit performed on the generated public package

- Required public files are present under their exact existing module folders.
- Five learner module READMEs + root README use valid repository-relative paths.
- Public PowerPoints have **no notesSlides, notesMasters or slide-level hidden flags**.
- Presenter-only filenames do not appear in the public ZIP.
- Quiz answers inside Module 5 README remain intentionally collapsible as self-study content; the full private delivery guide and timing notes are private.
- Module 2 awareness PPTX is a **source document** for Gemini Notebook, not the missing final Module 2 seminar audience deck.
- Module 3 illustrates the video-production workflow but does **not** contain a finished Veo-generated commercial.
- Remote GitHub-hosted images require that the original repository image URLs remain accessible.

## What is still not complete

This Phase 3 package is a **privacy/publication reorganisation**, not a claim that all demonstrations are finished. The live Gemini Notebook outputs, final Veo commercial, and actual published quiz/feedback form still require account-side creation and testing.

## Reuse for other audiences

Keep SMIT event context in the repository identity or cover only. The core READMEs and clean slides are written to support future college, faculty, and corporate sessions without exposing trainer schedules or backstage logistics.

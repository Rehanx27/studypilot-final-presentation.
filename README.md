# StudyPilot — Final Presentation Edition

This is the final standalone, publishable presentation prototype prepared for the StudyPilot portfolio.

## Files
- `index.html` — the actual interactive website (not a placeholder)
- `README.md` — setup and publishing steps
- `CHANGELOG.md` — what changed in this edition
- `curriculum-audit.md` — honest curriculum and launch-readiness status
- `vercel.json` — static-site security headers
- `robots.txt` — allows indexing of public pages
- `PORTFOLIO_COPY.md` — copy-ready text for the published Notion portfolio note

## Publish on Vercel from Android
1. Extract this ZIP on your phone.
2. In Vercel, create or open the StudyPilot project.
3. For the simplest publishing path, upload the project folder through a Git repository connected to Vercel. Create a GitHub repository, upload all files at the repository root, then import that repository in Vercel.
4. Framework preset: **Other**. Build command: leave blank. Output directory: leave blank / project root. Install command: leave blank.
5. Deploy a preview first. Test it on mobile, then promote/deploy to production.
6. Copy the public `https://...vercel.app` URL into the Notion portfolio page.

## Important: do not overwrite the backend-connected project blindly
The earlier StudyPilot setup had Supabase/auth work in progress and an email redirect still pointing to `localhost:2435`. This edition is intentionally a standalone portfolio demo and does not use Supabase. Deploy it as a separate presentation project or preview first, unless you deliberately want to replace the current app.

## Scope and limitations
- It is a clickable, mobile-responsive demo with navigation, Classes 6–10 selection, subject explorer, English/Bangla interface toggle, one original maths sample quiz, local-only demo progress, and a readiness audit.
- Curriculum topics shown are illustrative. This is **not** a complete, chapter-verified NCTB syllabus.
- The interface toggle does not translate every lesson or guarantee equivalent coverage between language versions.
- No login, cloud sync, database, admin dashboard, analytics, or student data collection is included.
- The security headers are useful baseline headers, not a substitute for testing or a full security review.
- The page links to the official NCTB textbook index but does not claim the source index verifies every topic.

## Pre-publication checklist
- [ ] Confirm the correct project and use a preview deployment first.
- [ ] Open on Android and test all four navigation sections.
- [ ] Test class, version and subject filters.
- [ ] Answer the sample quiz correctly and incorrectly; check feedback and progress.
- [ ] Toggle English/Bangla and inspect layout.
- [ ] Check the public page from a logged-out browser.
- [ ] Add the public website URL to the Notion portfolio.
- [ ] Keep the limitations statement visible.
- [ ] Before any real student pilot, verify official books, map chapter order, review original questions, and test auth/permissions/privacy separately.

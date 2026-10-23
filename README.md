# HRE4M Activity Hub

A central, public GitHub Pages repository for **HRE4M1 - Christ and Culture**, Grade 12 Catholic Religion. This is the **umbrella repository for future HRE4M web-based activities and assignments**, not a one-off website.

## Student entry point

When GitHub Pages is enabled for the `main` branch, students open:

- **Course hub:** `https://fslb10.github.io/4M-Activity-Hub/`
- **Unit 1.5 - Paschal Mystery student investigation:** `https://fslb10.github.io/Interactive-Lessons/paschal-mystery/` (hosted in the separate Interactive-Lessons repository)
- **Unit 1.5 - Paschal Mystery teacher take-up:** `https://fslb10.github.io/4M-Activity-Hub/unit-1/paschal-mystery-teacher/`
- **Unit 1.8 - Virtue in Real Life:** `https://fslb10.github.io/4M-Activity-Hub/unit-1/virtue-presentations/`
- **Lessons 1.10–1.12 - Humanity in the Age of AI activity:** `https://fslb10.github.io/4M-Activity-Hub/unit-1/ai-and-humanity/`
- **Lessons 1.10–1.12 - AI and the Human Person assessment:** `https://fslb10.github.io/4M-Activity-Hub/unit-1/ai-and-humanity/assessment.html`
- **Lesson 1.11 - Who Decides What Is Good?:** `https://fslb10.github.io/4M-Activity-Hub/unit-1/objective-moral-truth/`
- **Lessons 1.11 and 1.12 - The Moral Crossroads:** `https://fslb10.github.io/4M-Activity-Hub/unit-1/moral-crossroads/`

## Repository structure

```text
4M-Activity-Hub/
├── index.html                    # Central student launch page
├── README.md                     # Repo-wide structure and maintenance
├── .nojekyll                     # Serve static HTML/CSS/JS directly
└── unit-1/
    ├── paschal-mystery-teacher/
    │   └── index.html            # Unit 1.5 teacher take-up and model responses
    ├── virtue-presentations/
    │   ├── index.html            # Accessible guided planner
    │   ├── styles.css            # Standalone app stylesheet
    │   └── app.js                # Logic, learning content and save/export
    ├── ai-and-humanity/
    │   ├── index.html            # Lessons 1.10–1.12 guided student activity
    │   └── assessment.html       # Separate 15-mark application assessment
    ├── objective-moral-truth/
    │   └── index.html            # Standalone Unit 1.11 student inquiry
    └── moral-crossroads/
        └── index.html            # Two-part activity for Lessons 1.11 and 1.12
```

Use the pattern `unit-N/activity-name/` for new assignments. Every activity should have its own `index.html`, a clear link on the hub landing page, and a one-paragraph explanation of outcomes and submissions. Shared components can be introduced in `/shared/` later, if useful. Do not mix private student submissions into this public repository.

## Unit 1.5 Paschal Mystery resources

The hub places the existing student Psalm 22 investigation directly above its teacher take-up edition. The teacher page is a self-contained presentation and discussion guide with staged answer reveals, model responses, facilitation notes, and a printable guide. Its Student activity link points to the existing page in `fslb10/Interactive-Lessons`. Because this hub is public, the teacher edition and its answers are publicly accessible.

## Unit 1.8 activity

**One group presentation**, format chosen by the students, based on a genuine dilemma from teenage life. It must show how an assigned virtue/quality guides moral choice and what the decision reveals about humanity's identity, dignity, and relationship with God. One planning record from the app is assessed separately as **rough work /10**. Total assignment **/50** (Knowledge/Understanding /10; Thinking/Inquiry /10; Application /10; Communication /10; Rough Work /10). No extra individual written reflection is required for this version.

Students use six stages: group focus → accurate Unit 1.8 understanding → a real dilemma → consequences and Catholic meaning → presentation outline and group roles → review/export. They are not asked to duplicate their answers in a second worksheet.

## Lessons 1.10–1.12 AI and Humanity activity and assessment

**Humanity in the Age of AI** is a six-step guided student inquiry connecting faith and reason, human dignity, conscience, and AI. Students save responses locally and can download a text record or print their work. The separate **AI and the Human Person** assessment has five independent application questions worth 15 marks. Its hub card says to complete it after the class debrief; both pages are publicly accessible. The assessment also saves locally and offers download and print options. Neither page submits answers automatically. The teacher guide and answer key from the local review package are not published here.

## Lesson 1.11 objective moral truth activity

**Who Decides What Is Good?** is a standalone student-led inquiry into objective moral truth. It uses a Canadian MAiD case study to ask students to distinguish claims, apply Catholic moral reasoning, and explain a supported position. The self-contained HTML saves work locally and lets students download or print their responses. It appears in the hub before the existing two-part Moral Crossroads activity.

## Lessons 1.11 and 1.12 activity

**The Moral Crossroads** is a two-part guided Catholic moral theology investigation. **Part 1, following Lesson 1.11**, distinguishes objective moral truth from personal opinion, social approval, and legality, and explains God as the ultimate source of goodness. **Part 2, following Lesson 1.12**, has students work in groups with contemporary moral cases, defend different approaches, evaluate ethical reasoning, and use Aquinas, natural law, conscience, virtue, and grace to reach a supported judgment. The Catholic perspective is explicitly taught; students are assessed on understanding and application, not personal religious assent. The self-contained HTML supports local autosave, response exports, backup/restore, and print.

## Save, portability, and privacy

- Automatic **localStorage** save to the **same browser/device**, with a save-time indicator. It is *not* a cloud account or guaranteed disk backup.
- **Download working file** exports all group inputs and self-checks as human-readable, versioned `.json`; **Restore a file** imports it on another device (explicit confirmation before replacing any existing draft).
- **Print / Save as PDF** produces a readable rough-work record for LMS submission; `.txt` is an alternative.
- Only one group member should maintain the master project file. There is no collaborative syncing or merging; parallel device edits can overwrite each other when one backup is imported.
- The website does not transmit, collect, or store student names on a server. The public GitHub repository contains **only app code**, never student data. Do not commit downloaded group JSON files to this repo.
- Clearing site data, using private/incognito mode, or switching browsers/devices can erase local saved data. Students should download backups often.
- Application is static HTML, CSS and JavaScript. No framework, server, third-party CDN, API key, trackers, or build process.

## How to publish

For a new repository, go to **Settings → Pages → Build and deployment** and choose **Deploy from a branch**, **Branch: `main`**, **Folder: `/(root)`**, then Save. GitHub Pages may take several minutes to publish. Confirm the URLs above load before sharing them with students. `index.html` is the root launch page.

## Maintenance standards

1. Base all religious instructional content on the assigned course notes, citing the section/Scripture/CCC accurately; student Scripture quotations should use the NRSV-CE.
2. Optimize for simple self-directed student progress, accessible keyboard controls, mobile screens and clear submission instructions.
3. Autosave and export/import student work on any activity with written input. Warn about the limits of local saving.
4. Never duplicate graded tasks in an app and a handout unless each artifact has a distinct purpose.
5. Test navigation, storage, export, re-import and printing before releasing any activity.

The updated student-facing handout and rubric are distributed by the teacher separately through the LMS.
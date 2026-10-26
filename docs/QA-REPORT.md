# V2 verification

Website: The Church Recording Studio, user-facing V2, package 4.0.0. Final findings and scope are also recorded in FINISH-REVIEW.md.

## Completed checks

- `npm run check`: 132 local references, fragments, metadata, image attributes, and required-file checks across 13 HTML pages; no broken local paths.
- `npm run build`: static `_site/` generated successfully. All four authored scripts pass syntax checks.
- Repository-path copy configured to `https://example.github.io/THECHURCHPGH/`; the same 132 checks pass. This exercises absolute metadata, canonical URLs, share image URLs and recovery-page base paths without changing relative asset/import paths.
- Source style lint: 7 changed files, 0 FAIL / 0 WARN.
- Independent rendered review: 1440×900, 768×1024, 677×724, 390×844 and 320×568. All 16 inspector images and 8 supplemental lower-page/contact captures reviewed. No page overflow, broken images or uncaught errors recorded in that matrix. The narrow email wrap was corrected and recaptured.
- Studio A title clearance from the image: 42px desktop; 32px at the current 677px view and 320px phone. No negative title offset remains.
- Browser refresh from contact reopens the console sequence, clears the hash, then returns to scroll position zero. After opening, exactly one canvas is mounted in the equipment chapter.
- Actual loading screen captured at 73% as the 1200×630 sharing image. OG/Twitter metadata on all four primary pages references it; dimensions and file bytes verified.
- Forty sequential faders: 0% all down; 50% first twenty raised; 51% next fader at 40% travel; 100% all forty raised. Module lifecycle checks cover canvas transfer, zero reset/reuse, reduced-motion exit, deep-link bypass and disposal of a model resolving after skip. Runtime screenshots show sequential raised/unraised banks.
- Studio B/Mastering selection updates image, details and inquiry action. Native Instagram public account/posts rendered; removed sign-in notice is absent. Personnel contains Dana only. Links are nonselectable; form text remains editable.
- Video inquiry chooses Video services. Green screen prepares a reviewable email message; it does not send. Video/green-screen messages do not assume a Studio A booking. No email was transmitted in testing.

## Inspector findings, correctly scoped

The final inspector records one heuristic FAIL at 677px: it mistakes the previous section's room inquiry and equipment links for eyebrow labels above the next heading. These are functional links in separate semantic sections with generous spacing, visually inspected by the independent reviewer. No decorative eyebrow was added. Seven advisories cover owned warm ink, fluid type roles, on-demand video, deliberate native horizontal gallery, name-only title despite the visible Recording Studio brand, title over its own hero photo, and motion counts that do not count physical WebGL faders. The requested bounded loading screen is an explicit exception to the tool's 1.2-second title deadline.

The static Impeccable scan reports unresolved-CSS contrast/padding estimates and the explicitly requested uppercase presentation. Those static estimates are not a rendered contrast certification. The independent visual review found no material readability issue in the reviewed captures.

## Limits

This is a local browser and source/build review, not physical-device, assistive-technology, all-browser, Lighthouse or production-hosting certification. The full website is deployable; it has not been published by this task. Social platforms may cache their previews after deployment. Instagram/YouTube remain third-party services with direct-link fallbacks. The loader stays bounded if assets fail, and the model is explicitly illustrative. No claim is made that a recording, mix or audio engine runs in the model.

# Legacy Chiropractic launch plan (preview only until approved)

## Held blog posts: redirects at launch (Brevin, Oct 13 6:30 PM CT)
- At launch each held post gets one 301 (single hop): to its matching service page per blog-audit-2026-10-13.md, otherwise to /blog/.
- When a held post is later published (monthly blog service): in the same deploy, remove its redirect, publish the rewritten draft (drafts branch, hold-drafts/<slug>/) at its original URL, and verify it returns 200 with one H1 and no redirect.
- Gate 2b check: the audit shows 0 ranking keywords and 0 referring domains for every held post, so none is a ranking URL and the /blog/ hub fallback does not break gate 2b. Recheck with GSC impressions before launch.
- Counts: 66 held URLs in the audit; 23 to a service page, 34 to /blog/, 9 conflicts (published on preview at the same URL, no redirect until decided).
- /low-back-pain-and-sitting-on-your-wallet/: audit offers /back-pain/ or /sciatica/; planned /back-pain/, confirm.

| Held URL | 301 target at launch | Note |
|---|---|---|
| /athletes-improve-chiropractic-care/ | /blog/ |  |
| /chiropractor-talks-headaches/ | /headaches-migraines/ |  |
| /chiropractic-pregnancy/ | /pregnancy/ |  |
| /chiropractic-treatment-car-accidents/ | /whiplash/ |  |
| /car-accident-tips-chiropractor/ | /whiplash/ |  |
| /finding-chiropractor/ | /blog/ |  |
| /chiropractic-ok-pregnancy/ | /pregnancy/ |  |
| /chiropractic-care-back-pain/ | /back-pain/ |  |
| /educational-requirements-chiropractor/ | /blog/ |  |
| /improve-golf-game-chiropractic/ | /blog/ |  |
| /3-tips-chiropractor/ | /blog/ |  |
| /chiropractors-may-help-tmj/ | /blog/ |  |
| /3-common-conditions-chiropractors-help/ | /blog/ |  |
| /chiropractor-talks-wellness-care/ | /wellness-care/ |  |
| /chiropractic-care-can-help-joint-inflammation/ | /blog/ |  |
| /chiropractic-care-helps-whiplash/ | /whiplash/ |  |
| /time-improve-health/ | /blog/ |  |
| /sitting-epidemic/ | /blog/ |  |
| /just-back-pain/ | /back-pain/ |  |
| /choosing-chiropractor/ | /blog/ |  |
| /headache-tips-chiropractic-office/ | /headaches-migraines/ |  |
| /exercise-smarter/ | /blog/ |  |
| /back-pain-tips-chiropractor/ | /back-pain/ |  |
| /achieve-healthier-spine/ | /blog/ |  |
| /hearty-health-salad-recipe-in-cary-nc/ | /blog/ |  |
| /chiropractor-talks-bulging-discs/ | /disc-injury/ |  |
| /chiropractors-may-relieve-migraines/ | /headaches-migraines/ |  |
| /start-boosting-your-immune-system-now/ | /blog/ |  |
| /choose-chiropractic-office/ | /blog/ |  |
| /chiropractor-explains-avoid-back-injuries/ | /back-pain/ |  |
| /5-tips-to-survive-the-holidays/ | /blog/ |  |
| /kale-5-ways-to-use-and-love-it-from-a-chiropractor-in-cary/ | /blog/ |  |
| /tom-ka-gai-soup-from-a-chiropractor-in-cary/ | /blog/ |  |
| /infant-re-flux/ | (none yet) | CONFLICT: published on preview (patient words kept / rebuilt page); audit target /blog/ |
| /acid-reflux-septembers-testimonial-of-the-month/ | (none yet) | CONFLICT: published on preview (patient words kept / rebuilt page); audit target /testimonials/ |
| /back-pain-relief-naturally/ | /back-pain/ |  |
| /back-and-neck-pain-augusts-testimonial-of-the-month/ | (none yet) | CONFLICT: published on preview (patient words kept / rebuilt page); audit target /testimonials/ |
| /healing-takes-time/ | /blog/ |  |
| /brain-fog-and-arm-weakness-julys-testimonial-of-the-month/ | (none yet) | CONFLICT: published on preview (patient words kept / rebuilt page); audit target /testimonials/ |
| /junes-testimonial-of-the-month-back-spasms-and-disc-herniation/ | (none yet) | CONFLICT: published on preview (patient words kept / rebuilt page); audit target /testimonials/ |
| /silent-spinal-degeneration/ | /blog/ |  |
| /free-dinner-with-the-doc/ | /blog/ |  |
| /nose-bleeds-and-knee-pain-patient-testimonial/ | (none yet) | CONFLICT: published on preview (patient words kept / rebuilt page); audit target /testimonials/ |
| /migraines-mays-testimonial-of-the-month/ | (none yet) | CONFLICT: published on preview (patient words kept / rebuilt page); audit target /headaches-migraines/ |
| /chiropractic-misconception-1-i-cant-afford-it/ | /blog/ |  |
| /chiropractic-and-eliminating-ear-infections-2/ | /chiropractic-care-kids/ |  |
| /specific-chiropractic-in-cary/ | /gonstead-system/ |  |
| /happy-thanksgiving-novembers-testimonial/ | (none yet) | CONFLICT: published on preview (patient words kept / rebuilt page); audit target /testimonials/ |
| /neck-lower-back-pain-decembers-success-story/ | /testimonials/ |  |
| /relief-for-shingles-pain/ | /blog/ |  |
| /chiropractic-for-stress/ | /blog/ |  |
| /cary-chiropractor-explains-to-spring-into-health/ | /blog/ |  |
| /finding-the-right-pillow-a-cary-chiropractic-office-article/ | /blog/ |  |
| /chicken-satays-recipe/ | /blog/ |  |
| /low-back-pain-and-sitting-on-your-wallet/ | /back-pain/ |  |
| /spinal-degeneration-and-time/ | /blog/ |  |
| /choosing-postural-exercise/ | /blog/ |  |
| /bullet-proof-your-low-back/ | /back-pain/ |  |
| /cary-chiropractor-discusses-newborn-chiropractic-checkups/ | /chiropractic-care-kids/ |  |
| /dramatic-posture-change-october-testimonial-of-the-month/ | (none yet) | CONFLICT: published on preview (patient words kept / rebuilt page); audit target /testimonials/ |
| /chiropractic-and-eliminating-ear-infections/ | /chiropractic-care-kids/ |  |
| /dinner-with-the-doc-at-annas-pizzeria/ | /blog/ |  |
| /layered-powerhouse-salad/ | /blog/ |  |
| /come-expecting-miracles/ | /blog/ |  |
| /fun-health-facts-i-bet-you-didnt-know/ | /blog/ |  |
| /headaches-and-the-spine/ | /headaches-migraines/ |  |

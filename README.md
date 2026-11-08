# Players Coach Finder: Accuracy Test

A single-page web app that checks whether phone-GPS yardage to the pin is accurate enough for a golf rangefinder app. It compares the phone's yardage with a laser rangefinder, shot by shot.

- **Open on iPhone:** the GitHub Pages link for this repository (Safari, then Add to Home Screen)
- **How to test:** see [ON-COURSE-GUIDE.md](ON-COURSE-GUIDE.md)
- **Privacy:** everything stays on the phone (browser storage). Nothing is uploaded. The camera image is never recorded.

## Pass / fail

| Result | Rule |
|---|---|
| **PASS** | 50+ comparisons, 90%+ within ±3 yards of the laser, average error 2 yards or less |
| **BORDERLINE** | 75–90% within ±3 yards (find the cause, retest) |
| **NOT YET** | Under 75% |

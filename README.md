# Task 1 Bar Charts

Generated bar charts to describe and compare, with key-feature questions and a timed writing space.

Part of the [IELTS Study Suite](https://github.com/Apurba94/ielts-study-suite): 100 free study apps for IELTS. This one is for the IELTS Academic test. It works offline, as a Windows program or in the browser.

## Download and run

- **Windows:** download `Task 1 Bar Charts.exe` from the [latest release](https://github.com/Apurba94/ielts-bar-charts/releases/latest) and open it. Nothing to install. It opens in its own window and saves your progress in your user folder.
- **Browser:** open it online in the suite's web edition at https://ielts-study-suite.vercel.app/apps/ielts-bar-charts/ . Progress stays in that browser.
- **From source:** `python launcher.py` (Python 3.10 or later, no packages needed).

## What it does

Bar charts in Task 1 usually compare several categories across a few years or groups. Every chart here is generated, with three categories over four periods. Check the key features, then write a report that compares rather than lists, in 20 minutes.

Sections: Key features, Write, Plan, Progress, About.

## How to use it

1. In **Key features**, judge the statements and choose the best overview.
2. In **Write**, group the bars into two or three main comparisons; do not describe every bar.
3. Use **Plan** to check your overview and details.

## Good to know

- All questions, passages, recordings and definitions were written for this suite. None are official IELTS questions. For official practice, use the materials on ielts.org and from the test partners.
- It follows IELTS as delivered on computer in 2026. Formats change, so check ielts.org before your test.
- Listening uses the voices installed on your computer, which sound less natural than real test recordings.
- Feedback on writing and speaking counts what a program can count honestly, such as length and linking words. It is not an IELTS band score. Band conversions for Listening and Reading are approximate.
- Not endorsed by or affiliated with the British Council, IDP or Cambridge University Press & Assessment. IELTS is a registered trademark of its owners.

## For developers

The app is plain HTML and JavaScript in `web/`, run by a small Python launcher that serves it on 127.0.0.1 only and needs a secret token for saving. Tests: `node --test "tests/*.test.js"` (29 tests) and `python -m unittest discover -s tests`. Build the .exe with `python build_exe.py`.

Built with AI assistance (Claude Code). MIT licence. By JANIN A APURBA.

# ShiftCal

A single-file work shift calendar. No build, no dependencies, no server — open `ShiftCal.html` in any browser.

## What it does

- Month view with **Prev / Next / Today** navigation
- Click a day to toggle a shift — cycles **Day → Night → off** (yellow / purple)
- Running **Selected shifts** list below the calendar
- **Export to .ics** — import your selected shifts straight into Apple/Google/Outlook calendars
- **Clear all** to start over

## Notes

Selections live in the page only — refreshing clears them, so export to `.ics` when you're done. Everything (markup, styles, logic) is in the one HTML file, which makes it trivial to host anywhere or just keep on your desktop.

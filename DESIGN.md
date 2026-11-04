# Design notes

Personal homepage and resume of Sina Mozaffari Rad, read mainly by professors and lab members in computer
architecture. Built with the Anti-Slop rulebook (github.com/miqdadbadjuber/anti-slop) as a filter.

**Design Read:** personal academic homepage for professors and lab members, calm academic style,
dial ENERGY 1 / RHYTHM 2 / MOTION 1.

## Decisions and reasons

- **Layout:** a fixed identity column (name, contact, section index) and one reading column. A reader can contact
  or jump to a section from anywhere without scrolling back up.
- **Typefaces:** Source Serif 4 for headings gives the academic, paper-like voice. IBM Plex Sans for body text comes
  from an engineering company's type family, is very readable at small sizes, and has clear figures for dates.
- **Colour:** warm paper background and near-black ink for long reading. One accent, copper, the colour of PCB
  traces, ties the page to hardware. Used only for links, the section index numbers, the interest keywords and
  the heading motif.
- **Identity motif:** each section heading ends in a thin copper line with a small ring at the end, like a trace
  ending in a via.
- **Focal point:** the interests statement at the top of the reading column is the largest text in it.
- **Projects:** the two co-design projects are shown as framed entries because they are closest to the M.Sc. field;
  everything else is a compact list. This gives the section a clear hierarchy instead of a grid of identical cards.
- **Rhythm:** each section uses the form its content needs: a statement, a dated timeline, a single job entry,
  framed entries plus lists, a table for certifications, and a definition list for skills.
- **Motion:** none besides hover and focus states and smooth scrolling for the section links (turned off under
  reduced motion). Nothing on this page needs to move.
- **Theme:** follows the system setting, with a toggle that is remembered. Both themes meet WCAG AA contrast.
- **Content:** everything comes from the LinkedIn profile and the GitHub repositories. No statistics, grades or
  claims that are not in those sources.

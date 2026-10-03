CHARLIE WU — WEBSITE UPDATE

Installation
1. Extract this ZIP.
2. Copy the eight HTML files and site.css into the root of your existing
   cwu4570.github.io repository, replacing matching HTML files.
3. Keep your existing images/ and files/ folders and nodal-cubic-favicon.svg.
   The updated pages use those same assets; they are not duplicated here.
4. Commit and push the changes to your GitHub Pages publishing branch.

Research(1).html has been packaged as Research.html because that is the filename
used by the website links. Home.html continues to redirect to the homepage.
Contact.html is included, using the email addresses and text from the live site.

Design
- Soft off-white background, navy links, and Georgia headings.
- One shared stylesheet for all pages.
- Direct navigation to Home, Research, Talk Notes, Code, Teaching, Gallery,
  and Contact.
- Responsive navigation and a single-column layout on narrow screens.
- Clearer publication titles, dates, and independently expandable abstracts.
- Abstract stays beside the arXiv link when opened; its text expands below
  both controls at the full available width.
- Explicit descending publication numbers (currently 2, then 1).
- Photo captions beneath their images, with uncropped gallery photographs.
- Keyboard focus indicators, a skip link, and descriptive image alternative text.

Content and maintenance
The three commented-out research drafts remain hidden in Research.html.
Published abstracts, mathematics, talk descriptions, and original links are
preserved. The homepage and contact information have been rearranged.
The existing teaching message is retained.

To change colors, spacing, or fonts, edit site.css. Navigation is repeated in
each HTML file, so update all pages when adding a new navigation item.
When adding a publication, update the publication list's start attribute and
each public publication's value attribute to keep the newest paper numbered
highest. Hidden draft entries do not count toward the numbering.

The new pages no longer load nicepage.css, the old page-specific stylesheets,
jquery.js, or nicepage.js. Those files can remain in your repository.
Open Sans and MathJax load from their existing external services. If a visitor
cannot load Open Sans, a system font is used. Mathematical notation requires
MathJax to finish loading.

Validation
Source checks cover all eight pages, shared stylesheet references, local page
links, image paths, original content links, and preserved research abstracts and
hidden drafts. Inline JavaScript syntax was checked. A browser-rendered
preview could not be run because the available browser blocks local file and
localhost URLs. Check the published pages on desktop and mobile after upload.

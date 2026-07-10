I'm building a landing page for "DevConf 2026," a developer conference 
website styled with a white background, Poppins font, and an indigo/blue 
accent color (#4747E0). The existing sections include a hero banner, a 
speaker grid, and a 3-tier pricing section with a dark navy "Pro" card 
(#111827).

For the AI Challenge section, design and code "The Commit Wall": a section 
styled as a macOS-style terminal window running `git log --oneline`, 
displaying attendee shoutouts formatted as git commit entries (hash, 
message, author handle, and a tag like [keynote] or [hallway]).

Constraints:
- HTML and CSS only — no JavaScript, since I'm only using these two
- Simulate a "live" feel using pure CSS @keyframes and staggered 
  animation-delay values, so each commit line fades in one after another 
  on page load
- Reuse the site's existing dark navy color (#111827) for the terminal 
  background so it feels consistent with the pricing section
- Include a heading, a one-line subheading, and a footer row with a CTA 
  button ("Submit a commit") using the site's existing button style
- All 6 sample commit messages must be unique and written in an authentic 
  developer voice — no Lorem Ipsum or generic filler text

Provide the code as a separate HTML block and CSS block, matching my 
existing class-naming style (e.g. .parent-commit, .commit-eyebrow).

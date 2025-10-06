# Resume Site (Kanad Marick)

A clean, single-page responsive resume website generated from your existing PDF resume. Update the placeholder content with your real details.

## Structure
```
resume/
  index.html      # Main resume page
  styles.css      # Styling (dark themed, responsive)
  README.md       # This documentation
```

## Sections
- About: Short professional summary + link to download the PDF.
- Experience: Timeline style cards; list achievements using action + impact.
- Projects: Showcase key work (add GitHub/demo links).
- Education: Degree(s) and relevant coursework.
- Skills: Grouped pill tags for fast scanning.
- Contact: Email + social profiles.

## How to Customize
1. Open `index.html`.
2. Replace placeholder headings, roles, dates, and bullet points.
3. Update contact links (email, LinkedIn, GitHub, etc.).
4. Add/remove project cards as needed.
5. Adjust skills in each group or add new groups.

## Adding More Projects
Duplicate one of the `<div class="card">` blocks inside the `projects` section. Keep descriptions concise and results-focused.

## Performance & Accessibility Tips
- Always include `alt` text for any images you add.
- Keep link text descriptive (avoid “click here”).
- Use measurable outcomes in experience bullets (e.g., Improved load time by 35%).

## Optional Enhancements
- Add a light mode toggle.
- Add a JSON-driven data structure and populate sections via JS.
- Deploy using GitHub Pages (see below).

## Deploy (GitHub Pages)
1. Commit the `resume/` folder.
2. Push to `main`.
3. In GitHub repo settings, enable Pages and set the root (or `/docs`) as source. You can alternatively move these files into `/docs`.
4. Access: `https://<username>.github.io/<repo>/resume/`

## License
Personal use only unless you decide to add a license.

## Next Steps
- Fill in real data.
- Optimize PDF file name if needed (already linked).
- Track visits with simple analytics (e.g., Plausible) if desired.

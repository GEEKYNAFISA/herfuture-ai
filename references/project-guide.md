# HerFuture AI project guide

This reference expands the main skill with practical defaults for website work. Treat these as design guidance, not as evidence that a service, resource, AI integration, or community partnership exists.

## Suggested page structure

- **Home:** a plain-language introduction and clear paths into learning, careers, opportunities, and stories.
- **Learn:** curated free courses and beginner learning paths. Record each resource’s title, publisher, URL, language, level, and last-checked date when those details can be verified.
- **Career guidance:** an interest form or guided prompts that help visitors explore possible tech roles. Make it clear that suggestions are exploratory, not a guarantee of employment.
- **Open source:** beginner explanations, contribution steps, and verified project or event links. Dates and eligibility can change; check the original organizer’s page before publishing them.
- **Women’s stories:** approved stories from women in technology. Obtain permission before publishing and provide a clear way to request a correction or removal.
- **About / contact:** explain the project’s purpose and provide contact information only when the project owner has supplied and approved it.

## Simple file structure for a static website

```text
website/
├── index.html
├── style.css
├── script.js
└── assets/
```

Keep the page structure in HTML, visual styling in CSS, and interactive behavior in JavaScript. Do not add a framework or build process unless there is a clear need.

## English and Hausa

- Keep user-facing strings in one clear translation object or similarly maintainable structure.
- Make the language switch keyboard accessible and expose the current language to assistive technology.
- Use natural Hausa reviewed by a fluent speaker for public-facing copy. Machine-generated translation should be treated as a draft until reviewed.
- Check text wrapping on small screens; Hausa and English labels may have different lengths.
- Do not translate official names or URLs in a way that makes them unrecognizable.

## Resource verification

For each course, event, community, or opportunity, use its official page where possible. Confirm the page is reachable and that its description supports the claim being made. Record a checked date when useful. If a link or detail cannot be verified, omit it or label it clearly as unverified; never fill the gap with a guessed URL, deadline, fee, scholarship, or eligibility rule.

## AI career guidance

A front-end form alone is not an AI system. If the project needs generated guidance, define the real model or service, how it is called, what data is sent, cost or connectivity assumptions, error handling, and user-facing disclosure. Keep secret keys on a trusted server, never in browser JavaScript. Avoid sending names, phone numbers, story submissions, or other unnecessary personal details to a model provider. If there is no working model integration, call the feature a prototype or demo and say what remains to be built.

## Stories and privacy

- Obtain permission before publishing a person’s story, name, photograph, employer, school, or contact details.
- Explain whether submissions are public, private, reviewed before publication, or not actually submitted anywhere.
- Do not build a pretend submit button that silently discards user content while implying it was sent.
- For real collection or storage, explain the destination, access, retention, deletion process, and necessary security controls before launch.

## Accessibility and responsive checks

- Use semantic HTML landmarks and a logical heading hierarchy.
- Label every input; connect errors and help text to the relevant field.
- Keep focus visible and ensure all controls work with a keyboard.
- Provide useful alt text for meaningful images and empty alt text for decorative images.
- Check text contrast and do not convey status using color alone.
- Test at a narrow mobile viewport and at a wider desktop size.
- Respect `prefers-reduced-motion` for non-essential animations.
- Avoid large downloads and unnecessary dependencies for visitors with limited connectivity.

## Beginner handoff

After a change, explain which files changed, how to open or run the site, what to click to test the feature, what checks were performed, and what remains unfinished. Use plain language and explain unfamiliar terms briefly.

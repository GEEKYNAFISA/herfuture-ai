# HerFuture AI Web Builder

An Agent Skill that helps an AI coding agent build and maintain the HerFuture AI website with beginner-friendly HTML, CSS, and JavaScript. The website is intended to help girls and women explore technology learning resources, free courses, open-source opportunities, AI-assisted career guidance, and women’s tech stories, with English and Hausa support.

The skill is a set of instructions for an AI agent; it is not itself the finished website and does not provide an AI model or backend. The agent should inspect the actual project and be honest about which features are implemented.

## Folder structure

```text
herfuture-web-builder/
├── SKILL.md
├── README.md
├── LICENSE
└── references/
    └── project-guide.md
```

## How to use / install

1. Keep the folder name exactly `herfuture-web-builder`.
2. Copy the entire folder into the skills directory supported by your AI coding agent. Skill locations and activation steps differ by product, so check that product’s current documentation.
3. Open your HerFuture AI project in that agent.
4. Ask something like “build the HerFuture AI website”, “add a feature to HerFuture AI”, or “improve the website”.
5. Review the generated changes and test them before publishing. The skill cannot independently guarantee that a feature works.

For a simple static website, the usual starter files are `index.html`, `style.css`, and `script.js`. These belong in the website project, not in this skill folder, unless you deliberately want to bundle a website template here.

## Validate

The recommended reference validator is `skills-ref`:

```bash
python -m pip install skills-ref
skills-ref validate ./herfuture-web-builder
```

Run the commands from the directory containing `herfuture-web-builder`. If installation fails because Python packaging tools or internet access are unavailable, retry in a suitable Python environment and report the failure honestly. A manual check is not the same as running the reference validator.

## Manual checks

- `SKILL.md` begins with YAML frontmatter and includes `name`, `description`, and `license`.
- The `name` is `herfuture-web-builder` and matches the folder name.
- The name uses lowercase letters, digits, and single hyphens only, with no leading or trailing hyphen.
- The description is non-empty and under 1,024 characters, and explains capability, triggers, and exclusions.
- The instruction body is under 200 lines as requested for this project.
- References are linked using paths relative to the skill root.

## License

The skill files are released under the MIT License. See `LICENSE`. The license on any model, external service, third-party code, image, font, or linked resource must be checked separately; this license does not relicense those materials.

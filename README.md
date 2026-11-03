
**Turn shipped work into a product story worth sharing.**

This repository contains **Release Story** (`release-story`), an AI agent skill that turns task lists into a release page and a dynamic product video. Show what changed, why it matters to users, and the people who made it happen.

## Why use it?

- Explain customer benefits instead of publishing a wall of task IDs.
- Give contributors visible credit alongside their work.
- Create consistent release content from one editable source.
- Work with any product and task tracker—not just XTRAMILE or Jira.

## What you get

A responsive release page, an animated HTML presentation, and a final MP4. The default style combines bold typography, dynamic transitions, real product screenshots, and readable feature explanations.

Music, long screenshots, and publishing are optional.

## Example

See our XTRAMILE release story in action:

**[View the example on LinkedIn →](https://lnkd.in/p/dbuKVRKd)**

## How to use

1. Add [skill.md](skill.md) to your agent's skills collection as `release-story/SKILL.md`, following your agent's installation instructions. You can also ask your agent to read the file directly.
2. Provide a task list, Markdown/CSV/JSON export, or access to a task tracker through MCP.
3. Include the product name, release version, audience, branding, screenshots, and contributor names where available.
4. Review the page and animation before the final video export. If screenshots are missing, the agent will list the images to supply.

Example prompt:

> Use release-story to present release 2.4 of our product. Use the attached task list and screenshots. Write in English for our customers, follow our brand colors, and credit the contributors. Create the release page and kinetic presentation, then export an MP4. Show me a preview before rendering the film.

## Make it your own

Customize the result in your prompt: choose colors, typography, animation style, pacing, or music. Your preferences override the default visual profile. You can also request changes after seeing the preview.

**Clean and calm**

> Use white (#FFFFFF), navy (#14213D), and sky blue (#38BDF8). Keep the design minimal, with generous whitespace, gentle transitions, and longer screenshot holds. Add a soft ambient instrumental without vocals.

**Bold and energetic**

> Use charcoal (#121212), lime (#C6FF00), and white (#FFFFFF). Use oversized typography, fast slide transitions, and punchy zooms. Add guitar-driven instrumental rock, with fills and changes in energy aligned to scene transitions. Keep feature descriptions easy to read.

**Playful and colorful**

> Use cream (#FFF8E7), purple (#7C3AED), and coral (#FF6B6B). Use rounded typography, playful shapes, and spring-like entrances at a moderate pace. Add upbeat instrumental funk with bass and drums, and accent each chapter change.

Music depends on available tools or a track you provide with permission to use it.

## Requirements

An AI coding agent with filesystem and browser access, an existing Playwright installation with a compatible browser, and an available video encoder/decoder for MP4 export. The skill checks these first and reports missing dependencies; it does not install or update them.

No Scenario MCP or additional skills are required. The [Scenario skills repository](https://github.com/scenario-labs/skills) serves as inspiration only; its code and installers are not executed.

## License

[MIT](LICENSE). External references and any assets you supply retain their own licenses.

# Urtentic Documentation - Agent Instructions

## Project overview

This is the Urtentic product documentation site, built with Mintlify. It covers identity verification APIs, SDKs, webhooks, and verification processes.

## Mintlify basics

- Configuration lives in `docs.json` - check it before making structural changes
- Use MDX format for documentation pages
- Run `mint dev` locally to preview changes before committing
- Run `mint broken-links` to check for broken links

## Mintlify components

Use Mintlify's built-in components for consistent formatting:
- `<CardGroup>` / `<Card>` for feature grids
- `<Steps>` / `<Step>` for sequential instructions
- `<Tabs>` / `<Tab>` for content tabs
- `<CodeGroup>` for multi-language code examples
- `<AccordionGroup>` / `<Accordion>` for collapsible sections
- `<Info>`, `<Warning>`, `<Note>` for callouts
- `<Frame>` for images with captions

See https://www.mintlify.com/docs/components for all available components.

## Style and formatting

- Use active voice and second person ("you")
- Keep sentences concise - one idea per sentence
- Use sentence case for headings
- When referencing UI elements, use bold: Click **Settings**
- Use code formatting for: file names, commands, paths, and code references

## Code examples

- Include language identifiers in fenced code blocks
- Use `<CodeGroup>` for multi-language examples (JavaScript, Python, PHP, Java)
- Show realistic parameter values, not placeholders like `foo` or `bar`
- Include error handling for API examples

## Content structure

- Add frontmatter (title, description) to every page
- Use `sidebarTitle` in frontmatter if the nav title should differ from the page title
- Include introductory context before diving into steps or details
- Add "Next steps" or related links where helpful

## What to avoid

- Don't edit `docs.json` without understanding the navigation structure
- Don't remove existing pages without checking for inbound links
- Don't use HTML when an MDX component exists for the same purpose
- Don't add pages to navigation that don't exist yet

---
name: example-skill-1
description: A sample Markdown document with YAML frontmatter containing name and description fields. The name uses only lowercase letters, digits, and hyphens (-), with a minimum length of one character. This example demonstrates a well-structured document header followed by rich body content.
---

# Example Document

This file begins with a YAML frontmatter block enclosed by `---` separators. The frontmatter stores structured metadata that tools can read before rendering the body.

## Frontmatter Fields

- **`name`**: Composed of lowercase letters, digits, and hyphens only (at least 1 character). Example: `example-skill-1`.
- **`description`**: A human-readable summary that explains what the document or skill does.

## Naming Rules

The `name` field must follow these constraints:

1. Use only lowercase letters (`a`–`z`), digits (`0`–`9`), and hyphens (`-`).
2. Contain at least one character.
3. Avoid spaces, uppercase letters, and special symbols.

Valid examples: `data-parser`, `report-2026`, `hello`
Invalid examples: `Data_Parser`, `report 2026`, `Hello!`

## Body Content

Below the frontmatter, you can write any Markdown content you like — headings, lists, code blocks, tables, and more. The frontmatter stays cleanly separated from the readable content, making the document easy to parse programmatically while remaining friendly to human readers.

### Example Section

You can organize longer documents into multiple sections, add step-by-step instructions, or embed reference material. This keeps your document both structured and easy to maintain.

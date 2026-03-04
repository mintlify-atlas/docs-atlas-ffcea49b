# Contribute to the cc-statusline documentation

Thank you for your interest in contributing to the cc-statusline documentation! This guide will help you get started.

## How to contribute

### Option 1: Edit directly on GitHub

1. Navigate to the page you want to edit
2. Click the "Edit this file" button (the pencil icon)
3. Make your changes and submit a pull request

### Option 2: Local development

1. Fork and clone this repository
2. Install the Mintlify CLI: `npm i -g mint`
3. Create a branch for your changes
4. Make changes to the MDX files
5. Navigate to the docs directory and run `mint dev`
6. Preview your changes at `http://localhost:3000`
7. Commit your changes and submit a pull request

## Writing guidelines

- **Use active voice**: "Run the command" not "The command should be run"
- **Address the reader directly**: Use "you" instead of "the user"
- **Keep sentences concise**: Aim for one idea per sentence
- **Use sentence case for headings**: "Getting started" not "Getting Started"
- **Lead with the goal**: Start instructions with what the user wants to accomplish
- **Use consistent terminology**: Don't alternate between synonyms for the same concept
- **Include examples**: Show real code from the cc-statusline source repository
- **Escape special characters**: Use `&lt;` and `&gt;` instead of `<` and `>` in MDX tables

## Documentation structure

The documentation is organized into:

- **Getting Started** - Introduction, installation, quickstart
- **Features** - Detailed feature documentation
- **Guides** - Configuration, troubleshooting, performance
- **CLI Reference** - Command and configuration reference
- **Advanced** - Architecture, development, integration

For questions about contributing to cc-statusline itself (not the docs), see the [Contributing guide](/advanced/contributing) in the documentation.

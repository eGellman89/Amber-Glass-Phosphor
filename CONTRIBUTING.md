# Contributing

Contributions, bug reports, and compatibility fixes are welcome.

## Reporting Issues

When reporting a problem, please include:

- Your Obsidian version.
- Your operating system.
- The selected phosphor palette.
- Whether Style Settings is installed.
- A screenshot or description of the affected interface element.
- Any relevant community plugins or CSS snippets.

## Pull Requests

Before submitting a pull request:

1. Test the change with the amber, green, and white palettes.
2. Check Reading view, Live Preview, and the Obsidian interface.
3. Preserve offline functionality and avoid external network requests.
4. Use the existing phosphor variables instead of hard-coded palette colors.
5. Avoid `!important` declarations.
6. Keep embedded font licensing and attribution intact.

Please explain what the change fixes and include screenshots for visible changes.

## CSS Style

- Prefer Obsidian CSS variables where available.
- Keep selectors as narrow as reasonably possible.
- Avoid duplicating existing declarations.
- Preserve Style Settings compatibility.
- Maintain readable contrast across every palette.

## License

By contributing, you agree that your contribution may be distributed under the project's MIT License. Embedded fonts remain subject to their respective SIL Open Font License terms.

# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is "Mine opskrifter" (My Recipes) - a documentation site built with MkDocs for organizing recipes. The project uses MkDocs to generate a static documentation website from Markdown files.

## Development Commands

### MkDocs Commands
- `mkdocs serve` - Start the live-reloading development server on 127.0.0.1:4000
- `mkdocs build` - Build the static documentation site
- `mkdocs new [dir-name]` - Create a new MkDocs project
- `mkdocs -h` - Show help and available commands

### Repository Information
- Repository: https://github.com/MSvante/opskrifter
- Site name: Mine opskrifter
- Development server: 127.0.0.1:4000

## Architecture

### File Structure
```
mkdocs.yml          # MkDocs configuration file
docs/
    index.md        # Documentation homepage
    ...             # Other markdown pages and files
```

### Configuration
- MkDocs configuration is in `mkdocs.yml`
- Custom development server address configured to 127.0.0.1:4000
- GitHub integration configured with repository URL

## Working with Content

- All content files are stored in the `docs/` directory as Markdown files
- The main homepage is `docs/index.md`
- MkDocs automatically processes Markdown files and generates the site structure
- Use standard Markdown syntax for content creation
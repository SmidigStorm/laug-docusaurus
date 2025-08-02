# Smidigakademiet Organization Design - Reference System

## Project Overview
This Docusaurus site serves as a knowledge base for the Smidigakademiet Organization Design Reference System. It's a tool to help organizations understand their current state, define their vision, and identify gaps between them.

## Core Concept
The system provides different "lenses" through which organizations can be viewed and analyzed. Each lens offers:
- **Theory**: Conceptual foundations and principles
- **Tools**: Drawing and modeling tools for visualization and analysis
- **Patterns & Anti-patterns**: Best practices to follow and pitfalls to avoid

## Site Structure
- **Introduction**: Main landing page introducing the reference system
- **About the Reference System**: Explanation of what it is and how to use it
- **Lenses**: Individual pages for each lens (5-9 planned total)
  - Each lens page contains Theory, Tools, and Patterns sections (not sub-pages)

## Current Lenses

### 1. Team and Product Group Structure
- **Focus**: Team topology, types of teams, and product group organization
- **Key Anti-pattern**: Too many teams organized around IT architecture components
- **Status**: Completed
- **Content includes**:
  - Theory on Conway's Law, cognitive load, and team types (stream-aligned, platform, enabling, complicated subsystem)
  - Tools: Team Topology Mapping, Value Stream Mapping, Cognitive Load Assessment, Team API Canvas
  - Multiple patterns and anti-patterns documented

### Future Lenses (Planned: 4-8 additional)
- TBD based on organizational design needs

## Technical Details
- **Domain**: laug.smidigakademiet.no (CNAME configured)
- **GitHub Repo**: SmidigStorm/laug-docusaurus
- **Deployment**: GitHub Pages with automatic deployment on push to main
- **Git Config**: User: Smidigstorm, Email: arnehenrik.storm@gmail.com

## Site Configuration
- **Title**: Laug
- **Tagline**: Smidigakademiet Organization Design - Reference System
- **URL**: https://SmidigStorm.github.io
- **Base URL**: /laug-docusaurus/
- **Custom Domain**: laug.smidigakademiet.no (DNS CNAME → smidigstorm.github.io)

## Key Files and Locations
- `/docs/intro.md` - Main introduction page
- `/docs/about-reference-system.md` - About the system
- `/docs/lenses/` - Directory for all lens pages
- `/docs/lenses/team-product-structure.md` - First implemented lens
- `/static/CNAME` - Contains custom domain for GitHub Pages
- `/.github/workflows/deploy.yml` - GitHub Actions workflow for automatic deployment

## Development Notes
- Keep theory, tools, and patterns on single pages per lens (not separate sub-pages)
- Maintain consistent structure across all lenses
- Focus on practical application for organizational transformation
- Blog functionality has been removed
- Footer simplified to only show copyright
- Navigation updated to show "Reference System" instead of "Tutorial"
- Homepage features updated to reflect multi-lens analysis, theory-informed practice, and patterns

## VS Code Setup
- VS Code configured to open with `code .` command
- Cursor IDE previously installed but replaced with VS Code
- Alias added to .bashrc to ensure VS Code opens instead of Cursor

## Content Guidelines
- Each lens should follow the structure established in team-product-structure.md:
  1. Overview section
  2. Theory section with fundamental concepts
  3. Tools section with practical frameworks and methods
  4. Patterns & Anti-patterns section with clear examples
  5. Assessment questions
  6. Next steps
  7. Further reading recommendations
- Use clear headings and subheadings for easy navigation
- Include practical examples and real-world applications
- Provide actionable insights and tools

## User Context
- Owner: Arne Henrik Storm (Smidigstorm)
- Purpose: Knowledge base for organizational design consulting/methodology
- Target audience: Organizational leaders, change agents, consultants, team leaders, HR professionals
- Approach: Practical, theory-informed, pattern-based
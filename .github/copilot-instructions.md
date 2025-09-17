# vis-aquilaei Creative Writing Repository

vis-aquilaei is a creative writing repository containing French prose narrative content themed around the Warhammer 40K universe. The repository contains narrative text files written in French with UTF-8 encoding to support French accented characters.

Always reference these instructions first and fallback to search or bash commands only when you encounter unexpected information that does not match the info here.

## Working Effectively

- Clone and navigate the repository:
  - `git clone https://github.com/guillaumemaiano/vis-aquilaei.git`
  - `cd vis-aquilaei`
- NO BUILD PROCESS: This repository does not require any build tools, package managers, or compilation steps.
- NO DEPENDENCIES: This repository has no external dependencies to install.
- NO TEST SUITE: This repository does not contain automated tests.

## Repository Structure

```
vis-aquilaei/
├── README.md                    # Minimal project description
├── Spire Secondus-ZegnonPrime  # Main French narrative content (UTF-8 text, 96 lines)
└── .github/
    └── copilot-instructions.md  # These instructions
```

## Working with Content Files

- All narrative content is in French and uses UTF-8 encoding for accented characters (é, è, à, etc.)
- Main content file: `"Spire Secondus-ZegnonPrime"` (note the filename has spaces and no extension)
- Always ensure UTF-8 encoding is preserved when editing files
- Use standard text editors that support UTF-8: `nano`, `vi`, or IDE text editors

## Common Tasks

### Reading Content
- View main narrative: `cat "Spire Secondus-ZegnonPrime"`
- View with line numbers: `cat -n "Spire Secondus-ZegnonPrime"`
- View specific lines: `head -20 "Spire Secondus-ZegnonPrime"` or `tail -20 "Spire Secondus-ZegnonPrime"`

### Editing Content
- Edit with nano: `nano "Spire Secondus-ZegnonPrime"`
- Edit with vi: `vi "Spire Secondus-ZegnonPrime"`
- Always verify UTF-8 characters display correctly after editing

### Content Analysis
- Line count: `wc -l "Spire Secondus-ZegnonPrime"`
- Word count: `wc -w "Spire Secondus-ZegnonPrime"`
- Character encoding check: `file "Spire Secondus-ZegnonPrime"`
- Search content: `grep "search_term" "Spire Secondus-ZegnonPrime"`

### Git Operations
- Standard git workflow applies
- Check status: `git status`
- Add changes: `git add .`
- Commit: `git commit -m "Description of changes"`
- Push: `git push origin branch-name`

## Validation

- ALWAYS verify French accented characters display correctly after any file modifications
- Ensure file encoding remains UTF-8: `file "Spire Secondus-ZegnonPrime"` should show "UTF-8 text"
- Check that content is readable: `head -3 "Spire Secondus-ZegnonPrime"` should display French text with proper accents
- No linting or formatting tools are required for this repository

## Content Guidelines

- Content is creative fiction in French language
- Themed around Warhammer 40K universe
- Maintain narrative consistency and French language quality
- Preserve existing formatting and structure when making edits

## Repository Facts

- Repository type: Creative writing/narrative content
- Primary language: French  
- Content type: UTF-8 text narrative
- Build requirements: None
- Dependencies: None
- Test suite: None
- CI/CD: None configured

## Troubleshooting

- If accented characters appear corrupted: Ensure your editor supports UTF-8 encoding
- If filename with spaces causes issues: Always quote the filename: `"Spire Secondus-ZegnonPrime"`
- For git operations: Use standard git commands, no special configuration needed

## Example Content

The repository contains French narrative text like:
```
Umbra se glissa sous l'énorme tuyau qui pulsait d'une vibration basse fréquence. 
La chaleur qui s'en dégageait était inconfortable...
```

Always maintain this literary quality and French language accuracy when making any content modifications.
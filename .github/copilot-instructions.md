# vis-aquilaei - Creative Writing Repository

vis-aquilaei is a creative writing repository containing French science fiction literature set in the Warhammer 40K universe. This repository focuses on narrative content creation, editing, and version control for literary works.

**ALWAYS reference these instructions first and fallback to search or bash commands only when you encounter unexpected information that does not match the info here.**

## Working Effectively

### Repository Structure
- `README.md` - Basic repository description
- `Spire Secondus-ZegnonPrime` - Main story file (96 lines of French narrative text)
- `.github/` - Repository configuration and workflows

### Essential Commands for Content Work
- View repository structure: `ls -la`
- Check file content: `cat "Spire Secondus-ZegnonPrime"`
- View file statistics: `wc -l "Spire Secondus-ZegnonPrime"`
- Check git status: `git --no-pager status`
- View recent changes: `git --no-pager diff`

### File Management
- **CRITICAL**: Always use quotes when referencing "Spire Secondus-ZegnonPrime" due to spaces in filename
- Use `file` command to identify file types: `file "Spire Secondus-ZegnonPrime"`
- The main story file is UTF-8 encoded French text with very long lines (666 characters per line)

## Validation

### Content Validation Steps
- **ALWAYS** verify file encoding remains UTF-8 after edits: `file "Spire Secondus-ZegnonPrime"`
- Check line count after modifications: `wc -l "Spire Secondus-ZegnonPrime"`
- Validate content integrity: `head -5 "Spire Secondus-ZegnonPrime"` and `tail -5 "Spire Secondus-ZegnonPrime"`
- Verify no corruption occurred: `cat "Spire Secondus-ZegnonPrime" | grep -c "Umbra\|Aquilaeus\|Ignivar"` (should return character references)

### Git Workflow Validation
- Always check git status before committing: `git --no-pager status`
- Review changes: `git --no-pager diff`
- Verify branch information: `git --no-pager branch -a`
- Check recent commit history: `git --no-pager log --oneline -n 5`

## Build and Test Requirements

### No Traditional Build System
- **IMPORTANT**: This repository has NO build system, package managers, or compilation steps
- **NO** npm, pip, make, or other build commands are needed
- **NO** dependencies to install or manage
- Content validation is performed through text inspection and git operations only

### Content Testing
- Validate French text encoding: `file "Spire Secondus-ZegnonPrime"`
- Check for text corruption: Visual inspection of content with `head`, `tail`, and `cat`
- Verify line endings: `file "Spire Secondus-ZegnonPrime"` (should show UTF-8 text)

## Common Tasks

### Content Editing
- Use `str_replace_editor` tool for precise text modifications
- Always preserve UTF-8 encoding and French accents
- Maintain narrative flow and consistency
- **NEVER** use commands that might corrupt text encoding

### File Operations
- View content: `cat "Spire Secondus-ZegnonPrime"`
- Edit content: Use str_replace_editor tool with exact string matching
- Check file size: `ls -lh "Spire Secondus-ZegnonPrime"`
- Backup before major edits: `cp "Spire Secondus-ZegnonPrime" "Spire Secondus-ZegnonPrime.backup"`

### Version Control
- Stage changes: `git add .`
- Check what will be committed: `git --no-pager diff --cached`
- Use report_progress tool for commits and pushes
- **NEVER** use direct git commit/push commands

## Time Expectations

### Instant Operations (< 1 second)
- File viewing with `cat`, `head`, `tail`
- Git status checks
- Basic file operations

### Quick Operations (< 10 seconds)
- Text editing with str_replace_editor
- Git diff operations
- File copying and backup operations

## Important Notes

### Character and Content Guidelines
- Content is French narrative text in Warhammer 40K universe
- Key characters: Umbra (Vindicare assassin), Aquilaeus, Ignivar, T'varis, Merash, Galahad, Asterion Luciano
- Setting: Spire Secondus on planet ZegnonPrime
- Narrative style: Third-person, military science fiction with detailed action sequences

### Technical Constraints
- File contains very long lines (666 characters) - this is normal for this content
- Always preserve French accents and special characters
- Text encoding must remain UTF-8
- Line count should remain approximately 96 lines unless intentionally modified

## Quick Reference Commands

### Repository Status
```bash
cd /home/runner/work/vis-aquilaei/vis-aquilaei
pwd
ls -la
git --no-pager status
```

### Content Inspection
```bash
file "Spire Secondus-ZegnonPrime"
wc -l "Spire Secondus-ZegnonPrime"
head -3 "Spire Secondus-ZegnonPrime"
```

### Backup and Safety
```bash
cp "Spire Secondus-ZegnonPrime" "/tmp/backup-$(date +%Y%m%d-%H%M%S).txt"
```

Remember: This is a creative writing repository, not a software project. Focus on content integrity, version control, and literary workflow rather than traditional development tools.
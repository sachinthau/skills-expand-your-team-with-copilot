# Issue Templates

This directory contains GitHub issue templates to help teachers submit well-structured change requests.

## Available Templates

### 🐛 Bug Report (`bug_report.yml`)
For reporting issues, errors, or broken functionality on the website.

**Use when:**
- Something isn't working as expected
- There's a visual bug or error
- Features are broken or malfunctioning

### ✨ Feature Request (`feature_request.yml`)
For requesting new features or enhancements to the website.

**Use when:**
- You need new functionality
- You want to add capabilities
- You have ideas for improvements

### 🎨 UI/Styling Enhancement (`ui_styling.yml`)
For requesting visual or design changes.

**Use when:**
- Colors need to be changed
- Layout needs adjustment
- Visual improvements are needed
- Styling doesn't match brand guidelines

### 📝 Documentation Update (`documentation.yml`)
For requesting updates to documentation, README files, or guides.

**Use when:**
- Documentation is outdated
- Instructions are missing or unclear
- Code comments are needed
- Guides need updating

### 📅 Activity Management (`activity_management.yml`)
For requesting changes to activities (add, modify, or remove).

**Use when:**
- New activity needs to be added
- Activity details need updating
- Activity schedule needs changing
- Activity should be removed

## Configuration

The `config.yml` file configures:
- Whether blank issues are allowed (currently: `true`)
- Contact links for additional support
- External resources

## Documentation

For detailed guidance on using these templates, see:
- [How to Submit Issues - Complete Guide](../../docs/how-to-submit-issues.md)
- [Quick Reference Guide](../../docs/issue-templates-quick-reference.md)

## Template Structure

Each template includes:
- **Clear title and description** - Explains when to use the template
- **Required fields** - Ensures necessary information is provided
- **Dropdown menus** - For common options and categorization
- **Text areas** - For detailed descriptions
- **Acceptance criteria** - Checklist for completion
- **Validation** - Ensures critical fields are filled out
- **Examples** - Placeholder text to guide users

## Design Principles

These templates follow best practices for Copilot coding agent:

1. **Completeness** - All information needed to implement changes
2. **Clarity** - Clear problem descriptions and acceptance criteria
3. **Structure** - Organized fields for easy parsing
4. **Context** - Space for hints, constraints, and related information
5. **Validation** - Required fields prevent incomplete submissions

## Maintenance

When updating templates:
1. Maintain consistent structure across all templates
2. Ensure YAML syntax is valid
3. Test that required validations work
4. Keep examples and placeholders helpful
5. Update documentation when templates change

## Testing Templates

To verify YAML syntax:
```bash
python3 -c "import yaml; yaml.safe_load(open('template_name.yml'))"
```

Templates will automatically appear in GitHub's "New Issue" interface when this directory is pushed to the repository.

---

For questions or issues with these templates, please contact the repository maintainers or use GitHub Discussions.

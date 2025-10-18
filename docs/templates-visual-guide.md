# Issue Templates Visual Guide

This guide shows what teachers will see when they create new issues using the templates.

## How to Access Templates

1. Go to the repository on GitHub
2. Click the **"Issues"** tab
3. Click the **"New Issue"** button
4. You'll see a list of template options

## Template Selection Screen

When creating a new issue, teachers will see:

```
┌─────────────────────────────────────────────────────────────┐
│  🐛 Bug Report                                    [Get started]│
│  Report a bug or issue with the Mergington High School       │
│  Activities website                                           │
└─────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────┐
│  ✨ Feature Request                               [Get started]│
│  Request a new feature or enhancement for the activities     │
│  website                                                      │
└─────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────┐
│  🎨 UI/Styling Enhancement                        [Get started]│
│  Request changes to the visual design, layout, or styling    │
│  of the website                                               │
└─────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────┐
│  📝 Documentation Update                          [Get started]│
│  Request updates to documentation, README files, or other    │
│  written content                                              │
└─────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────┐
│  📅 Activity Management Request                   [Get started]│
│  Request to add, modify, or remove activities from the       │
│  system                                                       │
└─────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────┐
│  Open a blank issue                                           │
└─────────────────────────────────────────────────────────────┘
```

## Example: Bug Report Template

When clicking "Get started" on Bug Report, teachers see:

```markdown
# Bug Report

Thanks for taking the time to report a bug! Please provide detailed 
information to help us understand and fix the issue.

─────────────────────────────────────────────────────────────────

Problem Description *
┌───────────────────────────────────────────────────────────────┐
│ Example - The website displays blue colors instead of our     │
│ school colors (white and lime green)                          │
│                                                                │
└───────────────────────────────────────────────────────────────┘
What is the bug or issue you're experiencing?

─────────────────────────────────────────────────────────────────

Current Behavior *
┌───────────────────────────────────────────────────────────────┐
│ Describe what you see now                                     │
│                                                                │
└───────────────────────────────────────────────────────────────┘
What is currently happening?

─────────────────────────────────────────────────────────────────

Expected Behavior *
┌───────────────────────────────────────────────────────────────┐
│ Describe what you expect to see                               │
│                                                                │
└───────────────────────────────────────────────────────────────┘
What should be happening instead?

─────────────────────────────────────────────────────────────────

Where is the issue occurring? *
[Choose an option ▼]
  - Homepage/Activity List
  - Activity Registration
  - Search/Filter functionality
  - Login/Authentication
  - Activity Details Display
  - Visual/Styling issue
  - Other (please describe below)

─────────────────────────────────────────────────────────────────

Steps to Reproduce
┌───────────────────────────────────────────────────────────────┐
│ 1. Go to the homepage                                         │
│ 2. Click on 'Soccer Club'                                     │
│ 3. Notice the incorrect color scheme                          │
│                                                                │
└───────────────────────────────────────────────────────────────┘
How can we reproduce this issue?

─────────────────────────────────────────────────────────────────

Acceptance Criteria *
┌───────────────────────────────────────────────────────────────┐
│ - [ ] School colors (white and lime green) are used          │
│       throughout the website                                  │
│ - [ ] Blue colors are replaced appropriately                  │
│ - [ ] All existing functionality still works                  │
│                                                                │
└───────────────────────────────────────────────────────────────┘
What needs to be true for this bug to be considered fixed?

─────────────────────────────────────────────────────────────────

Additional Context
┌───────────────────────────────────────────────────────────────┐
│ Add any screenshots, error messages, or related information   │
│ here                                                           │
│                                                                │
└───────────────────────────────────────────────────────────────┘

─────────────────────────────────────────────────────────────────

Confirmation *
☐ I have checked that this issue hasn't already been reported
☐ This issue is specific to the Mergington High School Activities 
  website
```

## Example: Feature Request Template

Key sections teachers will see:

```markdown
# Feature Request

Thanks for suggesting a new feature! Please provide detailed 
information so we can understand and implement your idea.

Fields include:
✓ Feature Description *
✓ Problem or Need *
✓ Feature Category * (dropdown)
  - New View/Display Option
  - Filter/Search Enhancement
  - Registration/Enrollment Feature
  - Activity Management
  - User Interface Improvement
  - Performance Enhancement
  - Accessibility Improvement
  - Other
✓ Proposed Solution *
✓ Acceptance Criteria *
✓ User Benefit *
✓ Implementation Hints (optional)
✓ Priority Level * (High/Medium/Low)
✓ Additional Context (optional)
```

## Example: Activity Management Template

Key sections for managing activities:

```markdown
# Activity Management Request

Use this template to request changes to activities (adding new 
ones, modifying existing ones, or removing activities).

Fields include:
✓ Request Type * (dropdown)
  - Add new activity
  - Modify existing activity
  - Remove activity
  - Bulk update (multiple activities)
✓ Activity Name *
✓ Activity Details *
  - Description
  - Category
  - Days
  - Time
  - Maximum participants
  - Difficulty level
✓ Category *
✓ Schedule Information *
✓ Maximum Participants *
✓ Reason for Change *
✓ Acceptance Criteria *
✓ Effective Date * (dropdown)
  - Immediately
  - Next week
  - Next month
  - Specific date
```

## Benefits of Form-Based Templates

### For Teachers:
✅ **No formatting needed** - Form handles structure
✅ **Guided input** - Clear labels and examples
✅ **Can't miss required fields** - Validation prevents submission
✅ **Dropdown menus** - Easy selection from options
✅ **Professional appearance** - Consistent formatting

### For Developers/Copilot:
✅ **Structured data** - Consistent format every time
✅ **Complete information** - Required fields ensure completeness
✅ **Easy parsing** - Standard YAML structure
✅ **Automatic labels** - Issues are pre-categorized
✅ **Clear criteria** - Checklist-based acceptance criteria

## Field Types Used

### Text Area (Multi-line)
Used for: Descriptions, detailed explanations, acceptance criteria
- Large input box
- Supports markdown formatting
- Can include examples in placeholder

### Dropdown
Used for: Categories, priorities, preset options
- Click to select from list
- Ensures consistent values
- Guides user choices

### Input (Single-line)
Used for: Short answers like names, numbers
- One line of text
- Quick to fill out
- Good for specific data

### Checkboxes
Used for: Confirmations, agreements
- Must check to submit (if required)
- Clear terms and conditions
- Prevents accidental submissions

### Markdown
Used for: Instructions, help text
- Provides guidance
- Explains the section
- Shows examples

## Tips for Teachers

1. **Read the placeholder text** - It shows examples
2. **Fill required fields (marked with *)** - Can't submit without them
3. **Use the dropdown menus** - Easier than typing
4. **Write clear acceptance criteria** - Use checklist format
5. **Add screenshots** - Paste directly into text areas
6. **Save drafts** - GitHub auto-saves as you type

## Common Questions

**Q: What if I choose the wrong template?**
A: You can close and start over with a different template.

**Q: Can I skip optional fields?**
A: Yes, but more information helps get better results.

**Q: What's acceptance criteria?**
A: A checklist of things that must be true when the work is done.

**Q: Can I edit after submitting?**
A: Yes, you can edit the issue description after creation.

**Q: What happens after I submit?**
A: The issue will be reviewed and may be assigned to Copilot.

## Example Filled-Out Template

Here's what a completed bug report looks like:

```markdown
Title: [Bug]: School colors not displayed correctly

Problem Description:
The website currently displays a blue color scheme, but our school 
colors are white and lime green.

Current Behavior:
- Header is dark blue
- Background is light blue
- Buttons are blue

Expected Behavior:
- Header should be lime green (#32CD32)
- Background should be white (#FFFFFF)
- Buttons should use lime green accent

Where is the issue occurring?
Visual/Styling issue

Acceptance Criteria:
- [x] Primary color changed to lime green (#32CD32)
- [x] Background colors use white (#FFFFFF)
- [x] Text colors provide good contrast
- [x] All existing functionality still works
- [x] Colors match school branding guidelines

Additional Context:
School branding guidelines: [link]
Reference color palette attached
```

---

**Note:** The actual GitHub interface may vary slightly from these mockups, but the structure and fields will be identical.

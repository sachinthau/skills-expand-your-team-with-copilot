# How to Submit Issues - Guide for Teachers

This guide explains how to submit well-structured issues that GitHub Copilot can work on automatically.

## Why Use Issue Templates?

Issue templates help you:
- Provide all necessary information for changes to be implemented
- Ensure consistent and clear communication
- Allow Copilot coding agent to work without additional clarification
- Track progress on your requests effectively

## Available Issue Templates

We have created several issue templates for different types of requests:

### 1. Bug Report 🐛
**Use when:** Something isn't working correctly on the website

**Examples:**
- Colors are wrong (e.g., website is blue instead of school colors)
- Registration isn't working
- Filters don't display correct activities
- Login issues

**What to include:**
- Clear description of the problem
- What you see vs. what you expect
- Where the issue occurs
- Steps to reproduce (if applicable)
- Acceptance criteria for when the bug is fixed

### 2. Feature Request ✨
**Use when:** You want to add new functionality to the website

**Examples:**
- Add a calendar view
- Add difficulty levels to activities
- Create a group-by option for filters
- Add export functionality

**What to include:**
- Description of the feature
- Problem or need it addresses
- How you envision it working
- Who will benefit from it
- Clear acceptance criteria

### 3. UI/Styling Enhancement 🎨
**Use when:** You want to change how something looks

**Examples:**
- Change color scheme to match school colors
- Add dark mode
- Improve mobile layout
- Add animations or visual effects
- Add school mascot images

**What to include:**
- What needs to change visually
- Current appearance vs. desired appearance
- Specific colors or styles (if known)
- Brand guidelines or references
- Acceptance criteria

### 4. Documentation Update 📝
**Use when:** Documentation needs to be updated or created

**Examples:**
- README file is outdated
- Missing setup instructions
- Need developer guide
- Code comments needed

**What to include:**
- Which documentation is affected
- What's wrong with current content
- What should be included instead
- Which sections need updates

### 5. Activity Management 📅
**Use when:** You need to add, modify, or remove activities

**Examples:**
- Add new activity (Robotics Club)
- Change meeting times
- Update capacity limits
- Remove discontinued activity

**What to include:**
- Activity name and details
- Complete schedule information
- Category and capacity
- Reason for the change
- When it should take effect

## How to Submit an Issue

1. **Go to the Issues tab** in the GitHub repository
2. **Click "New Issue"**
3. **Select the appropriate template** from the list
4. **Fill out all required fields** - the more detail, the better!
5. **Review your submission** to ensure all information is clear
6. **Submit the issue**

## Tips for Writing Good Issues

### ✅ DO:
- Be specific and detailed
- Include examples where helpful
- Provide clear acceptance criteria (checklist of what needs to be true when done)
- Mention any constraints or special requirements
- Include links to examples or reference materials
- Use precise technical terms when known (e.g., "24-hour time format" or "hex color codes")

### ❌ DON'T:
- Leave required fields empty
- Be vague (e.g., "make it better")
- Assume everyone knows the context
- Submit duplicate issues (search first!)
- Mix multiple unrelated requests in one issue

## Acceptance Criteria

Every issue template asks for **acceptance criteria**. This is a checklist of things that must be true for the issue to be considered complete.

**Good acceptance criteria example:**
```
- [ ] School colors (white #ffffff and lime green #32CD32) are used throughout
- [ ] Header background is lime green
- [ ] Activity cards have white backgrounds
- [ ] Text remains readable with good contrast
- [ ] All existing functionality still works
```

**Poor acceptance criteria example:**
```
- [ ] Colors are fixed
- [ ] Looks good
```

## After Submitting

Once you submit an issue:
1. The issue will be reviewed
2. Copilot coding agent may be assigned to work on it
3. You can track progress through comments and updates
4. You'll be notified when the work is complete
5. You can test the changes and provide feedback

## Questions?

If you're unsure which template to use or how to fill it out, you can:
- Start with the template that seems closest to your need
- Provide as much detail as you can
- Ask for help in the Additional Context section
- Use GitHub Discussions for general questions

## Examples of Well-Written Issues

### Example 1: Bug Report
**Problem:** Website colors don't match school branding

**Current Behavior:** The website uses a blue color scheme

**Expected Behavior:** Website should use white and lime green (school colors)

**Acceptance Criteria:**
- [ ] Primary color changed to lime green (#32CD32)
- [ ] Background colors use white (#ffffff)
- [ ] Text colors adjusted for readability
- [ ] All existing features still work

### Example 2: Feature Request
**Feature:** Add difficulty levels to activities

**Problem:** Freshmen and seniors are in the same activities, but some students want level-appropriate options

**Proposed Solution:**
- Add optional difficulty field (Beginner, Intermediate, Advanced)
- Add filter in sidebar
- Only show difficulty if specified

**Acceptance Criteria:**
- [ ] Backend supports difficulty field
- [ ] Activities can be tagged with difficulty
- [ ] Filter option appears in sidebar
- [ ] Activities without difficulty don't show the field

---

**Remember:** The more detailed and clear your issue is, the faster and more accurately it can be implemented! 🚀

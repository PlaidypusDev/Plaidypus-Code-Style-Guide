# Commit Messages

*Based on [this](http://chris.beams.io/posts/git-commit/) guide by Chris Beams.*

## Table of Contents

  1. [Rules](#rules)
  1. [Template](#template)

## Rules

  1. Separate subject from body with a blank line
  1. Limit the subject line to 50 characters
  1. Capitalize the subject line
  1. Do not end the subject line with a period
  1. Use the imperative mood in the subject line
  1. Wrap the body at 72 characters
  1. Use the body to explain what and why vs. how

## Template

### To apply this template to SourceTree:

  1. Open SourceTree.
  1. Select 'General'.
  1. Check the box for 'Display column guide in commit messages at character:' and type '72' in the box.
  1. Select 'File' > 'Preferences'.
  1. Select 'Commit Template'.
  1. Copy and paste the following template into the text area:

```
Enter 50 char capitalized imperitive subject-----|

If necessary, this is where you will type a longer summary of the 
commit. Git does not automatically wrap the line of the commit message 
so you should manually go to a new line at the 72 character mark. Use 
the body to explain "what and why" vs. "how."
```

# Uncommon HTML Bug: Incorrectly Closed Paragraph Tag
This repository demonstrates an uncommon HTML bug related to incorrectly closing paragraph tags when dynamically adding content. The bug occurs in some browsers due to how they handle malformed HTML.  This can lead to unexpected formatting and layout issues.  The solution shows how to correctly close tags to avoid this.

## Bug
The `bug.html` file contains the problematic code.  The dynamically added paragraph is missing a closing `</p>` tag, which can lead to inconsistencies in how different browsers render the page.

## Solution
The `bugSolution.html` file provides a corrected version of the code. The closing `</p>` tag has been added to ensure proper HTML structure and consistent rendering across all major browsers.
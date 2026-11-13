# Accessibility Conformance Starter

Use this small site for Module 5 practice if you do not want to use your capstone yet.

## Files

- `index.html`: sample page with intentional accessibility issues.
- `styles.css`: starter styles with some focus, contrast, reflow, and motion issues to audit.

## Practice goal

Audit and remediate:

- landmarks and heading structure
- link and button names
- keyboard access and visible focus
- zoom/reflow behavior
- contrast
- form labels and required states
- table caption/headers
- image alternatives
- motion preference

Document each issue, fix, and retest result.


Questions

1. After an automated check via Lighthouse, the following issues were found
        - The buttons do not have an accessible name. What will happen is that screen readers will announce it as "button", making it unusable for users who rely on screen readers.
        - The form elements do not have the associated labels, resulting in screen readers not being able to identify the purpose of the text box properly.
        - Heading elements are not in sequential-descending order. Properly ordered headings that do not skip levels convey the semantic structure of the page, making it easier to navigate and understand when using assistive technologies.


Notes: 

An issue that the automated tool caught was the inaccessible button name, and an issue that I found myself was the viewport size not scaling for smaller viewports.

AI Disclosure:

AI was not used for this assignment. Everything done in this practice was done by myself.

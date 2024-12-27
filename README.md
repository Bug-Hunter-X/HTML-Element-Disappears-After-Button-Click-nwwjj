# Uncommon HTML Bug: Disappearing Element

This repository demonstrates a simple yet uncommon bug in HTML where an element disappears after a button click and lacks the code to restore its visibility.  The bug's root cause is the absence of code to reverse the `display: none;` style applied to the element.

The `bug.html` file contains the flawed code, while `solution.html` provides the corrected version.

## Bug Description

A button click hides a div element using JavaScript. However, there's no mechanism to make the div reappear, resulting in a permanently hidden element after the first click.  This is an easy-to-miss bug and exemplifies the importance of comprehensive state management in dynamic web pages.
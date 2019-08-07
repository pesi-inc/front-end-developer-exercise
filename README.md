# Introduction

This exercise is expected to take 2 hours or less. However, time spent is not part of our assessment. Please work at your own pace in whatever environment is most comfortable for you. If you have any questions, please reach out to us!

# Exercise

Using the accompanying `index.html`, `index.css`, and `messages.json` files as references, create an Angular or React application which:

- Displays a list of messages (see `messages.json` for sample data)
- Visually distinguishes read from unread messages based on message state (see `index.html` and `index.css` for example styling)
- Visually distinguishes a selected message from unselected messages (see `index.html` and `index.css` for example styling)
- Selects a message when it is clicked with a maximum of one selected message
- Displays a dynamic count of unread messages (see `index.html` for an example)
- Dynamically at runtime (i.e. not statically and directly referenced in templates or components) adds buttons for marking a message read or unread (see `index.html` for example placement; think of these actions as local plugins)
    - If no messages are selected, `Mark Read` and `Mark Unread` should be disabled
    - If an unread message is selected, `Mark Read` should be enabled while `Mark Unread` should be disabled
    - If a read message is selected, `Mark Unread` should be enabled while `Mark Read` should be disabled
    - Clicking `Mark Read` should change the selected message state to read, should visually indicate the message is read, and should update the unread message count
    - Clicking `Mark Unread` should change the selected message state to unread, should visually indicate the message is unread, and should update the unread message count

Feel free to use the included HTML in `index.html` and styles in `index.css` or introduce your own markup and styling.

## Deliverables

- An Angular or React application which meets the above criteria and which can be run locally via NPM or Yarn

Preferred delivery is via public Git repository (e.g. GitHub). Please exclude `node_modules` from your repository (or any attachments if delivering by email).
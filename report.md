# AI Challenge Project Report

## Project Overview

Replicated and anonymized a company leaderboard web page using AI-assisted development tools.

---

## Step 1: Capture Original Site Styling

Used the Claude MCP (Model Context Protocol) browser tool to navigate to the original SharePoint leaderboard page. The MCP tool allowed Claude to inspect the live page and extract:

- HTML structure and layout
- CSS styles and class definitions
- Component hierarchy and visual design patterns

From this inspection, created a standalone `index.html` file with an embedded or linked `styles.css` that reproduced the original page's look and feel without requiring SharePoint infrastructure.

---

## Step 2: Anonymize Employee Data

Used Claude's coding agent to replace real employee data with fake/synthetic data:

- First names and last names replaced with randomly generated fictional names
- Department names changed to fake alternatives
- Updated `employees.js` to contain only anonymized records

This ensured no real personal information remained in the project while preserving the data structure and visual layout.

---

## Step 3: Integrate Fake Avatars

Used a prompt to instruct Claude to integrate placeholder/fake avatar images for each employee entry:

- Replaced any real profile photos with generated or placeholder avatars
- Avatars linked to each employee record in `employees.js`
- Visual consistency maintained with the original design

---

## Step 4: Make Selectors and Search Interactive

Used prompts and Claude's coding agent to implement interactive UI features:

- **Department selector**: Dropdown filters the employee list by department
- **Search field**: Text input filters employees by name in real time
- JavaScript event listeners added to wire up filter logic
- UI updates dynamically without page reload

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Claude MCP browser tool | Navigate live site, extract HTML/CSS |
| Claude coding agent | Data anonymization, JS interactivity |
| Claude prompts | Avatar integration, feature specification |

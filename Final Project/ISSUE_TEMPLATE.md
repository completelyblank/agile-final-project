## User Story

**Title**: Add dark mode toggle to UI

**As a** frequent user  
**I need** a toggle to switch between light and dark mode  
**So that** I can reduce eye strain during night-time use

---

## Details and Assumptions

- UI is built with Tailwind CSS
- Theme should persist across sessions using localStorage
- Button will be placed in the top navbar
- Default mode is light unless previously toggled

---

## Acceptance Criteria

**Given** the user is on any page of the app  
**When** they click the "dark mode" toggle  
**Then** the color theme changes to dark, and the choice is saved

**Given** a user previously enabled dark mode  
**When** they revisit the site  
**Then** the UI loads in dark mode automatically

---

## Labels

- `feature`, `frontend`, `ui/ux`, `priority-low`

---

## Assignees

- @completelyblank

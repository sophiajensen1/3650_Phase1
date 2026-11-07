# Accessibility Notes

## HTML Structure

- `<header>` holds the home link and `<nav>` for the main menu.
- `<main>` holds the page heading and task. Use `<section>` to group related content, like office results.
- `<aside>` can hold optional help.
- `<footer>` holds Contact DMV and Update mailing address.

## Keyboard Order

On each page, Tab moves through **Skip to main content** > **Home** > **Header links** > **Breadcrumbs** (if shown) > **Main controls** > **Footer links**.

| Screen | Main controls in Tab order |
|---|---|
| Home | Book appointment > Find an office > Out-of-state registration > Renew registration |
| Offices & Appointments | Find an office > Book appointment > Change or cancel > What to bring |
| Find an office | City or ZIP > Search > Office results |
| Office details | Book at this office > Back to results |
| Walk-in-only office | Check walk-in options > Find another office |
| Choose service | Service choices > Continue |
| Choose office | Office choices > Continue |
| Choose date and time | Date choices > Time choices > Continue |
| Review appointment | Name > Email > Book appointment > Change date or time |
| Confirmation | Review what to bring |
| Registration | Renew > Register a new vehicle > Out-of-state registration > Fees |
| Choose ownership | I own my vehicle > I lease my vehicle |
| Owned and leased checklists | Find an office > Change vehicle type |

Use arrow keys to move through radio button selection. 

## Screen Reader Notes

- Name the two menus `aria-label="Primary"` and `aria-label="Breadcrumb"`.
- Give each input a visible `<label>`. 
- Move focus to the new heading after each booking step.

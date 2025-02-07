# :focus-visible Pseudo-class Issue

This repository demonstrates a problem with the CSS `:focus-visible` pseudo-class.  The expected behavior is that the outline is only shown when the focus is programmatically set (e.g., using the Tab key) and there is no other visual change to indicate focus.  However, in this example, the outline appears even when the button's background color changes on hover, making the outline redundant and potentially jarring to the user experience.

## Steps to Reproduce

1. Clone this repository.
2. Open `index.html` in your web browser.
3. Observe the button's behavior when it receives focus (using Tab or mouse click).
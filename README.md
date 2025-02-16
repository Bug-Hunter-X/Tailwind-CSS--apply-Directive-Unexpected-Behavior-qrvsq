# Tailwind CSS @apply Directive Unexpected Behavior
This repository demonstrates an uncommon bug encountered when using the `@apply` directive in Tailwind CSS with complex selectors. The issue involves unexpected behavior and inconsistencies in how styles are applied.

## Description
The bug involves using the `@apply` directive with a complex selector that includes pseudo-classes or sibling combinators. In some cases, the expected styles aren't applied correctly, leading to visual inconsistencies or broken layouts.

## Reproduction
To reproduce this bug, follow the steps below:
1. Clone this repository.
2. Install the dependencies using `npm install`.
3. Run the development server using `npm start`.
4. Observe the unexpected styling on the elements that utilize `@apply` with complex selectors.

## Solution
This repository includes a proposed solution that addresses the unexpected behavior. In addition to the bug reproduction files (bug.js, bug.css), there's a solution file (bugSolution.js, bugSolution.css) that demonstrates a workaround or fix.

## Additional Notes
This bug might be related to specific versions of Tailwind CSS or interactions with other CSS frameworks or libraries. Refer to the solution for potential fixes and workarounds.
# Uncommon HTML Bug: Button Inside Label

This repository demonstrates an uncommon HTML bug involving a button nested within a label element associated with a form input.  The unexpected behavior manifests primarily in the inconsistent toggling of the checkbox or radio button when clicking the button.

Some browsers may not correctly associate the button click with the checkbox, resulting in the checkbox not being checked/unchecked as expected.  Others might trigger unexpected actions entirely.

## Bug Description
The bug involves the interaction between the nested button element and the form input element.  The expected behavior is a direct and reliable toggling of the form element upon clicking the button. However, browsers exhibit inconsistencies in achieving this functionality.

## Solution
The solution uses alternative methods to maintain the desired user experience and achieve reliable form element manipulation. Specifically, we will add Javascript event listeners and directly handle the checkbox state change.
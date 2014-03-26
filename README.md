This is a working example of accessible checkboxes using ARIA attributes to achieve accessibility. 

A JavaScript function checks for the activation of the space bar as default HTML checkboxes are activated via the space bar and toggles the image and state upon pressing the key.

The "aria-labelledby" attribute is required because label elements can only be applied to form elements.
Span elements are being used instead of default HTML checkbox inputs so aria-labelledby is needed for association.

NOTE: This is not a recommended solution. Default HTML checkbox elements should be used when checkboxes are desired however this is a proof of concept that ARIA properties can be used to achieve accessible checkboxes if desired. Developers may wish to use this concept if using images instead of default HTML input elements for custom checkboxes.

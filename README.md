# hugo-mod-error-message

Hugo module for configurable error messages.

## Syntax

The module contains the partial `error-msg` expecting 2 to 4 parameters in the context map:

**errorMsg** the message string (mandatory)

**errorLevel** One of ["ignore", "warning", "error"] to determine the behaviour. (mandatory)

**ctx** The context in which the partial is called. (optional)

**caller** The name of the calling template (optional)

The context is used to determine the relative path to the erroneous content.

Run `hugo` in the folder `exampleSite` for a demonstration and watch the console.

The partial is always called from `layouts/index.html`.

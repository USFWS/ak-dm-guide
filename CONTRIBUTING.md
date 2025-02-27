---
title: "How to contribute"
---

Install Quarto

The install should update your path and run from any command terminal.

Change to the project directory (if using GitHub Desktop, select "Repository - Open in Command prompt", or `Ctrl+\`)

Run the "Quarto preview" to start a live preview session that will render the updated pages as you edit. Some changes may not be automatically rendered by the preview, and you may need to exit (type `Ctrl-c` in the command window) and then restart the preview.

The site may need to be re-built (run "Quarto render") after edits are complete. This is usually only needed prior to deploying a site to the server.

# Style guide

## Graphics

Use short (this is subjective, so use your best judgement) but desriptive names

```default
Good: rdr-uri-elements.png
Bad: image (8).png
Bad: regionalDataRepository-uri-components.png
```



## Callout boxes

Come up with some guidance on when callout boxes should be used. See Quarto [Callout Blocks](https://quarto.org/docs/authoring/callouts.html) documentation for details.

:::{.callout-note}
Note that there are five types of callouts, including:
`note`, `warning`, `important`, `tip`, and `caution`.
:::

:::{.callout-tip}
## Custom title can be added
Tip callout. Use this for a general tip.
:::

:::{.callout-warning}
Warning callout
:::

:::{.callout-caution}
Caution callout
:::

:::{.callout-important}
Important callout. Maybe use this to higlight destructive operations.
:::


## Icons##

Quarto uses [Bootstrap icons](https://icons.getbootstrap.com/) for various components (e.g., [Sidebar Tools](https://quarto.org/docs/reference/projects/websites.html#sidebar-tools)). Icons are referenced by name, as displayed on the Bootstrap icon page.

:::{.callout-note}
There is an extension that allows for the display of [Font Awesome](https://fontawesome.com/icons) icons within the body of the text, however, it is not currently installed.
:::


## Directories

A directory renders as a collapsable section. Do we want to limit the depth to one subdirectory-level?
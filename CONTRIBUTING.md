---
title: "How to contribute"
---

Install Quarto

The install shoudld update your path and run from any command terminal

Change to the project directory (if using GitHub Desktop, select "Repository - Open in Command prompt", or `Ctrl+\`)

Run the "Quarto preview" to start a live preview session that will render the updated pages as you edit.

After edits are complete, run "Quarto render" to render the entire site.

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


## Directories

A directory renders as a collapsable section. Do we want to limit the depth to one subdirectory-level?
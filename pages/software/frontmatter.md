---
title: Frontmatter
subtitle: FVTC Software Documentation
hide-nav: false

live: https://fvtc.software/fvtc/software/frontmatter
---

# Frontmatter

Frontmatter is metadata that is included at the top of a Markdown file. It is used to provide information about the page, such as the title, subtitle, etc.

Here is an example of frontmatter:

```yaml
---
title: Introduction
subtitle: FVTC Software Documentation
hide-nav: false

live: https://fvtc.software/fvtc/software/introduction
---
```

# Page Generation

Frontmatter is used by the FVTC.Software platform to generate pages. The `title` and `subtitle` fields are used to generate the page title and subtitle, respectively. The `hide-nav` field is used to determine if the page should display the navigation bar on the left side of the page.

# Live Link

This field doesn't affect the page generation, but it is used to provide a link to the live version of the page. This is just for convenience and is not required. In VS Code, you can click on the link to open the page in your browser, by holding `Ctrl` and clicking on the link.
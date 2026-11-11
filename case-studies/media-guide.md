# Media guide and editorial tools

I contributed to an editorial product that brings structured profile information, generated draft material, and human review into one working environment. The challenge is more than displaying a guide: editors need to know what is saved, what is approved, and which edition they are changing.

The work involved connecting structured content to editable pages, supporting review and reopening, carrying previously approved material into the next edition as a draft, and making supporting information available for inspection. My focus is the relationship between generated material and editorial judgment. A draft becoming available is a different event from someone approving it for use.

Engineering considerations include preserving edits when saving fails, rejecting changes based on an older revision, keeping edition context attached to content, and making navigation land on the intended subject. These decisions matter because an apparently successful page load does not establish that the right content or version is being shown.

This is a contribution summary, not a claim of sole authorship or of an autonomous AI author. Structured content generation and an AI assistant are different capabilities. No internal copy, images, statistics collection, branding, screenshots, or system links are reproduced here.

## Inspect an independent example

[Publication Workbench](https://github.com/dgoetz365/publication-workbench) is a newly built arts-program application with fictional performers and venues. Edit a draft, validate its links, review the exact revision, publish an immutable edition, search to a particular entity, and export a self-contained program.

Its tests demonstrate the public example's behavior. They are not runtime verification of the internal product. The example illustrates the editorial engineering decisions while using an unrelated setting and original content.

[All work notes](../WORK.md) · [Profile](../README.md)

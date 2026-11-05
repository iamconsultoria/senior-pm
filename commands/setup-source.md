---
description: Point the plugin at your copy of the PMBOK Guide 8th Edition for verified citation
---

Configure the PMBOK source for this plugin, per
`skills/senior-project-manager/references/00-source-protocol.md`.

Path or upload: $ARGUMENTS

If the user supplied a path, confirm the file exists and is readable, then record it in
`pmbok-source.txt` at the plugin root so future sessions find it automatically. If they
uploaded the PDF instead, confirm you can read it and note that the upload lasts for this
conversation only.

Verify by extracting the table of contents and reporting what you found — book structure, page
ranges, edition. If the file is not the 8th edition, say so.

If no source is available, explain plainly: the plugin works fully without it, using its own
knowledge of the framework, but citations will be section-level rather than page-verified.
Nothing is gated behind having the book.

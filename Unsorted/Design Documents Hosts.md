# Design Documents Hosts

This document features thoughts on various hosts for collaborating on design documents.


## Overview

- Hosting platform
	- Penflip (privacy: _paid_)
	- GitHub (privacy: _paid_)
	- Bitbucket (privacy: **free**) 
- Editor
	- Online (Penflip)
	- Offline (Any editor e.g. TextMate and Byword)
- Format
	- WYSIWYG
		- Let's not go there... (@snorredc)
	- Markdown
		- Very, *very* widely supported
		- Good for most things, though not extensible
		- Enforced by certain hosts/editors
	- RestructuredText
		- Extensible
		- Harder to write than Markdown
	- Textile
		- Probably extensible?
		- Probably old?
		- Probably inferior to the other two?
- Preview
	- Online (GitHub, Bitbucket)
	- Offline (TextMate, `pandoc`, `markdown`)


## Online editors

### [Penflip](https://www.penflip.com)

- No free privacy
- Untested (@snorredc: it just popped up in my inbox)
- Seems powerful
- Has Git support
- Has a very structured contribution system, it seems
- Supports fenced code blocks and syntax colouring ... but not in preview and not for Rust
- Supports MathJax.


## Hosting

### Dropbox
**Nominated for disqualification on 2014-12-23 (@snorredc)**

- Free privacy (2 GB)
- Automatic file syncing
- No collaboration
- Not so powerful collaborative versioning (@snorredc: Is this true?)

**@snorredc**: I'd rather not. Specifically the small overall size, and less focus on collab/versioning.


### GitHub

- No free privacy
- Syncing with `git`
	- VCS: powerful and explicit \<3
- Very pretty preview
- Any editor will do


### Bitbucket

- Free privacy (unlimited? :)
- Syncing with `git` or `hg`
	- VCS: powerful and explicit \<3
- Pretty preview
- Any editor will do


## Disqualified

### Typewrite.io 
**Disqualified on 2014-12-23 (@snorredc, @machtan)**

- Source control
	- BUGGY :(
	- Markdown
		- Cannot handle fenced code blocks
		- Cannot handle syntax colouring
	- Private by default
	- Handles versions
		- But does not handle collaborative changes very well
		- Cannot delete saves (yet)
		- Twitchy `Cmd+S` spams versions
	- No syncing/export (yet)
	- Minimalistic, but maybe not quite powerful enough
- Editor
	- Immaturity
		- Caret position inconsistent (@snorredc: Safari for Mac)
		- Does not handle bullet indentiation very well (@snorredc)
	- Nice enough style
- Preview
	- Nice enough style
- IT KEEPS TWITCHING (Collected on Mozilla Firefox at 2014-12-23)

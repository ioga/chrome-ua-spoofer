It's totally experimental
===
As of Chromium version 16, it stopped working, and i failed to figure out the reason :(

Description
===
This extension just substitutes Firefox user-agent for all url matching `/\/owa\//`.

Motivation
===
Older OWA installations forbid full mode for Chromium (since they don't recognize it), and the 'light' one definitly sucks.

Installation
===
- Get new chromium
- Go to chrome://flags
- Turn on Experimental API out there
- Go to Tools -> Extentions
- Click 'Developer Mode'
- Load unpacked extension
- Select this dir
- Success.

Q&A
===
**Q**: Yet another User-Agent spoofing extension?

**A**: Yep, but this one actually works.


# Tim Clifford's firefox config

My own firefox config, based on
[minimal-functional-fox](https://github.com/mut-ex/minimal-functional-fox) and
[ff-vertical-tabs](https://git.sr.ht/~ranmaru/ff-vertical-tabs).
`userChrome.css` is from both, the svg's are
from mff, and `tabCenterReborn.css` is from ff-vertical-tabs.

##  How to install

**From ff-vertical-tabs `bf16f382`:**

- Go to `about:config` in your URL bar, search for
  `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to
  `true`.
- Go to `about:profiles` in your URL bar, click "Open Directory" next to
your Root Directory under your default profile
  - If there is no `chrome` folder, create it.
  - Create a file called `userChrome.css` inside the `chrome` folder.
  - Copy & paste the contents of `userChrome.css` into your file (or
    symlink it).
- Install the [Tab Center Reborn](https://addons.mozilla.org/en-US/firefox/addon/tabcenter-reborn/)
  extension.
- Make sure to enable "Allow this extension to run in Private windows"
  so you're not left stranded while browsing.
- Go to `about:addons` in your URL bar, select *Tab Center Reborn*, go
  to *Preferences* and set:
  - *Animations*: on.
  - *Use current browser theme*: on, if you want to use dark mode.
  - *Compact Mode*: either "Dynamic" or "Enabled". It works with
    "Disabled" too but looks nicer with only favicons.
  - *Favicon-only pinned tabs*: off.
  - Activate *Custom Stylesheet* and paste the contents of
    `tabCenterReborn.css` into the text area below, and click "Save
    CSS" under the text box.
- Restart Firefox.

# Confluence User Macros
[![Groovy](https://img.shields.io/badge/Language-Groovy-informational.svg)](https://groovy-lang.org/)
[![Velocity](https://img.shields.io/badge/Language-Velocity-informational.svg)](https://velocity.apache.org/)
[![Support](https://img.shields.io/badge/Supported-yes-009900.svg)](https://github.com/glewe/confluence-user-macros/issues)

## What are Confluence User Macros ?

If you run your own Confluence instance (Server or Data Center) you can create custom “User Macros”, little scripts 
that can be included in pages creating content on the fly. With those macros you can create simple HTML code snippets 
as well as utilize Velocity code accessing information from your Confluence database.

I will not address the basics of writing a user macro here. That is well documented in the Confluence documentation 
[here](https://confluence.atlassian.com/doc/writing-user-macros-4485.html).

## My User Macros

Along my work as a Confluence administrator I ran into several situations where native Confluence Server features did 
not offer what admins or users needed. Plugins were not available either or too expensive for the purpose. In many of 
those cases I found that a user macro was just the right solution to the challenge. The Confluence user community 
helped me a lot writing them. Here are my most useful ones as my contribution back to that community.

---

### [Anonymous Permissions](/src/anonymous-permissions)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/anonymous-permissions/kgpg-32.png?raw=true" align="left" alt=""/>
This Confluence user macro lists all spaces where 'Anonymous' has at least view permissions.

---

### [Audio Control](/src/audio-control)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/audio-control/arts-32.png?raw=true" align="left" alt=""/>
This Confluence user macro adds an HTML5 audio control element to your page that can play MP3, OGG and WAV files.

---

### [Blockquote](/src/blockquote)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/blockquote/info-32.png?raw=true" align="left" alt=""/>
This Confluence user macro adds a styled blockquote to your page.

---

### [Bootstrap Button](/src/bootstrap-button)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/bootstrap-button/bootstrap-32.png?raw=true" align="left" alt=""/>
This Confluence user macro adds a Bootstrap 3 styled button, supporting different colors and sizes, and linking to a URL.

---

### [Bootstrap Progress Bar](/src/bootstrap-progress-bar)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/bootstrap-progress-bar/bootstrap-32.png?raw=true" align="left" alt=""/>
This set of two Confluence user macros adds a Bootstrap like progress to your page, offering different coloring and animation options.

---

### [ChartJs v2](/src/chartjsv2)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/chartjsv2/kchart-32.png?raw=true" align="left" alt=""/>
This set of Confluence user macros adds animated diagrams to your page based on Chart.js v2.

---

### [Colored Panel](/src/colored-panel)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/colored-panel/window_list-32.png?raw=true" align="left" alt=""/>
This Confluence user macro adds a headed panel to your page with several coloring options.

---

### [Profile Info](/src/profile-info)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/profile-info/vcard-32.png?raw=true" align="left" alt=""/>
This Confluence user macro displays a panel with the profile info of a single user or all users of a group.


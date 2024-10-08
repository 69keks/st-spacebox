✨ st-spacebox
--------------
st-spacebox is a simple terminal emulator fork with custom
colors derived from spaceduck and gruvbox material palettes
for X which sucks less.


📦 Requirements
---------------
In order to build st-spacebox you need this repo, `dina-font-ttf`,
any nerd font for glyph cache and the Xlib header files.


🚀 Installation
---------------
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

\# `make clean install`


🏃 Running st
-------------
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

$ `tic -sx st.info`

See the man page for additional details.

📷 Screenshots
![Intro](./assets/intro.png?raw=true)
![Workflow](./assets/workflow.png)
![Neovim](./assets/neovim.png)

©️ Credits
----------
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

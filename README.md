##### dot-config 
`babel`
`bash`
`curl`
`eslint`
`gulp`
`json`
`vim`
`SSH`
`tern` 
`terminator`
`tmux`
`webpack`
`xkb`
`setxkbmap`

###### structure
```
.
├── .bash_aliases
├── .bashrc
├── cat-spec
│   ├── .babelrc
│   ├── .config
│   │   ├── gtk-3.0
│   │   │   └── gtk.css
│   │   └── terminator
│   │       └── config
│   ├── crontab
│   │   └── git-auto-push
│   ├── .curlrc
│   ├── gatsby
│   │   ├── .eslintrc.js
│   │   └── package.json
│   ├── gulp
│   │   ├── latest-gulpfile.babel.js
│   │   └── old-test-gulpfile.js
│   ├── ssh
│   │   └── ssh-config-example
│   ├── tdd-bdd
│   │   ├── jest.config.json
│   │   └── mocha-standardJS-example-packagage.json
│   ├── .tern-config
│   ├── .tern-project
│   ├── vim
│   │   └── plugins-vim
│   │       └── vim-jsx
│   │           └── xml.vim
│   └── webpack
│       ├── webpack.common.js
│       ├── webpack.dev.js
│       └── webpack.prod.js
├── doc
│   ├── gallium-doc
│   │   └── gallium-notes.md
│   ├── git-doc
│   │   └── template.txt
│   ├── nix-doc
│   │   ├── bash
│   │   │   ├── .bash_aliases
│   │   │   ├── .bashrc
│   │   │   ├── notes.md
│   │   │   ├── redirect-pipe-sort-uniq.sh
│   │   │   ├── shell-scripts.md
│   │   │   └── shortcuts-bash.md
│   │   ├── curl-GET-jq-etc.md
│   │   ├── default-shell-apps.md
│   │   ├── misc-notes.txt
│   │   ├── older-config-notes.md
│   │   └── test.txt
│   ├── tdd-bdd-doc
│   │   └── notes-unit-testing.md
│   └── vim-doc
│       ├── shortcuts-vim.md
│       └── vimium-notes-vim.md
├── .eslintrc.js
├── os-spec
│   └── gallium-os
│       ├── .bash_aliases
│       ├── .bashrc
│       ├── .vimrc
│       └── xkb
│           ├── chromebook_minimal
│           ├── chromebook_minimal_vim
│           ├── mykbd
│           ├── vimSwap
│           ├── .xkb
│           │   ├── keymap
│           │   │   └── mykbd
│           │   ├── recomp.sh
│           │   └── symbols
│           │       └── vimSwap
│           └── xkb-notes.md
├── README.md
├── .tmux.conf
└── .vimrc

26 directories, 51 files
last generated: Sat Jan  5 21:40:49 PST 2019
```
###### packages
null
###### notes
null
###### changelog
`2019.01.05.1`
  - significant clean-up and organization
  - extensive `.tmux.conf` created and added 
  - add `gtk.css` (fix blank line in gnome-terminal)
  - updates to `.vimrc` and `.bash_aliases`
  - update RM / structure (tree) accordingly
  - remove unused including `.gemrc` and `git.run`


`2019.01.04.2`
  - improve default shell app notes
  - fix path for `z` in `.bashrc`


`2019.01.04.1`
  - fzf add in `.bashrc`
  - add vim-repeat `.vimrc`
  - update tree
  - create shell app notes + organize


`2018.12.28.4`
  - remove redundant CL since it's here for now


`2018.12.28.3`
  - new alias `.bash_aliases`


`2018.12.28.2`
  - create gatsby directory
  - add gatsby config files `package.json` & `.eslintrc.js` (standard, react)
  - update tree


`2018.12.28.1`
  - add mkdircd() to `.bashrc`


`2018.12.27.1`
  - edit `.bashrc` (organize + remove unused)
  - update `.bash_aliases` with git commands


`2018.12.26.1`
  - add `.tmux.conf`
  - bash and terminator upates 
  - update this RM, tree, cl


`2018.12.14.1`
  - remove scripts from here (rethought)
  - terminator config
  - .bashrc $HOME addendum


`2018.12.14`
  - adjust terminator config again
  - add shell scripts (for replication and use)
  - add tree / notes sections
  - update this README / changelog

`2018.12.13`
- update and clean-up README

`2018.6.25`
- start switch from standard to jslint / prettier
- add .eslintrc.js

`2017.2.4`
- add / refine / improve gallium-notes
- add GalliumOS config notes and other updates
- other organization and refactoring

`2017.2.3`
- add GalliumOS updated .vimrc
- other minor tweaks
- create dir for unit tests, ssh, gulp + mv related files
- add GalliumOS keyboard mapping files for chromebooks (xkb)

*resources:*

- [Reddit: GalliumOS - "Help with keyboard mapping"](https://www.reddit.com/r/GalliumOS/comments/7fj1wl/help_with_keyboard_mapping/)
- [Stack Exchange: "Use setxkbmap to swap the Left Shift and Left Control"](https://unix.stackexchange.com/questions/65507/use-setxkbmap-to-swap-the-left-shift-and-left-control/65600)

`2017.12.1`
- changed <leader> in .vimrc
- updated README
- see commit -m's for prior minor updates

`2017.10.1`
- update .bash_aliases with cp-dot (refactor)
- added ssh-config-example
- update documentation

`2017.9.29`
- added new `cd` aliases to .bash_aliases
- added new `cp` file aliases to .bash_aliases
- added .bashrc to VCS

`2017.5.31`
- misc. 

`2017.5.18`
- vimrc: change noexpandtab to expandtab for standardjs and syntastic error checking compatibility

`2017.5.15`
- vimrc: remove old/unused lines from previous plugins / settings
- other misc.

`2017.5.13`
- vimrc: add syntastic, remove overflow hl, remove pathogen
- added standardjs and html tidy things

`2017.5.8`
- added gem and curl.
- testing text width and text width highlighting.

`2017-5-7`
- added vundle to .vimrc
- you complete me (YCM) / config via vundle
- added change log

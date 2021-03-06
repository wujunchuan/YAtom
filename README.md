
## YAtom

* Integrated more than 200 plugins and well tuned settings without conflicts.
* Vim-style key mappings, which are as consistent as possible with [YVim](https://github.com/dexteryy/YVim)'s.
* Screenshot:

![Atom screenhhost](https://raw.github.com/dexteryy/YAtom/master/screenshot.png)

## Setup

#### Step 1

```
git clone https://github.com/dexteryy/YAtom.git ~/.atom
cp ~/.atom/config_sample.cson ~/.atom/config.cson
```

#### Step 2

Use [package-sync](https://atom.io/packages/package-sync) to accomplish a "one-click install":

* Open Atom
* Install a plugin named 'package-sync' (`apm install package-sync`)
* Restart Atom
* Press `cmd-shift-P`
* Type `package sync: sync` to start installing plugins
* Wait for the installation process to complete (see the bottom bar for the process information)
* Restart Atom

#### Step 3 (optional)

Install [Hack](http://sourcefoundry.org/hack/) font

#### Step 4

Done. Take a minute to get familiar with key mapping, toolbar and plugins.

## Plugins

See [packages.cson](https://github.com/dexteryy/YAtom/blob/master/packages.cson)

## Key Mappings

See [keymap.cson](https://github.com/dexteryy/YAtom/blob/master/keymap.cson)

## Toolbar

See [toolbar.cson](https://github.com/dexteryy/YAtom/blob/master/toolbar.cson)

## Theme

* Syntax theme: [monokai-blackboard](https://github.com/dexteryy/monokai-blackboard)
* UI theme: [customized](https://github.com/dexteryy/YAtom/blob/master/styles.less) Atom Dark

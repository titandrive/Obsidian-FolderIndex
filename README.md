# FolderIndex

FolderIndex is a simple Obsidian plugin that automatically opens a selected note when you click on a folder in the filetree. 

Do you frequently find yourself clicking through your obsidian filetree just to open the same note and wish there was a quicker way? This plugin is for you. 

## How it works

When you click on a folder, FolderIndex opens a selected note from that folder. If there is a note titled `index` it will open that note. If an index note does not exist, you can set it to instead open the topmost note or the most recently edited note. 

Additionally, you can set it so clicking on a folder opens your index note but keeps the folder closed. This can be helpful if you have a folder full of notes but only need to view your index note on a freqent basic. 

### Example
I keep a folder full of notes for every book I've read along with an index note that catelogs each of these books. I frequently like to look at my index note but dont like the visual clutter that a big folder of notes provides. FolderIndex allows me to quickly access my book index. This is especially helpful on the mobile app where space is limited. 

### Tip
If you generally prefer the default Obsidian behavior (where clicking on a folder expands it but does not open anything), you can set it to do nothing when there is not an index note. Set fallback to `nothing`. Therefore, it will behave as it always has unless you specify an index note. 

## Installation
FolderIndex can be installed either via the BRAT Plugin (recommended) or manually. 

### BRAT Installation
Using BRAT is the recommended, and easiest, way to install Obsidian plugins that are not available in the Obsidian Community Store.

1. Install BRAT via community plugins. 
2. Open BRAT and select "Add Beta Plugin"
3. Paste `https://github.com/titandrive/obsidian-folderindex` into the text bar
4. Click "Add Plugin"

FolderIndex is now installed and BRAT will automatically keep track of updates for you. 

### Manual Installation
1. Browse to FolderIndex [Releases](https://github.com/titandrive/obsidian-folderindex/releases)
2. Download the latest release
3. Extract the release and copy it to your obsidian vault: `.../MyVault/.obsidian/plugins/FolderIndex`
4. Restart Obsidian
5. Enable FolderIndex in Settings/Community Plugins

## Settings
FolderIndex is quite straightforward and works without any configuration. There are only a few settings:

- **Fallback behavior** (What to open when a folder has no `index.md`)
  - *Most recent:* The most recently edited note
  - *Topmost:* The first note alphabetically
  - *Nothing:* Do nothing
- **Strict Matching:** Whether it will open any note containing "index" in the title, or whether it will only open notes named exactly `index.md`. Defaulted to off.
- **Allow folder toggle:** Whether clicking a folder name expands/collapses it. When disabled, you can still collapse a folder by clicking the arrow. 

## AI Disclosure
This plugin was made with the assistance of Claude Code. 

## License
MIT

# IDE PhpStorm setup
How to setup PhpStorm
## Editor
- Clean-up via View -> Appearance
  - Navigation Bar
  - Tool Window Bars
  - Status Bar
- Tabs
  - 2x Shift -> Search for "Tab placement" -> Left
## Theme
Carbon by Luis Fernando Jimenez
## Font
- Size: 10
- Line height: 1.6
## Disable lines in the editor
- Preferences -> Editor -> General
  - Appearance -> Disable "Show hard wrap and visual guides"
  - Code Folding -> Disable "Show code folding outline"
## Plugins
- Synced by "IDE Settings Sync"
  - .env files support
  - .ignore
  - Carbon (theme)
  - Prettier
## Prettier settings
- npm install prettier --save-dev
- Prettier package: ".../node_modules/prettier
- Run for files: {**/*,*}.{js,ts,jsx,tsx,php,vue}
- Activate
  - On 'Reformat Code' action
  - On save
- Find the following files in this repo
  - .prettierrc (Options)
  - .prettierignore

___
## Shortcuts
- 2x Shift: Search for all classes, commands, files...
- Command + Comma: IDE Preferences


___
Inpired by: https://laracasts.com/series/jeffreys-larabits/episodes/1

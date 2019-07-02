### 2.10.0 (2018-08-30)

- [MJML](https://github.com/mjmlio/mjml) 4.1.2
- Allow to use custom v4 engine again ([#255](https://github.com/mjmlio/mjml-app/pull/255)) - @kmcb777
- Change path of tmp file for screenshots to respect relative paths ([#246](https://github.com/mjmlio/mjml-app/pull/246)) - @eikaramba
- Change default path of html export ([#245](https://github.com/mjmlio/mjml-app/pull/245)) - @eikaramba
- Stop displaying migrate button after migrating ([44c8137](https://github.com/mjmlio/mjml-app/commit/44c8137ba941a8e816e355e223541f1d96e5841c)) - @kmcb777
- Allow attributes in mjml tag ([5defeae](https://github.com/mjmlio/mjml-app/commit/5defeaec0f9364dfb3973bb818aa2116a97a7e03)) - @kmcb777

### 2.9.0 (2018-04-05)

- Ability to create and update code snippets ([#227](https://github.com/mjmlio/mjml-app/pull/227)) - @ngarnier
- [MJML](https://github.com/mjmlio/mjml) 4.0.3
- Ability to search projects from dashboard ([#220](https://github.com/mjmlio/mjml-app/issues/220))
- Associate .MJML extension with MJML app ([#144](https://github.com/mjmlio/mjml-app/issues/144))
- Fix click on links behind mobile/desktop switch ([#191](https://github.com/mjmlio/mjml-app/issues/191))

### 2.8.0 (2018-03-06)

- [MJML](https://github.com/mjmlio/mjml) 4 ([#213](https://github.com/mjmlio/mjml-app/issues/213)), update of default templates for MJML 4
- Setup auto-updates
- Crashes fixes ([#188](https://github.com/mjmlio/mjml-app/issues/188)) - @kmcb777
- Handle subfolders when create/delete file ([#192](https://github.com/mjmlio/mjml-app/issues/192)) - @kmcb777
- Fix path resolution in node_modules ([#174](https://github.com/mjmlio/mjml-app/issues/174)) - @kmcb777

### 2.7.0 (2017-09-22)

- Ability to change the sender name when sending test email - @Mistra - [#177](https://github.com/mjmlio/mjml-app/pull/177)
- Ability to duplicate project from projects list
- Securize app - prevent crash ([#171](https://github.com/mjmlio/mjml-app/issues/171))

### 2.6.0 (2017-08-18)

- Mass export to JPG/PNG ([#166](https://github.com/mjmlio/mjml-app/issues/166))
- Improved beautify ([#140](https://github.com/mjmlio/mjml-app/issues/140))
- Put in trash instead of permanently delete folders & files ([#168](https://github.com/mjmlio/mjml-app/issues/168))

### 2.5.0 (2017-07-28)

- Paste multiple target emails in the send modal ([#164](https://github.com/mjmlio/mjml-app/issues/164))
- Export multiple emails to HTML ([#154](https://github.com/mjmlio/mjml-app/issues/154))
- Open file with drag & drop ([#143](https://github.com/mjmlio/mjml-app/issues/143))
- Fix Documentation link in menu ([#146](https://github.com/mjmlio/mjml-app/issues/146))

### 2.4.0 (2017-06-09)

- MJML 3.3.3
- Sync autocomplete attributes with MJML 3.3.3 - @ngarnier
- Add Try-it-live link to the menu - @MateuszDabrowski
- Alternative high contrast theme ([#136](https://github.com/mjmlio/mjml-app/issues/136))
- Display syntax errors directly in editor ([#142](https://github.com/mjmlio/mjml-app/issues/142))
- Customize `Subject` field when sending email ([#139](https://github.com/mjmlio/mjml-app/issues/139))
- Prevent scrollbars on screenshots ([#120](https://github.com/mjmlio/mjml-app/issues/120))

### 2.3.0 (2017-05-26)

- Send email to multiple targets ([#126](https://github.com/mjmlio/mjml-app/issues/126))
- Keep track of recent sent emails targets ([#125](https://github.com/mjmlio/mjml-app/issues/125))
- Compact view for API informations ([#127](https://github.com/mjmlio/mjml-app/issues/127))
- Option to minify HTML output ([#133](https://github.com/mjmlio/mjml-app/issues/133))
- Option to beautify HTML output ([#137](https://github.com/mjmlio/mjml-app/pull/137))
- Hide app with Cmd+H ([#131](https://github.com/mjmlio/mjml-app/issues/131))
- Refresh file list on app focus ([#135](https://github.com/mjmlio/mjml-app/issues/135))
- Display local images using relative path ([#134](https://github.com/mjmlio/mjml-app/issues/134))

### 2.2.0 (2017-05-12)

- Export desktop & mobile view to image ([#120](https://github.com/mjmlio/mjml-app/issues/120))
- Option to automatically fold lines based on indentation level ([#117](https://github.com/mjmlio/mjml-app/issues/117))
- Option to highlight matching tags ([#116](https://github.com/mjmlio/mjml-app/issues/116))
- Button to beautify MJML ([#96](https://github.com/mjmlio/mjml-app/issues/96))
- Keep history by file when switching file
- Preview images directly in app (to be improved)

### 2.1.0 (2017-05-01)

- Link to online documentation in app menu ([#109](https://github.com/mjmlio/mjml-app/issues/109))
- Display project name in project view ([#108](https://github.com/mjmlio/mjml-app/issues/108))
- Ability to rename file inside project ([#104](https://github.com/mjmlio/mjml-app/issues/104))
- Ability to rename projects and option to remove them from fs when remove from list ([#103](https://github.com/mjmlio/mjml-app/issues/103))
- Ability to hide file list on project view ([#105](https://github.com/mjmlio/mjml-app/issues/105))
- On OSX, ensure opened Finder is on top when opening project ([#106](https://github.com/mjmlio/mjml-app/issues/106))
- Remember last created project destination ([#107](https://github.com/mjmlio/mjml-app/issues/107))

### 2.0.1 (2017-04-26)

- [FIX] Reset Codemirror history when switching file

### 2.0.0 (2017-04-23)

- New interface, full rewrite.
- Projects are now based on file-system folders
- Support for `mj-include` ([#65](https://github.com/mjmlio/mjml-app/issues/65))
- Ability to use custom MJML binary for rendering
- Resizable panels, for easier responsive work
- Customizable breakpoints for mobile/desktop
- Fetch official templates from source (not stored in source code)
- Open email links in browser ([#73](https://github.com/mjmlio/mjml-app/issues/73))
- Better alert system for notifying new version
- ... and certainly other things

### 1.8.1 (2017-03-25)
 - Fix email sending ([#85](https://github.com/mjmlio/mjml-app/issues/85)) :mailbox:

### 1.8.0 (2017-03-17)
 - [MJML 3.3.0](https://github.com/mjmlio/mjml/releases/tag/3.3.0) 🆙

### 1.7.0 (2017-01-26)
 - [MJML 3.2.2](https://github.com/mjmlio/mjml/releases/tag/3.2.2) 🆙
 - Remember last used folder when exporting a template ([#69](https://github.com/mjmlio/mjml-app/issues/69)) :recycle:

### 1.6.0 (2016-12-15)
 - [MJML 3.1.1](https://github.com/mjmlio/mjml/releases/tag/3.1.1) 🆙

### 1.5.0 (2016-10-18)
 - [MJML 3.0.0](https://github.com/mjmlio/mjml/releases/tag/3.0.0) 🆙

### 1.4.1 (2016-08-20)
 - [MJML 2.3.3](https://github.com/mjmlio/mjml/releases/tag/2.3.3) 🆙

### 1.4.0 (2016-06-15)
 - Sync Scrolling ⚖
 - Font size in editor settings 🍅
 - [MJML 2.2](https://github.com/mjmlio/mjml/releases/tag/2.2.0) 🆙
 - Fixed Package version notification on first load ✋

### 1.3.3 (2016-06-08)

 - Fix a bug which caused issues with template saves #47 :bug:

### 1.3.2 (2016-05-27)

 - Add modal to show app version and mjml version :notebook:
 - Correct bug with notification bar :bug:
 - Mjml 2.1.1 with new components 💥

### 1.3.1 (2016-05-19)

 - Fix buggy overlay hover, and prevent edit name of preset :smiley:

### 1.3.0

 - Typos fixes :pencil:
 - Correct app quit when closing main window :clap:
 - Better windows size :computer:
 - Confirmation modal when deleting template :smile:

### 1.2.0

 - Thumbnails support for Windows :laughing:
 - Custom notifications system :point_up:
 - Local bug reporter :bug:
 - All presets updated with mjml@2 syntax :fireworks:
 - Human windows size :computer:
 - Visual helper texts in UI (for send email) :question:
 - Display a notification bar when an update is available :metal:
 - Dependencies updates: mjml@2 and react@15 :white_check_mark:

### 1.1.2

 - New Design for modals 💡
 - Home is the new AppData 🍊
 - Developer config folder is separated from the prod one 💉
 - EsDoc compilant comments 📄
 - Redux crash report middleware 💥

#### 1.1.1

 - Prevent drag'n'drop on the app ☂
 - Added dmg build config for OSX ❤️
 - Better Error handling on the editor 🛡

#### 1.0.0

 - Templates manager on the Home Page 🖼
 - Mobile/Desktop preview 📲
 - Live reloading 🏃
 - Auto save 😄
 - Theme manager 🖼
 - Test email 💬
 - Export as Gist 🍊

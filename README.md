# Sketch Texts Translate
[![Download from Sketchpacks.com](https://badges.sketchpacks.com/plugins/com.sketchapp.examples.sketch-translate/version.svg)](https://api.sketchpacks.com/v1/plugins/com.sketchapp.examples.sketch-translate/download) [![Compatible Sketch Version](https://badges.sketchpacks.com/plugins/com.sketchapp.examples.sketch-translate/compatibility.svg)](https://sketchpacks.com/laresgoiti/texts_translate)

![Sketch Texts Translate demo](http://g.recordit.co/uDd59vA5I9.gif)

Manage texts in [Sketch](http://bohemiancoding.com/sketch/) in multiple locales by this plugin.

## Installation
[Download](https://github.com/laresgoiti/texts_translate/archive/master.zip) and double-click **sketch_translate** file and let Sketch automatically install the plugin.

OR

<a href="https://sketchpacks.com/laresgoiti/texts_translate/install" rel="nofollow" title="Install Texts Translate with Sketchpacks">
  <img width="160" height="41" src="http://sketchpacks-com.s3.amazonaws.com/assets/badges/sketchpacks-badge-install.png" alt="Install Texts Translate with Sketchpacks">
</a>

<a href="http://bit.ly/SketchRunnerWebsite" rel="nofollow" title="Install via Sketch Runner">
  <img width="160" height="41" src="http://sketchrunner.com/img/badge_blue.png" >
</a>

## Usage
- Go to <code>Plugins -> Texts Translation -> Save locale</code> to save current locale.
- Go to <code>Plugins -> Texts Translation -> Change locale</code> to create new locale or change to an existing one.

## Important
You need to have a saved Sketch document before using the plugin. Locales files are saved in same folder ('Sketch document name'+'_translations').

![Sketch Texts Translate files](http://g.recordit.co/Qk9KqFc8No.gif)

## Manually created/edited locales
You can manually create/edit locale files. These files have a very easy structure; "TextLayer objectID" as key and "text content" as value in a JSON file, where file name is the locale name.

You can create a new locale by:
1. Duplicate existing locale.
2. Edit TextLayer value.
3. Save in same folder with "locale name" and same format (JSON).
4. This locale will be available when "Change locale" action.

## Feedback
If you discover any issues or you think this plugin can be improved by new features, create a new issue in this repository or find me on twitter [@laresgoiti](https://twitter.com/laresgoiti).

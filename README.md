# Sketch Texts Translate

![Sketch Texts Translate demo](http://g.recordit.co/uDd59vA5I9.gif)

Manage texts in [Sketch](http://bohemiancoding.com/sketch/) in multiple locales by this plugin.

## Installation
[![Install Texts Translate with Sketchpacks](http://sketchpacks-com.s3.amazonaws.com/assets/badges/sketchpacks-badge-install.png "Install Texts Translate with Sketchpacks")](https://sketchpacks.com/laresgoiti/texts_translate/install)

OR

[Download](https://github.com/laresgoiti/texts_translate/archive/master.zip) and double-click **sketch_translate** file and let Sketch automatically install the plugin.

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

M-3PO-i18n

Please refer to [language_changelog.md](language_changelog.md) for new translations required.

When submitting a pull request, please tag the version which the PR is targeting. (e.g `0.12.5 Spanish`)

**Translating Updates**  
The `/dev/` folder contains all reference material that may not be included in `en` folder. The [language_changelog.md](language_changelog.md) will have changes listed per file. 
1. Find the file and each dot seperated value is a key, for example `commands.set` is `{ "commands": { "set": {...}}}`. 
2. If the change is an addition, you can copy the new key-value pair to the existing translation file or manually type it in.. the important part is the keys are the same. If it's an edit or reword, simply change the existing value in the translation file as applicable. 

**Want to translate to a new language?**  
1. Copy the /dev/ folder to the new language's i18n code (e.g German is de) folder.
2. Translate the core.json, common.json, and events.json files. **Do not translate** the JSON keys or text inside of `{{here}}` as these are references for the bot.
3. Submit a new Pull Request with the version it's translated for (should be current) and the i18n hypen the language name. (e.g `0.14.1 ru-Russian`).

**Translator badge** _(coming in a future version)_  
In the text you can include your Discord User ID to recieve the translator badge when it becomes available.

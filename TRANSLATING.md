## Translating for Necesse

To begin, log in to your GitHub account, or if you don't have one yet, create it [here](https://github.com/).

Consult [this list](https://www.science.co.il/language/Locale-codes.php) to find the locale code for your language. Once you've found it, 
head over to the translation bundle folder and check the [list of bundles](https://github.com/VizardAlpha/Necesse-Translation/tree/main/locale) that have already been created. 
You're looking for a file called "(insert locale code here)`.lang`". If you don't find one, create one manually (more info below).

#### Editing an existing translation

If a translation bundle already exists, that means someone has already started working on a translation. To edit it or translate text, simply click the file and press the edit (pencil) button in the top right. Once you're done editing, press the green "propose file change" button at the bottom, then "create pull request" (twice).
Once this is done, all you need to do is wait for me to approve your changes.

#### Creating a new translation bundle

If a translation bundle for your language *doesn't* exist, you need to create one yourself.  
In the folder with all the bundles in it, click the *'create new file'* button, and name it `(locale code here).lang`. 
Then, copy-paste the entire contents of the [English translation bundle](https://raw.githubusercontent.com/VizardAlpha/Necesse-Translation/main/en.lang) into the file, and translate all the necessary text to your language.
Once you are done, press the *propose new file* button at the bottom, then 'create pull request' twice.  

#### Useful Information

- When you see a oint, such as `§a`, `§4` or `#D57E17`, following a number, letter or #hexcode means the following text will be formatted, not to be translated.
- `<settlement>` means an argument that will be replaced when the text is displayed. For example, `<mod>% damage` will replace the `<mod>` with numbers or text, not to be translated.
- Empty lines are fine, and it doesn't matter in what order you place the text.
- `\n` means "new line". If you want to split text into multiple lines, use `\n` to do it.
- `//` means comment. Can be useful if you're working on a bundle with a few people to leave information. The game will not read this part of the code
- `[item/input=...]` will be replaced by an icon of the item/control key. For example, `[item=coin]` or `[input=placetorch]`, not to be translated.
- `SAME_TRANSLATION` means that the original English word is also used in your language, an example of the French translation. `SAME_TRANSLATION:surface=Surface`, always place before the translation key.

#### Testing your translation bundle

There are one way to test the translation bundle:
1) Assuming you have the game downloaded, download your bundle file, then place it in the same folder as the Necesse `steamapps\common\Necesse\locale` and run it.

**And that's it.**  

*(...of course, that's never really it. Bother me on Discord when something inevitably goes wrong.)*

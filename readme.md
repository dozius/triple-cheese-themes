# Triple Cheese Themes

Various themes for the free synthesizer plug-in [Triple Cheese by U-he](http://www.u-he.com/cms/triple-cheese).

## Enable Themes

Triple Cheese supports the U-He theme system. However, it is not setup properly "out of the box". Follow these directions to setup theme support.

1. Locate the built in theme folder on your PC.

    * Windows: `<install-dir>/TripleCheese.data/data/Scripts`
    * Mac: `???`

2. Rename `TripleCheese.txt` to `TripleCheese_original.txt`.

3. Create a new file named `TripleCheese.txt`.

4. Open the newly created file in a text editor and add the following:
   ```
   ALTERNATIVE name='original' filename='TripleCheese_original.txt'
   INCLUDE filename='default'
   ```

## Install

1. Locate the theme directory on your PC.

    * Windows: `<install-dir>/TripleCheese.data/Support/Themes/`
    * Mac: `/Library/Application Support/u-he/Themes/`

2. Place the desired theme folder into the theme directory.

3. Reload Triple Cheese.

4. Open the context menu on the Triple Cheese GUI and select the theme.

## Save Default GUI Size

Triple Cheese seems to have a bug where the default size is not saved. Fortunately, you can manually edit the preference.

1. Locate the support directory on your PC.

    * Windows: `<install-dir>/TripleCheese.data/Support/`
    * Mac: `/Library/Application Support/u-he/`

2. Open the file `com.u-he.TripleCheese.Preferences.txt` in a text editor.

3. Look for the line `V_PROPERTY name='Preference' id='0' value='AllViews:DefaultUISize:100%'` and edit the value to your desired default.

4. Save the file.

## Flat Theme

A "flat" theme that is made entirely from vector shapes built into the plug-in (i.e. no image files are used). It comes in multiple flavours based on popular syntax highlighting palettes.

Alternate versions use colour accents for the mod source labels.

Screenshots at 150%.

### Dracula
![Alt text](/screenshots/dracula.png?raw=true "dracula gui")
![Alt text](/screenshots/dracula-manager.png?raw=true "dracula gui manager")
![Alt text](/screenshots/dracula-alt.png?raw=true "dracula-alt gui")

### Monokai
![Alt text](/screenshots/monokai.png?raw=true "monokai gui")
![Alt text](/screenshots/monokai-manager.png?raw=true "monokai gui manager")
![Alt text](/screenshots/monokai-alt.png?raw=true "monokai-alt gui")

### OneDark
![Alt text](/screenshots/onedark.png?raw=true "onedark gui")
![Alt text](/screenshots/onedark-manager.png?raw=true "onedark gui manager")
![Alt text](/screenshots/onedark-alt.png?raw=true "onedark-alt gui")

# VSCode-theme
A colorblindness-friendly theme for Visual Studio Code, built on the cucpake theme under Dobri Next.

This theme works well for most people. However, for people with Red-Blind/Protanopia or Green-Blind/Deuteranopia, the accent colours across types might not seem too different.

--------------------

HOW TO INSTALL THIS THEME FOR VSCODE:
1. Open VSCode.
2. Install the Dobri Next - Themes and Icons Extension from here https://marketplace.visualstudio.com/items?itemName=sldobri.bunker.
3. In VSCode, naviagate to `Extensions`.
4. Click on `Dobri Next - Themes and Icons`. This will open a new tab with various details about the extension.
5. In the Dobri Next tab, click `Set Color Theme`.
6. Choose `Dobri Next-C03-Cupcake`.
7. Go to `Settings`.
8. In the search box, type "Token Color".
9. Under `Editor: Token Color Customizations`, click on the link `Edit in settings.json`.
10. This will open your `settings.json` file, and create a new section `editor.tokenColorCustomizations: {}`.
11. Delete this section, and instead copy and paste the contents of `visiblefile` from this repository into your `settings.json` file. Do not overwrite any other existing code in `settings.json`.
12. Save the `settings.json` file, and restart VSCode.

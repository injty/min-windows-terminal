<div align=center>
    <img src="https://raw.githubusercontent.com/mdxv/min-windows-terminal/main/icon.png" width="200" />

# Min Windows Terminal
Min Theme for Windows Terminal.
![Frame 2(1)](https://github.com/user-attachments/assets/b7a29e6f-1dd3-4dab-aaf3-80a66c9ff939)

</div>

## Installation
1. Launch Windows Terminal
2. Open the **Settings** panel (<kbd>Ctrl + ,</kbd>)
3. Select **Open JSON file** at bottom left corner (<kbd>Ctrl + Shift + ,</kbd>)
4. Choose your _theme_ (min-dark, min-light) and _application-theme_ (min-dark-application-theme/min-light-application-theme)
5. Copy the contents of _theme_ (example: min-dark.json) into the opened JSON file under **"schemes"**:

```json
{
    "schemes":
    [
        ..min theme
        ..other schemes
    ],
}
```
6. Copy the contents of _theme_ (example: min-dark-application-theme.json) into the opened JSON file under **"themes"**:

```json
{
    "theme":
    [
        ..min dark application theme
        ..other themes
    ],
}
```
7. Save and exit
8. In the **Settings** panel under Profiles, select the profile you want to apply the theme to. **Defaults** will apply to all profiles.
9. Select **Appearance**
10. Choose your _theme_ in the **Color scheme** drop down menu
11. In the sidebar, go to the **General** menu.
12. Open the **Appearance** tab.
13. Under **Application Theme**, select **Min Dark** or **Min Light**.
14. Click on **Save**, enjoy!


Based on [Min Theme](https://github.com/miguelsolorio/min-theme) for VSCode.

## License

[MIT License](LICENSE)

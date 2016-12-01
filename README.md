<!-- TODO: Submit theme to Package Control and adjust usage instructions accordingly -->

# Sublime Text Themes
Minimally ok-ish themes for Sublime Text.

Tested on `Sublime Text 3 (3083)`.

Inspired by [base16](https://github.com/chriskempson/base16), [spacegray](https://github.com/kkga/spacegray), [material-theme](https://github.com/equinusocio/material-theme), and [soda-theme](https://github.com/buymeasoda/soda-theme).

<!-- TODO: ![screenshot](https://raw.githubusercontent.com/adrfer/sublime-themes/Themes/Themes - Pulsar/master/Screenshot.png) -->

## Usage

### Install

To install customized themes:

1. Open **Sublime Text**, go to **Preferences**, and then **Browse Packages...**
2. Download the custom theme, unzip it, and rename the its folder to **Theme - Pulsar**
3. Copy the theme folder into to the **User** folder
4. Open/restart **Sublime Text** and activate it

### Activation

To activate customized themes:

1. Open **Sublime Text**, go to **Preferences**, and then **Settings - User** ( <kbd>⌘</kbd><kbd>,</kbd> )
2. Comment or delete the customized settings:

```json
{
  "theme": "Pulsar.sublime-theme",
  "color_scheme": "Packages/Theme - Pulsar/Color Schemes/Pulsar.tmTheme"
}
```

## Uninstall

To remove customized themes:

1. Open **Sublime Text** and deactivate it
2. Go to **Preferences**, **Browse Packages...**, and then **User** folder
3. Select the custom theme and delete it
4. Open/restart **Sublime Text**

### Deactivation

To deactivate customized themes:

1. Open **Sublime Text**, go to **Preferences**, and then **Settings - User** ( <kbd>⌘</kbd><kbd>,</kbd> )
2. Comment or delete the customized settings:

```json
{
  "theme": "Pulsar.sublime-theme",
  "color_scheme": "Packages/Theme - Pulsar/Color Schemes/Pulsar.tmTheme"
}
```

--
Hey, looking for custom settings? Check out [sublime-settings](https://github.com/adrfer/sublime-settings).

Interested in key bindings? Take a look at [sublime-keybindings](https://github.com/adrfer/sublime-keybindings).

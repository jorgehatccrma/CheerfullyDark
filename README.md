## CheerfullyDark

[CheerfullyDark](http://github.com/jorgehatccrma/CheerfullyDark) is a color scheme for [Sublime Text 2/3](http://www.sublimetext.com/), by [jorgeh](https://github.com/jorgehatccrma). It's a subtle scheme, gentle on the eyes.


### Installation and Usage

[CheerfullyDark](http://github.com/jorgehatccrma/CheerfullyDark) is available to instal via Sublime's [Package Control](https://packagecontrol.io/).

To use it simple add/edit the `color_scheme` entry in you `Preferences.sublime-settings`:

    {
        ...
        "color_scheme": "Packages/CheerfullyDark/Cheerfully Dark.tmTheme",
        ...
    }

(or use the `Menu` -> `Preferences` -> `Color Scheme` -> `Cheerfully` -> `Cheerfully Dark`).

### Update

Now there's a light version included: `Cheerfully Light`:

    {
        ...
        "color_scheme": "Packages/CheerfullyDark/Cheerfully Light.tmTheme",
        ...
    }


---

This screen shot shows the color scheme on [Python](http://python.org) code

![screenshot](https://raw.github.com/jorgehatccrma/CheerfullyDark/master/screenshot.png)

### Warning

This is only a color scheme. In other words, it will only change the text edit area, not the file tree on the left, nor the tabs. I personally use the Soda dark theme (availble via `Package Control` as well) to also change the appereance of those parts of ST. In case you care, this is the content of my settings file:

    {
        "color_scheme": "Packages/CheerfullyDark/Cheerfully Dark.tmTheme",
        "dictionary": "Packages/Language - English/en_US.dic",
        "font_face": "Source Code Pro Light",
        "font_size": 13.0,
        "scroll_past_end": true,
        "soda_classic_tabs": true,
        "spell_check": true,
        "tab_size": 4,
        "theme": "Soda Dark.sublime-theme",
        "translate_tabs_to_spaces": true,
        "trim_automatic_white_space": true,
        "trim_trailing_white_space_on_save": true
    }


# Linux Setup

This is a simple project page for easy reference for setting up my preferred Linux desktop environment. Feel free to use this if it suits your needs.

## Software Updates

Since my go-to Linux distro is [Fedora](https://getfedora.org/), we need to ensure that all software is updated.

1. Open `Software` application
2. Update applications / OS & restart device
3. That's it!

## Applications

Below is a list of my go-to and daily applications I use for web design and development. Other applications used "for fun" are omitted from this reference.

### Evolution (Email)

1. Open `Software` application
2. Search for `Evolution` and install

### Inkscape

1. Open `Software` application
2. Search for `Inkscape` and install

### GIMP

1. Open `Software` application
2. Search for `GIMP` and install

### Chromium (browser testing)

1. Open `Software` application
2. Search for `Chromium` and install

### Sublime Text

1. Install application

    ```
    sudo rpm -v --import https://download.sublimetext.com/sublimehq-rpm-pub.gpg
    ```

    ```
    sudo dnf config-manager --add-repo https://download.sublimetext.com/rpm/stable/x86_64/sublime-text.repo
    ```

    ```
    sudo dnf install sublime-text
    ```

2. Install `Package Control`

3. Install following packages:
    - Guna
    - Emmet
    - Sass
    - Sass Build
    - MarkdownLivePreview

4. Setup default preferences:

    ```
    {
        "caret_extra_width": 5,
        "color_scheme": "Packages/Guna/themes/Guna.tmTheme",
        "font_size": 14,
        "gn_hide_tab_dropdown": true,
        "gn_overlay_scroll_bars": true,
        "gn_sb_cnvx": true,
        "gn_sidebar_box": true,
        "gnc_h10": true,
        "gnc_m02": true,
        "gnc_m11": true,
        "gnwidg1": true,
        "highlight_line": true,
        "ignored_packages":
        [
            "Vintage"
        ],
        "line_padding_bottom": 4,
        "line_padding_top": 4,
        "spell_check": true,
        "theme": "Guna.sublime-theme",
        "translate_tabs_to_spaces": true,
        "trim_trailing_white_space_on_save": true,
        "word_wrap": true
    }
    ```

### Local / LocalbyFlywheel

1. Download from the direct link: [https://local-by-flywheel-flywheel.netdna-ssl.com/latest/linux/rpm](https://local-by-flywheel-flywheel.netdna-ssl.com/latest/linux/rpm)
2. Install and follow step instructions

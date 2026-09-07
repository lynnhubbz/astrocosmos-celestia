# Astrocosmos Celestia Add-on

This repository contains Astrocosmos celestial objects translated into data files for [Celestia].

The repository itself is intended to be used as a **grouped Celestia add-on**. When installed, the repository root corresponds to the `Astrocosmos/` directory inside Celestia's `extras/` directory.

## Installation

1. Place this repository into Celestia's `extras/` directory and name the resulting directory `Astrocosmos`.

    For example:

    ```text
    Celestia/
    ├── ...
    └── extras/
        ├── your_other_addons/ 
        └── Astrocosmos/
            ├── content/
            ├── scripts/
            ├── splash/
            ├── celestia.cfg
            ├── README.md
            └── ...
    ```

    The repository therefore represents:

    ```text
    Celestia/extras/Astrocosmos/
    ```

    The `content/` directory contains the Astrocosmos celestial-object data provided by this add-on.

    If you want a nightly update, you can git clone this repo and fetch change every day.
    If you want a stable release, you can git clone the tagged version, or just simply download the source code.

2. Run the `sync_config.celx` via Celestia

    This add-on may provide or modify Celestia configuration.

    > [!WARNING]
    > If installing or updating this add-on requires replacing or modifying your existing `celestia.cfg`, make a backup of your original configuration before installation.

3. Re-run Celestia so the config take effects


## Development


Some content in this repository is translated (generated) from the main Astrocosmos repository and is therefore **not intended to be edited directly**.

Changes to the source worldbuilding data should be made in the main Astrocosmos repository and then translated into Celestia data.

Scripts included in the repository may be used with Celestia or for maintaining the add-on.

Celestia can execute `.celx` scripts, but scripts are not necessarily executed automatically when the add-on is loaded. Some changes made by scripts may therefore require Celestia to be restarted before they take effect.

This repository may contain development files and assets that are not part of the translated Astrocosmos content.

### Assets

* [Troligi's Add-ons](https://celestiaproject.space/forum/viewtopic.php?f=23&t=20395&sd=d)
* [Fictious Nebulae](http://www.celestiamotherlode.net/catalog/fictional.html#1800)

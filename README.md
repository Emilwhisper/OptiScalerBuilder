# OptiScalerBuilder

Automated GitHub Actions builder for creating packaged OptiScaler builds with the latest supported helper components.

## What this Repository Does

This repository automatically:

* Builds the latest version of OptiScaler directly from source
* Downloads and integrates the latest release of fakenvapi
* Downloads and integrates the latest release of OptiPatcher
* Downloads and integrates the latest NVIDIA Streamline SDK runtime components
* Downloads and integrates the latest DLSS Enabler package available in this repository
* Creates a clean, portable package ready for use
* Generates a GitHub Release containing the packaged build and component version information

## Automated Builds

Builds are generated automatically every 6 hours using GitHub Actions.

Each release includes:

* OptiScaler
* fakenvapi
* OptiPatcher
* NVIDIA Streamline SDK
* DLSS Enabler

## Downloading Builds

You can find all generated builds on the [Releases](https://github.com/bygalacos/OptiScalerBuilder/releases) page.

## Building It Yourself

If you want to generate your own builds:

1. Fork this repository.
2. Open the **Actions** tab.
3. Select the workflow you would like to build.
4. Click **Run workflow**.
5. Wait for the workflow to complete.
6. Download the generated artifact or release package.

You may also modify the workflow to include your own custom components or packaging preferences.

## Included Components

| Component             | Source                                             |
| --------------------- | -------------------------------------------------- |
| OptiScaler            | https://github.com/optiscaler/OptiScaler           |
| fakenvapi             | https://github.com/optiscaler/fakenvapi            |
| OptiPatcher           | https://github.com/optiscaler/OptiPatcher          |
| NVIDIA Streamline SDK | https://github.com/NVIDIA-RTX/Streamline           |
| DLSS Enabler          | https://github.com/artur-graniszewski/DLSS-Enabler |
| dlssg-to-fsr3         | https://github.com/Nukem9/dlssg-to-fsr3            |

## Notes

* Releases are generated automatically by GitHub Actions.
* Release names include the build timestamp to ensure every build is uniquely identifiable.
* Component versions included in each build are listed directly in the GitHub Release description.
* DLSS Enabler packages stored in this repository are static. To use newer DLSS Enabler versions, update the repository contents accordingly.

## Credits

All credit for the software included in generated packages belongs entirely to the original project authors and maintainers.

Please consider supporting the original projects by:

* Starring their repositories
* Reporting bugs
* Contributing code
* Following development updates

## Disclaimer

This project is an unofficial build automation and packaging utility.

It is not affiliated with, endorsed by, or maintained by the OptiScaler, NVIDIA, AMD, Intel, DLSS Enabler, Nexus Mods, or any other upstream project teams.

This repository does not redistribute ownership of any included software. Its sole purpose is to automate building, packaging, and organizing components obtained from their respective sources.

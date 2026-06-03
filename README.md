# OptiScalerBuilder

Automated GitHub Actions builder for creating a packaged OptiScaler build with optional helper components.

## What this repo does
- Prepares a clean portable package
- Builds the latest [OptiScaler](https://github.com/optiscaler/OptiScaler) from source
- Adds the latest [OptiPatcher](https://github.com/optiscaler/OptiPatcher) plugin
- Adds latest required components from the [NVIDIA Streamline SDK](https://github.com/NVIDIA-RTX/Streamline)
- Adds the latest [DLSS-Enabler](https://github.com/artur-graniszewski/DLSS-Enabler) available in the repository

## Credits / Dependencies
- [OptiScaler](https://github.com/optiscaler/OptiScaler)
- [OptiPatcher](https://github.com/optiscaler/OptiPatcher)
- [dlssg-to-fsr3](https://github.com/Nukem9/dlssg-to-fsr3) by Nukem9
- [DLSS-Enabler](https://github.com/artur-graniszewski/DLSS-Enabler) by artur-graniszewski
- [NVIDIA Streamline SDK](https://github.com/NVIDIA-RTX/Streamline)

## Usage
1. Fork the repository.
2. Go to **Actions**.
3. Run **Build OptiScaler Package**.
4. Download the generated artifact.

## Disclaimer
This project is an unofficial builder and packaging utility. It is not affiliated with OptiScaler, NVIDIA, AMD, Intel, Nexus Mods, or any of the original project authors. All credit for the software, technologies, and innovations used by this project belongs to their respective developers and maintainers.

This repository does not aim to replace, compete with, or redistribute ownership of any of these projects. Its purpose is simply to automate the process of building, packaging, and organizing components from their original sources.

If you find this project useful, please consider supporting the original developers by starring their repositories, reporting issues, contributing code, or following their work.

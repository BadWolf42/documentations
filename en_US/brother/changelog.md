## 2024-09-27 (v12 - Stable & Beta)
- Fixed a bug that reloaded the printer information each time the dashboard was loaded
- Fixed a PHP error if a command or its value was missing
- Added new command "Last switch-on"
- Added a tooltip with more information (request from *mich0111*)
- Updated the Python lib brother 4.3.0 -> 4.3.1

## 2024-09-08 (v11)
- Fixed daemon output (Model, S/N & Firmware were missing, thanks *sodaveli*)
- Added [automatic translation workflow][https://github.com/Mips2648/plugins-translations] (thanks *Mips*)
- Added infobubbles to chart on widget

## 2024-09-07 (v10)
- Added Debian 12 support
- Rework dependancies using NebzHB/dependance.lib & Mips2648/pyenv.lib
- Updated Python lib requests 2.31.0 -> 2.32.3
- Updated Python lib brother 1.0.2 -> 4.3.0
- Fix Changelog beta url
- Fix case of status command value

## 2024-03-18 (v9)
- Fixed commands not displayed on an equipment (thanks *echo*)
- Fixed an issue when dependencies are not installed and a refresh is launched (thanks *echo*)
- Fixed a field alignment issue on the equipment page

## 2024-03-17 (v8)
- Last Beta is now Stable

## 2024-03-03 (v8)
- Removed jQuery where possible
- Added Todo to Issue Workflow
- Improved logs (clearer and less verbose)

## 2023-11-26 (v7)
- Externalisation of documentation and changelog

## 2023-10-01 (v6)
- Last Beta is now Stable

## 2023-09-29 (v6)
- Fixed issue with [pyasn1 package](https://community.jeedom.com/t/107671) (using a Python3 venv)
- Fixed some log levels (too verbose)

## 2023-05-14 (v5)
- Fixed issues with widget on Jeedom 4.4

## 2023-04-30 (v4)
- **The widget on the Dashboard is now updated when changing a value**
- **Logo update, using yellow instead of dark blue**
- **Minimum version support is now Jeedom 4.3**
- Add Luna as supported hardware
- Add version number in info.json
- Cleanup of installation, update and migration scripts
- Include changelod and beta documentation in info.json
- Updated Equipment Commands tab in Jeedom 4.3 style
- Fixed "None" item was missing on Equipment tab of equipments
- Fixed PHP Notice when printer was turned on
- Fixed some typos

## 2023-02-27
- Updated Equipment Commands tab in Jeedom 4.3 style
- Fixed "None" item was missing on Equipment tab of equipments
- Fixed PHP Notice when printer was turned on
- Fixed some typos

## 2023-02-20
- **Plugin taken over by BadWolf**
- Change in the way refresh works: a callback is used to avoid creating a cron
- Renamed the "master" branch to "stable", to those who use Github and not the Market, please update your branch
- Added usage statistics
- Code indentation/cleanup

## 2023-02-14
- **Plugin taken over by BadWolf**
- Added usage statistics
- Code indentation/cleanup

## 2022-02-04
- Logs typo fix
- Useless sudo rights removal
- Manual refresh in cron to prevent UI lock
- Compatibility with tile background graphics

## 2022-02-18
- Fix on last prints computation

## 2022-02-12
- First stable version

## 2022-02-11
- Python package logging level respect Jeedom logging config
- Gauge items clickable for history
- Grey background on gauge for better visibility of black ink

## 2022-02-10
- Choice of printer's type (color or back & white)
- Smaller widget with status and page counters information
- Widget compatible with visible status of commands

## 2022-02-07
- Add logs
- New commands for number of prints in the last hour

## 2022-02-06
- Initial revision (beta)

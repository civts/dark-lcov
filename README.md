# Dark theme for lcov reports

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Mantained: yes](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/civts/dark-gcov/graphs/commit-activity)
![Made with CSS](https://img.shields.io/badge/Made%20with%20CSS%20-%231572B6.svg?&logo=css3&logoColor=white)

Bring a dark, modern look to your coverage reports.

|               Original               |                 Dark                 |
| :----------------------------------: | :----------------------------------: |
| ![](https://i.imgur.com/h1HK7RM.png) | ![](https://i.imgur.com/DhJW1fE.png) |

## ❓ What this is

This a simple CSS theme for the reports generated with the `genhtml` command from the [lcov utility](https://github.com/linux-test-project/lcov).  
The aim is to give a nice makeover to the original UI.

## 🔧 Usage

Just download a copy of the [gcov.css file](https://github.com/civts/dark-gcov/blob/master/gcov.css). At this point you are pretty much set and can choose to either

- Run the command `genhtml -c ./path/to/gcov.css` to generate a new report with the new theme.
- Replace the `gcov.css` file in an existing report.

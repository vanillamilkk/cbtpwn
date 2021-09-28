# CBTPWN
## _Aplikasi Simulasi Mandiri Downloader_

![N|Solid](https://img.shields.io/badge/Made%20with-bash-green) ![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)



A script to download question / exam from Aplikasi Simulasi Mandiri made by Bimasoft


## Features

- Free as in free beer and freedom
- Anonymous (excluding web server access log)
- Automatic download to html page
- Skipping empty or already existing file
- Support Aplikasi Simulasi Mandiri v12.0 + (Not tested on v13)


## Installation

CBTPWN requires bash to run (Exist in almost any Linux distribution)

Clone the repo, and it's just work!

```sh
git clone https://github.com/vanillamilkk/cbtpwn.git
cd cbtpwn
```

## Usage example

Generating a token for test.co.id server
```sh
./token test.co.id
```

Downloading all exam from test.co.id server
```sh
./cbtpwn test.co.id
```

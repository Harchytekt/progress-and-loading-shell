# Progress and Loading Bash

This repository contains a simple shell script to display progress bars and loading animations in the terminal.  
The script is designed to be easy to understand and integrate into your own projects.

## Features

- Customizable progress bars with percentage indicators
- Loading animations with a rotating icon
- Color-coded output for easy readability

## Usage

- Clone the repository:

```shell
git clone git@github.com:Harchytekt/progress-and-loading-shell.git
```

- Navigate to the repository folder:

```bash
cd progress-and-loading-shell
```

- Give the script execution permissions:

```bash
chmod +x progress_bars.sh
```

- Run the script:

```bash
./progress_bars.sh
```

## Customization

You can easily customize the script to fit your needs by modifying the colors and symbols used for the progress bars and loading animations. Look for the following variables in the `progress_bars.sh` script:

- `c_green` and `c_clear` to change the colors
- `bar_symbols` array to change the progress bar symbols
- `loading` and `loading_alt` arrays to change the loading animation symbols
- Feel free to contribute and make improvements to this script. Pull requests and suggestions are welcome!

## License

This project is licensed under the MIT License. See the LICENSE file for details.

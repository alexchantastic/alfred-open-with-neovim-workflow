# alfred-open-with-neovim-workflow

![Screenshot](https://github.com/alexchantastic/alfred-open-with-neovim-workflow/assets/604167/db0d0e03-c2c5-45fe-87d6-bc7d7db2b962)

An [Alfred 5](https://www.alfredapp.com/) workflow opening files or folders with [Neovim](https://neovim.io/) in your [configured terminal](https://www.alfredapp.com/help/features/terminal/).

## Configuration

There isn't any configuration necessary with the workflow itself. However, if you would like Neovim to open in your terminal of choice, you can configure Alfred to specify a custom terminal application to use.

If you are using iTerm2, check out [vitorgalvao/custom-alfred-iterm-scripts](https://github.com/vitorgalvao/custom-alfred-iterm-scripts) for how to configure Alfred.

## Installation

1. [Download the workflow](https://github.com/alexchantastic/alfred-open-with-neovim-workflow/releases/latest)
2. Double click the `.alfredworkflow` file to install

Note that the [Alfred Powerpack](https://www.alfredapp.com/powerpack/) is required to use workflows.

## Usage

### Open

1. Use the keyword `nvim` to trigger the workflow
2. Press `enter` to open the current folder or the selected file
3. Alternatively, type a path to open (e.g., `~/Desktop`)

When multiple folders are selected, the workflow will only open the first selected folder (all other selected folders are ignored).

When a heterogenous selection of files _and_ folders are selected, the workflow will open the files in one Neovim instance and the first selected folder in a separate Neovim instance.

### Search & Open

1. Use the keyword `nvimf` to trigger the workflow
2. Press `enter` or begin to type your file or folder search term
3. Select the file or folder you want to open and press `enter`

## License

Code released under the [MIT License](https://github.com/alexchantastic/alfred-open-with-neovim-workflow/blob/main/LICENSE).

Neovim logo by [Jason Long](https://twitter.com/jasonlong), licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/).

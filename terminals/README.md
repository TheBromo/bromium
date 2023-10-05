# themer - My Color Set

## Vim

Copy or symlink `Vim/ThemerMyColorSet.vim` to `~/.vim/colors/`.

Then set the colorscheme in `.vimrc`:

```
" The background option must be set before running this command.
colorscheme ThemerMyColorSet
```

## Vim lightline

1. Make sure that the `background` option is set in `.vimrc`.
2. Copy or symlink `Vim lightline/ThemerMyColorSetLightline.vim` to `~/.vim/autoload/lightline/colorscheme/`.
3. Set the colorscheme in `.vimrc`: `let g:lightline = { 'colorscheme': 'ThemerMyColorSet' }`
4. Restart Vim.

## Alacritty

1. Paste the contents of `Alacritty/Themer My Color Set.yml` into your Alacritty config file.
2. Select the desired theme by setting the `colors` config key to reference the scheme's anchor (i.e., `colors: *light` or `colors: *dark`).

## Windows Terminal

1. Open the Windows Terminal settings (`Ctrl`-`,`)
2. Add the contents of 'Windows Terminal/themer-my-color-set-dark.json' to the `schemes` array in `profile.json`
3. Set the `colorScheme` property to the desired scheme name ("Themer My Color Set Dark") in the profiles section of `profile.json`, e.g.:

```
"profiles": {
  "defaults": {
    "colorScheme": "Themer My Color Set Dark"
  }
}
```
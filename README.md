# How to Update Keymap

Edit the `config/corneish_zen.keymap` file, commit changes, then push to repo.

This will trigger github actions which will then generate a firmware file which can then be flashed onto the board when it's in bootloader mode.

Note that if only the keymap is being changed, only the left side needs to be flashed.

Info on this process in more detail can be found [here]("https://zmk.dev/docs/user-setup")

# Keymaps

[General info](https://zmk.dev/docs/keymaps)

[Keycodes](https://zmk.dev/docs/keymaps/list-of-keycodes)

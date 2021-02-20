# park.fish

`park.fish` lets you park your current command line in a temporary buffer to the side.

It is useful for when you forget a necessary step before the current command you're typing, and you don't want to re-type the current command.

## Example

You finally figure out that perfect commit message, only to realize you need to stage another file. Hit <kbd>Ctrl-Q</kbd> to park:

`$ git commit -m "Carefully crafted commit message involving evil race condition` <kbd>Ctrl-Q</kbd>

The command line is saved, and cleared, allowing you to stage the file:

`$ git add main.c`<kbd>Enter</kbd>

...and then the parked command line is magically restored:

`$ git commit -m "Carefully crafted commit message involving evil race condition`

## Configuration
Send a PR if you want the keybinding to be configurable.

## License
MIT

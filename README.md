# Luke's vim helpers

Just some little things I source in my vimrc. Moving these from the
[voidrice](https://github.com/lukesmithxyz/voidrice) repo for extensibility's
sake. Mostly language-related.

## Who's who?

### `deadkeys.vim`

A script modeled off one on the vim wiki by Max Baker, but with more deadkeys
and a toggling command.

This gives you a function `ToggleDeadKeys()` that will, as its name suggest,
make ', ", ~ and : into keys that can be combined with other letters to give
you accents, specifically:

* ' gives you acute accents (á)
* ~ gives you tildes (ã)
* ` gives you grave accents (à)
* : gives you macrons (ā)
* " gives you umlauts (ä)

These will all work with most vowels and some consonants if the combination is
commonly used.

### `ipa.vim`

Adjustable bindings for International Phonetic Alphabet characters. Can be
toggled with `ToggleIPA()`.

### `prose.vim`

A prose mode.

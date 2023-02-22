# Tag missing media

_Note_: As of Anki 2.1.60+, this feature is available natively, so this add-on won't be updated for these versions.

## Rationale

When you click on «check media», anki gives the list of missing
media. I find that it does not help a lot to correct them. Indeed, I
would need to check by hand each missing media in the browser.

This add-on ensures that, when «check media» is used, it adds the tag
"MissingMedia" to each note with a missing media and open the browser
with the notes which have a missing media.

## Warning

check media also removes the tag «MissingMedia» from notes which does
not have a missing media. So that if you have corrected a note, it
does not appear anymore when you search for notes with Missing Media.

## Internal

It totally redefines the method `aqt.mediacheck.MediaChecker.check`. So
this add-on is incompatible with any other add-on changing this
method.

## Download

You can download the add-on from its page on AnkiWeb: https://ankiweb.net/shared/info/2027876532

## License

GNU AGPL, version 3 or late. See [LICENSE](LICENSE)

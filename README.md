# Character Sheet
A flutter character sheet to DnD using flutter.
Cause both are awesome.

## TODO
 - ~~Configure lint~~
 - ~~Define one Design System~~
    - [Material](https://flutter.dev/docs/development/ui/widgets/material)
 - Define architecture to be used ([examples here](https://fluttersamples.com/))
    - Bloc
    - Redux (is that possible?)
    - Another one that I don't know
 - Define router
    - [Navigator](https://api.flutter.dev/flutter/widgets/Navigator-class.html) ([cookbook](https://flutter.dev/docs/cookbook/navigation))
    - [Nuvigator](https://github.com/nubank/nuvigator)
    - Do more research later about it.
 - Finish one Feature
 - Configure pipeline (maybe use github actions)
    - analyze
    - dartfmt
    - tests
 - Configure Deploy (Android Only)
    - Configure steps
    - Configure pipeline
    - Set Secrets
 - Do more Features

### Features
 - Create form to add a new sheets
    - Basic DnD 5e sheet
    - I think it could receive all data for now
    - Save in disk
    - More tests
 - Show Sheet Widget
    - Basic DnD 5e sheet
    - Tests of course
 - List Sheets Widget
    - List all saved sheets
    - More tests
 - Home Widget
    - Show list
    - Add a button to call Create Sheet Widget
    - Tests :dog-please:

### Future
 - Add Native channels for "I don't know" things
 - Create a service to save chars cloud
 - Add monsters and pre made chars on database

# Meta Buttons

The Meta Buttons module is a shortcut collection of all Predix Experience button related modules.

## Dependencies

Px's Meta Buttons module depends on two other Px modules:

* [px-button-group-design](https://github.build.ge.com/PXd/px-button-group-design)
* [px-buttons-design](https://github.build.ge.com/PXd/px-buttons-design)

## Installation

Install this module and its dependencies using bower:

    bower install --save https://github.build.ge.com/PXd/px-meta-buttons-design.git

Once installed, `@import` into your project's Sass file in its Meta layer:

    @import "../px-meta-buttons-design/meta.buttons";

See [px-getting-started](https://github.build.ge.com/PXd/px-getting-started#a-note-about-relative-import-paths) for an explanation of the `../`

## Variable Flags

By using Meta Buttons you will also set these module feature switches to `true`:

    $inuit-enable-btn--primary
    $inuit-enable-btn--tertiary
    $inuit-enable-btn--small
    $inuit-enable-btn--large
    $inuit-enable-btn--huge
    $inuit-enable-btn--full
    $inuit-enable-btn--icon
    $inuit-enable-btn--bare
    $inuit-enable-btn--disabled
# Changelog

Changelog of Blockstudio Snippets

## 1.0.0

- Initial release

## 1.0.1

- Removed duplicate bs.link snippet

## 1.0.2

- Changed the icon of this extension

## 1.0.3

- For now, all field types that were still missing have been added, however, many additional properties such as `default` or `help` are still missing, these will be added with the next update (patch).

- I am already working on version v2, which will automatically create all field types and their properties as snippets based on the blockstudio schema.

### Added Field Types

- Toggle
- Radio
- Icon
- Token
- Textarea
- Repeater
- Color
- Date
- Tabs
- Range
- Gradient
- Datetime

## 1.0.4

- Fixed tabindex of toggle and text field
- Added textAlign property to bs.wysiwyg
- Added trailing commas to the snippets for a faster workflow
- Added default, fallback and placeholder property to inputs
- Added default property to toggle
- Added allowNull to select
- Added population snippet (bs.populate)

## 1.0.5

- Fixed allowNull and multiple properties on bs.select are strings instead of booleans
- Fixed bs.toggle "default" property was a string instead of a boolean
- Fixed bs.link "opensInNewTab" was a string instead of a boolean
- Added "default" property to bs.select

## 1.0.6

- Fixed bs.number, default value were a string, now its a number.
- Changed bs.block and bs.block.hph "category" property to be blank

## 1.0.7

- Removed "," from bs.block.hph snippet (caused error)
- Changed category property on bs.block.hph for faster workflow
- Added the new Unit field (bs.unit)

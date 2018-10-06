

# yarle: Yet Another Rope Ladder from Evernote

A tool that converts enex note(s) into Markdown format in order to let you escape from Evernote universe with all your belongings.

## Features:

- Works with enex files that contain single or multiple notes also.
- Works with notes that contain pictures too.
- Puts `title`, `creation time`, `update time`, `tags`, and `latlong` meta-information into md as metadata.
- Updates md files' access and modification timestamps according to the notes update time.
- Organizes all attachments into a _resources subfolder (to keep the notes' folder as simple as possible).

## Usage:

The converted Markdown files will be stored in `out/md` directory.

### Using cmd: 
```shell
  node ./dropTheRope.js <your_enex_filepath>
```

### In program: 

```javascript
 yarle.dropTheRope(<your_enex_filepath>);
```

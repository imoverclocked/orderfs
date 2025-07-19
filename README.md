# orderfs

Ordered File Listing based on extension, size and location.

Pronounced like "hors d'oeuvres."

## Usage

`orderfs --print0 [dir1 ...] | xargs -0 tar --append --file archive.tar && xz archive.tar`

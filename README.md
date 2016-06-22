# wp-themes

## Requirements
- Bash
- Imagemagick
- GAWK

## Optional
- Feh (for wallpaper) [img2wal]
- Python (for gtk theme changing)

## Scripts
- col2pal: Convert color list to a palette file, sorting colors by brightness (darkest to brightest)
- col2prv: Convert color list to a preview file, displaying each color in a square
- col2sys: Reload system programs to use new colors (you may need to edit this one)
- col2thm: Generate a color theme (termcolors, xresources, gtk) based on a color list
- dir2thm: Generate a color scheme for all files of a specific folder
- img2col: Extract 16 dominant colors out from a specific image
- img2thm: Generate a color theme (termcolors, xresources, gtk) based on an image
- img2wal: Set a specific image to the background wallpaper, using feh

## Notes
- GTK color theme is not finished and not supposed to work as of yet
- GTK icon theme is not started yet
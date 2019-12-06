# Updating ICO Files

As with the [Creating new `.ico` files](creating-ico-files.md) documentation,
this documentation will also go through the updating of `.ico` files with new
sizes using [GIMP](https://www.gimp.org/).

## Step 1 (Loading the icon project)

A Gimp project file, is any file with the `.xcf` file extension.
Just open this file as you would any other type, and it should load GIMP.

## Step 2 (Adding a new size)

I will assume that the size you want to add is higher than the already defined
highest size in the project.
If it is lower, you can Duplicate a new layer from the highest size as detailed in [Step 2 of Creating new `.ico` files](creating-ico-files.md#step-2-defining-the-different-supported-sizes).

1. Import the `.svg` file as a new layer. As with most other things in GIMP,
   this can be done in several ways. (Remember to input the desired width and height in the dialog that will be shown)
   - Go to menu `File --> Open as layer...`
   - Press `Ctrl+Alt+O`
   - Drag `.svg` file onto GIMP.
2. This will put the import the image as a new layer, but without updating the
   Canvas size. This must be done.
3. Go to the menu `Image --> Fit Canvas to Layers`.
4. You may have noticed in the Layer section, that new layer may have been
   put in the wrong order. While it should not really matter, you can fix that
   by just dragging the layer to the desired location.

Now that this is done, you can now follow [Step 3 of Creating new `.ico` files](creating-ico-files.md#step-3-exporting-and-saving-the-ico-file) for exporting the updated `.ico` file.
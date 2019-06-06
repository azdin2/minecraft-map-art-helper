# minecraft-map-art-helper
A static HTML tool to help you convert an image into Minecraft map art in survival

First use Photopea (basically a free online photoshop made by a guy in Prague) to edit your image into 128x128 pixels and remove any transparency. Save it as png (preferred), gif (limited to 256 colors), or jpg (compression artifacts) to your desktop. You can actually load larger images but only the top left 128x128 pixels will be used.

Change any options below like what blocks to exclude.

Use the "Select File..." link to select the file from your desktop to convert the colors to the nearest Minecraft map colors.

Note that this script can only do flat maps with 51 colors. It is possible to have 153 colors using the staircase method but it significantly increases the complexity of making the map art so it has not been implemented.

Once loaded, you can hover your mouse over a pixel to see the coordinates and block types.

You can click on a pixel to highlight it and preserve your place while you go place blocks in game.

If you then click on another pixel while holding shift, the pixels in a square between the two will be highlighted and the tooltip will be updated with the boxes' dimensions.

Ideally your screen resolution is at least 1280x960 so you do not have to scroll sideways since each pixel is zoomed by 10 pixels.

Block totals are shown in a table below the image.

If you're using this script on a website, you can auto load an images by adding this to the end of the URL ?image=http://sameurl.com/images/image.png or relative path: ?image=/images/image.png but browsers block loading an image from another website and then trying to read its image data for security reasons. 

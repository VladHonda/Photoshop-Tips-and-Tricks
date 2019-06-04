# Photoshop-Tips-and-Tricks

Multiply person layer if background is white (no more selection)
Channel blue inverted (ctrl+i) brush with ovelay opacity 100 color white for highlights
                               brush with ovelay opacity 50 color black for shadows
Or duplicate layer or ad an adjustment layer and change the blending mode (multiply pentru piele bronzata)

Problems with layer styles? Just right click on effect/create layer
to do an independent layer with the right clicked layer style.

Content aware scaling protect with alpha channels when using it.
shift+numeric key schimba fill opacity
luminosity blending - fuzziness tii apasat pe alt si imparti triunghiul de la layer effects/blending options default
8 blend modes repond diffenrently to fill opacity the opacity
- color burn, linear burn, color dodge, linear dodge, vivid light, linear light, hard mix and difference
You can blend filters (at the right of the layer filter is a double slider)
window/arrange/new window for partially masked.psd
ctrl+] moves layer up by one, ctrl+shift+] moves layer first
alt+] muta vizualizarea layerului mai sus
edit/auto-align layers
file/script/load files into stack
white edge mask, no problem, apply gausian blur 1-2 pixel and the levels command on the mask (ctrl+l) and take the white slider to the left to take out that white edge.
For hair (coloring clothes) if u have a color edge, select the complementary color channel edge and paste it on the mask with the bad edge and if the color is slightly different use levels and drag the white slider
density mask for highpass (take the lightest channel invert it and copy to the highpass mask layer or alt+click on the add layer mask with the highpass layer selected)
Nice transition moveble gradient (radial or linear) Create the gradient on a separate layer then select layer styles and choose the knockout to shallow (does not pass groups) deep (goes through groups) and set the fill opacity to 0
edge mask: take a channel with the less noise duplicate it, use levels to increase the contrast, filter/stylise/find edges, invert it, use other/maximum to increase the luminance (n pixels), use noise/median with the same n value as the maximum filter, use gausian blur with 2xn value from maximum, apply it to the mask of high pass layer from below:

high pass filter can be used with levels (increase contrast) or hue and saturation (for desaturation) both cliped to it (high pass is in overlay mode). 
channel mixer for black and white from channels (use monochrome checkbox)
standard rgb 40 50 10
Sepia HSB 30 45 80, cc9e70 and use a desity mask (blue channel inverted...)
layer/change layer content (u can use it on adjustment layers)
infrared in channel mixxer: red gren high blue small RGB 110 190 -200 (total 100%) (good for shadows inverted of course)
increase highlights with channel mixer RGB 50 90 -90 (total 50%)
shift++ changes to next blending mode
lab mode, keep the light channel (black and white effect)
gradient map effects all the layers below it

Green channel increase contrast: duplicate the layer use image/apply image... and use the green channel and set the layer opacity to luminosity or use a channel mixer with RGB 0 100 0 and use the luminosity blend mode
Pesky Red eye use channel mixer to eradicate the red and after inspection mix the other 2
shift+F - multiple window mode
/ - lock transparency
layer/vector mask/current path sau selectezi path si tii apasat pe ctrl si apesi pe create new layer icon si face masca vectoriala dupa path-ul selectat
shift alt click pe un vertex care apartine unui shape si back space dupa aceea (sterge shape-ul respectiv)
difference mask: calculations 2 channels and difference blending mode
Enhace contrast using arbitrary map: curves and use the pencil tool on top to move pixells to white or down 0 to move pixels to black and use smooth button to make the transition softer to keep a nice organic edge.
Use the dodge and burn tool to make even finer adjustments on the mask with highlights, shadows option on.
Power duplication: ctrl+alt+t face duplicat care il rotesti apesi enter si dupa aia apesi ctrl+shift+alt+t si repeta transformarea.
Magnetic pen tool: free form pen tool with the magnetic checkbox on.
ctrl+alt - smooth point converted to a cusp point.
Multiple arbitrary maps on a single image use the rectangular marquee tool (no anti-alias-good couse there are no fringes left to fix between the selections). Once u finish a selection arbitrary map use the dodge and burn to tune it and after invert the mask ctrl+shift+i and select with the rect marquee and adjacent portion of the image.
Use snapshots when U r not sure how thing will turn becouse U can use the history brush.
Highpass masking: use high pass 20-30 pix, then levels 120 white point,  135 black point. then look through the outline and invert the portions with white ouside and black inside with the lasso tool and the ctrl+i.
The start to color white inside and black outside.
If U want to combine masks use calculations with the screen blending mode. 
DIsplacement maps: Gradient ones, use gausian blur with high pixel values to make the wave more rouded.
White goes up and to the top and black goes down and to the right (from the diplacement maps wich are saved as a sigle layer sigle or multi channel psd file) (first chanel is horizontal and second si vertical movement, the others are bypassed)

# Miasma_1.03_Revised

Note: use the BOM included in this repository. Some of the components have been relabelled in this revision so the BOM on SinPhi's website is no longer current.

The changes from version 1.03 are:

1) Updated the footprints and symbols to ones included in KiCAD 5.1.5, or otherwise included the auxillary libraries in the repository.

2) Made the 4QX output no longer inverted and added a jumper pin on the back that allows you to switch between (non-inverted) summing and 4QX modes.

3) Added diodes and jumper pins between the cycle gate input and trigger switch for each side. This allows you to choose whether applying a gate to the cycle input will cause it to start cycling automatically (jumper on) or require a trigger to start cycling (jumper off).

4) Fixed the EOC2 output from not being grounded.

5) Small tweaks such as adjusting track spacing, etc.

# Acknowledgements

Original Miasma board by Sin Phi http://www.sinphi.com/synths/miasma/miasma.html, based on the Befaco Rampage http://www.befaco.org/rampage-2/. 4QX and diode mods inspired by Mcop http://www.mcop.co.uk/diy/mods-and-stripboard-layouts/miasma-function-generator-modifications/.

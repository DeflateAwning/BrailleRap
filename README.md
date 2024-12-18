
<figure>
<img src="https://github.com/braillerap/BrailleRap/blob/master/docs/IMG/github_logo.png" alt="BrailleRAP image" style="width:75%; align:center;">
</figure>

# BrailleRAP

Based on the [RepRap 3d printer controller](https://reprap.org/wiki/RepRap), BrailleRAP is an open hardware device to emboss Braille text and/or Vector graphics. You can use software like [AccessBrailleRAP](https://github.com/braillerap/AccessBrailleRAP) or [DesktopBrailleRAP](https://github.com/braillerap/DesktopBrailleRAP) to build tangible documents with the device.

BrailleRAP now exist in 2 different sizes: **BrailleRAP** and **BrailleRAP XL**. 
- **BrailleRAP** emboss sheet up to 210x297 mm. Lightweight, a completed device will weight less than 5 kg and fit in cabin travel case. So it's easy to travel with.
- **BrailleRAP XL** emboss sheet up to 297x420 mm. A larger surface if you need to emboss vector graphics. But also heavyer, around 7.5 kg and not as easy to travel with than the standard model.

<figure>
<img src="https://github.com/braillerap/BrailleRap/blob/master/docs/IMG/github_logo2.jpg" alt="BrailleRAP and BrailleRAP XL image" style="width:75%; align:center;">
</figure>

<figure>
<img src="https://github.com/braillerap/BrailleRap/blob/master/docs/IMG/brap_sample.jpg" alt="Tangible documents examples made on BrailleRAP" style="width:75%; align:center;">
</figure>


## BrailleRAP is supported by the NLnet foundation.
<figure>
    <a href="https://nlnet.nl/">
        <img src="https://github.com/braillerap/BrailleRap/blob/master/docs/IMG/logo-sh.png" alt="NLnet foundation logo" style="width:30%; align:center;"/>
    </a>
</figure>


## BrailleRap 6.6

Embosseuse Braille Open Source DIY

[![Documentation Status](https://readthedocs.org/projects/braillerap/badge/?version=latest&style=plastic)](https://braillerap.readthedocs.io/fr/latest/?badge=latest)

La documentation complete [est disponible ici braillerap.readthedocs.io](https://braillerap.readthedocs.io/fr/latest/index.html).

==========================================================================

DIY Open Source Braille embosser

[![Documentation Status](https://readthedocs.org/projects/braillerap-en/badge/?version=latest&style=plastic)](https://braillerap-en.readthedocs.io/en/latest/index.html)

The full documentation [is available at braillerap-en.readthedocs.io](https://braillerap-en.readthedocs.io/en/latest/index.html).

## Repository Structure

### `docs/`
The source file for readthedoc documentation, viewable at [braillerap.readthedocs.io](https://braillerap.readthedocs.io/fr/latest/index.html).

### `lasercut/`
SVG/DXF file for laser cut

### `MarlinBraille/`
BrailleRAP Firmware for MKS GEN 1.4 & MKS GEN L 2.1.

The firmware is already configured for DRV8825 stepper drivers.

### `printed_parts/`
STL files for 3D printed parts.

There is an xlsx (3D printed parts excel board.xlsx) files that detail the parts to print.

### `NatBrailleTools/`
Java source code for NatBraille BrailleRAP driver. This is a little obsolete now. Consider using AccessBrailleRAP (https://github.com/braillerap/AccessBrailleRAP) instead.

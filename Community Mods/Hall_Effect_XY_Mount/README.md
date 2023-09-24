# Hall Effect XY Mount
![Image of Hall Effect magnet mount](/Hall_Effect_XY_Mount.png)

I designed a new magnet mount for the CNC tap which places the magnet in the same location as the stock Srealthburner X Carriage. 

I had already begun creating this before finding the STL for the XY_Switch_Adapter.
I had a few concerns with the original switch adapter:
- The magnet position does not match the original location of the magnet in the Voron X Carriage.
- I did not like the use of just a hexagon for retaining the magnet.
- Thin neck of the body from where the screws mount to the tap carriage and where the magnet resides.

I also wanted a mount that clipped into place and then uses the original included M2x8 mm socket head cap screws to mount to the CNC Tap.

## Magnet Choice
For my project I chose to use high temperature SH rated magnets. I could only find these in 1/4" x 1/8" size instead of the standard 6mm x 3mm metic size. While close these magnets are really 6.35mm x 3.2mm

The STL folder contains two .3mf files depending on the magnet being used.
- Hall_Effect_XY_Mount_6x3mm.3mf

  For use with the Voron BOM 6x3 mm magnets
  
- Hall_Effect_XY_Mount_D42SH-0.25x0.125in.3mf

  For use with the D42SH or any 1/4" x 1/8" magnet.

## CAD
Included in the CAD folder are step files for both magnet types.
- Hall_Effect_XY_Mount_6x3mm.step
- Hall_Effect_XY_Mount_D42SH-0.25x0.125in.step

I have also included the Fusion 360 project which uses parameters to define a custom magnet size for use in the mount.
The magnet measurements can be entered in the MagnetDiameter and MagnetThickness parameters to update the component body magnet hole dimensions.

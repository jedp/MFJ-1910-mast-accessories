# MFJ-1910 telescoping antenna mast accessories

Some components for improving
the [MFJ 1910 telescoping fiberglass mast](https://mfjenterprises.com/products/mfj-1910).

- Guy wire yoke
- Seven antenna wire clips for different mast segments
- Ring for top of mast

![model](MFJ-1910-models.png)

![physical print](MFJ-1910-slicer.png)

## Parametric Values

These values worked for me and my printer and filament (Prusa i3 MK3S; PETG;
0.20mm SPEED). YMMV with a different printer, nozzle, filament, slicer, etc.

The single most important values will be the snug-fit inner diameters of the wire clips.
These are the values I arrived at after some trial and error.

- `segment_diameter_1`: 0.30in (top element)
- `segment_diameter_2`: 0.60in
- `segment_diameter_3`: 0.83in
- `segment_diameter_4`: 0.95in
- `segment_diameter_5`: 1.10in
- `segment_diameter_6`: 1.25in
- `segment_diameter_7`: 1.35in

Also crucial for the snug fit of the clips is the wire diameter:

- `wire_diameter`: 1.9mm

Finally, the inner diameter of the guy wire yoke worked for me at 1.75 in: Same as the
diameter of the tube with no extra constriction for fit.




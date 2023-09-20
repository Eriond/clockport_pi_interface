# Alternative PCB for Niklas Ekström's "clockport pi interface"

This is a fork from Niklas Ekström where an alternate PCB layout has been made to enable an even smaller and more low-profile end product.
The fork contains PCB files in KiCAD 6.99 format, and an updated pin constraint file (.ucf) to accomodate for the new PCB.

![PCB](Docs/BarePCB.jpg?raw=true)
![PCB /w components](Docs/WithCmpnt.jpg?raw=true)
![Low profile installation](Docs/InAnA1200.jpg?raw=true)

## Details about how the interface works

For further details about this excellent project, please visit this forks origin site @ [niklasekstrom/clockport_pi_interface](https://github.com/niklasekstrom/clockport_pi_interface)<br>
You will find a schematic PDF for this forked PCB in the Hardware folder.

## Bill of materials

| References                     | Value                                                | Footprint                       | Quantity |
|--------------------------------|------------------------------------------------------|---------------------------------|----------|
| C1, C2, C3, C4, C5, C6, C7, C8 | 0.1u                                                 | C_0603_1608Metric               | 8        |
| U1                             | XC9572XL-VQ64                                        | TQFP-64_10x10mm_P0.5mm          | 1        |
| IC2, IC3                       | SN74LVC573APWRE4<br>(alt: 74LVC573APW,118)           | SOP65P640X120-20N               | 2        |
| IC1                            | IS63WV1288DBLL-10TLI<br>(alt: IS61WV1288EEBLL-10TLI) | SOIC127P1176X120-32N            | 1        |
| J1                             | Raspberry Pi Zero 2W                                 | PinSocket_2x20_P2.54mm_Vertical | 1        |
| J2                             | Molex 87381-2218<br>2row, 11pos, 2mm grid            | PinSocket_2x11_P2.00mm_Vertical | 1        |

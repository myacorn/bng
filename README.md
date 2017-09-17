# British National Grid (BNG)

This repository will contain our python tools for working with British National Grid (BNG) grid references.

For now, here is a summary of the size and area of [grid references](https://en.wikipedia.org/wiki/Ordnance_Survey_National_Grid#Datum_shift_between_OSGB_36_and_ED_50) at various precisions.

|Example     | Num. figures | Distance  | Comment                                        |
|------------|:------------:|----------:|------------------------------------------------|
|T           | 0            |500 km     | (split into 5 sub squares, e.g. TQ)            |
|TQ          | 0            |100 km     | (each split from now on is into 10 sub squares)|
|TQ28        | 2            |10 km      |                                                |
|TQ2980      | 4            |1 km       |                                                |
|TQ299804    | 6            |100 m      |                                                |
|TQ29908040  | 8            |10 m       |                                                |
|TQ2990080400| 10           |1 m        |                                                |

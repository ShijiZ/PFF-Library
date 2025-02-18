# PFF-Library
The repository for `Pantetheine Force Field (PFF)` library containing parameters of various `pantetheine-containing ligands (PCLs)` compatible with [Amber force fields](https://ambermd.org/AmberModels.php). Three charging methods (Gasteiger, AM1-BCC, or RESP) combined with gaff2 and ff14SB parameter sets were employed.

## Tutorial
The tutorial for using PFF library for Phosphopantetheine adenylyltransferase-phosphopantetheine (PPAT-Ppant system) and 3-hydroxy-3-methylglutaryl synthase/acyl carrier protein complex-phosphopantetheinyl serine (HGMS/ACP-Ppant-Ser) can be found on:
- [Tutorial on Github](http://htmlpreview.github.io/?https://github.com/ShijiZ/PFF-Library/blob/main/tutorial/pff-tutorial.html)
- [Tutorial on Amber](https://ambermd.org/tutorials/basic/tutorial20/index.php)

## Parameter Files
| PCL Name                                       | PDB ID   | Description                                | URL Links                                                      |
|:-----------------------------------------------|:---------|:-------------------------------------------|:---------------------------------------------------------------|
| `Coenzyme A (CoA) Library`                                                                                   |
| CoA                                            | COA      | “apo” coenzyme A                           | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/CoA-lib/COA)         |
| Acetyl-CoA                                     | ACO      | 2 Carbon Acyl-CoA                          | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/CoA-lib/ACO)         |
| Propionyl-CoA                                  | 1VU      | 3 Carbon Acyl-CoA                          | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/CoA-lib/1VU)      |
| Butyryl-CoA                                    | BCO      | 4 Carbon Acyl-CoA                          | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/CoA-lib/BCO)        |
| Hexanoyl-CoA                                   | HXC      | 6 Carbon Acyl-CoA                          | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/CoA-lib/HXC)       |
| Octanoyl-CoA                                   | CO8      | 8 Carbon Acyl-CoA                          | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/CoA-lib/CO8)       |
| Decanoyl-CoA                                   | MFK      | 10 Carbon Acyl-CoA                         | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/CoA-lib/MFK)       |
| Dodecanoyl-CoA                                 | DCC      | 12 Carbon Acyl-CoA                         | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/CoA-lib/DCC)     |
| Tetradecanoyl-CoA                              | MYA      | 14 Carbon Acyl-CoA                         | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/CoA-lib/MYA)  |
| Hexadecanoyl-CoA                               | PKZ      | 16 Carbon Acyl-CoA                         | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/CoA-lib/PKZ)   |
| Malonyl-CoA                                    | MLC      | CoA derivative of malonic acid             | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/CoA-lib/MLC)        |
| Acetoacetyl-CoA                                | CAA      | Precursor of HMG-CoA in mevalonate pathway | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/CoA-lib/CAA)    |
| `Phosphopantetheine (Ppant) Library`                                                                         |
| Ppant                                          | PNS      | “apo” phosphopantetheine                   | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/Ppant-lib/PNS) |
| Acetyl-Ppant                                   | 6VG      | 2 Carbon Acyl-Ppant                        | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/Ppant-lib/6VG)       |
| Butyryl-Ppant                                  | PSR      | 4 Carbon Acyl-Ppant                        | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/Ppant-lib/PSR)      |
| Hexanoyl-Ppant                                 | SXH      | 6 Carbon Acyl-Ppant                        | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/Ppant-lib/SXH)     |
| Octanoyl-Ppant                                 | SXO      | 8 Carbon Acyl-Ppant                        | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/Ppant-lib/SXO)     |
| Decanoyl-Ppant                                 | PM8      | 10 Carbon Acyl-Ppant                       | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/Ppant-lib/PM8)     |
| Dodecanoyl-Ppant                               | 8Q1      | 12 Carbon Acyl-Ppant                       | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/Ppant-lib/8Q1)   |
| Tetradecanoyl-Ppant                            | ZMP      | 14 Carbon Acyl-Ppant                       | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/Ppant-lib/ZMP)|
| Hexadecanoyl-Ppant                             | G9S      | 16 Carbon Acyl-Ppant                       | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/Ppant-lib/G9S) |
| `Phosphopantetheinyl-Serine (Ppant-Ser) Library`                                                             |
| Ppant                                          | PNS      | “apo” phosphopantetheinyl-serine           | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/Ppant-Ser-lib/PNS) |
| Acetyl-Ppant                                   | 6VG      | 2 Carbon Acyl-Ppant                        | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/Ppant-Ser-lib/6VG)   |
| Butyryl-Ppant                                  | PSR      | 4 Carbon Acyl-Ppant                        | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/Ppant-Ser-lib/PSR)  |
| Hexanoyl-Ppant                                 | SXH      | 6 Carbon Acyl-Ppant                        | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/Ppant-Ser-lib/SXH) |
| Octanoyl-Ppant                                 | SXO      | 8 Carbon Acyl-Ppant                        | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/Ppant-Ser-lib/SXO) |
| Decanoyl-Ppant                                 | PM8      | 10 Carbon Acyl-Ppant                       | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/Ppant-Ser-lib/PM8) |
| Dodecanoyl-Ppant                               | 8Q1      | 12 Carbon Acyl-Ppant                       | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/Ppant-Ser-lib/8Q1) |
| Tetradecanoyl-Ppant                            | ZMP      | 14 Carbon Acyl-Ppant                       | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/Ppant-Ser-lib/ZMP) |
| Hexadecanoyl-Ppant                             | G9S      | 16 Carbon Acyl-Ppant                       | [Link](https://github.com/ShijiZ/PFF-Library/tree/main/Ppant-Ser-lib/G9S) |

## Citation
To cite PFF library, see the following publication:

[Shiji Zhao, Andrew J. Schaub, Shiou-Chuan Tsai, and Ray Luo. "Development of a Pantetheine Force Field Library for Molecular Modeling." Journal of Chemical Information and Modeling 61, no. 2 (2021): 856-868.](https://pubs.acs.org/doi/10.1021/acs.jcim.0c01384)

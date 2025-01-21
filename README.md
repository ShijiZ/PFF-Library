# PFF-Library
The repository for `Pantetheine Force Field (PFF)` library containing parameters of various `pantetheine-containing ligands (PCLs)` compatible with Amber force fields. Three charging methods (Gasteiger, AM1-BCC, or RESP) combined with gaff2 and ff14SB parameter sets were employed.

## Tutorial
The tutorial for using PFF library can be found [here](https://ambermd.org/tutorials/basic/tutorial20/index.php).

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
| Ppant                                          | PNS      | “apo” phosphopantetheine                   | [Link](http://rayluolab.org/pff-files-for-phosphopantetheine/) |
| Acetyl-Ppant                                   | 6VG      | 2 Carbon Acyl-Ppant                        | [Link](http://rayluolab.org/pff-files-for-acetyl-ppant/)       |
| Butyryl-Ppant                                  | PSR      | 4 Carbon Acyl-Ppant                        | [Link](http://rayluolab.org/pff-files-for-butyryl-ppant/)      |
| Hexanoyl-Ppant                                 | SXH      | 6 Carbon Acyl-Ppant                        | [Link](http://rayluolab.org/pff-files-for-hexanoyl-ppant/)     |
| Octanoyl-Ppant                                 | SXO      | 8 Carbon Acyl-Ppant                        | [Link](http://rayluolab.org/pff-files-for-octanoyl-ppant/)     |
| Decanoyl-Ppant                                 | PM8      | 10 Carbon Acyl-Ppant                       | [Link](http://rayluolab.org/pff-files-for-decanoyl-ppant/)     |
| Dodecanoyl-Ppant                               | 8Q1      | 12 Carbon Acyl-Ppant                       | [Link](http://rayluolab.org/pff-files-for-dodecanoyl-ppant/)   |
| Tetradecanoyl-Ppant                            | ZMP      | 14 Carbon Acyl-Ppant                       | [Link](http://rayluolab.org/pff-files-for-tetradecanoyl-ppant/)|
| Hexadecanoyl-Ppant                             | G9S      | 16 Carbon Acyl-Ppant                       | [Link](http://rayluolab.org/pff-files-for-hexadecanoyl-ppant/) |
| `Phosphopantetheinyl-Serine (Ppant-Ser) Library`                                                             |
| Ppant                                          | PNS      | “apo” phosphopantetheinyl-serine           | [Link](http://rayluolab.org/pff-files-for-phosphopantetheinyl-serine/) |
| Acetyl-Ppant                                   | 6VG      | 2 Carbon Acyl-Ppant                        | [Link](http://rayluolab.org/pff-files-for-acetyl-ppant-ser/)   |
| Butyryl-Ppant                                  | PSR      | 4 Carbon Acyl-Ppant                        | [Link](http://rayluolab.org/pff-files-for-butyryl-ppant-ser/)  |
| Hexanoyl-Ppant                                 | SXH      | 6 Carbon Acyl-Ppant                        | [Link](http://rayluolab.org/pff-files-for-hexanoyl-ppant-ser/) |
| Octanoyl-Ppant                                 | SXO      | 8 Carbon Acyl-Ppant                        | [Link](http://rayluolab.org/pff-files-for-octanoyl-ppant-ser/) |
| Decanoyl-Ppant                                 | PM8      | 10 Carbon Acyl-Ppant                       | [Link](http://rayluolab.org/pff-files-for-decanoyl-ppant-ser/) |
| Dodecanoyl-Ppant                               | 8Q1      | 12 Carbon Acyl-Ppant                       | [Link](http://rayluolab.org/pff-files-for-dodecanoyl-ppant-ser/) |
| Tetradecanoyl-Ppant                            | ZMP      | 14 Carbon Acyl-Ppant                       | [Link](http://rayluolab.org/pff-files-for-tetradecanoyl-ppant-ser/) |
| Hexadecanoyl-Ppant                             | G9S      | 16 Carbon Acyl-Ppant                       | [Link](http://rayluolab.org/pff-files-for-hexadecanoyl-ppant-ser/) |

## Citation
To cite PFF library, see the following publication:

[Shiji Zhao, Andrew J. Schaub, Shiou-Chuan Tsai, and Ray Luo. "Development of a Pantetheine Force Field Library for Molecular Modeling." Journal of Chemical Information and Modeling 61, no. 2 (2021): 856-868.](https://pubs.acs.org/doi/10.1021/acs.jcim.0c01384)

# SweetenersDB (v2.0)

Updated and curated database of 316 sweet molecules.

v2.0 : [Bouysset et al. (2020) Food Chem.](https://doi.org/10.1016/j.foodchem.2020.126864)

v1.0 : [Chéron et al. (2017) Food Chem.](https://doi.org/10.1016/j.foodchem.2016.10.145)

Differences between v2.0 and v1.0 :

- Updated sucralose to its D conformer
- Updated D-tagatose to have all stereocenters defined, and removed tagatose as duplicate
- Removed DHQ-3-SIFA-4'-methyl_ether (duplicate with isovanillic_13, and can't find it on ChemSpider or other chemical DB)
- Updated arabinose, ribose and xylose to their D conformer
- asp_10 (1.43) and asp_12 (1.56) were grouped as a single entry (asp_10_12), with logSw = 1.495, because their delta(logSw) < 0.2
- Same for asp_171 (1.41) and asp_178 (1.23), asp_171_178 = 1.32
- Same for asp_173 (1.44) and asp_180 (1.31), asp_173_180 = 1.375
- The remaining duplicates of the asp_ series with delta(logSw) > 0.2 were removed:
57: asp_11 1.54 | 68: asp_13 1.85
66: asp_128 1.16 | 72: asp_133 0.88
98: asp_167 1.26 | 106: asp_174 0.71
99: asp_168 1.93 | 107: asp_175 0.66
100: asp_169 2.08 | 108: asp_176 1.51
102: asp_170 1.93 | 109: asp_177 0.91
104: asp_172 1.97 | 111: asp_179 1.36
130: asp_198 2.79 | 131: asp_199 3.06
138: asp_208 3.16 | 139: asp_209 4.79
155: asp_56 1.16 | 156: asp_57 0.75
- Updated aspartame to have all stereocenters defined
- Updated galactitol, mannitol and sorbitol to their D conformer
- Updated galactose and glucose to their D conformer
- Updated lactitol and maltitol to have all stereocenters defined
- Updated lactose and maltose to have all stereocenters defined
- Updated lactulose, leucrose, isomaltulose to have both oses in their cyclic form, and used the LogSw values from Ruiz-Aceituno et al.:
lactose: from -0.6 to -0.54
lactulose: from -0.3 to -0.52
leucrose: from -0.3 to -0.46
isomaltulose (palatinose): from -0.32 to -0.52
- Added α-D-lactose (-0.44) from Yang
- Added alanine (0.11), trehalulose (-0.26), arabitol (-0.6), glycerol (-0.8), glycyrrhizinate 2 (2.3) and 3 (2.18), isomogroside V (3.27) from Cheron
- Added α-D-Mannopyranose, α-D-Psicofuranose, α-D-Tagatopyranose, α-L-Arabinopyranose, α-L-Rhamnopyranose, α-L-Sorbopyranose, β-D-Fructopyranose, β-D-Galactopyranose, β-D-Glucopyranose, β-D-Ribopyranose, β-D-Xylofuranose, β-L-Fucopyranose from Cheron
- Added kojibiose (-0.57), maltulose (-0.51), turanose (-0.44), 4-galactosyl-kojibiose (-0.66), lactulosucrose (-0.60) from Ruiz-Aceituno. 4-galactosyl-kojibiose and lactulosucrose chemical structures were constructed with ChemAxon MarvinSketch, using beta-D-Gal-(1-4)-beta-D-Glc-(2-1)-alpha-D-Glc and beta-D-Gal-(1-4)-beta-D-Fru-(2-1)-alpha-D-Glc respectively.
- molecules have been sorted according to LogSw and their IDs have been updated

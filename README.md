biochar_calcs.ipynb contains code to recompute net CO2 sequestration potential from a range of crop-residue biochar feedstocks to factor in upstream emissions.

Crop residue constants used by the notebook are stored in `crop_residue_data.csv` and loaded into `crop_residue_data` at runtime.

Methodology and assumptions for raw biochar CO2 sequestration potential taken from Karan et al. 2023 paper.

Upstream emissions recalculated using inputs from ecoinvent, and residue-product ratios (RPRs) from the Karan et al. 2023 paper where residue yields were not provided in Ecoinvent.

Key limitations:
- Extrapolates global upstream emissions for a given crop residue based on the 'Rest of World' dataset crop residue values in ecoinvent, rather than accurately representing regional variations in biochar sequestration potential from the same crop type
- Assumes constant H/C ratio for all crops included

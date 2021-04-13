# Broadband Multi-wavelength Observations of M87 During the 2017 Event Horizon Telescope Campaign

**Authors:** The EHT MWL Science Working Group et al. (EHT Collaboration, Fermi-LAT Collaboration, H.E.S.S. Collaboration, MAGIC Collaboration, VERITAS Collaboration, and EAVN Collaboration)

**Date:** April 14th, 2021

**Primary Reference:** [The EHT MWL Science Working Group et al. (2021), ApJL, 911, L11, DOI: 10.3847/2041-8213/abef71](https://doi.org/10.3847/2041-8213/abef71)

**Data Product Code:** [2021-D02-01](https://eventhorizontelescope.org/for-astronomers/data)

**Brief Description:**

In 2017, the Event Horizon Telescope (EHT) Collaboration succeeded in capturing the first direct image of the center of the M87 galaxy, revealing an asymmetrically bright, fuzzy ring of light surrounding a dark interior. The ring morphology and size are consistent with theoretical expectations for the light pattern around a weakly accreting supermassive black hole with mass of approxixmately 6.5 billion Solar masses. To support the physical interpretation and modeling, the EHT Collaboration partnered with several international facilities in space and on the ground, to arrange an extensive, quasi-simultaneous multi-wavelength (MWL) campaign. Through this repository, we release the processed data from MWL observations of M87 in easily downloadable formats, as a legacy product of the EHT 2017 campaign on M87.

Our 2017 observations capture M87 in a historically low state, both for its core as well as the nearest knot, HST-1. The core flux dominates over HST-1 in the high-energy, making it possible to combine with the more spatially precise VLBI data. In the paper associated with this data release, Algaba et al. (2021), we present the most complete simultaneous, MWL spectrum of the active nucleus to date, as well as discuss the complexity and caveats of combining data from different spatial scales into a single broadband spectrum. The MWL spectrum is provided in a machine-readable format as the CSV file `m87_2017_mwl_spectrum.csv`. A brief description of MWL observations and data processing is given in the file `observations_and_data_description.txt`; for further details please refer to [The EHT MWL Science Working Group et al. (2021)](https://doi.org/10.3847/2041-8213/abef71). In addition to this primary data product, we also release machine-readable versions of other tables presented in the Appendix of the paper.

Intermediate data products of the X-ray analysis and sampled posteriors of X-ray and MWL model parameters are publicly available only in the associated [CyVerse repository (DOI: 10.25739/mhh2-cw46)](https://datacommons.cyverse.org/browse/iplant/home/shared/commons_repo/curated/EHTC_M87mwl2017_Apr2021), since the files are too large to host on GitHub.

**List of Data Products:**

- MWL spectrum (Table A8): `m87_2017_mwl_spectrum.csv`
- description of observations and data processing: `observations_and_data_description.txt`
- fluxes from H.E.S.S., MAGIC, and VERITAS observations (Table A7): `m87_2017_vhe.csv`
- fluxes from Swift-XRT observations (part of Table A6): `m87_2017_swiftxrt.csv`
- flux densities from HST observations (Table A5): `m87_2017_hst.csv`
- flux densities from Swift-UVOT observations (Tables A3 and A4): `m87_2017_swiftuvot.csv`
- flux densities from radio observations (Table A1): `m87_2017_radio.csv`

Available via [CyVerse repository (DOI: 10.25739/mhh2-cw46)](https://datacommons.cyverse.org/browse/iplant/home/shared/commons_repo/curated/EHTC_M87mwl2017_Apr2021):
- scripts, spectral, and response files for modeling Swift-XRT data: `m87_2017_swiftxrt_data_modeling.zip` (file size: 25 MB)
- scripts, spectral, and response files for modeling Chandra and NuSTAR data: `m87_2017_chandra_nustar_data_modeling.zip` (file size: 64 MB)
- sampled posterior distributions of X-ray spectrum model based on Chandra and NuSTAR data: `m87_2017_xray_model_posteriors.zip` (file size: 6.8 GB)
- sampled posterior distributions of the MWL spectrum model: `m87_2017_mwl_model_posteriors.zip` (file size: 18 MB)

**Related References:**

- [EHT Collaboration Data Portal Website](https://eventhorizontelescope.org/for-astronomers/data)
- [The Event Horizon Telescope Collaboration, et al. 2019a, ApJL, 875, L1 (M87 Paper I)](https://doi.org/10.3847/2041-8213/ab0ec7)
- [The Event Horizon Telescope Collaboration, et al. 2019b, ApJL, 875, L2 (M87 Paper II)](https://doi.org/10.3847/2041-8213/ab0c96)
- [The Event Horizon Telescope Collaboration, et al. 2019c, ApJL, 875, L3 (M87 Paper III)](https://doi.org/10.3847/2041-8213/ab0c57)
- [The Event Horizon Telescope Collaboration, et al. 2019d, ApJL, 875, L4 (M87 Paper IV)](https://doi.org/10.3847/2041-8213/ab0e85)
- [The Event Horizon Telescope Collaboration, et al. 2019e, ApJL, 875, L5 (M87 Paper V)](https://doi.org/10.3847/2041-8213/ab0f43)
- [The Event Horizon Telescope Collaboration, et al. 2019f, ApJL, 875, L6 (M87 Paper VI)](https://doi.org/10.3847/2041-8213/ab1141)
- [The Event Horizon Telescope Collaboration, et al. 2021a, ApJL, 910, L12 (M87 Paper VII)](https://doi.org/10.3847/2041-8213/abe71d)
- [The Event Horizon Telescope Collaboration, et al. 2021b, ApJL, 910, L13 (M87 Paper VIII)](https://doi.org/10.3847/2041-8213/abe4de)
- [The EHT MWL Science Working Group et al. 2021, ApJL, 911, L11 (M87 Paper IX)](https://doi.org/10.3847/2041-8213/abef71)


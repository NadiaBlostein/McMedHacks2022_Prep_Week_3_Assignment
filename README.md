
# McMedHacks2022 Prep Week 3: Assignment
McMedHacks 2022 Prep Week 3 introduces participants to scientific programming with Python through a workshop prepared by Saman Rahbar and an assignment prepared by Nadia Blostein and Cesare Spinoso. The assignment leverages the new concepts from the workshop in order to introduce students to data processing, a critical  prerequisite to any data analysis or machine learning application. 

## About the Human Connectome Project (HCP) Data

### 1. Behavioral data: `HCP_csv_data/unrestricted_HCP_behavioral.csv`

The dataset that you are being provided only contains the open access HCP behavioral features (some are restricted, see [here](https://wiki.humanconnectome.org/display/PublicData/HCP-YA+Data+Dictionary-+Updated+for+the+1200+Subject+Release#HCPYADataDictionaryUpdatedforthe1200SubjectRelease-Instrument:Demographics) for more info). It is possible to apply for permission to access the Tiers 1 and 2 restricted data.

### 2. Brain structure volume data: `HCP_csv_data/HCP_volumes.csv`

Structural MRI data was acquired from the WU-Minn HCP S1200 Release ([Van Essen et al., 2013](https://pubmed.ncbi.nlm.nih.gov/23684880/); [Glasser et al., 2016](https://pubmed.ncbi.nlm.nih.gov/27571196/)). Volumes were obtained using the high-resolution 3T T1-weighted (T1w) magnetic resonance imaging (MRI) data (n = 1086 subjects, HCP S1200 Reference Manual, downloaded directly from the [HCP online repository](https://db.humanconnectome.org/data/projects/HCP_1200)).

Total brain volume (TBV) as well as the volume and total surface area of 6 other structures (left striatum, right striatum, left thalamus, right thalamus, left globus pallidus, right globus pallidus) were obtained by Nadia Blostein and colleagues from the [Computational Brain Anatomy (CoBrA) Laboratory](https://cobralab.ca/) (Cerebral Imaging. Center, Douglas Mental Health University Institute) under the supervision of Dr. Mallar Chakravarty. Images were processed and volume and surface area measures extracted using a standard lab pipeline that involved the publicly available [minc-bpipe library](https://github.com/CoBrALab/minc-bpipe-library) and [MAGeTbrain segmentation algorithm](https://github.com/CobraLab/MAGeTbrain). More thorough details on image processing and volume obtention can be found [here](https://www.biorxiv.org/content/10.1101/2022.04.11.487874v1).

### 3. 2D Slices from MR images: `HCP_2D_slices_MRI_data/*png`

2D slices of open access T1w 3D MR images from 5 different subjects of the HCP dataset.


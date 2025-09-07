# Lithology_Prediction_using_log_data
This repository consist of different classifier used for declaring the score (precision, recall, F1score, accuracy) of well_log_data, And also the data Analysis of the dataset, describing and plotting of log data.

# Dataset

The dataset comes from a class excercise from The University of Kansas and contains logs from the largest gas fields in North America, the Hugoton and Panoma Fields.

Facies (types of rocks) are studied from core samples in every half foot and matched with logging data in well location. Feature variables include five from wireline log measurements and two geologic constraining variables that are derived from geologic knowledge.

The seven variables are:

GR: this wireline logging tools measure gamma emission
ILD_log10: this is resistivity measurement
PE: photoelectric effect log
DeltaPHI: Phi is a porosity index in petrophysics.
PNHIND: Average of neutron and density log.
NM_M:nonmarine-marine indicator
RELPOS: relative position
The nine discrete facies (classes of rocks) are:

SS: Nonmarine sandstone
CSiS: Nonmarine coarse siltstone
FSiS: Nonmarine fine siltstone
SiSH: Marine siltstone and shale
MS: Mudstone (limestone)
WS: Wackestone (limestone)
D: Dolomite
PS: Packstone-grainstone (limestone)
BS: Phylloid-algal bafflestone (limestone)
These facies aren't discrete, and gradually blend into one another. Some have neighboring facies that are rather close. Mislabeling within these neighboring facies can be expected to occur. The following table lists the facies, their abbreviated labels and their approximate neighbors.

Facies	Label	Adjacent Facies
1	SS	2
2	CSiS	1,3
3	FSiS	2
4	SiSh	5
5	MS	4,6
6	WS	5,7
7	D	6,8
8	PS	6,7,9
9	BS	7,8


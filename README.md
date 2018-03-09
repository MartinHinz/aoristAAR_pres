# aoristAAR_pres
Abstract for CAA 2018

Aoristic research in R: Correcting temporal categorizations in archaeology

When aggregating temporal data in archaeology, it is often the case that we have to deal with overlapping categories set in ordinal scale. Examples of such data are typological ‘dating’ or anthropological age categories. In order to make the ordinal categories comparable, they have to be transferred to a numeric scale. The usual solution to approach this problem could be termed „aoristic“: The temporal categories are allocated a certain time span, and each year within this time span is then assigned a value proportional to the time span of the category as a whole. However, with the help of simulations in R we will show that this approach is flawed, at least when the categories overlap. In such sequences, the temporal ranges where the categories overlap tend to be overemphasised, leading to estimates which are simply wrong. To overcome this problem we present „aoristAAR“, a function in R which down-weights such phases. We use aoristic raw data of archaeological cultural groupings as well as anthropological life tables (generated with „mortAAR“) and compare it with the results after normalisation with „aoristAAR“.

*Nils Müller-Scheeßel, Martin Hinz*
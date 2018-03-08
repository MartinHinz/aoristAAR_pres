# aoristAAR_pres
Abstract for CAA 2018

Aoristic research in R: Correcting temporal categorizations in archaeology

When aggregatng temporal data in archaeology, it is often the case that we have to deal with overlapping categories set in ordinal scale. Examples of such data are typological ‘dating’ or anthropological age categories. In order to make the ordinal categories comparable, they have to be transferred to a numeric scale. The usual soluton to approach this problem could be termed „aoristc“: The temporal categories are allocated a certain tme span, and each year within this tme span is then assigned a value proportional to the time span of the category as a whole. However, with the help of simulations in R we will show that this approach is flawed, at least when the categories overlap. In such sequences, the temporal ranges where the categories overlap tend to be overemphasised, leading to estimates which are simply wrong. To overcome this problem we present „aoristAAR“, a functon in R which downweights such phases. We use aoristc raw data of archaeological cultural groupings as well as anthropological life tables (generated with „mortAAR“) and compare it with the results afer normalizaton with „aoristAAR“.
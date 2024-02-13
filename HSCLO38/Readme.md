HSCLO38 is an ontologized genomic coordinate binning schema.  HSCLO38's purpose is to simplify the integration of genomic experimental data at different resolution scales within biomedical knowledge graphs. 

HSCLO38 defines chromosomal locations within the GRCh38 release for chr 1-22, X,Y and M. HSCLO38 provides 3,431,153 classes at five distinct resolution levels: whole chromosome, 1 megabase pair (Mbp), 100 kilobase pairs (kbp), 10 kbp, and 1 kbp. Each node within these class levels is interconnected to its scale parent and to the immediate neighbors on either side to support mapping and association between genomic datasets and features.

For example, the 1kbp element HSCLO38:chr1.20517001-20518000 is_a connected to its "scale parent" HSCLO38:chr1.20510001-20520000 as well as to the 5' neighbor HSCLO38:chr1.20516001-20517000 and 3' neighbor HSCLO38:chr1.20518001-20519000. 

Code for generating HSCLO38 can be found in this repository.

The actual edgelist for HSCLO38 can be found at https://osf.io/pe8v7/

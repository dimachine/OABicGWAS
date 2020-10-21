# Object-Attribute Biclustering for Elimination of Missing Genotypes in Ischemic Stroke Genome-Wide Data

# Abstract 
Missing genotypes can affect efficacy of the application of machine learning approaches to identify the risk genetic variants of common diseases and traits. The problem occurs when genotypic data are collected from different experiments with different DNA microarrays, each being characterised by its pattern of uncalled (missing) genotypes. This can prevent the machine learning classifier from assigning the classes correctly. To tackle this issue, we used well-developed notions of object-attribute biclusters and formal concepts that correspond to dense subrelations in the binary relation patients x SNPs. The code contains experimental results on applying a biclustering algorithm to a large real-world dataset collected for studying the genetic bases of ischemic stroke. The algorithm could identify large dense biclusters in the genotypic matrix for further processing, which in return significantly improved the quality of machine learning classifiers. The proposed algorithm was also able to generate biclusters for the whole dataset without size constraints in comparison to the In-Close4 algorithm for formal concepts generation.


# Data in archived numpy arrays: 

Before elimination: https://www.dropbox.com/s/ui5kgkjdrztovt2/X.tar.gz
After elimination: https://www.dropbox.com/s/yow78p9hhjko1m4/X_.tar.gz

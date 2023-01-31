# Computer Science assignment
Duplicate Detection method
1. Packages and data are imported
2. All functions are defined
3. Full_detection_model is runned to compute the F1, F1star and fractions of comparison
4. Here, model words are extracted using RegEx and binary vectors for each product are formed from 
    whether a model word is present in the product description. Afterwards, This binary matrix is minhashed, LSH is performed
    and candidates are evaluated. 
5. For 5 bootstraps and 4 different number of rows, the scores are computed which can thereafter be plot into a figure.

# Document-Summarizer

Its the implementation of the publised paper : https://www.aaai.org/ocs/index.php/AAAI/AAAI12/paper/viewFile/4991/5247

Document summarization is of great value to many real world applications, such as snippets generation for search results and news headlines generation. Traditionally, document summarization is implemented by extracting sentences that cover the main topics of a document with a minimum redundancy. In this project, we take a different perspective from data reconstruction and propose a novel framework named Document Summarization based on Data Reconstruction (DSDR). Specifically, our approach generates a summary which consist of those sentences that can best reconstruct the original document. To model the relationship among sentences, we introduce two objective functions: 
(1) linear reconstruction, which approximates the document by linear combinations of the selected sentences; 
(2) nonnegative linear reconstruction, which allows only additive, not subtractive, linear combinations. In this framework, the reconstruction error becomes a natural criterion for measuring the quality of the summary. For each objective function, we develop an efficient algorithm to solve the corresponding optimization problem. 
Extensive experiments on summarization benchmark data sets DUC 2006 and DUC 2007 demonstrate the effectiveness of our proposed approach

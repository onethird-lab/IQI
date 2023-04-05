# IQI
Java package for IQI calculation and DQ test
#===============================================
# command-line example: 
java -jar IQI.jar -DQ.test -input.pheno_1 phenotype_1.txt -input.pheno_0 phenotype_0.txt -input.geno_0 genotype_0.txt -input.geno_1 genotype_1.txt -output.IQI_0 IQI_0.txt -output.IQI_1 IQI_1.txt -output.eQe_test DQ_test_result.txt
#===============================================

Please put the input files to the same directory as software, open the dos interface and change to the directory of software to carry out DQ test using the command line (as the example). The result files will be generated in the same directory.
More details are in the website (http://www.onethird-lab.com/iqi/).

parameters:
	-input.pheno_1: Input the phenotype information of the case group;
	-input.pheno_0: Input the phenotype information of the control group;
	-input.geno_0: Input the SNP genotype data of the case group;
	-input.geno_1: Input the SNP genotype data of the control group;
	-output.IQI_0: Specify the file name of the IQI values of the SNP-phenotype pairs of all samples in the control group;
	-output.IQI_1: Specify the file name of the IQI values of the SNP-phenotype pairs of all samples in the case group;
	-output.eQe_test: Specify the file name of the results of DQ test.

#===============================================
 The input phenotype file : phenotype_0.txt and phenotype_1.txt
#===============================================

#===============================================
 The input genotype file : genotype_0.txt and genotype_1.txt
#===============================================

#===============================================
 The output IQI file : IQI_0.txt and IQI_1.txt
#===============================================

#===============================================
 The output result of DQ test file : DQ_test_result.txt
#===============================================

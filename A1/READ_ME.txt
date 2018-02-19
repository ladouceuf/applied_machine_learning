Here is a breif description of what each file contains:
-A1.1.1: 	#1.1 of A1
-A1.1.2: 	#1.2 of A1
-A1.2:	 	#2 of A1. I tweeked the hyperparameters(at the top of document) to complete 2.1,2.2 and 2.3 individually.
-A1.3.1-2: 	#3.1 and 3.2 of A1. They store their output files in the "out" folder as explained below
-A1.3.3: 	#3.3 of A1.

-out:	-3.1:	-This contains the completed (filled) Dataset_3
	-3.2:	-3.2_w_star.csv: This file contains the w parameters learnt in the 5 different splits of data.
		Each row represents a different dataset and the columns represent the feature number (w0,w1,...w122).
		-CandC: This folder contains the 5 different splits of data
	-3.3:	-3.3_w_star.csv: This file contains the best solution parameter for the dataset 3. Each row is a different
		feature (r1=w0, r2=w1,...)
-plots: This folder contains a picture of every plot that appears in the word doc.

How to use: 

1-Prepare the file with the data sets: (Or use the examples in exapleData folder)

	a- The first 4 numbers represent this data in this order: 
	    Number of data sets, number of input neurons,
            number of hidden neurons and number of outputs
        b-Afther 4 linejumps: The first input data for the neurons (The amount of numbers must much the input neurons amount)
	c-Afther 2 linejumps: The expected output (The amout of numbers must much the output neurons amount )
 	d-Jump to step b if the number of data sets is not over. 

	"See the data examples to undestand better how to creat your own training set"

2-Make your first traing with: 
	"See a Demo at the end of the file nn.py"

	NN.newtrain('inputDataSet', 'outputNeuralNetwork', NN-MAX-ERROR,  MAX-ITERATIONS, LEARNING-RATE, MOMENTUN-IMPORTANCE)

3-If you want to continue trainig: 
	
    	NN.train('inputDataSet', 'inputNeuralNetwork', 'outputNeuralNetwork', NN-MAX-ERROR,  MAX-ITERATIONS,LEARNING-RATE, MOMENTUN-IMPORTANCE)

4-If you want to test the NN with the dataset: 

	print NN.test('inputNeuralNetwork', 'inputDataSet' )


Notes: 

	Use small learning rates and momentum values under 0.01


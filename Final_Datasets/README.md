### Final Datasets for Capstone

These files were created using the cleanup scripts available [here](https://github.com/dbouquin/DATA_698/blob/master/data_vis_examples/data_cleanup_for_vis.ipynb). Each directory contains the files that were used to train an LSTM ANN using [torch](http://torch.ch/) and use the following structure:    
* discipline
	* subfolder named for discipline + _number; number = the nunber of titles included in training dataset
		* discipline_number.txt = training data
		* discipline_number_sample.txt = sample of 100 titles generated using LSTM trained on training data
		* discipline_number_sample1.txt = single sample title generated using LSTM trained on training data
		* screenshots showing torch commands run in the terminal to train and build sample of titles 
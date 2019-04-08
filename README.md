# Task_Project

### PYTHON Problem

A python script which can fetch all the tweets (as many as allowed by Twitter API) done by ​ midas@IIITD​ twitter handle and dump the responses into JSON lines file.
The other part parses these JSON line files to display the following for every tweet in a tabular format.
● The text of the tweet.
● Date and time of the tweet.
● The number of favorites/likes.
● The number of retweets.
● Number of Images present in Tweet. If no image returns None.


### Computer Vision Problem

The given dataset has 4 classes. Labels for training data are provided. It is a Classifier problem. I have used neural nets with pytorch support for gpu computation. 

## Prerequisites & Important Information

● This project task has 2 problems:
	  a. A python problem
	  b. A Computer Vision (CV) problem

● The Github Repository follows the following structure.
	  /root
	  |
	  |_/Pyhton_problem
	  |
	  |_/(CV/NLP)_Problem

● Code of each problem is in a Jupyter Notebook.

● Codes are properly documented.
	  a. Before each code block, a markdown block is there which mentions the following
		  i. What the code block is doing.
		  ii. What is the intuition behind doing this? Why it is useful?

● For python problem --
	    ● One will need oauth installed or have outh.py attached on my github repository 
	    ● One has to include hidden.py file containing keys for authentication
		    template:-
			  def oauth():
    		  return {"consumer_key": "......",
           				"consumer_secret": ".....",
           				"token_key": "......",
			            "token_secret": "....."}


● For CV problem -- 
	    CUDA, pytorch, and fastai (version < 1.0.0) should be installed

## Acknowledgements

● Jemremy Howard ( His fastai courses and practical learning motivation helped me a lot )
● Dr. Chuck Severence

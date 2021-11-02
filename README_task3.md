Task 3: Human Activity Recognition:

As the name suggests, identify and recognize human activity from a video
source and classify it based on the activity thus performed.
 
Dataset Link: http://www.cis.fordham.edu/wisdm/dataset.php

*The Dataset holds Accelerometer Data. The data is highly unbalanced and thus is downsampled to 3555 per activity available. 

*To train the model, we use 2D Convolutional Neural Networks.

*The loss function used is 'Sparse Categorical Entropy' and the metrics is 'accuracy'. We plot learning curves to demonstrate the accuracy and loss and conclude with a confusion matrix.

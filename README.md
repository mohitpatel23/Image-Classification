# Image-Classification

The training dataset consists of 18000 records and the test dataset consists of 3000 records. The attributes are floating point values and are presented in a dense matrix format within train.dat and test.dat. <br/>
- train.dat: Training set (dense matrix, samples/images in lines, features in columns).<br/>
- train.labels: Training class labels (integers, one per line).<br/>
- test.dat: Test set (dense matrix, samples/images in lines, features in columns).<br/>
- format.dat: A sample submission with 3000 entries randomly chosen to be 1-11.<br/>

Objective: Analyze features extracted from traffic images depicting different objects to determine their type as one of 11 classes, noted by integers 1-11: car, suv, small_truck, medium_truck, large_truck, pedestrian, bus, van, people, bicycle, and motorcycle. The object classes are heavily imbalanced. For example, the training data contains 8855 cars but only 2 bicycles and 0 people. Classes in the test data are similarly distributed. <br/>

Use/implement a feature selection/reduction technique and classify the dataset with a high F1 score.

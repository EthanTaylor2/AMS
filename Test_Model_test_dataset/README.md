# Test AMS model on test dataset

After training step, we can use the trained model to predict the result on test dataset.

See our own trained model:  [here](http://pan.baidu.com/s/1hrZxSiS)

password: 4sl3

------
## How to run the code
1. Use Apparance model to predict the result on test dataset. More details can be found in ./Appearance
2. Use Motion model to predict the result on test dataset. More details can be found in ./Motion
3. Use Skeleton model to predict the result on test dataset. More details can be found in ./Skeleton
4. Fusion these three models' result. More details can be found in ./Fusion

---------
## Implementation Details

1. Platform: TensorFlow 1.1.0 with cuda 8.0 and cudnn 5.1
2. GPU: GTX TITAN X 12GB of memory  
3. Memory required: 8GB  
4. Time: In our own test, we use 3 GPU in the same time, the expended time is about 25 hours.

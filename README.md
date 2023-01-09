# Object Detection

this Notebook provides a complete set of code to be able to train and leverage your own custom object detection model using the Tensorflow Object Detection API.
![plot](https://github.com/AliFayod/Object_detection/blob/master/plot/detect.jpg)


## How To

1. Clone this repository: https://github.com/AliFayod/Object_detection
2. Create a new virtual environment
```
python -m venv tf210
```

3. Activate your virtual environment
```
source tf210/bin/activate # Linux
.\tf210\Scripts\activate # Windows
```
4. Install dependencies and add virtual environment to the Python Kernel
```
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=tf210
```
5. Collect images using the instructions in the Notebook
6.Manually divide collected images into two folders train and test. So now all folders and annotations should be split between the following two folders.
\Tensorflow\workspace\images\train
\Tensorflow\workspace\images\test

7. Follow the rest instruction to start train the model on your data.

8. when you receive a notification indicating that the API has installed successfully with the stating OK, every thing will be work.
If not, resolve installation errors by referring to the [ErrorGuide.md](https://github.com/AliFayod/Object_detection/blob/master/ErrorGuide.md) in this file.

9. by following you will get command to train your model, hence use it in your command prompt after change your directory to the project path.

10. you will finish and will use your webcam and detect objects.

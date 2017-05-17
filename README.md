# Emotion-Recognition
This project creates a classification model in Machine Learning capable of recognizing human facial emotions.

## Getting Started

This project uses the CK+ dataset containing 8 classes of facial expressions encoded as {0=neutral, 1=anger, 2=contempt, 3=disgust, 4=fear, 5=happy, 6=sadness, 7=surprise}.

### Prerequisites

1. [CK+ dataset](http://www.consortium.ri.cmu.edu/ckagree/) - The dataset used
2. Python 2.7
3. OpenCV 3

### Installing

Clone the repository
```
git clone 'https://github.com/jahin07/Emotion-Recognition.git'
```
Download the CK+ dataset

Install OpenCV 3
```
conda install -c menpo opencv3=3.2.0
```

## Running the code

To run the code
```
python dataset_org.py
python extract_faces.py
python classi.py
```

## Authors

* **Jahin Majumdar** - [GitHub](https://github.com/jahin07)

## Reference
1. van Gent, P. (2016). Emotion Recognition With Python, OpenCV and a Face Dataset. A tech blog about fun things with Python and embedded electronics. Retrieved from: [here](http://www.paulvangent.com/2016/04/01/emotion-recognition-with-python-opencv-and-a-face-dataset/)
2. Kanade, T., Cohn, J. F., & Tian, Y. (2000). Comprehensive database for facial expression analysis. Proceedings of the Fourth IEEE International Conference on Automatic Face and Gesture Recognition (FG'00), Grenoble, France, 46-53.
3. Lucey, P., Cohn, J. F., Kanade, T., Saragih, J., Ambadar, Z., & Matthews, I. (2010). The Extended Cohn-Kanade Dataset (CK+): A complete expression dataset for action unit and emotion-specified expression. Proceedings of the Third International Workshop on CVPR for Human Communicative Behavior Analysis (CVPR4HB 2010), San Francisco, USA, 94-101.

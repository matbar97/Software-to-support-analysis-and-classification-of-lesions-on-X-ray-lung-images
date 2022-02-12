# Software-to-support-analysis-and-classification-of-lesions-on-X-ray-lung-images
This is the software to analyse and classify images of people lung X-rays (collected from kaggle, github) to 5 different diseases categories. The images differ from the processing type. The pretrained MobileNetV2, VGG19, ResNet50 and SVM with fine-tuning were used for this task. The results are deeply compared and analysed using confusion matrices, ROC Curves, classification reports (accuracy, precision, recall, f - score). The models behave very well and could be considerably helpful for radiologists in case of decision making.

Libraries: Tensorflow 2.x, keras, scikit-learn, seaborn, matplotlib, numpy, pandas, opencv.
Programming language: Python 3

# Machine Learning Specialization

My notes, labs, and projects from the Machine Learning Specialization (DeepLearning.AI on Coursera), organized by course and week.

## Courses
- `course-1-supervised-ml`: Supervised Machine Learning: Regression and Classification
- `course-2-advanced-learning-algorithms`: Advanced Learning Algorithms (neural networks, TensorFlow)
- `course-3-unsupervised-recommenders-rl`: Unsupervised Learning, Recommenders, Reinforcement Learning

## Projects
### [Handwritten Digit Classifier: 0 vs 1](projects/digit-classifier-0-vs-1)
A neural network in TensorFlow (784 → 25 → 15 → 1, sigmoid) trained on Kaggle's Digit Recognizer data, with a hand-written 80/20 train/test split.

**Result:** 1763 of 1764 unseen test images classified correctly (99.94%).

This is a binary (0 vs 1) classifier, not full ten-digit recognition.

**Dataset:** [Kaggle Digit Recognizer](https://www.kaggle.com/c/digit-recognizer). `train.csv` is not included here, so download it from Kaggle to run the notebook.

<h2>Facial Expression Recognition (FER) using Deep Learning</h2>

<p>
This project implements a deep learning–based <strong>Facial Expression Recognition (FER)</strong> system developed as part of the
<em>IT461 – Practical Machine Learning</em> course at King Saud University.
The goal is to automatically classify human facial expressions into seven emotion categories:
Anger, Disgust, Fear, Happiness, Sadness, Surprise, and Neutral.
</p>

<h3>Overview</h3>
<p>
The system formulates FER as a multi-class supervised learning problem using grayscale facial images
from the <strong>FER-2013</strong> dataset. Multiple neural network architectures were designed, trained, and evaluated
to compare performance and generalization.
</p>

<h3>Models Implemented</h3>
<ul>
  <li>Baseline Fully Connected Neural Network</li>
  <li>Baseline Convolutional Neural Network (CNN)</li>
  <li><strong>Enhanced CNN</strong> with Batch Normalization, Global Average Pooling, and AdamW optimizer</li>
  <li>Fine-tuned <strong>VGG-16</strong> transfer learning model</li>
</ul>

<h3>Results</h3>
<p>
The <strong>Enhanced CNN</strong> achieved the best performance with a validation accuracy of
<strong>66.43%</strong>, outperforming the baseline CNN and transfer learning model.
The results highlight the importance of architectural depth and regularization for effective
facial expression recognition on challenging datasets.
</p>

<h3>Technologies Used</h3>
<ul>
  <li>Python</li>
  <li>TensorFlow / Keras</li>
  <li>Deep Learning &amp; Computer Vision</li>
  <li>Google Colab (GPU)</li>
  <li>FER-2013 Dataset</li>
</ul>

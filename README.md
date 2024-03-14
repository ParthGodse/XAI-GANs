# Deepfake Audio Detection using XAI-GANs

Created our own deep faked audio using Generative Adversarial Neural Networks (GANs) and objectively evaluate generator quality using Fréchet Audio Distance (FAD) metric. We augment a pre-existing dataset of real audio samples with our fake generated samples and classify data as real or fake using MobileNet, Inception, VGG and custom CNN models. MobileNet is the best performing model with an accuracy of 91.5% and precision of 0.507. We further convert our black box deep learning models into white box models, by using explainable AI (XAI) models. We quantitatively evaluate the classification of a MEL Spectrogram through LIME, SHAP and GradCAM models. We compare the features of a spectrogram that an XAI model focuses on to provide a qualitative analysis of frequency distribution in spectrograms. Used StreamLit for demonstration purpose where you can select any audio file from the dataset and then convert it to spectogram and run models and XAI technqiues giving results at the same time.

## Tech Stack 

Programming Language : Python\n
Libraries : Tensorflow, Keras, Sci-kit Learn, Matplotlib, Pandas, Numpy
Models : MobileNet, VGG16, Inception, Custom CNN
Explainable AI (XAI) methods : SHAP, LIME, GradCam
Additional Softwares : StreamLit

## Data

Fake-or-Real dataset from York Univeristy containing sample audio files which are real and some which were generated by adversarial networks. Sample Spectogram image converted from audio signal file denoting frequency distribution as a heatmap.

![image](https://github.com/ParthGodse/XAI-GANs/assets/98154485/9a9839bd-38f1-4429-b6cf-7331525899e4)

## System Design 

![image](https://github.com/ParthGodse/XAI-GANs/assets/98154485/b95031f5-0de6-493c-8fa5-1f8276dab211)

## Results

![image](https://github.com/ParthGodse/XAI-GANs/assets/98154485/da07a3e6-dc4a-4773-8cc2-3001b89a2e3a)

## Spectogram results after applying Explainable AI

![image](https://github.com/ParthGodse/XAI-GANs/assets/98154485/a4e86bc9-d9d9-4f5c-bfc9-983b3e05bba8)

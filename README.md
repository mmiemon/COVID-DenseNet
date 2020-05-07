Coronavirus disease (COVID-19) is a pandemic
infectious disease that has a severe risk of spreading rapidly.
The quick identification and isolation of the affected persons is
the very first step to fight against this virus. In this regard,
chest radiology images have been proven to be an effective
screening approach of COVID-19 affected patients. A number
of AI based solutions have been developed to make the screening
of radiological images faster and more accurate in detecting
COVID-19. In this study, we are proposing a deep learning
based approach using Densenet-121 to effectively detect COVID-
19 patients. We incorporated transfer learning technique to
leverage the information regarding radiology image learned by
another model (CheXNet) which was trained on a huge Radiology
dataset of 112,120 images. We trained and tested our model
on COVIDx dataset containing 13,800 chest radiography images
across 13,725 patients. To check the robustness of our model,
we performed both two-class and three-class classifications and
achieved 96.49% and 93.71% accuracy respectively. To further
validate the consistency of our performance, we performed
patient-wise k-fold cross-validation and achieved an average
accuracy of 92.91% for three class task. Moreover, we performed
an interpretability analysis using Grad-CAM to highlight the
most important image regions in making a prediction. Besides
ensuring trustworthiness, this explainability can also provide new
insights about the critical factors regarding COVID-19. Finally,
we developed a website that takes chest radiology images as
input and generates probabilities of the presence of COVID-19
or pneumonia and a heatmap highlighting the probable infected
regions.

Code for twoclass, three class, and patient-wise cross-validation classification is given in the notebooks. 

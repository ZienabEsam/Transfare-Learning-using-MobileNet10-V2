# Transfare-Learning-using-MobileNet10-V2
Implementation of CNN transfare Learning using base model MobileNetV2 
Transfare learning is using a stored konwlage of earlier modules to solve
other problemsa like ImageNet.

It's used mostly in NLP and computer vision.
It's more of a design methodology 
-----------------------------------------------------------------------------------------
Fine tuning in turn is suited for bigger dataset
in fine tuning we don't freez the whole model, otherwise we only freez half of the model and the other half is trained by the custom 
dataset && i general.
to choose wether to use Trasnfare Learning of Fine Tuning :
1.If you have a large and verry different dataset than used in the Base model you use Transfare Learning
-------------------------------------------------------------------------------------------------------------
2.If you have Large and similar dataset from the base model you use fine tuning for training
-----------------------------------------------------------------------------------------------
3.If you have samll and different dataset from the base model you use fine tuning
-------------------------------------------------------------------------------------------------
4.If you have samll and similar dataset from base model you use transfare learning
-------------------------------------------------------------------------------------------------

for more about machine learning and CNN visit my blog Enjoy Engineering:
https://enjoyengineerings.blogspot.com/

# NST-for-Data-Augmentation

En la sociedad actual el uso de filtros y de técnicas que modifiquen el estilo de imágenes es muy común, es allí donde surge la necesidad de que los modelos de clasificación sean robustos a estas transformaciones. Los códigos dispuestos en este repositorio permiten replicar los resultados obtenidos al utilizar la técnica de style transfer como método de data augmentation para mejorar la capacidad de generalización en modelos de clasificación de imágenes, ganando alrededor de 2% de accuracy promedio con respecto al modelo original en una base de datos derivada de ’AnimalFaces’, que contenía imágenes alteradas en estilo con la técnica de style transfer.

Referencias

[1] Gatys, Leon A., Alexander S. Ecker, and Matthias Bethge. ”Image style transfer using convolutional neural networks.” Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2016.
[2] Philip T. Jackson, Amir Atapour-Abarghouei, Stephen Bonner, Toby Breckon, Boguslaw Obara. ”Style Augmentation: Data Augmentation via Style Randomization.” Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops, 2019.
[3] Animal Faces Dataset. Disponible en: https://www.kaggle.com/andrewmvd/animal-faces. 
[4] SGD Pytorch. Disponible en: https://pytorch.org/docs/stable/generated/torch.optim.SGD.html. 
[5] Neural Transfer Using Pytorch. Disponible en: https://pytorch.org/tutorials/advanced/neural_style_tutorial.html.
[6] Transfer Learning For Computer Vision Tutorial. Disponible en: https: //pytorch.org/tutorials/beginner/transfer_learning_tutorial.html.
[7] Neural Networks. Disponible en: https://pytorch.org/tutorials/beginner/blitz/neural_networks_tutorial.html.
[8] How To Find Test Accuracy AfterTraining [En l´ınea]. Disponible en:https://discuss.pytorch.org/t/how-to-find-test-accuracy-after-training/88962.

(Optional) The StyleGAN Paper

Amazed by StyleGAN's capabilities? Take a look at the original paper! Note that it may take a few extra moments to load because of the high-resolution images.
A Style-Based Generator Architecture for Generative Adversarial Networks (Karras, Laine, and Aila, 2019): https://arxiv.org/abs/1812.04948
(Optional) StyleGAN Walkthrough and Beyond

Want another explanation of StyleGAN? This article provides a great walkthrough of StyleGAN and even discusses StyleGAN's successor: StyleGAN2!
GAN — StyleGAN & StyleGAN2 (Hui, 2020): https://medium.com/@jonathan_hui/gan-stylegan-stylegan2-479bdf256299
(Optional Notebook) Finetuning Notebook: FreezeD

Notebook: https://colab.research.google.com/github/https-deeplearning-ai/GANs-Public/blob/master/C2W3_FreezeD_(Optional).ipynb
Please note that this is an optional notebook meant to introduce more advanced concepts. If you’re up for a challenge, take a look and don’t worry if you can’t follow everything. There is no code to implement—only some cool code for you to learn and run!
In this notebook, you'll learn about and implement the fine-tuning approach proposed in Freeze the Discriminator: a Simple Baseline for Fine-Tuning GANs (Mo et al. 2020), which introduces the concept of freezing the upper layers of the discriminator in fine-tuning. Specifically, you'll fine-tune a pretrained StyleGAN to generate anime faces from human faces.
Due to the size and dependence on recent PyTorch features (e.g. Automatic Mixed Precision (AMP)), this is provided as a Colab notebook. 

Works Cited

All of the resources cited in Course 2 Week 3, in one place. You are encouraged to explore these papers/sites if they interest you! They are listed in the order they appear in the lessons.
From the videos:
* Generative Adversarial Networks (Goodfellow et al., 2014): https://arxiv.org/abs/1406.2661
* Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks (Radford, Metz, and Chintala, 2016): https://arxiv.org/abs/1511.06434
* Coupled Generative Adversarial Networks (Liu and Tuzel, 2016): https://arxiv.org/abs/1606.07536
* Progressive Growing of GANs for Improved Quality, Stability, and Variation (Karras, Aila, Laine, and Lehtinen, 2018): https://arxiv.org/abs/1710.10196
* A Style-Based Generator Architecture for Generative Adversarial Networks (Karras, Laine, and Aila, 2019): https://arxiv.org/abs/1812.04948
* The Unusual Effectiveness of Averaging in GAN Training (Yazici et al., 2019): https://arxiv.org/abs/1806.04498v2
* Progressive Growing of GANs for Improved Quality, Stability, and Variation (Karras, Aila, Laine, and Lehtinen, 2018): https://arxiv.org/abs/1710.10196
* StyleGAN - Official TensorFlow Implementation (Karras et al., 2019): https://github.com/NVlabs/stylegan
* StyleGAN Faces Training (Branwen, 2019): https://www.gwern.net/images/gan/2019-03-16-stylegan-facestraining.mp4
* Facebook AI Proposes Group Normalization Alternative to Batch Normalization (Peng, 2018): https://medium.com/syncedreview/facebook-ai-proposes-group-normalization-alternative-to-batch-normalization-fb0699bffae7


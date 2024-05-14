# MS-RGCN
Multi-scale relational graph convolutional network (MS-RGCN) for histopathology images of prostate cancer

# How to run
Use the following order of folders and their code based on your data
1. multiscale_patch_extractor: To extract patches
2. color_normalizer: To normalize the color in order to use the (Bazargani et al.,2023) color augmentation
3. feature_extractor_6class: First use ResNet.ipynb to train the model and then, get_embeddings.ipynb to get the embeddings
4. GNN_multiscale_ResNet_PANDA: Run graph_multi_magnification.ipynb to generate the graphs based on extracted features and their locations in the patch images name. Next, run main_advanced.ipynb to train the model.

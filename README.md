The procedure for determining the cause for strokes makes heavy use of computed tomographic (CT) images. 
The existing methods try different Machine Learning (ML) based methods but haven’t so far explored the self-supervised learning approach. 
In this study we showcase a simple technique for improving the feature representation generated using Deep learning models through self-supervised technique. 
We utilized (triplet) loss for generating different embeddings for normal and acute stroke cases and developed a simple strategy to improve the same for better differentiability. 
We showcase this refining technique improves the discriminability and is able to classify using simple Machine Learning model. 
The results are tested against different DL models for better generality with the best begin ResNetV2 101 with 95.16% accuracy. 
We also compare the results based on different levels of refinement based on their architecture. We feel this is the first study on such approach applied to this domain.

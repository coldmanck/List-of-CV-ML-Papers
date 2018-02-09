# List-of-CV-ML-Papers
My curated list of CV/ML papers.

## Index
- [Computer Vision]()
  - [Image Classification]()
  - [Object Detection]()
  - [Semantic Segmentation]()
  - [Image Captioning]()
    - [*Attention* Image Captioning]()
    - [Where Is *Attention* From]()
    - [Why should classifier attend to objects and salient image regions]()
    - [Semantic Attention Mechanisms (Bottom Up + Top Down, but no spatial information)]()
    - [Bottom up + Top Down Attention (with spatial information)]()
    - [Variants of Attention Mechanism: Stacked, Multi-headed, Bidirectional Attention (also for VQA)]()
  - [Visual Question Answering]()
  - [Visualizing CNN]()
  - [Deeper representations in CNN capture higher-level visual constructs]()
- [Machine Learning]()

## Computer Vision
### Image Classification
- J. Deng, W. Dong, R. Socher, L.-J. Li, K. Li, and L. Fei-Fei. ImageNet: A Large-Scale Hierarchical Image Database. In CVPR, 2009.
- A. Krizhevsky, I. Sutskever, and G. E. Hinton. Imagenet classification with deep convolutional neural networks. In NIPS, 2012.
- K. He, X. Zhang, S. Ren, and J. Sun. Deep residual learning for image recognition. In CVPR, 2016

### Object Detection
- R. Girshick, J. Donahue, T. Darrell, and J. Malik. Rich Feature Hierarchies for Accurate Object Detection and Semantic Segmentation. In CVPR, 2014.

### Semantic Segmentation
- J. Long, E. Shelhamer, and T. Darrell. Fully convolutional networks for semantic segmentation. In CVPR, 2015.

### Image Captioning
- O. Vinyals, A. Toshev, S. Bengio, and D. Erhan. Show and tell: A neural image caption generator. In CVPR, 2015.
- X. Chen, H. Fang, T.-Y. Lin, R. Vedantam, S. Gupta, P. Dollár, and C. L. Zitnick. Microsoft COCO captions: Data Collection and Evaluation Server. arXiv preprint arXiv:1504.00325, 2015.
- H. Fang, S. Gupta, F. Iandola, R. K. Srivastava, L. Deng, P. Dollár, J. Gao, X. He, M. Mitchell, J. C. Platt, et al. From Captions to Visual Concepts and Back. In CVPR, 2015.
- J. Johnson, A. Karpathy, and L. Fei-Fei. DenseCap: Fully Convolutional Localization Networks for Dense Captioning. In CVPR, 2016.

#### *Attention* Image Captioning
- S. J. Rennie, E. Marcheret, Y. Mroueh, J. Ross, and V. Goel. Self-critical sequence training for image captioning. In CVPR, 2017.
- J. Lu, C. Xiong, D. Parikh, and R. Socher. Knowing when to look: Adaptive attention via a visual sentinel for image captioning. In CVPR, 2017.
- Z. Yang, Y. Yuan, Y. Wu, R. Salakhutdinov, and W. W. Cohen. Review networks for caption generation. In NIPS, 2016.
- K. Xu, J. Ba, R. Kiros, K. Cho, A. C. Courville, R. Salakhutdinov, R. S. Zemel, and Y. Bengio. Show, attend and tell: Neural image caption generation with visual attention. In ICML, 2015.

#### Where Is *Attention* From
- T. J. Buschman and E. K. Miller. Top-down versus bottom-up control of attention in the prefrontal and posterior parietal cortices. Science, 315(5820):1860–1862, 2007.
- M. Corbetta and G. L. Shulman. Control of goal-directed and stimulus-driven attention in the brain. Nature Reviews Neuroscience, 3(3):201–215, 2002.

#### Why should classifier attend to objects and salient image regions
- R. Egly, J. Driver, and R. D. Rafal. Shifting visual attention between objects and locations: evidence from normal and parietal lesion subjects. Journal of Experimental Psychology: General, 123(2):161, 1994.
- B. J. Scholl. Objects and attention: The state of the art. Cognition, 80(1):1–46, 2001.

#### Semantic Attention Mechanisms (Bottom Up + Top Down, but no spatial information)
- Q. You, H. Jin, Z. Wang, C. Fang, and J. Luo. Image captioning with semantic attention. In CVPR, 2016.
- Y. Yu, H. Ko, J. Choi, and G. Kim. End-to-end concept word detection for video captioning, retrieval, and question answering. In CVPR, 2017.

#### Bottom up + Top Down Attention (with spatial information)
- P. Anderson, X. He, C. Buehler, D. Teney, M. Johnson, S. Gould, and L. Zhang. Bottom-up and top-down attention for image captioning and vqa. arXiv preprint arXiv:1707.07998, 2017.
- J. Jin, K. Fu, R. Cui, F. Sha, and C. Zhang. Aligning where to see and what to tell: image caption with region-based attention and scene factorization. arXiv preprint arXiv:1506.06272, 2015.
- M. Pedersoli, T. Lucas, C. Schmid, and J. Verbeek. Areas of attention for image captioning. arXiv preprint arXiv:xxxx, 2015.

#### Variants of Attention Mechanism: Stacked, Multi-headed, Bidirectional Attention (also for VQA)
- Z. Yang, X. He, J. Gao, L. Deng, and A. J. Smola. Stacked attention networks for image question answering. In CVPR, 2016.
- A. Jabri, A. Joulin, and L. van der Maaten. Revisiting visual question answering baselines. arXiv preprint arXiv:1606.08390, 2016.
- V. Kazemi and A. Elqursh. Show, ask, attend, and answer: A strong baseline for visual question answering. arXiv preprint arXiv:1704.03162, 2017.
- J. Lu, J. Yang, D. Batra, and D. Parikh. Hierarchical question-image co-attention for visual question answering. In NIPS, 2016.

#### "Soft" Top-Down Attention
- S. J. Rennie, E. Marcheret, Y. Mroueh, J. Ross, and V. Goel. Self-critical sequence training for image captioning. In CVPR, 2017.
- J. Lu, C. Xiong, D. Parikh, and R. Socher. Knowing when to look: Adaptive attention via a visual sentinel for image captioning. In CVPR, 2017.
- K. Xu, J. Ba, R. Kiros, K. Cho, A. C. Courville, R. Salakhutdinov, R. S. Zemel, and Y. Bengio. Show, attend and tell: Neural image caption generation with visual attention. In ICML, 2015.

### Visual Question Answering
- S. Antol, A. Agrawal, J. Lu, M. Mitchell, D. Batra, C. Lawrence Zitnick, and D. Parikh. VQA: Visual Question Answering. In ICCV, 2015.
- H. Gao, J. Mao, J. Zhou, Z. Huang, L. Wang, and W. Xu. Are You Talking to a Machine? Dataset and Methods for Multilingual Image Question Answering. In NIPS, 2015.
- M. Malinowski, M. Rohrbach, and M. Fritz. Ask your neurons: A neural-based approach to answering questions about images. In ICCV, 2015.
- M. Ren, R. Kiros, and R. Zemel. Exploring models and data for image question answering. In NIPS, 2015.

### Visualizing CNN
- K. Simonyan, A. Vedaldi, and A. Zisserman. Deep inside convolutional networks: Visualising image classification models and saliency maps. CoRR, abs/1312.6034, 2013.
- J. T. Springenberg, A. Dosovitskiy, T. Brox, and M. A. Riedmiller. Striving for Simplicity: The All Convolutional Net. CoRR, abs/1412.6806, 2014.
- M. D. Zeiler and R. Fergus. Visualizing and understanding convolutional networks. In ECCV, 2014.
- C. Gan, N. Wang, Y. Yang, D.-Y. Yeung, and A. G. Hauptmann. Devnet: A deep event network for multimedia event detection and evidence recounting. In CVPR, 2015.
- A. Mahendran and A. Vedaldi. Salient deconvolutional networks. In European Conference on Computer Vision, 2016. (Comparison Report)

### Deeper representations in CNN capture higher-level visual constructs
- Y.Bengio,A.Courville,andP.Vincent.Representationlearning:A review and new perspectives. IEEE transactions on pattern analysis and machine intelligence, 35(8):1798–1828, 2013
- A. Mahendran and A. Vedaldi. Visualizing deep convolutional neural networks using natural pre-images. International Journal of Computer
Vision, pages 1–23, 2016.

### LSTM for Visual Recognition
- S. Hochreiter and J. Schmidhuber. Long short-term memory. Neural Computation, 1997
- J. Donahue, L. A. Hendricks, S. Guadarrama, M. Rohrbach, S. Venugopalan, K. Saenko, and T. Darrell. Long-term recurrent convolutional networks for visual recognition and description. In CVPR, 2015.

## Machine Learning

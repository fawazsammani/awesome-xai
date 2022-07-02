# Awesome Explainable AI [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Simply imagine a bank system rejecting an application based on "shoe color" of the customer. Or a self-driving car which has always seen a tree next to a red traffic light and therefore the decision to stop at the red light is based on a tree being present. Or an object detector which detects "horses" because of a watermark at the bottom of the image, simply because all "horse" training data had this watermark. These are actually real stories that happened, and the need of Explainable AI (XAI) is now a must.

If you find some overlooked papers, please open issues or pull requests, and provide the paper(s) in this format:
```
- **[]** Paper Name [[pdf]]() [[code]]()
```

## Papers
- Visualizing and Understanding Convolutional Networks [[pdf]](https://arxiv.org/pdf/1311.2901.pdf)
- Deep Inside Convolutional Networks: Visualising Image Classification Models and Saliency Maps [[pdf]](https://arxiv.org/pdf/1312.6034.pdf) [[saliency code]](https://github.com/sunnynevarekar/pytorch-saliency-maps)
- Striving for Simplicity: The All Convolutional Net [[pdf]](https://arxiv.org/pdf/1412.6806.pdf)
- Understanding Neural Networks Through Deep Visualization [[pdf]](https://arxiv.org/pdf/1506.06579.pdf)
- Understanding Deep Image Representations by Inverting Them [[pdf]](https://arxiv.org/pdf/1412.0035.pdf)
- Visualizing deep convolutional neural networks using natural pre-images [[pdf]](https://arxiv.org/pdf/1512.02017.pdf)
- Interpretable Explanations of Black Boxes by Meaningful Perturbation [[pdf]](https://arxiv.org/pdf/1704.03296.pdf) [[code]](https://github.com/jacobgil/pytorch-explain-black-box)
- Top-down Neural Attention by Excitation Backprop [[pdf]](https://arxiv.org/pdf/1608.00507.pdf)
- Salient Deconvolutional Networks [[pdf]](https://www.robots.ox.ac.uk/~vedaldi/assets/pubs/mahendran16salient.pdf)
- Explaining and Harnessing Adversarial Examples [[pdf]](https://arxiv.org/pdf/1412.6572.pdf) [[code]](https://www.tensorflow.org/tutorials/generative/adversarial_fgsm) [[code]](https://github.com/Harry24k/FGSM-pytorch) [[code]](https://pytorch.org/tutorials/beginner/fgsm_tutorial.html)
- Adversarial Training for Free! [[pdf]](https://arxiv.org/pdf/1904.12843.pdf) [[code]](https://github.com/mahyarnajibi/FreeAdversarialTraining) [[video]](https://www.youtube.com/watch?v=v8U9mM1Vwv0&ab_channel=AminJun)
- Towards Deep Learning Models Resistant to Adversarial Attacks [[pdf]](https://arxiv.org/pdf/1706.06083.pdf) [[code]](https://github.com/MadryLab/mnist_challenge)
- Intriguing properties of neural networks [[pdf]](https://arxiv.org/pdf/1312.6199.pdf)
- Robustness May Be at Odds with Accuracy [[pdf]](https://arxiv.org/pdf/1805.12152.pdf) [[code]](https://github.com/ylsung/pytorch-adversarial-training)
- High Confidence Predictions for Unrecognizable Images [[pdf]](https://arxiv.org/pdf/1412.1897.pdf)
- Visualizing Higher-Layer Features of a Deep Network [[pdf]](https://www.researchgate.net/publication/265022827_Visualizing_Higher-Layer_Features_of_a_Deep_Network)
- Towards better understanding of gradient-based attribution methods for Deep Neural Networks [[pdf]](https://arxiv.org/pdf/1711.06104.pdf)
- On the (In)fidelity and Sensitivity of Explanations [[pdf]](https://arxiv.org/pdf/1901.09392.pdf) [[code]](https://github.com/chihkuanyeh/saliency_evaluation)
- Interpretation of Neural Networks is Fragile [[pdf]](https://arxiv.org/pdf/1710.10547.pdf)
- Adversarial Token Attacks on Vision Transformers [[pdf]](https://arxiv.org/pdf/2110.04337.pdf)
- A Benchmark for Interpretability Methods in Deep Neural Networks [[pdf]](https://arxiv.org/pdf/1806.10758.pdf)
- On the Robustness of Interpretability Methods [[pdf]](https://arxiv.org/pdf/1806.08049.pdf)
- Sanity Checks for Saliency Maps [[pdf]](https://arxiv.org/pdf/1810.03292.pdf)
- Relative Attributing Propagation: Interpreting the Comparative Contributions of Individual Units in Deep Neural Networks [[pdf]](https://arxiv.org/pdf/1904.00605.pdf)
- Transformer Interpretability Beyond Attention Visualization [[pdf]](https://arxiv.org/pdf/2012.09838.pdf) [[code]](https://github.com/hila-chefer/Transformer-Explainability) [[video]](https://www.youtube.com/watch?v=a0O_QhE9XFM&ab_channel=DataScienceBond)
- Investigating the influence of noise and distractors on the interpretation of neural networks [[pdf]](https://arxiv.org/pdf/1611.07270.pdf)
- Generic Attention-model Explainability for Interpreting Bi-Modal and Encoder-Decoder Transformers [[pdf]](https://arxiv.org/pdf/2103.15679.pdf) [[code]](https://github.com/hila-chefer/Transformer-MM-Explainability) 
- Visualization of Supervised and Self-Supervised Neural Networks via Attribution Guided Factorization [[pdf]](https://arxiv.org/pdf/2012.02166.pdf) [[code]](https://github.com/shirgur/AGFVisualization)
- Do Explanations Explain? Model Knows Best [[pdf]](https://arxiv.org/pdf/2203.02269.pdf) [[code]](https://github.com/CAMP-eXplain-AI/Do-Explanations-Explain)
- Visualizing Deep Neural Network Decisions: Prediction Difference Analysis [[pdf]](https://arxiv.org/pdf/1702.04595.pdf) [[code]](https://github.com/lmzintgraf/DeepVis-PredDiff)
- Visualizing and Understanding Generative Adversarial Networks [[pdf]](https://arxiv.org/pdf/1811.10597.pdf) [[code]](https://github.com/CSAILVision/GANDissect) [[website]](http://gandissect.csail.mit.edu/)
- Network Dissection: Quantifying Interpretability of Deep Visual Representations [[pdf]](https://arxiv.org/pdf/1704.05796.pdf) [[code]](https://github.com/CSAILVision/NetDissect) [[website]](http://netdissect.csail.mit.edu/)
- Deep Image Prior [[pdf]](https://arxiv.org/pdf/1711.10925.pdf) [[code]](https://github.com/DmitryUlyanov/deep-image-prior) [[website]](https://dmitryulyanov.github.io/deep_image_prior)
- Breaking Batch Normalization for better explainability of Deep Neural Networks through Layer-wise Relevance Propagation [[pdf]](https://arxiv.org/pdf/2002.11018.pdf)
- Revisiting The Evaluation of Class Activation Mapping for Explainability: A Novel Metric and Experimental Analysis [[pdf]](https://arxiv.org/pdf/2104.10252.pdf)
- A Framework for Learning Ante-hoc Explainable Models via Concepts [[pdf]](https://arxiv.org/pdf/2108.11761.pdf)
- Explaining image classifiers by removing input features using generative models [[pdf]](https://arxiv.org/pdf/1910.04256.pdf) [[code]](https://github.com/anguyen8/generative-attribution-methods)
- Building Reliable Explanations of Unreliable Neural Networks: Locally Smoothing Perspective of Model Interpretation [[pdf]](https://arxiv.org/pdf/2103.14332.pdf)
- Do Vision Transformers See Like Convolutional Neural Networks? [[pdf]](https://arxiv.org/pdf/2108.08810.pdf)
- Explaining Classifiers using Adversarial Perturbations on the Perceptual Ball [[pdf]](https://arxiv.org/pdf/1912.09405.pdf)
- Explaining Knowledge Distillation by Quantifying the Knowledge [[pdf]](https://arxiv.org/pdf/2003.03622.pdf)
- Interpreting Super-Resolution Networks with Local Attribution Maps [[pdf]](https://arxiv.org/pdf/2011.11036.pdf)
- Is the deconvolution layer the same as a convolutional layer? [[pdf]](https://arxiv.org/ftp/arxiv/papers/1609/1609.07009.pdf)
- Towards Human-Understandable Visual Explanations: Imperceptible High-frequency Cues Can Better Be Removed [[pdf]](https://arxiv.org/pdf/2104.07954.pdf)
- Pitfalls of Explainable ML: An Industry Perspective [[pdf]](https://arxiv.org/pdf/2106.07758.pdf)
- Do Feature Attribution Methods Correctly Attribute Features? [[pdf]](https://arxiv.org/pdf/2104.14403.pdf)
- Look at the Variance! Efficient Black-box Explanations with Sobol-based Sensitivity Analysis [[pdf]](https://arxiv.org/pdf/2111.04138.pdf)
- The effectiveness of feature attribution methods and its correlation with automatic evaluation scores [[pdf]](https://arxiv.org/pdf/2105.14944.pdf)
- Interpreting Deep Neural Networks with Relative Sectional Propagation by Analyzing Comparative Gradients and Hostile Activations [[pdf]](https://arxiv.org/pdf/2012.03434.pdf)
- The (Un)reliability of saliency methods [[pdf]](https://arxiv.org/pdf/1711.00867.pdf)
- Explaining Convolutional Neural Networks through Attribution-Based Input Sampling and Block-Wise Feature Aggregation [[pdf]](https://arxiv.org/pdf/2010.00672.pdf)
- Explainable Models with Consistent Interpretations [[pdf]](https://web.cs.ucdavis.edu/~hpirsiav/papers/gc_aaai21.pdf) [[code]](https://github.com/UMBCvision/Explainable-Models-with-Consistent-Interpretations)
- Interpreting Multivariate Shapley Interactions in DNNs [[pdf]](https://arxiv.org/pdf/2010.05045.pdf)
- Scaling Symbolic Methods using Gradients for Neural Model Explanation [[pdf]](https://arxiv.org/pdf/2006.16322.pdf) [[code]](https://github.com/google-research/google-research/tree/master/smug_saliency)
- Finding and Fixing Spurious Patterns with Explanations [[pdf]](https://arxiv.org/pdf/2106.02112.pdf) 
- Rethinking the Role of Gradient-Based Attribution Methods for Model Interpretability [[pdf]](https://arxiv.org/pdf/2006.09128.pdf)
- Revisiting Backpropagation Saliency Methods [[pdf]](https://arxiv.org/pdf/2004.02866.pdf)
- Towards Visually Explaining Variational Autoencoders [[pdf]](https://arxiv.org/pdf/1911.07389.pdf)
- Understanding Integrated Gradients with SmoothTaylor for Deep Neural Network Attribution [[pdf]](https://arxiv.org/pdf/2004.10484.pdf)
- Understanding Deep Networks via Extremal Perturbations and Smooth Masks [[pdf]](https://arxiv.org/pdf/1910.08485.pdf)
- Interpretable and Fine-Grained Visual Explanations for Convolutional Neural Networks [[pdf]](https://arxiv.org/pdf/1908.02686.pdf)
- Towards Robust Interpretability with Self-Explaining Neural Networks [[pdf]](https://arxiv.org/pdf/1806.07538.pdf)
- Influence-Directed Explanations for Deep Convolutional Networks [[pdf]](https://arxiv.org/pdf/1802.03788.pdf)
- Interpretable Basis Decomposition for Visual Explanation [[pdf]](https://openaccess.thecvf.com/content_ECCV_2018/papers/Antonio_Torralba_Interpretable_Basis_Decomposition_ECCV_2018_paper.pdf) [[code]](https://github.com/CSAILVision/IBD)
- Real Time Image Saliency for Black Box Classifiers [[pdf]](https://arxiv.org/pdf/1705.07857.pdf)
- Grounding Visual Explanations [[pdf]](https://arxiv.org/pdf/1807.09685.pdf)
- Bias Also Matters: Bias Attribution for Deep Neural Network Explanation [[pdf]](http://proceedings.mlr.press/v97/wang19p/wang19p.pdf)
- Understanding Impacts of High-Order Loss Approximations and Features in Deep Learning Interpretation [[pdf]](https://arxiv.org/pdf/1902.00407.pdf)
- On the Connection Between Adversarial Robustness and Saliency Map Interpretability [[pdf]](https://arxiv.org/pdf/1905.04172.pdf)
- Explaining Deep Neural Networks with a Polynomial Time Algorithm for Shapley Values Approximation [[pdf]](https://arxiv.org/pdf/1903.10992.pdf)
- Towards Automatic Concept-based Explanations [[pdf]](https://arxiv.org/pdf/1902.03129.pdf)
- Visualizing Deep Similarity Networks [[pdf]](https://arxiv.org/pdf/1901.00536.pdf) [[code]](https://github.com/GWUvision/Similarity-Visualization)
- Improving Deep Learning Interpretability by Saliency Guided Training [[pdf]](https://arxiv.org/pdf/2111.14338.pdf) [[code]](https://github.com/ayaabdelsalam91/saliency_guided_training)
- Explainability Methods for Graph Convolutional Neural Networks [[pdf]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Pope_Explainability_Methods_for_Graph_Convolutional_Neural_Networks_CVPR_2019_paper.pdf) [[code]](https://github.com/ndey96/GCNN-Explainability)
- Learning Accurate and Interpretable Decision Rule Sets from Neural Networks [[pdf]](https://arxiv.org/pdf/2103.02826.pdf)
- Learning to Explain: An Information-Theoretic Perspective on Model Interpretation [[pdf]](http://proceedings.mlr.press/v80/chen18j/chen18j.pdf)
- Right for the Right Reasons: Training Differentiable Models by Constraining their Explanations [[pdf]](https://arxiv.org/pdf/1703.03717.pdf)
- Are Vision Transformers Robust to Patch Perturbations? [[pdf]](https://arxiv.org/pdf/2111.10659.pdf)
- Are Transformers More Robust Than CNNs? [[pdf]](https://arxiv.org/pdf/2111.05464.pdf)
- Unmasking Clever Hans predictors and assessing what machines really learn [[pdf]](https://www.nature.com/articles/s41467-019-08987-4.pdf)
- Interpreting Multivariate Shapley Interactions in DNNs [[pdf]](https://arxiv.org/pdf/2010.05045.pdf)
- Explaining Deep Neural Networks with a Polynomial Time Algorithm for Shapley Values Approximation [[pdf]](https://arxiv.org/pdf/1903.10992.pdf)
- Multimodal Neurons in Artificial Neural Networks [[blog]](https://distill.pub/2021/multimodal-neurons/)
- **[BlurIG]** Attribution in Scale and Space [[pdf]](https://arxiv.org/pdf/2004.03383.pdf) [[code]](https://github.com/PAIR-code/saliency)
- **[VRX]** Interpreting with Structural Visual Concepts [[pdf]](https://arxiv.org/pdf/2105.00290.pdf)
- **[LS-Tree]** Model Interpretation When the Data Are Linguistic [[pdf]](https://arxiv.org/pdf/1902.04187.pdf)
- **[ConceptSHAP]** On Completeness-aware Concept-Based Explanations in Deep Neural Networks [[pdf]](https://arxiv.org/pdf/1910.07969.pdf) [[code]](https://github.com/chihkuanyeh/concept_exp)
- **[D-RISE]** Black-box Explanation of Object Detectors via Saliency Maps [[pdf]](https://arxiv.org/pdf/2006.03204.pdf)
- **[SAGs]** Structured Attention Graphs for Image Classification [[pdf]](https://arxiv.org/pdf/2011.06733.pdf)
- **[SmoothGrad]** Removing noise by adding noise [[pdf]](https://arxiv.org/pdf/1706.03825.pdf) 
- **[Integrated Gradients]** Axiomatic Attribution for Deep Networks [[pdf]](https://arxiv.org/pdf/1703.01365.pdf) [[code]](https://www.tensorflow.org/tutorials/interpretability/integrated_gradients) [[code]](https://vl8r.eu/posts/2021/10/15/how-the-integrated-gradients-method-works/)
- **[Integrated Hessians]** Explaining Explanations: Axiomatic Feature Interactions for Deep Networks [[pdf]](https://arxiv.org/pdf/2002.04138.pdf) [[code]](https://github.com/suinleelab/path_explain)
- **[LRP]** On Pixel-Wise Explanations for Non-Linear Classifier Decisions by Layer-Wise Relevance Propagation [[pdf]](https://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0130140&type=printable) [[pdf]](https://iphome.hhi.de/samek/pdf/MonXAI19.pdf) [[pdf]](https://www.sciencedirect.com/science/article/pii/S1051200417302385) [[tutorial]](https://git.tu-berlin.de/gmontavon/lrp-tutorial) [[code]](https://github.com/fhvilshoj/TorchLRP) [[code]](https://github.com/deepfindr/xai-series/blob/master/05_lrp.py) [[blog]](https://towardsdatascience.com/indepth-layer-wise-relevance-propagation-340f95deb1ea)
- **[DeepDream]** Inceptionism: Going Deeper into Neural Networks [[blog]](https://ai.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html) [[code]](https://github.com/eriklindernoren/PyTorch-Deep-Dream) [[code]](https://github.com/gordicaleksa/pytorch-deepdream) [[code]](https://github.com/ProGamerGov/neural-dream)
- **[Archipelago]** How does this interaction affect me? Interpretable attribution for feature interactions [[pdf]](https://arxiv.org/pdf/2006.10965.pdf)
- **[RISE]** Randomized Input Sampling for Explanation of Black-box Models [[pdf]](https://arxiv.org/pdf/1806.07421.pdf) [[code]](https://github.com/eclique/RISE)
- **[DeepLIFT]** Learning Important Features Through Propagating Activation Differences [[pdf]](https://arxiv.org/pdf/1704.02685.pdf) [[video]](https://www.youtube.com/playlist?list=PLJLjQOkqSRTP3cLB2cOOi_bQFw6KPGKML) [[code]](https://github.com/kundajelab/deeplift)
- **[SHAP]** A Unified Approach to Interpreting Model Predictions [[pdf]](https://arxiv.org/pdf/1705.07874.pdf) [[code]](https://github.com/slundberg/shap)
- **[LIME]** "Why Should I Trust You?": Explaining the Predictions of Any Classifier [[pdf]](https://arxiv.org/pdf/1602.04938.pdf) [[code]](https://github.com/marcotcr/lime) [[blog]](https://www.oreilly.com/content/introduction-to-local-interpretable-model-agnostic-explanations-lime/)
- **[Layer Conductance]** How Important Is a Neuron? [[pdf]](https://arxiv.org/pdf/1805.12233.pdf) [[pdf]](https://arxiv.org/pdf/1807.09946.pdf)
- **[TCAV]** Quantitative Testing with Concept Activation Vectors [[pdf]](https://arxiv.org/pdf/1711.11279.pdf)
- **[BiLRP]** Building and Interpreting Deep Similarity Models [[pdf]](https://arxiv.org/pdf/2003.05431.pdf) [[code]](https://github.com/oeberle/BiLRP_explain_similarity)
- **[LaViSE]** Explaining Deep Convolutional Neural Networks via Latent Visual-Semantic Filter Attention [[pdf]](https://arxiv.org/pdf/2204.04601.pdf) [[code]](https://github.com/YuYang0901/LaViSE)
- **[CGC]** Consistent Explanations by Contrastive Learning [[pdf]](https://arxiv.org/pdf/2110.00527.pdf) [[code]](https://github.com/UCDvision/CGC)
- **[ProtoTrees]** Neural Prototype Trees for Interpretable Fine-grained Image Recognition [[pdf]](https://arxiv.org/pdf/2012.02046.pdf) [[code]](https://github.com/M-Nauta/ProtoTree) 
- **[CLRP]** Understanding Individual Decisions of CNNs via Contrastive Backpropagation [[pdf]](https://arxiv.org/pdf/1812.02100.pdf) [[code]](https://github.com/JindongGu/Contrastive-LRP)
- **[FAM]** Visual Explanations for the Feature Representations from Deep Convolutional Networks [[pdf]](https://openaccess.thecvf.com/content/CVPR2022/papers/Wu_FAM_Visual_Explanations_for_the_Feature_Representations_From_Deep_Convolutional_CVPR_2022_paper.pdf)
- **[CRP]** From “Where” to “What”: Towards Human-Understandable Explanations through Concept Relevance Propagation [[pdf]](https://arxiv.org/pdf/2206.03208.pdf) [[code]](https://github.com/rachtibat/zennit-crp)
- **[HINT]** Hierarchical Neuron Concept Explainer [[pdf]](https://arxiv.org/pdf/2203.14196.pdf) [[code]](https://github.com/AntonotnaWang/HINT)
- **[BagNet]** Approximating CNNs with Bag-of-local-Features models works surprisingly well on ImageNet [[pdf]](https://arxiv.org/pdf/1904.00760.pdf) [[code]](https://github.com/wielandbrendel/bag-of-local-features-models) [[blog]](https://sh-tsang.medium.com/review-bagnet-approximating-cnns-with-bag-of-local-features-models-works-surprisingly-well-on-125f4295c433)
- **[ShapNets]** Shapley Explanation Networks [[pdf]](https://arxiv.org/pdf/2104.02297.pdf) [[code]](https://github.com/inouye-lab/ShapleyExplanationNetworks)
- **[ProtoPNet]** This Looks Like That: Deep Learning for Interpretable Image Recognition [[pdf]](https://arxiv.org/pdf/1806.10574.pdf) [[code]](https://github.com/cfchen-duke/ProtoPNet)
- **[Deformable ProtoPNet]** An Interpretable Image Classifier Using Deformable Prototypes [[pdf]](https://arxiv.org/pdf/2111.15000.pdf)
- **[CALM]** Keep CALM and Improve Visual Feature Attribution [[pdf]](https://arxiv.org/pdf/2106.07861.pdf) [[code]](https://github.com/naver-ai/calm)
- **[SGLRP]** Explaining Convolutional Neural Networks using Softmax Gradient Layer-wise Relevance Propagation [[pdf]](https://arxiv.org/pdf/1908.04351.pdf)
- **[DTD]** Explaining NonLinear Classification Decisions with Deep Taylor Decomposition [[pdf]](https://arxiv.org/pdf/1512.02479.pdf) [[code]](https://github.com/myc159/Deep-Taylor-Decomposition)
- **[GradCAT]** Nested Hierarchical Transformer: Towards Accurate, Data-Efficient and Interpretable Visual Understanding [[pdf]](https://arxiv.org/pdf/2105.12723.pdf)
- **[FastSHAP]** Real-Time Shapley Value Estimation [[pdf]](https://arxiv.org/pdf/2107.07436.pdf) [[code]](https://github.com/iancovert/fastshap)
- **[VisualBackProp]** Efficient visualization of CNNs [[pdf]](https://arxiv.org/pdf/1611.05418.pdf)
- **[NBDT]** Neural-Backed Decision Trees [[pdf]](https://arxiv.org/pdf/2004.00221.pdf) [[code]](https://github.com/alvinwan/neural-backed-decision-trees)
- **[XRAI]** Better Attributions Through Regions [[pdf]](https://arxiv.org/pdf/1906.02825.pdf)
- **[Proto2Proto]** Can you recognize the car, the way I do? [[pdf]](https://arxiv.org/pdf/2204.11830.pdf) [[code]](https://github.com/archmaester/proto2proto)
- **[MeGe, ReCo]** How Good is your Explanation? Algorithmic Stability Measures to Assess the Quality of Explanations for Deep Neural Networks [[pdf]](https://arxiv.org/pdf/2009.04521.pdf)

## CAM Papers
- **[CAM]** Learning Deep Features for Discriminative Localization [[pdf]](https://arxiv.org/pdf/1512.04150.pdf)
- **[Grad-CAM]** Visual Explanations from Deep Networks via Gradient-based Localization [[pdf]](https://arxiv.org/pdf/1610.02391.pdf) [[code]](https://github.com/ramprs/grad-cam/) [[website]](http://gradcam.cloudcv.org/)
- **[Grad-CAM++]** Improved Visual Explanations for Deep Convolutional Networks [[pdf]](https://arxiv.org/pdf/1710.11063.pdf) [[code]](https://github.com/adityac94/Grad_CAM_plus_plus)
- **[Score-CAM]** Score-Weighted Visual Explanations for Convolutional Neural Networks [[pdf]](https://arxiv.org/pdf/1910.01279.pdf) [[code]](https://github.com/haofanwang/Score-CAM)
- **[LayerCAM]** Exploring Hierarchical Class Activation Maps for Localization [[pdf]](http://mftp.mmcheng.net/Papers/21TIP_LayerCAM.pdf) [[code]](https://github.com/PengtaoJiang/LayerCAM-jittor)
- **[Eigen-CAM]** Class Activation Map using Principal Components [[pdf]](https://arxiv.org/ftp/arxiv/papers/2008/2008.00299.pdf)
- **[XGrad-CAM]** Axiom-based Grad-CAM: Towards Accurate Visualization and Explanation of CNNs [[pdf]](https://arxiv.org/pdf/2008.02312.pdf) [[code]](https://github.com/Fu0511/XGrad-CAM)
- **[FullGrad]** Full-Gradient Representation for Neural Network Visualization [[pdf]](https://arxiv.org/pdf/1905.00780.pdf)
- **[Relevance-CAM]** Your Model Already Knows Where to Look [[pdf]](https://openaccess.thecvf.com/content/CVPR2021/papers/Lee_Relevance-CAM_Your_Model_Already_Knows_Where_To_Look_CVPR_2021_paper.pdf) [[code]](https://github.com/mongeoroo/Relevance-CAM)
- **[Poly-CAM]** High resolution class activation map for convolutional neural networks [[pdf]](https://arxiv.org/pdf/2204.13359.pdf)
- **[Zoom-CAM]**  Generating Fine-grained Pixel Annotations from Image Labels [[pdf]](https://arxiv.org/pdf/2010.08644.pdf)

## Temporal Explanations
- Explaining Time Series Predictions with Dynamic Masks [[pdf]](https://arxiv.org/pdf/2106.05303.pdf)
- Feature Importance Explanations for Temporal Black-Box Models [[pdf]](https://arxiv.org/pdf/2102.11934.pdf)
- Benchmarking Deep Learning Interpretability in Time Series Predictions [[pdf]](https://arxiv.org/pdf/2010.13924.pdf)
- Input-Cell Attention Reduces Vanishing Saliency of Recurrent Neural Networks [[pdf]](https://arxiv.org/pdf/1910.12370.pdf)
- TimeSHAP: Explaining Recurrent Models through Sequence Perturbations [[pdf]](https://arxiv.org/pdf/2012.00073.pdf)
- Instance-wise feature importance for time-series black-box models [[pdf]](https://arxiv.org/pdf/2003.02821.pdf)

## Review Papers
- Explaining Deep Neural Networks and Beyond: A Review of Methods and Applications [[pdf]](https://arxiv.org/pdf/2003.07631.pdf)
- Benchmarking and Survey of Explanation Methods for Black Box Models [[pdf]](https://arxiv.org/pdf/2102.13076.pdf)
- RobustART : Benchmarking Robustness on Architecture Design and Training Techniques [[pdf]](https://arxiv.org/pdf/2109.05211.pdf)
- An Empirical Study of Deep Neural Network Explanation Methods [[pdf]](https://proceedings.neurips.cc/paper/2020/file/2c29d89cc56cdb191c60db2f0bae796b-Paper.pdf) [[code]](https://github.com/nesl/Explainability-Study)
- Quantitative Evaluations on Saliency Methods: An Experimental Study [[pdf]](https://arxiv.org/pdf/2012.15616.pdf)
- Methods for Interpreting and Understanding Deep Neural Networks [[pdf]](https://arxiv.org/pdf/1706.07979.pdf)

## Natural Language Explanations
- **[GVE]** Generating visual explanations [[pdf]](https://arxiv.org/pdf/1603.08507.pdf)
- **[PJ-X]** Multimodal Explanations: Justifying Decisions and Pointing to the Evidence [[pdf]](https://arxiv.org/pdf/1802.08129.pdf) [[code]](https://github.com/Seth-Park/MultimodalExplanations)
- **[FME]** Faithful Multimodal Explanation for Visual Question Answering [[pdf]](https://arxiv.org/pdf/1809.02805.pdf) 
- **[RVT]** Natural Language Rationales with Full-Stack Visual Reasoning [[pdf]](https://arxiv.org/pdf/2010.07526.pdf) [[code]](https://github.com/allenai/visual-reasoning-rationalization)
- **[e-UG]** e-ViL: A Dataset and Benchmark for Natural Language Explanations in Vision-Language Tasks [[pdf]](https://arxiv.org/pdf/2105.03761.pdf) [[code]](https://github.com/maximek3/e-ViL)
- **[NLX-GPT]** A Model for Natural Language Explanations in Vision and Vision-Language Tasks [[pdf]](https://arxiv.org/pdf/2203.05081.pdf) [[code]](https://github.com/fawazsammani/nlxgpt)
- **[Explain Yourself]** Leveraging Language Models for Commonsense Reasoning [[pdf]](https://arxiv.org/pdf/1906.02361.pdf) 
- **[e-SNLI]** Natural Language Inference with Natural Language Explanations [[pdf]](https://arxiv.org/pdf/1812.01193.pdf)
- **[CLEVR-X]** A Visual Reasoning Dataset for Natural Language Explanations [[pdf]](https://arxiv.org/pdf/2204.02380.pdf) [[code]](https://github.com/ExplainableML/CLEVR-X) [[website]](https://explainableml.github.io/CLEVR-X/)
- **[VQA-E]** Explaining, Elaborating, and Enhancing Your Answers for Visual Questions [[pdf]](https://arxiv.org/pdf/1803.07464.pdf)
- **[PtE]** Are Training Resources Insufficient? Predict First Then Explain! [[pdf]](https://arxiv.org/pdf/2110.02056.pdf)
- **[WT5]** Training Text-to-Text Models to Explain their Predictions [[pdf]](https://arxiv.org/pdf/2004.14546.pdf)
- **[REXC]** Rationale-Inspired Natural Language Explanations with Commonsense [[pdf]](https://arxiv.org/pdf/2106.13876.pdf)
- **[ELV]** Towards Interpretable Natural Language Understanding with Explanations as Latent Variables [[pdf]](https://arxiv.org/pdf/2011.05268.pdf) [[code]](https://github.com/JamesHujy/ELV)
- Textual Explanations for Self-Driving Vehicles [[pdf]](https://arxiv.org/pdf/1807.11546.pdf) [[code]](https://github.com/JinkyuKimUCB/explainable-deep-driving)
- Few-Shot Self-Rationalization with Natural Language Prompts [[pdf]](https://arxiv.org/pdf/2111.08284.pdf)
- Measuring Association Between Labels and Free-Text Rationales [[pdf]](https://arxiv.org/pdf/2010.12762.pdf) [[code]](https://github.com/allenai/label_rationale_association)
- Reframing Human-AI Collaboration for Generating Free-Text Explanations [[pdf]](https://arxiv.org/pdf/2112.08674.pdf)
- Few-Shot Out-of-Domain Transfer Learning of Natural Language Explanations [[pdf]](https://arxiv.org/pdf/2112.06204.pdf)

## XAI for NLP
- Analyzing Multi-Head Self-Attention: Specialized Heads Do the Heavy Lifting, the Rest Can Be Pruned [[pdf]](https://arxiv.org/pdf/1905.09418.pdf) [[code]](https://github.com/lena-voita/the-story-of-heads)
- Visualizing and Understanding Neural Machine Translation [[pdf]](https://aclanthology.org/P17-1106.pdf)
- A Diagnostic Study of Explainability Techniques for Text Classification [[pdf]](https://arxiv.org/pdf/2009.13295.pdf) [[code]](https://github.com/copenlu/xai-benchmark)
- Why use attention as explanation when we have saliency methods? [[pdf]](https://arxiv.org/pdf/2010.05607.pdf)
- Attention is not Explanation [[pdf]](https://arxiv.org/pdf/1902.10186.pdf)
- Attention is not not Explanation [[pdf]](https://arxiv.org/pdf/1908.04626.pdf)
- Analyzing Individual Neurons in Pre-trained Language Models [[pdf]](https://arxiv.org/pdf/2010.02695.pdf)
- Identifying and Controlling Important Neurons in Neural Machine Translation [[pdf]](https://arxiv.org/pdf/1811.01157.pdf)
- Did the Model Understand the Question? [[pdf]](https://arxiv.org/pdf/1805.05492.pdf)
- Explaining Compositional Semantics for Neural Sequence Models [[pdf]](https://arxiv.org/pdf/1911.06194.pdf) [[code]](https://github.com/INK-USC/hierarchical-explanation-neural-sequence-models)
- FreeLB: Enhanced Adversarial Training for Natural Language Understanding [[pdf]](https://arxiv.org/pdf/1909.11764.pdf)
- Fooling Explanations in Text Classifiers [[pdf]](https://openreview.net/pdf?id=j3krplz_4w6)
- Inside BERT from BERT-related-papers Github [[link]](https://github.com/tomohideshibata/BERT-related-papers#inside-bert)

## XAI Libraries for NLP
- [BertViz](https://github.com/jessevig/bertviz)
- [Transformers Interpret](https://github.com/cdpierse/transformers-interpret)
- [Ecco](https://github.com/jalammar/ecco)
- [LIT](https://github.com/PAIR-code/lit)

## XAI Libraries for Vision
- [Captum](https://captum.ai/)
- [pytorch-cnn-visualizations](https://github.com/utkuozbulak/pytorch-cnn-visualizations)
- [pytorch-grad-cam](https://github.com/jacobgil/pytorch-grad-cam)
- [torch-cam](https://github.com/frgfm/torch-cam)
- [grad-cam-pytorch](https://github.com/kazuto1011/grad-cam-pytorch)
- VL-InterpreT [[pdf]](https://arxiv.org/pdf/2203.17247.pdf) [[github]](https://github.com/IntelLabs/VL-InterpreT) [[demo]](http://vlinterpret38-env-2.eba-bgxp4fxk.us-east-2.elasticbeanstalk.com/) [[video]](https://www.youtube.com/watch?v=4Rj15Hi_Pdo&ab_channel=CognitiveAI)
- [TorchRay](https://github.com/facebookresearch/TorchRay)
- [Alibi](https://github.com/SeldonIO/alibi)
- [Xplique](https://github.com/deel-ai/xplique)
- [tf-explain](https://github.com/sicara/tf-explain)

## Other Awesomes
- [awesome-explainable-ai](https://github.com/wangyongjie-ntu/Awesome-explainable-AI)
- [awesome-xai](https://github.com/altamiracorp/awesome-xai)

## Other Resources
- [Explainable AI: Interpreting, Explaining and Visualizing Deep Learning](https://link.springer.com/book/10.1007/978-3-030-28954-6)
- [Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/)
- [Distil](https://distill.pub/) 
- [OpenAI Microscope](https://microscope.openai.com/models)
- [Summary - Captum](https://captum.ai/docs/algorithms)
- [Stanford CS231n notes](http://cs231n.stanford.edu/slides/2022/lecture_8_ruohan.pdf)
- [TU Berlin Notes](https://www3.math.tu-berlin.de/numerik/CoSIPICDL2017/Talks/mueller.pdf)
- [Tutorial Notebooks](https://github.com/1202kbs/Understanding-NN)
- NPTEL-NOC IITM Videos [[Early Methods]](https://www.youtube.com/watch?v=a4TDSLGhKi8&ab_channel=NPTEL-NOCIITM) [[Visualization Methods]](https://www.youtube.com/watch?v=u3FBpyUA1dc&ab_channel=NPTEL-NOCIITM) [[CAM Methods]](https://www.youtube.com/watch?v=VmbBnSv3otc&ab_channel=NPTEL-NOCIITM) [[Recent Methods]](https://www.youtube.com/watch?v=9OzwN-Ub6Lg&ab_channel=NPTEL-NOCIITM) [[Beyond Explaining]](https://www.youtube.com/watch?v=9Moxmab_Y4I&ab_channel=NPTEL-NOCIITM)
- [AI Explained Video Series by Fiddler AI](https://www.youtube.com/watch?v=TORUp11Of-8&list=PL9ekywqME2AiINPJUmAy2bk0DoSRlltP-&index=1&ab_channel=FiddlerAI)
- [XAI Explained Video Series by DeepFindr](https://www.youtube.com/watch?v=OZJ1IgSgP9E&list=PLV8yxwGOxvvovp-j6ztxhF3QcKXT6vORU&index=1&ab_channel=DeepFindr)
- [Visualizing and Understanding Stanford Video](https://www.youtube.com/watch?v=6wcs6szJWMY&t=2668s&ab_channel=StanfordUniversitySchoolofEngineering)
- [CVPR 2021 Tutorial](https://interpretablevision.github.io/)
- [FAIR Tutorial Towards falsifiable interpretability research](https://www.youtube.com/watch?v=BQ06EydLF0Q&ab_channel=BoleiZhou)
- [CS231n Assignments Solutions](https://github.com/srinadhu/CS231n)
- Filter and Feature Maps Visualization [[blog]](https://towardsdatascience.com/how-to-visualize-convolutional-features-in-40-lines-of-code-70b7d87b0030) [[blog]](https://www.kaggle.com/code/magokecol/pytorch-feature-maps-visualizer-snake-version/notebook) [[blog]](https://debuggercafe.com/visualizing-filters-and-feature-maps-in-convolutional-neural-networks-using-pytorch/) [[pytorch discuss]](https://discuss.pytorch.org/t/visualize-feature-map/29597/2)
- Hooks in PyTorch [[tutorial]](https://web.stanford.edu/~nanbhas/blog/forward-hooks-pytorch/) [[tutorial]](https://towardsdatascience.com/the-one-pytorch-trick-which-you-should-know-2d5e9c1da2ca)

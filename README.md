# Awesome Explainable AI [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

- [Bank Employee] I'm Sorry, your loan application is rejected. [Customer] Why? I satisfy all the requirements. [Bank Employee] I know, but our AI systems says there is a risk if we give you the loan. [Bank Employee] (thinking) Hmmm...This is strange... Let me call some AI guys to figure out what's the problem. [AI Engineers] Hi, so we analyzed your model and found out that this previous customer was rejected because he is wearing blue shoes. 
- [Investigator] Your friend is unfortunately dead... Our condolences to you.... [Friend] (crying) Why? What Happened. [Investigator] The self-driving car didn't stop at the red traffic light...We will sue the company in court. [Company] After analysis and investigation, the AI System didn't find a tree next to the traffic light and thus thought the red traffic light is a dodgeball. 

If you find some overlooked papers, please open issues or pull requests, and provide the paper(s) in this format:
```
- **[]** Paper Name [[pdf]]() [[code]]()
```

## Papers
- Visualizing and Understanding Convolutional Networks [[pdf]](https://arxiv.org/pdf/1311.2901.pdf)
- Deep Inside Convolutional Networks: Visualising Image Classification Models and Saliency Maps [[pdf]](https://arxiv.org/pdf/1312.6034.pdf)
- Striving for Simplicity: The All Convolutional Net [[pdf]](https://arxiv.org/pdf/1412.6806.pdf)
- Understanding Neural Networks Through Deep Visualization [[pdf]](https://arxiv.org/pdf/1506.06579.pdf)
- Understanding Deep Image Representations by Inverting Them [[pdf]](https://arxiv.org/pdf/1412.0035.pdf)
- Interpretable Explanations of Black Boxes by Meaningful Perturbation [[pdf]](https://arxiv.org/pdf/1704.03296.pdf)
- Explaining and Harnessing Adversarial Examples [[pdf]](https://arxiv.org/pdf/1412.6572.pdf)
- Towards Deep Learning Models Resistant to Adversarial Attacks [[pdf]](https://arxiv.org/pdf/1706.06083.pdf) [[code]](https://github.com/MadryLab/mnist_challenge)
- High Confidence Predictions for Unrecognizable Images [[pdf]](https://arxiv.org/pdf/1412.1897.pdf)
- Visualizing Higher-Layer Features of a Deep Network [[pdf]](https://www.researchgate.net/publication/265022827_Visualizing_Higher-Layer_Features_of_a_Deep_Network)
- Towards better understanding of gradient-based attribution methods for Deep Neural Networks [[pdf]](https://arxiv.org/pdf/1711.06104.pdf)
- Polynomial calculation of the Shapley value based on sampling [[pdf]](https://www.sciencedirect.com/science/article/abs/pii/S0305054808000804)
- On the (In)fidelity and Sensitivity of Explanations [[pdf]](https://arxiv.org/pdf/1901.09392.pdf) [[code]](https://github.com/chihkuanyeh/saliency_evaluation)
- Interpretation of Neural Networks is Fragile [[pdf]](https://arxiv.org/pdf/1710.10547.pdf)
- On the Robustness of Interpretability Methods [[pdf]](https://arxiv.org/pdf/1806.08049.pdf)
- Sanity Checks for Saliency Maps [[pdf]](https://arxiv.org/pdf/1810.03292.pdf)
- Influence-Directed Explanations for Deep Convolutional Networks [[pdf]](https://arxiv.org/pdf/1802.03788.pdf)
- **[SmoothGrad]** Removing noise by adding noise [[pdf]](https://arxiv.org/pdf/1706.03825.pdf) 
- **[Integrated Gradients]** Axiomatic Attribution for Deep Networks [[pdf]](https://arxiv.org/pdf/1703.01365.pdf) 
- **[LRP]** On Pixel-Wise Explanations for Non-Linear Classifier Decisions by Layer-Wise Relevance Propagation [[pdf]](https://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0130140&type=printable) [[pdf]](https://iphome.hhi.de/samek/pdf/MonXAI19.pdf) [[pdf]](https://www.sciencedirect.com/science/article/pii/S1051200417302385) [[tutorial]](https://git.tu-berlin.de/gmontavon/lrp-tutorial) [[code]](https://github.com/fhvilshoj/TorchLRP) [[code]](https://github.com/deepfindr/xai-series/blob/master/05_lrp.py)
- **[DeepDream]** Inceptionism: Going Deeper into Neural Networks [[blog]](https://ai.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html) [[code]](https://github.com/eriklindernoren/PyTorch-Deep-Dream) [[code]](https://github.com/gordicaleksa/pytorch-deepdream) [[code]](https://github.com/ProGamerGov/neural-dream)
- **[RISE]** Randomized Input Sampling for Explanation of Black-box Models [[pdf]](https://arxiv.org/pdf/1806.07421.pdf) [[code]](https://github.com/eclique/RISE)
- **[DeepLIFT]** Learning Important Features Through Propagating Activation Differences [[pdf]](https://arxiv.org/pdf/1704.02685.pdf) [[video]](https://www.youtube.com/playlist?list=PLJLjQOkqSRTP3cLB2cOOi_bQFw6KPGKML) [[code]](https://github.com/kundajelab/deeplift)
- **[SHAP]** A Unified Approach to Interpreting Model Predictions [[pdf]](https://arxiv.org/pdf/1705.07874.pdf) [[code]](https://github.com/slundberg/shap)
- **[LIME]** "Why Should I Trust You?": Explaining the Predictions of Any Classifier [[pdf]](https://arxiv.org/pdf/1602.04938.pdf) [[code]](https://github.com/marcotcr/lime)
- **[Layer Conductance]** How Important Is a Neuron? [[pdf]](https://arxiv.org/pdf/1805.12233.pdf) [[pdf]](https://arxiv.org/pdf/1807.09946.pdf)
- **[TCAV]** Quantitative Testing with Concept Activation Vectors [[pdf]](https://arxiv.org/pdf/1711.11279.pdf)

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
- Textual Explanations for Self-Driving Vehicles [[pdf]](https://arxiv.org/pdf/1807.11546.pdf) [[code]](https://github.com/JinkyuKimUCB/explainable-deep-driving)
- **[VQA-E]** Explaining, Elaborating, and Enhancing Your Answers for Visual Questions [[pdf]](https://arxiv.org/pdf/1803.07464.pdf)
- **[PtE]** Are Training Resources Insufficient? Predict First Then Explain! [[pdf]](https://arxiv.org/pdf/2110.02056.pdf)
- **[WT5]** Training Text-to-Text Models to Explain their Predictions [[pdf]](https://arxiv.org/pdf/2004.14546.pdf)

## Libraries
- [Captum](https://captum.ai/)
- [pytorch-cnn-visualizations](https://github.com/utkuozbulak/pytorch-cnn-visualizations)
- [pytorch-grad-cam](https://github.com/jacobgil/pytorch-grad-cam)
- [torch-cam](https://github.com/frgfm/torch-cam)
- [grad-cam-pytorch](https://github.com/kazuto1011/grad-cam-pytorch)

## Other Awesomes
- [awesome-explainable-ai](https://github.com/wangyongjie-ntu/Awesome-explainable-AI)

## Other Resources
- [Explainable AI: Interpreting, Explaining and Visualizing Deep Learning](https://www.amazon.com/Explainable-AI-Interpreting-Explaining-Visualizing/dp/3030289532)
- [Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/)
- [Distil](https://distill.pub/) 
- [OpenAI Microscope](https://microscope.openai.com/models)
- [Summary - Captum](https://captum.ai/docs/algorithms)
- [Stanford CS231n notes](http://cs231n.stanford.edu/slides/2021/lecture_14.pdf)
- [TU Berlin Notes](https://www3.math.tu-berlin.de/numerik/CoSIPICDL2017/Talks/mueller.pdf)


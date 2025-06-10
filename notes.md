# Assignment

The three essays to deliver are: a) A full essay written by you; b) a full essay written by an LLM; c) an essay comparing  a) and b).

a) YOUR ESSAY. I can be about one of the topics from the shortlist at the bottom of this message (or a sub-topic from one of the shortlisted topics), or on a different topic relevant to the course suggested by you (and in this case, you need my prior approval to go for it) The length of the essay is expected to be 10-20 pages in standard format; a 10 p. essay must be extremely compact and informative to get decent marks. Different types of essay are accepted: state-of-the-art, review (collected work with historical perspective), or analytical (you get some relevant data to analyze and you organize the essay as an analytical study, conference-like style).

b) LLM's ESSAY. You must convince an LLM to write a similar essay to yours. In fact, as similar as possible in content and structure.

c) COMPARATIVE ESSAY. You must compare your essay with that by the LLM: main differences, strong and weak points of both, LLM prompting strategy you followed, and any other aspect you consider relevant. 4-5 pages would do nicely.

NOTES:

- Your marks will be related to essays a) and c)

- Submission deadline: June 12th

SHORTLIST OF TOPICS:

- ML models inspired by neuroscience

- Deep Learning and Neurocscience

- The Bayesian Brain: probabilistic models in computational neuroscience

- The connectome and network analysis

- AI models in decision making and the brain reward system

- ML models for the computational model of the visual system

# **Essay Outline: Reverse-Engineering Brain Mechanisms through Interpretable Neural Networks**

## **Part I: The Symbiotic Evolution of AI and Neuroscience: A Historical Perspective**

* **Introduction:**
    * Hook: The enduring quest to understand the human brain, the most complex computational machine known.
    * Thesis Statement: The intertwined history of Artificial Intelligence and Neuroscience has led to a symbiotic relationship where advances in one field have consistently fueled progress in the other. This essay will trace this co-evolution, from early computational models inspired by neural processes to the contemporary use of interpretable neural networks to reverse-engineer the brain's intricate mechanisms, culminating in a review of the current state-of-the-art and future directions.
    * Roadmap: Briefly outline the essay's structure, covering the historical review, the rise of deep learning, the advent of interpretable AI (XAI), and the application of these tools in modern neuroscience.

* **Chapter 1: The Dawn of AI and Early Neural Models (1940s-1960s)**
    * **The McCulloch-Pitts Neuron (1943):** The first mathematical model of a biological neuron. Discuss its significance as a foundational concept for both AI and computational neuroscience.
    * **Hebb's Postulate and Learning (1949):** "Neurons that fire together, wire together." Explain the Hebbian learning rule and its influence on early learning algorithms in neural networks.
    * **The Perceptron (1958):** Frank Rosenblatt's invention and its initial promise for pattern recognition. Connect this to early models of sensory processing in the brain.
    * **The "AI Winter" and its Thaw:** Briefly discuss the limitations identified by Minsky and Papert (1969) and the subsequent decline and eventual resurgence of neural network research.

* **Chapter 2: Connectionism and the Rise of Parallel Distributed Processing (1980s)**
    * **The PDP Group and the "Connectionist" Bible:** Discuss the impact of Rumelhart, Hinton, and McClelland's work.
    * **Backpropagation and Multi-Layer Networks:** Explain the significance of the backpropagation algorithm in training more complex networks, allowing for the modeling of more sophisticated cognitive functions.
    * **Early Applications in Cognitive Science:** Provide examples of how these models were used to simulate and understand phenomena like language acquisition, memory, and perception.

* **Chapter 3: The Deep Learning Revolution and its Impact on Neuroscience (2000s-Present)**
    * **The Unreasonable Effectiveness of Data and Computation:** The convergence of large datasets (e.g., ImageNet) and powerful GPUs.
    * **Convolutional Neural Networks (CNNs) and the Visual Cortex:**
        * Draw strong parallels between the hierarchical structure of CNNs and the organization of the primate visual stream (V1, V2, V4, IT).
        * Discuss seminal work (e.g., Yamins & DiCarlo) showing that CNNs trained on object recognition tasks develop representations remarkably similar to those found in the visual cortex.
    * **Recurrent Neural Networks (RNNs) and Sequential Processing:**
        * Explain the architecture of RNNs (including LSTMs and GRUs) and their suitability for modeling time-series data.
        * Connect this to the brain's processing of language, motor sequences, and decision-making over time.

***

## **Part II: The Black Box Dilemma and the Rise of Interpretable AI (XAI)**

* **Chapter 4: The "Black Box" Problem in Deep Learning**
    * **Defining the Challenge:** While deep neural networks achieve impressive performance, their internal workings are often opaque and difficult to understand.
    * **Implications for Scientific Discovery:** In the context of neuroscience, a "black box" model that mimics brain function without revealing *how* it does so offers limited scientific insight. The goal is not just to replicate but to understand the underlying principles.

* **Chapter 5: A Taxonomy of Interpretable AI Methods**
    * **Post-hoc vs. Intrinsically Interpretable Models:** Differentiate between methods that analyze a trained model and those that are designed to be transparent from the outset.
    * **Feature Attribution Methods:**
        * **Saliency Maps:** Visualizing which input features (e.g., pixels in an image) are most important for a model's prediction.
        * **LIME (Local Interpretable Model-agnostic Explanations) and SHAP (SHapley Additive exPlanations):** Explain how these methods build simpler, interpretable local models to approximate the behavior of the complex "black box" model.
    * **Model-based Interpretation:**
        * **Analyzing Network Activations and Representations:** Techniques for visualizing and understanding the features learned by different layers of a network.
        * **Causal Intervention and "Ablation" Studies:** Simulating lesion studies in neuroscience by deactivating specific neurons or connections in the network to observe the effect on its output.

* **Chapter 6: Interpretable AI in Action: Bridging the Gap to Neuroscience**
    * **Reverse-Engineering Sensory Systems:**
        * **Vision:** Beyond object recognition, how XAI helps us understand how CNNs represent texture, shape, and motion, and how this compares to neural data from different visual areas.
        * **Audition:** Using deep learning models to understand the neural coding of sound, from the cochlea to the auditory cortex.
    * **Decoding and Encoding Models:** Using interpretable models to predict neural activity from stimuli (encoding) and to decode mental states or perceived stimuli from neural recordings (decoding).
    * **Understanding Higher Cognitive Functions:**
        * **Language:** Analyzing the representations within large language models (LLMs) like BERT and GPT, and comparing them to the brain's language processing centers (e.g., Broca's and Wernicke's areas).
        * **Decision-Making and Reinforcement Learning:** How interpretable reinforcement learning models can shed light on the neural circuits involved in reward, planning, and action selection.

***

## **Part III: The State of the Art and the Future of Brain-Inspired AI**

* **Chapter 7: Current Frontiers in Interpretable Neural Networks for Neuroscience**
    * **Generative Models and "In Silico" Experiments:** Using generative adversarial networks (GANs) and other generative models to create stimuli that maximally activate specific neurons or brain regions, allowing for more targeted experiments.
    * **Beyond Supervised Learning:** The role of self-supervised and unsupervised learning in creating models that learn more brain-like representations without requiring massive labeled datasets.
    * **The Rise of "Neuro-AI":** The growing field of research that explicitly aims to build AI systems based on principles from neuroscience, creating a virtuous cycle of discovery.
    * **Thinking LLMs and Simulating Thought Processes:** Discussing the emerging use of large language models to model and understand human-like reasoning, planning, and problem-solving.

* **Chapter 8: Challenges, Limitations, and Ethical Considerations**
    * **The "Simile" vs. "Model" Distinction:** Emphasize that even the most brain-like ANNs are still simplifications. Discuss the key biological details they often omit (e.g., dendritic computation, neuromodulation).
    * **The Dangers of Over-interpretation:** The risk of drawing premature or overly simplistic conclusions about the brain based on analogies with AI models.
    * **Data Privacy and Neuromarketing:** Briefly touch on the ethical implications of being able to decode brain states with increasing accuracy.

* **Conclusion: The Future of a Fruitful Partnership**
    * **Recap of the Main Arguments:** Summarize the historical co-evolution and the current state of synergy between AI and neuroscience.
    * **Future Outlook:** Project how this interdisciplinary collaboration will continue to unravel the complexities of the brain and, in turn, inspire more general and capable artificial intelligence. The ultimate goal: a unified theory of intelligence, both biological and artificial.
    * **Final Thought-Provoking Statement:** Reiterate the profound potential of this research to not only advance science but also to fundamentally alter our understanding of ourselves.

---

## **Relevant Sources**

**Historical and Foundational**

* **McCulloch, W. S., & Pitts, W. (1943).** A logical calculus of the ideas immanent in nervous activity. *The bulletin of mathematical biophysics, 5*(4), 115-133.
* **Hebb, D. O. (1949).** *The organization of behavior: A neuropsychological theory.* Wiley.
* **Rosenblatt, F. (1958).** The perceptron: a probabilistic model for information storage and organization in the brain. *Psychological review, 65*(6), 386.
* **Minsky, M., & Papert, S. (1969).** *Perceptrons: An introduction to computational geometry.* MIT press.
* **Rumelhart, D. E., Hinton, G. E., & Williams, R. J. (1986).** Learning representations by back-propagating errors. *Nature, 323*(6088), 533-536.
* **McClelland, J. L., Rumelhart, D. E., & PDP Research Group. (1986).** *Parallel distributed processing: Explorations in the microstructure of cognition, vol. 2.* MIT press.

**Deep Learning and Neuroscience**

* **LeCun, Y., Bengio, Y., & Hinton, G. (2015).** Deep learning. *Nature, 521*(7553), 436-444.
* **Yamins, D. L., & DiCarlo, J. J. (2016).** Using goal-driven deep learning models to understand sensory cortex. *Nature neuroscience, 19*(3), 356-365.
* **Kriegeskorte, N., & Douglas, P. K. (2018).** Cognitive computational neuroscience. *Nature Neuroscience, 21*(9), 1148-1160.*
* **Richards, B. A., Lillicrap, T. P., Beaudoin, P., Bengio, Y., Bogacz, R., Christensen, A., ... & Kording, K. P. (2019).** A deep learning framework for neuroscience. *Nature neuroscience, 22*(11), 1761-1770.*
* **Savage, N. (2019).** How AI is helping to explain the brain. *Nature, 571*(7766), S16-S18.*

**Interpretable AI (XAI)**

* **Ribeiro, M. T., Singh, S., & Guestrin, C. (2016).** "Why should I trust you?": Explaining the predictions of any classifier. *In Proceedings of the 22nd ACM SIGKDD international conference on knowledge discovery and data mining* (pp. 1135-1144).
* **Lundberg, S. M., & Lee, S. I. (2017).** A unified approach to interpreting model predictions. *In Advances in neural information processing systems* (pp. 4765-4774).
* **Olah, C., Satyanarayan, A., Johnson, I., Carter, S., Schubert, L., Ye, K., & Mordvintsev, A. (2018).** The building blocks of interpretability. *Distill, 3*(3), e10.
* **Doshi-Velez, F., & Kim, B. (2017).** Towards a rigorous science of interpretable machine learning. *arXiv preprint arXiv:1702.08608.*
* **Miller, T. (2019).** Explanation in artificial intelligence: Insights from the social sciences. *Artificial Intelligence, 267*, 1-38.

**XAI for Neuroscience**

* **McClure, P., & Kriegeskorte, N. (2024).** How to compare representations in brains and machines. *bioRxiv*, 2024-01.
* **Fong, R. C., & Vedaldi, A. (2017).** Interpretable explanations of black boxes by meaningful perturbation. *In Proceedings of the IEEE international conference on computer vision* (pp. 3429-3437).
* **Bau, D., Zhou, B., Khosla, A., Oliva, A., & Torralba, A. (2017).** Network dissection: Quantifying interpretability of deep visual representations. *In Proceedings of the IEEE conference on computer vision and pattern recognition* (pp. 6541-6549).
* **Schrimpf, M., Kubilius, J., Hong, H., Majaj, N. J., Rajalingham, R., Issa, E. B., ... & DiCarlo, J. J. (2020).** Brain-Score: A framework for comparing computational models of the brain. *bioRxiv*.
* **Toneva, M., & Wehbe, L. (2019).** Interpreting and improving natural language processing models for neuro-imaging analyses. *In Advances in Neural Information Processing Systems* (pp. 14382-14392).

**Large Language Models and Thought Processes**

* **Caucheteux, C., & King, J. R. (2022).** Brains and algorithms partially converge in natural language processing. *Communications Biology, 5*(1), 1-12.
* **Wei, J., Wang, X., Schuurmans, D., Bosma, M., Chi, E., Le, Q., & Zhou, D. (2022).** Chain of thought prompting elicits reasoning in large language models. *arXiv preprint arXiv:2201.11903.*
* **Binz, M., & Schulz, E. (2023).** Using cognitive psychology to understand large language models. *Nature Reviews Psychology, 2*(7), 385-386.*
* **Mahowald, K., Ivanova, A. A., Blank, I. A., Kanwisher, N., Tenenbaum, J. B., & Fedorenko, E. (2023).** Dissociating language and thought in large language models: a cognitive perspective. *arXiv preprint arXiv:2301.06627.*

# TODOs

[x] XAI Taxonomy Table
[ ] Add figures
  [x] First artificial neuron
  [x] Back-propagation?
  [ ] MLP
  [x] CNN?
  [x] RNN?
  [ ] XAI Taxonomy?
  [ ] Saliency Maps?
  [ ] LIME/SHAP?
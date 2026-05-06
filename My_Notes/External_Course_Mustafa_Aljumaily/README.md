# Pattern Recognition – Course Overview

This repository contains visual notes from a **Pattern Recognition** course (based on YouTube lectures).  
The following chapters cover fundamental topics: Bayesian decision theory, density estimation, EM algorithm, HMM, neural networks, SVM, clustering, and more.

> 📌 **Images** are taken from the original slides. Click any image to enlarge (if using GitHub with supported viewer).

---

## 📖 Table of Contents

- [Chapter 1: Introduction to Pattern Recognition](#chapter-1-introduction-to-pattern-recognition)
- [Chapter 2: Bayesian Decision Theory](#chapter-2-bayesian-decision-theory)
- [Chapter 3: Maximum Likelihood & Bayesian Density Estimation](#chapter-3-maximum-likelihood--bayesian-density-estimation)
- [Chapter 4: Expectation-Maximization & Mixture Density](#chapter-4-expectation-maximization--mixture-density)
- [Chapter 5: Hidden Markov Models (HMM)](#chapter-5-hidden-markov-models-hmm)
- [Chapter 6: Bayesian Belief Networks](#chapter-6-bayesian-belief-networks)
- [Chapter 7: Non‑parametric Methods (Parzen Windows)](#chapter-7-nonparametric-methods-parzen-windows)
- [Chapter 8: Feature Reduction & Selection](#chapter-8-feature-reduction--selection)
- [Chapter 9: k‑Nearest Neighbor Classifier](#chapter-9-knearest-neighbor-classifier)
- [Chapter 10: Linear Discriminants & SVM](#chapter-10-linear-discriminants--svm)
- [Chapter 11: Neural Networks & Decision Trees](#chapter-11-neural-networks--decision-trees)
- [Chapter 12: Unsupervised Learning & Clustering](#chapter-12-unsupervised-learning--clustering)
- [Chapter 13: Algorithm‑Independent Learning Issues](#chapter-13-algorithmindependent-learning-issues)
- [Chapter 14: Structural & Syntactic Pattern Recognition](#chapter-14-structural--syntactic-pattern-recognition)
- [Additional Figures (uncertain mapping)](#additional-figures-uncertain-mapping)

---

## Chapter 1: Introduction to Pattern Recognition

*Biometric recognition example.*

<img src="./Pic/IMG-20260506-WA0045.jpg" alt="Chapter 1 - Biometric" width="500"/>

> ⚠️ *Image filename: WA0045.jpg (assumed – based on your upload order). If missing, please replace.*

---

## Chapter 2: Bayesian Decision Theory

*Posteriors, decision regions, and reducible error.*

<img src="./Pic/IMG-20260506-WA0043.jpg" alt="Chapter 2 - Bayesian decision regions" width="550"/>

---

## Chapter 3: Maximum Likelihood & Bayesian Density Estimation

*Examples of true vs. estimated pdfs (Gaussian, mixture, Gamma).*

<img src="./Pic/IMG-20260506-WA0047.jpg" alt="Chapter 3 - MLE examples" width="600"/>

*(Duplicate file WA0047(1).jpg is identical)*

---

## Chapter 4: Expectation-Maximization & Mixture Density

*Illustration of EM iterations for a mixture of two Gaussians (L = 2,5,20).*

> ❌ **Image not yet available** in the uploaded set. Please add the slide showing `L=2, L=5, L=20`.

---

## Chapter 5: Hidden Markov Models (HMM)

*State transition matrix for weather example (rain/snow, cloudy, sunny).*

> ❌ **Image not yet available**. Expected matrix:  
> `[[0.4,0.3,0.3],[0.2,0.6,0.2],[0.1,0.1,0.8]]`

---

## Chapter 6: Bayesian Belief Networks

*Graph with nodes A, B, X, C, D and conditional probabilities.*

<img src="./Pic/IMG-20260506-WA0053.jpg" alt="Chapter 6 - Belief network" width="500"/>

---

## Chapter 7: Non‑parametric Methods (Parzen Windows)

*Parzen window estimates for a bivariate Gaussian with different window widths `h` and sample sizes `n`.*

<img src="./Pic/IMG-20260506-WA0051.jpg" alt="Chapter 7 - Parzen window table" width="550"/>

> The original figure also contains multiple density plots – this table shows numerical values for `h₁ = 2, 1, 0.5` and `n = 10, 100, 1000`.

---

## Chapter 8: Feature Reduction & Selection

*No figure was present in the original slides.*

---

## Chapter 9: k‑Nearest Neighbor Classifier

*Diagram with points `x₁, x₂, x₃`.*

<img src="./Pic/IMG-20260506-WA0049.jpg" alt="Chapter 9 - k-NN points" width="450"/>

> If this image is incorrect (shows red/blue/green points), it may belong to SVM. Please verify.

---

## Chapter 10: Linear Discriminants & SVM

*Mapping from ℝ² to ℝ³ using `(x₁², √2 x₁x₂, x₂²)` to obtain a non‑linear decision boundary.*

<img src="./Pic/IMG-20260506-WA0048.jpg" alt="Chapter 10 - SVM feature mapping" width="500"/>

<img src="./Pic/IMG-20260506-WA0050.jpg" alt="Chapter 10 - coordinates" width="400"/>

---

## Chapter 11: Neural Networks & Decision Trees

*Fully connected 3‑layer network and a fruit classification tree.*

<img src="./Pic/IMG-20260506-WA0052.jpg" alt="Chapter 11 - Network/table" width="600"/>

> The uploaded image shows repeated numeric entries – likely a placeholder. The original slide contains a clear network diagram and a tree (root: green/yellow/red, then size, shape).

---

## Chapter 12: Unsupervised Learning & Clustering

*How many clusters do you see? (resolution‑dependent).*

> ❌ **Image missing**. Original figure shows a 2D scatter plot with varying number of clusters.

---

## Chapter 13: Algorithm‑Independent Learning Issues

*Validation vs. training error – where to stop training.*

<img src="./Pic/IMG-20260506-WA0054.jpg" alt="Chapter 13 - Training/validation curves" width="500"/>

---

## Chapter 14: Structural & Syntactic Pattern Recognition

*Scene matching using attributed graphs (query, query graph, node labels, subgraph match).*

<img src="./Pic/IMG-20260506-WA0055.jpg" alt="Chapter 14 - Scene matching (a,b,c,d)" width="600"/>

---

## Additional Figures (uncertain mapping)

These images were uploaded but could not be confidently assigned to a specific chapter. They may be duplicates or parts of exercises.

<img src="./Pic/IMG-20260506-WA0044.jpg" alt="Uncertain table" width="400"/>

<img src="./Pic/IMG-20260506-WA0046.jpg" alt="Uncertain figure 1" width="400"/>

<img src="./Pic/IMG-20260506-WA0056.jpg" alt="Uncertain figure 2" width="400"/>

---

## 📝 How to use this README

- Make sure all image files are in the `./Pic/` folder **exactly** as named above.
- Adjust the `width` attribute inside `<img>` if you want larger/smaller images.
- For missing chapters (4,5,12), replace the `❌` placeholder with your actual images later.

---

**Happy studying!** 🎓  
*Last updated: May 2026*

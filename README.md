# Generative Adversarial Networks (GANs)

**ENGINEERING DIVISION | NYU Abu Dhabi**  
**Course:** ENGR-UH 3332 – *Applied Machine Learning: Generative Adversarial Networks*

---

## 🧠 Introduction
Deep neural networks are typically used for supervised learning tasks such as classification and regression. Generative Adversarial Networks (GANs), however, use neural networks for a different goal — **generative modeling**, an unsupervised learning approach that enables a model to discover patterns in input data and generate new, realistic samples that could plausibly come from the original dataset.  

*Reference:* [What Are Generative Adversarial Networks (GANs)? – Machine Learning Mastery](https://machinelearningmastery.com/what-are-generative-adversarial-networks-gans/)

A GAN consists of two neural networks:  
- **Generator** – creates fake samples from random noise  
- **Discriminator** – distinguishes between real samples (from the dataset) and fake ones (from the generator)  

Both models are trained together in a dynamic, adversarial process where each improves by competing against the other.

---

## 🎨 Dataset
**Anime Faces Dataset**  
This dataset contains over **63,000 cropped anime face images**.  
Since GANs are used for unsupervised learning, the dataset does not include labels.

---

## ⚙️ Requirements
1. Load the Anime Faces dataset into your notebook (Google Colab or local environment).  
2. Build the **Generator** and **Discriminator** neural networks.  
3. Train the **Discriminator** using a Binary Cross Entropy loss function.  
4. Train the **Generator** using the Discriminator’s output as part of its loss function.  
5. Alternate training between the two networks for multiple epochs to generate realistic anime faces.  
6. Save and display the generated images as output.

---


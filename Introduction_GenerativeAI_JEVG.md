# 📚 Notes: Introduction to Generative AI

## 🎙️ **Speaker**: Roger Martinez  
**Role**: Developer Relations Engineer at Google Cloud


## 🌟 **What We’ll Learn**  
1. Definition of Generative AI  
2. How Generative AI works  
3. Types of Generative AI models  
4. Applications of Generative AI  

---

## 🤖 **Understanding Generative AI**  
- **Definition**:  
  Generative AI is an AI technology that creates new content such as text, images, audio, and synthetic data.

- **Relation to AI & Machine Learning**:  
  - **AI (Artificial Intelligence)**: A computer science field focused on creating intelligent agents that reason, learn, and act autonomously.  
  - **Machine Learning (ML)**: A subset of AI where models learn from data without explicit programming.

---

## 🧩 **Machine Learning Models**  
- **Supervised Learning**: Uses **labeled data** to predict future outcomes (e.g., predicting tip amounts based on restaurant orders).  
- **Unsupervised Learning**: Uses **unlabeled data** to discover patterns or clusters (e.g., grouping employees by income and tenure).  
- **Semi-Supervised Learning**: Combines small labeled data with large unlabeled data for training neural networks.

### 🧪 **Supervised vs Unsupervised Learning**

```plaintext
+--------------------+            +---------+            +-----------------+            +--------+
|  Supervised        |            | Model   |            | Predicted Output |            | Error  |
|  Learning          |----------->|         |----------->|       (ŷ)        |----------->|        |
| (Input Data: x)    |            +---------+            +-----------------+            +--------+
|                    |                                  | Compare to       |
|                    |<----------------------------     | Expected Output  |
|                    |      Model Update                |       (y)        |
+--------------------+                                  +-----------------+


+--------------------+            +---------+            +-----------------------+
|  Unsupervised      |----------->| Model   |----------->|   Generated Example    |
|  Learning          |            +---------+            +-----------------------+
| (Input Data: x)    |
+--------------------+
```
---

## 🧠 **Deep Learning & Neural Networks**  
- **Deep Learning**:  
  - Subset of ML using **artificial neural networks** (ANNs).  
  - Can process complex patterns.  
  - Uses multiple layers (deep networks) for enhanced pattern recognition.

- **Neural Networks**:  
  - Inspired by the human brain.  
  - Made of interconnected nodes (neurons) that process and predict outcomes.

---

## 🎨 **Generative vs. Discriminative Models**  
- **Discriminative Models**: Classify or predict labels (e.g., identifying an image as a dog or cat).  
- **Generative Models**: Learn data patterns and **generate new content** (e.g., generating images of dogs).

---

## 🌐 **What Makes Generative AI Special?**  
- Generates new data similar to what it was trained on.  
- Example:  
  - Input: "I'm making a sandwich with peanut butter and..."  
  - Output: "jelly" (predicts the most likely continuation).

- **Outputs of GenAI**:  
  - Text (e.g., stories, code)  
  - Images (e.g., art generation)  
  - Audio (e.g., music, speech)  
  - Video (e.g., animations)

---

## ⚡ **Transformers in GenAI**  
- **Transformers**: Revolutionized natural language processing (NLP) in 2018.  
- **Structure**:  
  - **Encoder**: Processes input.  
  - **Decoder**: Generates output based on encoded data.  
- **Challenge**:  
  - **Hallucinations**: Inaccurate or nonsensical outputs due to insufficient or noisy training data.

---

## ✍️ **Prompt Design**  
- **Prompt**: Text given to an LLM to generate a specific output.  
- **Prompt Design**: Crafting effective prompts for desired results.

---

## 🏗️ **Generative AI Model Types (Text Input)**  
1. **Text-to-Text**: Language translation, summarization.  
2. **Text-to-Image**: Generate images from descriptions (e.g., using diffusion models).  
3. **Text-to-Video**: Create videos from scripts.  
4. **Text-to-3D**: Generate 3D models for virtual environments.  
5. **Text-to-Task**: Perform specific tasks (e.g., navigating interfaces, answering questions).

---

## 🏛️ **Foundation Models**  
- **Definition**: Large AI models pre-trained on massive datasets.

### 🔄 **Foundation Model Workflow**

```plaintext
+----------------+      Training       +--------------------+       Adaption       +-----------------------+
|     Data       |  ---------------->  |   Foundation Model  |  ---------------->  |         Tasks         |
+----------------+                     +--------------------+                      +-----------------------+
| - Text         |                     |                    |                      | - Question Answering  |
| - Image        |                     |                    |                      | - Sentiment Analysis  |
| - Speech       |                     |                    |                      | - Information Extraction|
| - Structured   |                     |                    |                      | - Image Captioning    |
|   Data         |                     |                    |                      | - Object Recognition  |
| - 3D Signals   |                     |                    |                      | - Instruction Following|
+----------------+                     +--------------------+                      +-----------------------+
```


 
- **Applications**:  
  - Sentiment analysis  
  - Image captioning  
  - Object recognition  
- **Tools**:  
  - **Vertex AI Studio**: Create & deploy GenAI models with pre-trained options.  
  - **Vertex AI Agent Builder**: Build chatbots and assistants with minimal coding.  
  - **Gemini**: Google’s multimodal AI for text, images, audio, and code.

---

## 🛠️ **Generative AI for Coding**  
- **Gemini Use Case**: Convert Python DataFrame to JSON.  
- **Code Generation Features**:  
  - Debugging  
  - Line-by-line code explanation  
  - SQL query creation  
  - Cross-language code translation  
  - Documentation generation

---

## 🚀 **Key Takeaways**  
- Generative AI **creates** rather than just **predicts**.  
- It uses deep learning, particularly **transformers**, for complex tasks.  
- **Prompt design** and **training data quality** are crucial for meaningful outputs.  
- **Foundation models** like those in **Vertex AI** and **Gemini** power real-world GenAI applications.

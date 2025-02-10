
# <img src="https://raw.githubusercontent.com/agentnovax/www.agentnovax.com/main/assets/banners/AgentNovaX-Banner.png" alt="AgentNovaX Banner" height="300" width="100%">

---

# AgentNovaX

Welcome to **AgentNovaX**! 🌍✨

At [AgentNovaX](https://www.agentnovax.com/), our vision is to create a world where **innovation**, **collaboration**, **technology**, and **sustainability** work hand-in-hand to empower communities. We aim to provide tools that **simplify tasks**, **increase productivity**, and contribute to a **better planet**. Through **creativity**, **inclusivity**, and **environmental consciousness**, we strive to inspire a global movement toward shared success and continuous growth. 🌱💡


---

# 🚀 **AgentNovaX-SpringAI-DeepSeek** - Spring Boot Project with Spring AI, Ollama and Deepseek

This project is a **Spring Boot API** that leverages **Spring AI**, **Ollama**, and the **DeepSeek 1.5B LLM model** to provide intelligent responses and perform advanced natural language processing (NLP) tasks. It is designed to explore the capabilities of the DeepSeek model while comparing it with other LLMs and techniques such as O1 and examining training methodologies like supervised fine-tuning and reinforcement learning.

---

## 🛠 Features

- **Integration with Spring AI**: Simplifies the usage of large language models (LLMs) in Spring applications.
- **Ollama Compatibility**: Uses the Ollama framework for seamless model hosting and interaction.
- **DeepSeek 1.5B Model**: Incorporates the advanced DeepSeek 1.5B parameter model for NLP tasks.
- **RESTful Endpoints**: Provides APIs to interact with the model for tasks like text generation and classification.

---

## 📦 Dependencies

| Dependency       | Version | Description                                                                 |
|-------------------|---------|-----------------------------------------------------------------------------|
| `Spring Boot`    | 3.x+    | Framework for building Java-based applications.                            |
| `Spring AI`      | Latest  | Simplifies AI model integration in Spring projects.                        |
| `Ollama`         | Latest  | A tool for hosting and managing LLMs locally or in the cloud.              |
| `DeepSeek 1.5B`  | -       | A compact, fine-tuned LLM optimized for balanced performance and usability.|

---

## 📝 Pros and Cons of DeepSeek 1.5B

### ✅ Pros
1. **Efficiency**: A smaller model size (1.5B parameters) means faster inference times compared to larger LLMs like GPT-3.
2. **Fine-Tuned Performance**: Designed for specific domains with high accuracy.
3. **Cost-Effective**: Requires less computational power for deployment and inference.
4. **Open Ecosystem**: Supports integration with popular frameworks like Ollama and Spring AI.

### ❌ Cons
1. **Limited Generalization**: Smaller models may struggle with broad, diverse tasks compared to models with tens of billions of parameters.
2. **Less Knowledge Depth**: May lack the extensive training data coverage found in models like GPT-4 or LLaMA 2.
3. **Scaling Issues**: Not ideal for handling very complex queries or tasks requiring reasoning over extensive context.

---

## 🔍 Comparison: DeepSeek 1.5B vs. O1 and Other LLMs

| Feature             | DeepSeek 1.5B        | O1                     | GPT-4                  | LLaMA 2               |
|---------------------|----------------------|------------------------|------------------------|-----------------------|
| **Model Size**      | 1.5B parameters      | 1.3B parameters        | ~175B parameters       | 7B/13B/70B variants  |
| **Inference Speed** | ⚡ Fast              | ⚡⚡ Faster             | 🐢 Slower              | ⚡⚡ Faster            |
| **Domain-Specific** | ✅ Yes               | ✅ Yes                 | ❌ Broad               | ❌ Broad              |
| **Cost to Run**     | 💲 Low               | 💲 Low                 | 💰 High                | 💲 Moderate           |
| **Open Source**     | ✅ Yes               | ✅ Yes                 | ❌ No                  | ✅ Yes                |

---

## 🤖 Training Approaches: Supervised Fine-Tuning vs. Reinforcement Learning

### 🎓 Supervised Fine-Tuning
- **Definition**: Involves training a model on a labeled dataset where correct input-output pairs are known.
- **Pros**:
    - Easier to implement.
    - Produces predictable and consistent outputs.
    - Effective for domain-specific applications.
- **Cons**:
    - Limited by the quality and size of the training dataset.
    - Cannot adapt dynamically to new scenarios.

### 🏆 Reinforcement Learning (e.g., RLHF)
- **Definition**: Uses feedback from humans or other agents to fine-tune a model iteratively.
- **Pros**:
    - Enables more nuanced, human-like responses.
    - Adaptive to broader tasks and diverse use cases.
- **Cons**:
    - Computationally expensive.
    - Requires complex setup and manual feedback loops.

---

## 🚀 Quick Start

### 1️⃣ Clone the Repository
```bash
git clone <repository-url>
cd springboot-ai-api
```

### 2️⃣ Configure Properties
Add your configuration in `application.yml`:
```yaml
spring:
  ai:
    model: deepssek-1.5b
    ollama:
      host: localhost
      port: 11400
```

### 3️⃣ Start the API
```bash
./mvnw spring-boot:run
```

---

## 📖 API Endpoint

### 1. **Generate Text**
```http
GET /prompt
```
- **Headers**: `Content-Type: application/json`
- **Parameter**:
  ```text
  ?prompt=Write a short story about AI.
  ```
- **Response**:
  ```text
    Once upon a time, an AI learned empathy...
  ```

---

## 🔧 Future Improvements
- Integration with more models like GPT-4 and LLaMA 2.
- Support for distributed inference using Kubernetes.
- Advanced fine-tuning features via reinforcement learning.

---

## ⚖ License
Licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).  - see the [LICENSE](LICENSE.md) file for details.

---

## Follow AgentNovaX 🌍

Stay connected with **AgentNovaX** through our social media channels:

- [X (Twitter)](https://twitter.com/agentnovax) 🐦
- [LinkedIn](https://linkedin.com/company/agentnovax) 🔗
- [Instagram](https://www.instagram.com/agentnovax/) 📸
- [Facebook](https://www.facebook.com/profile.php?id=61571252049491) 📘
- [YouTube](https://www.youtube.com/@agentnovaxp) 🎥

---

## NovaLeaf Concept 🌱

**NovaLeaf** is an initiative focused on environmental sustainability, aiming to contribute to a greener planet. Through this initiative, **AgentNovaX** is committed to planting trees, fostering green projects, and encouraging eco-friendly practices among individuals and communities.

- **Plant a Tree, Empower a Community**: For every milestone achieved in our platform, a tree will be planted in a designated area.
- **Green Nova Trees**: These trees represent our growth and commitment to sustainability, and each one is named for the cause it supports.
- **Join the Movement**: Become part of the **NovaLeaf** family and help us plant the future, one tree at a time. 🌳

🌟 **Please consider starring this repository to support the NovaLeaf initiative** 🌟

For more information, visit [NovaLeaf](https://novaleaf.agentnovax.com).

---

## DataFlux 🔄

**DataFlux** provides free tools for data conversion, JSON/YAML beautification, and validation to help developers and data enthusiasts streamline their workflow.

- Tools available: JSON/YAML Beautifiers and Validators, JSON/YAML conversion, Text Compare, JavaScript Validators, and more.
- Visit [DataFlux](https://dataflux.agentnovax.com) to explore our tools and enhance your productivity.

---
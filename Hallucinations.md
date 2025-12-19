# Understanding AI Hallucinations

*Summary of IBM's guide on the causes, risks, and prevention of AI-generated errors.*

## 1. What are AI Hallucinations?
AI hallucination is a phenomenon where a generative AI tool (like a chatbot or image generator) produces outputs that are not based on training data or fail to follow an identifiable pattern. To a human, these results appear as confident but incorrect "facts" or surreal imagery.

## 2. Why Do They Happen?
- **Data Quality:** Training on biased, incomplete, or unrepresentative data.
- **Overfitting:** When a model "memorizes" training data too well, it fails to generalize to new information correctly.
- **Complexity:** Transformer models may incorrectly decode information during the generation process.

## 3. Real-World Risks
- **Misinformation:** News bots spreading unverified or false stories.
- **Healthcare:** Incorrect medical diagnosis or analysis.
- **Security:** Vulnerability to "adversarial attacks" where small input tweaks cause the AI to malfunction.

## 4. How to Prevent Hallucinations
IBM recommends several strategies for developers and organizations:
* **High-Quality Training Data:** Ensure diversity and balance in datasets.
* **Human-in-the-Loop:** Have subject matter experts validate AI outputs.
* **Data Templates:** Use predefined formats to force output consistency.
* **Strict Constraints:** Limit the model's response range using probabilistic thresholds.

## 5. The "Creative" Side
While usually seen as a defect, AI hallucinations are leveraged in creative fields such as:
- **Art & Design:** Creating surreal, dream-like visuals.
- **Gaming:** Generating unpredictable and novel virtual worlds.
- **Data Visualization:** Uncovering unconventional connections in complex data.

---
*Source: [IBM - What are AI Hallucinations?](https://www.ibm.com/think/topics/ai-hallucinations)*

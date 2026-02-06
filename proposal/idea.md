# MAE301 Project Idea Pitch - Team YEEURT

## 1. Project Title
The De-Fluffer: AI-Powered Concept Extractor for Efficient Learning

## 2. Team Members
*   Team YEEURT
*   Gemini CLI Assistant

## 3. Problem Statement
*   **Who is the user?**
    Students, researchers, or anyone needing to quickly grasp core concepts from dense educational materials.
*   **What problem or pain point do they experience today?**
    The current methods of learning from lectures and textbooks are inefficient. They contain excessive "fluff," lack clear application examples, and suffer from poor organization. This makes it difficult to quickly extract core concepts, rules, formulae, and application steps, hindering efficient learning in a fast-paced world. Users spend too much time sifting through materials instead of engaging in practical learning.

## 4. Why Now?
*   **Why does this problem matter in the next 3-5 years?**
    As information proliferation accelerates and educational demands intensify, the need for efficient learning tools will become even more critical. Students and professionals will require smarter ways to consume and apply knowledge to stay competitive and effective.
*   **What changed (technology, regulations, culture) that makes this possible now?**
    The significant advancements in AI, particularly in Natural Language Processing (NLP) and Large Language Models (LLMs), now allow for information to be retrieved and processed with unprecedented speed and specificity. This enables AI to act as an intellectual assistant, capable of directly extracting and presenting targeted information from complex texts, thereby fostering a "man-machine" synergy similar to Tony Stark and Jarvis for learning efficiency. This is contingent on the AI remaining accurate and neutral.

## 5. Proposed AI-Powered Solution
*   **What does your product do for the user?**
    The "De-Fluffer" processes uploaded course materials (e.g., lecture notes, slides, textbook chapters) to generate a "distilled" view. This includes concise summaries of core concepts, an extracted list of key formulae, rules, and definitions, and auto-generated flashcards for quick review.
*   **Where does AI/ML add unique value vs simple rules / heuristics?**
    AI/ML provides unique value through:
    *   **Abstractive Summarization:** Understanding context and semantics to produce coherent, human-like summaries beyond keyword extraction.
    *   **Concept Recognition & Categorization:** Intelligently identifying and classifying various types of information (formulas, definitions, rules) based on linguistic patterns.
    *   **Intelligent Question Generation:** Creating relevant review questions for flashcards that test conceptual understanding, not just rote memorization.

## 6. Initial Technical Concept
*   **What data would you need (or already have)?**
    Access to a variety of educational texts including lecture transcripts (potentially from speech-to-text), PDF textbooks/slides, and user-provided notes.
*   **What model(s) might you use (e.g., GPT-style text model, classifier, recommender, vision model)?**
    The core would likely be a powerful pre-trained Large Language Model (LLM) with capabilities in summarization, information extraction, and question-answering. This could be accessed via API (e.g., Gemini, OpenAI) or an open-source model hosted locally.
*   **How could your nanoGPT work feed into this (e.g., custom generative component, fine-tuning, evaluation)?**
    Our `nanoGPT` will be instrumental. It can be fine-tuned on specific subject matter (e.g., a particular course's textbook, lecture notes) to specialize in generating highly accurate and domain-specific extractions and summaries, acting as a custom generative component tailored to the user's learning domain.

## 7. Scope for MVP
*   **What can you realistically build in ~6 weeks?**
    Within 6 weeks, we aim to build a foundational system capable of accurately processing a single, clean text document to extract its core educational components. The focus will be on the robustness of the extraction algorithm rather than broad input compatibility or advanced UI.
*   **Define a very concrete v1 feature: “A user can [...] and our system returns [...]”**
    A user can upload a single plain text document (e.g., lecture notes or a course-related article), and our system returns an extracted list of key terms, definitions, and relevant formulas from the document.

## 8. Risks and Open Questions
*   **Top 3 unknowns:**
    1.  **Over-Generalization/Under-Generalization:** Will the `nanoGPT` fine-tuning lead to models that are too specific (only work for one type of document) or too general (miss fine-grained details) for concept extraction?
    2.  **Computational Resources for Training:** Even with the provided hardware (RTX 5060 8GB VRAM), fine-tuning an LLM on a large corpus for this task might exceed local capabilities without significant optimization or external resources.
    3.  **Evaluation Metrics:** How do we objectively measure the "quality" and "completeness" of an extracted concept list, definitions, or formulas, especially for comparing across different models or configurations?

## 9. Planned Data Sources
*   **Curated Personal & Public Hybrid:** A combination of the user's personal lecture notes (manually pre-processed for clarity and potentially including annotations for terms/definitions/formulas) and a smaller, highly curated set of public domain textbooks or articles directly relevant to a specific course topic (e.g., Electrical Engineering, Computer Science fundamentals) to augment the dataset for fine-tuning.

---
**Video Pitch Link:** [Insert Link to 5-minute Video Pitch Here]

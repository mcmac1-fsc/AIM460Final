# Project AIM 460: Factual Narrative Triage using Sentence Embeddings

## A Final Report on Classifier Architecture and Validation

<div align="center">
  <img 
    src="https://raw.githubusercontent.com/mcmac1-fsc/AIM460Final/main/Gemini_Generated_Image_1bm35b1bm35b1bm3.png" 
    alt="Semantic Ambiguity Spectrum Diagram" 
    width="800"
  />
</div>

### Abstract

This report details the design and validation of a high-accuracy **Natural Language Processing (NLP) system** for classifying factual narratives against specific New York Penal Law (PL) statutes. The primary objective was to overcome the **semantic ambiguity** inherent in legal texts, specifically differentiating between closely related Stalking subdivisions ($\text{PL 120.45(2)}$ and $\text{PL 120.45(3)}$) and scaling the solution to a comprehensive 21-charge Triage Index. The project successfully migrated from a general-purpose language model to a highly-specific **Two-Step Classifier (V46)** achieving a validated accuracy of $\sim97.5\%$ for the Stalking subdivision task, and then further developed a **Stacked Ensemble Classifier (V10)** to deliver robust, multi-charge Triage Evidence.

# Semantic Classification Prompt for TikTok Comment Analysis

This repository contains the semantic classification prompt used in the undergraduate Computer Science thesis project and accompanying research paper **"Collection, Classification, and Analysis of TikTok Comments Involving Children and Pre-Adolescents Using Artificial Intelligence"**.

## Overview

The prompt was designed to support the semantic analysis of public TikTok comments posted on content involving children and pre-adolescents. Its purpose is to guide a Large Language Model (LLM) in identifying linguistic, behavioral, symbolic, emotional, and contextual indicators that may be relevant to research on child online safety.

The prompt was developed as part of an academic research project focused on supporting the collection, organization, and analysis of large volumes of public social media interactions.

The prompt is used as part of a broader system responsible for:

* Collecting public TikTok comments;
* Classifying comments into risk categories;
* Assigning behavioral tags;
* Generating explanations and confidence scores;
* Supporting the construction of structured datasets for research purposes.

## Prompt Development

The prompt was developed using three primary sources:

1. Academic literature on online grooming, child objectification, child exposure on social media, and online safety;
2. Publications and educational materials produced by organizations dedicated to child protection;
3. Empirical observations conducted during the manual analysis of TikTok publications involving children and pre-adolescents.

These sources were used to define contextual indicators, behavioral patterns, and classification criteria employed by the system.

## Classification Categories

The prompt instructs the language model to classify each comment into one of the following categories:

* **Neutral** – No apparent indicators of inappropriate or risky behavior;
* **Sensitive** – Ambiguous, suggestive, overly intimate, or potentially inappropriate interactions requiring additional attention;
* **High Risk** – Comments containing stronger indicators of sexualization, objectification, private contact attempts, platform migration, coded language, or other potentially risky behaviors.

In addition to the main classification, the system may assign behavioral tags, provide a brief justification, and return a confidence score for each analyzed comment.

## Research Purpose

This prompt was created exclusively for academic and research purposes.

It is **not** intended to:

* Identify criminals or offenders;
* Infer criminal intent;
* Produce legal evidence;
* Perform law enforcement activities;
* Make definitive judgments about users or comments.

The system is designed to identify patterns and indicators that may be relevant for research and exploratory analysis.

## Transparency and Reproducibility

This repository is publicly available to promote transparency, reproducibility, and future research related to child online safety, social media analysis, and the application of artificial intelligence to large-scale textual data.

## License

This repository is provided for academic, educational, and research purposes.

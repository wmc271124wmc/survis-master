# Multi-Agent LLM Systems: Interactive Literature Review

[![COMP4126 Research Methods](https://img.shields.io/badge/Course-COMP4126_Research_Methods-blue)](https://www.example.com/course_link) [![License](https://img.shields.io/badge/License-See_Details-lightgrey)](LICENSE) This repository contains an interactive visualization of a literature review on multi-agent Large Language Model (LLM) systems. This project was created as part of the COMP4126 Research Methods coursework and is powered by [SurVis](https://github.com/fabian-beck/survis), a visual literature browser framework.

## Overview

This interactive literature browser presents a curated collection of 10 key papers exploring diverse approaches to multi-agent LLM systems. The papers are categorized based on their primary agent interaction paradigms, application domains, and memory integration approaches, facilitating a structured exploration of this rapidly emerging research field.

## Table of Contents

- [Literature Categorization](#literature-categorization)
  - [Self-Improvement Methods](#self-improvement-methods)
  - [Debate-Based Methods](#debate-based-methods)
  - [Role-Based Collaboration Frameworks](#role-based-collaboration-frameworks)
  - [Game-Theoretic Approaches](#game-theoretic-approaches)
  - [Cross-cutting Dimensions](#cross-cutting-dimensions)
- [How to Use the Visualization](#how-to-use-the-visualization)
- [Technical Information](#technical-information)
- [Paper Selection Methodology](#paper-selection-methodology)
- [About the Coursework](#about-the-coursework)
- [Local Installation](#local-installation)
- [Credits](#credits)
- [License](#license)
- [Contributing](#contributing)

## Literature Categorization

The papers are organized into four main categories based on how LLM agents interact:

### 1. Self-Improvement Methods
Papers focusing on agents learning from their own experiences or reflections.
* *Reflexion: Language Agents with Verbal Reinforcement Learning*
* *Improving Language Model Negotiation with Self-Play and In-Context Learning from AI Feedback*
* *Unleashing Cognitive Synergy through Multi-Persona Self-Collaboration*

### 2. Debate-Based Methods
Papers using structured argumentation between multiple agents.
* *Improving Factuality and Reasoning through Multiagent Debate*
* *Encouraging Divergent Thinking through Multi-Agent Debate*
* *ChatEval: Towards Better LLM-Based Evaluators Through Multi-Agent Debate*

### 3. Role-Based Collaboration Frameworks
Papers establishing structured workflows with specialized agent roles.
* *CAMEL: Communicative Agents for Mind Exploration*
* *MetaGPT: Meta Programming for Multi-Agent Collaboration*
* *Multi-Agent Collaboration: Harnessing Intelligent LLM Agents*

### 4. Game-Theoretic Approaches
Papers applying multi-agent interaction to game scenarios.
* *Exploring LLMs for Communication Games: An Empirical Study on Werewolf*

### Cross-cutting Dimensions
The literature is also analyzed across:
* **Application Domains:** Code generation, reasoning, negotiation, evaluation.
* **Memory Integration Approaches:** External memory, in-context experience, no explicit memory.

## How to Use the Visualization

1.  **Filtering:** Use the tag selectors at the top of the visualization page to filter papers by categories, application domains, or memory integration approaches.
2.  **Searching:** Utilize the search box to find papers by author, title, or specific keywords.
3.  **Visualization Modes:** Explore different visualization modes (if available in your SurVis setup) to understand relationships and patterns among the papers.
4.  **Details on Demand:** Click on any paper in the visualization to expand and read its full abstract and other details.

## Technical Information

This visualization was created using [SurVis](https://github.com/fabian-beck/survis), a framework for Visual Literature Browsers developed by Beck et al. The literature data is stored in BibTeX format (`.bib`) and converted to JSON (`.json`) for the interactive visualization.

## Paper Selection Methodology

The 10 papers included in this review were selected under the supervision of Dr. Qiao Lin. The selection process involved a systematic search focusing on influential multi-agent LLM research published primarily in 2023. The chosen works represent key developments and diverse approaches within the field.

## About the Coursework

This interactive visualization serves as a component of a comprehensive literature review on multi-agent LLM systems for the COMP4126 Research Methods course. The full literature review encompasses:

* An analysis of current challenges in the research field.
* A clearly defined scope for the survey.
* Detailed summaries of each selected paper, organized by the categories outlined above.
* An in-depth discussion of emerging research trends and future directions.

## Local Installation

To run this visualization locally on your machine:

1.  **Clone the Repository:**
    ```bash
    git clone [https://your-repository-url.git](https://your-repository-url.git) # Replace with your actual repository URL
    cd your-repository-directory
    ```
2.  **Open in Browser:**
    Navigate to the directory where you cloned the repository and open the `index.html` file (or `src/index.html` depending on your file structure) in a modern web browser (e.g., Chrome, Firefox, Edge).

3.  **No Additional Setup:**
    No additional installation, dependencies, or server setup are required to view the visualization.

## Credits

* **Visualization Framework:** [SurVis](https://github.com/fabian-beck/survis) by Fabian Beck et al.
* **Academic Supervisor:** Dr. Qiao Lin
* All papers included in the visualization are properly cited with links to their original sources.

## License

The SurVis framework is provided under its original license (please refer to the [SurVis repository](https://github.com/fabian-beck/survis) for specific details).

The literature collection, categorization, and analysis presented in this repository are part of academic coursework for COMP4126 Research Methods (2025). If you reuse or reference this work, please provide appropriate citation.

## Contributing

This project is primarily an academic coursework submission. However, if you have suggestions for improving the README or find issues with the visualization setup, feel free to open an issue.

---

Created for COMP4126 Research Methods, 2025.

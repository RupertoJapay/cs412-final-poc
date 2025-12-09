# CS412 Final Requirement: Netflix Locus of Control PoC

## 📌 Project Overview
This repository contains the *Proof-of-Concept (PoC)* for our CS412 Final Requirement (Group Work).
We are exploring the *"Locus of Control"* dilemma in Adaptive Systems, specifically within the context of the *Netflix Recommender System*.

### 🎯 Core Argument
The project contrasts two modes of interaction based on the "Locus of Control" controversy:
* *Mode A (Agent Control):* Represents the current state of "frictionless" streaming (Auto-play, implicit tracking) where the system decides for the user.
* *Mode B (User Control):* Represents our proposed ethical alternative (Explicit overrides, transparency) where the user retains ultimate decision-making power.

*Thesis:* We argue that *Mode B (User Control)* is ethically superior because it prevents "filter bubbles" and ensures the user model remains accurate to the user's actual intent.

## 📂 Files
* index.html: The single-file, self-contained prototype including all HTML, CSS (Tailwind), and JavaScript logic.

## 🚀 How to Run
Since this is a client-side prototype, you do not need to install complex dependencies.

### Option 1: Live Demo (Recommended)
You can test the active prototype here:
*https://rupertojapay.github.io/cs412-final-poc/*
(Note: Ensure GitHub Pages is enabled in Settings > Pages > Branch: main)

### Option 2: Local Testing
1.  Clone the repository:
    
    git clone [https://github.com/RupertoJapay/cs412-final-poc.git](https://github.com/RupertoJapay/cs412-final-poc.git)
    
2.  Navigate to the folder and open index.html in any modern web browser (Chrome, Edge, Firefox).

## 🕹️ Controls & Features
The prototype demonstrates the trade-off between efficiency and autonomy:

1.  *System Logic Toggle:* Use the buttons at the top to switch between *Agent Mode* and *User Mode*.
2.  *Agent Mode (Red):* Observe how the system "locks" you out of decisions. It detects a "Predicted Mood" and auto-plays content immediately.
3.  *User Mode (Gray):* Observe the *Override Panel* appearing. This allows you to:
    * Manually correct the predicted mood (e.g., change "Bored" to "Focused").
    * View the *Transparency Explanation* (why a recommendation was made).

## 👥 Group Members & Contribution Summary
* *Jezrelle Cris Beriana:* Lead Researcher. Authored the Introduction and Thesis Statement. Wrote the primary arguments regarding the "Inaccuracy of Implicit Feedback" and "Trust Through Transparency."
* *Ruperto C. Japay III:* Lead Developer. Responsible for the core HTML structure and JavaScript logic for the Proof-of-Concept. Implemented the "Mode A vs. Mode B" toggle functionality.
* *Paulene G. Pacalda:* Analyst & Defense. Authored the "Counter-Argument & Rebuttal" section. Wrote the third argument regarding "Filter Bubbles" and ensured theoretical alignment with course concepts.
* *John Kyle Cuarteros:* Editor & QA. Responsible for the Abstract, Conclusion, and Reference compilation. Managed the GitHub repository documentation (README) and final formatting of the PDF submission.
CS412 PoC: Netflix Control Dilemma

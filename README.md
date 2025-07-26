# Gnanadeepti 🧭 – Agentic Career Counseling Companion

"Lighting the path to your dream career with clarity, courage, and code."

## Overview

Gnanadeepti is an AI-powered intelligent assistant designed to provide personalized career path suggestions. Built on IBM Cloud, this tool helps individuals explore potential career avenues based on their academic stream, interests, strengths, and even high-scoring subjects.

## Features

* **Personalized Career Suggestions:** Recommends career paths tailored to user inputs.
* **Multi-factor Analysis:** Considers academic stream, personal interests, inherent strengths, and specific high-scoring subjects for comprehensive recommendations.
* **Wide Range of Streams:** Supports various academic streams including AI & DS, AI & ML, CSM, CAI, CSE, IT, Cybersecurity, IoT, ECE, EEE, Mechanical, Civil, and Pharmacy.
* **Interest-Based Matching:** Connects user interests (e.g., problem-solving, coding, research) to relevant career roles.
* **Strength-Based Matching:** Aligns user strengths (e.g., math, logic, creativity, analysis) with suitable professions.
* **Subject-Specific Influence:** Integrates high scores in subjects like Maths, Biology, and English to refine suggestions.

## How it Works

The core of Gnanadeepti is a Python-based recommendation engine that utilizes predefined mappings between academic streams, interests, strengths, and high-scoring subjects to a comprehensive list of career options.

The `career_advisor` function takes the following inputs:
* `stream` (string): The academic stream of the user (e.g., "AI and DS", "CSE", "Mechanical").
* `interest` (string): A key interest of the user (e.g., "problem-solving", "coding", "research").
* `strength` (string): A core strength of the user (e.g., "math", "logic", "creativity").
* `high_scores` (list of strings, optional): A list of subjects where the user has scored highly (e.g., ["Maths", "English"]).

Based on these inputs, the function aggregates potential careers from its internal knowledge base and returns a sorted list of unique recommendations.

## Installation

To run Gnanadeepti locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Kaja-avinash/Gnanadeepti-Agentic-Career-Counseling-Companion.git](https://github.com/Kaja-avinash/Gnanadeepti-Agentic-Career-Counseling-Companion.git)
    cd Gnanadeepti-Agentic-Career-Counseling-Companion
    ```
    (Note: The repository is located at `https://github.com/Kaja-avinash/Gnanadeepti-Agentic-Career-Counseling-Companion`.)

2.  **Ensure you have Python installed.** This project uses Python 3.11.

3.  **No specific external libraries are required** beyond a standard Python installation to run the core logic in `CareerBotPlus.ipynb`.

## Usage

To get career recommendations, you can interact with the provided Jupyter Notebook (`CareerBotPlus.ipynb`).

1.  **Open the Jupyter Notebook:**
    ```bash
    jupyter notebook CareerBotPlus.ipynb
    ```

2.  **Modify the input variables** in the code cell where `stream`, `interest`, `strength`, and `high_scores` are defined:

    ```python
    stream = "AI and DS"
    interest = "problem-solving"
    strength = "coding"
    high_scores = ["Maths", "English"]
    ```

    Replace these values with your own academic background, interests, and strengths.

3.  **Run all cells** in the notebook. The final cell will print the career recommendations.

    Example Output:
    ```
    🎓 Career Recommendations:

    1. AI Developer
    2. AI Researcher
    3. Control Systems Engineer
    4. Cybersecurity Analyst
    5. Data Analyst
    6. Data Scientist
    7. ML Engineer
    8. Penetration Tester
    9. Regulatory Affairs Specialist
    10. Software Developer
    11. Technical Consultant
    ```

## Contributing

We welcome contributions to enhance Gnanadeepti! If you have suggestions for new career paths, interests, strengths, or improvements to the recommendation logic, please feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-feature-name`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add new feature'`).
5.  Push to the branch (`git push origin feature/your-feature-name`).
6.  Open a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
(Note: You should create a LICENSE file in your repository if you haven't already).

# Prompt Engineering Impact on Generative Code Models

## Project Overview
This project presents a benchmarking framework designed to analyze how different prompt engineering strategies influence the performance and behavior of generative code models. The system reads programming problem definitions from JSON files and evaluates multiple prompting techniques—such as zero-shot, few-shot, chain-of-thought, persona, and template prompts—by generating two key performance metrics for each model–strategy combination. Through these comparisons, the project demonstrates that different prompts are effective for different types of problems, offering insights that help improve the accuracy, speed, and overall reliability of AI-assisted programming by guiding better prompt selection for each task.

## Prompt Strategies Used
- **Zero-Shot:** AI generates code with no examples, relying only on the task description.
- **Few-Shot:** AI is given a few example problems and solutions to learn from.
- **Chain-of-Thought:** AI is guided to reason step-by-step before generating code.
- **Persona-Based:** AI takes on an expert developer role for better coding style.
- **Template-Based:** AI follows a fixed code template for consistent structure.

## Results Summary
- Persona prompting works best for common algorithmic problems by activating expert coding patterns.
- Few-Shot helps with specialized or unfamiliar problems using examples.
- Zero-Shot is effective for simple tasks without extra context.
- Chain-of-Thought, though useful for reasoning, was less efficient for code generation.
- Template-based prompts gave steady but less flexible results.

## Conclusion
The performance of AI-generated code varies with the prompt type and task. Choosing the right prompt for each problem can improve accuracy, speed, and efficiency. This study helps in designing better AI tools for software development with adaptive prompt selection.

## Technologies Used
- Python
- Hugging Face Transformers
- PyTorch
- Pandas and Matplotlib (for data analysis and visualization)

## How to Run
1. Clone the repository.
2. Install required packages listed in `requirements.txt`.
3. Run the benchmark script to evaluate prompt strategies on Java coding tasks.
4. View generated reports with performance statistics and visualizations.

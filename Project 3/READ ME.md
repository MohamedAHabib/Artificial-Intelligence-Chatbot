# AI Career Path Recommender

This project implements a simple AI-powered career path recommender based on user-provided skills. It uses TF-IDF vectorization and cosine similarity to match user skills with predefined career roles and their associated skills.

## Features

- **Skill-based Recommendation**: Recommends career paths based on a weighted list of user skills.
- **TF-IDF Vectorization**: Utilizes TF-IDF to convert skill sets into numerical representations for similarity calculation.
- **Cosine Similarity**: Measures the similarity between user skills and career role skills.
- **Cold Start Fallback**: Provides a fallback mechanism for new roles with limited skill data.

## How to Use

1.  **Prepare Data**: Ensure you have a `raw_skills.csv` file in the same directory as the notebook. This CSV should contain at least two columns: `role` and `skills`.
2.  **Run the Notebook**: Execute all cells in the `ArtificialIntelligenceproject3.ipynb` notebook.
3.  **Enter Your Skills**: When prompted, enter at least three skills, ordered from most to least important, separated by commas (e.g., `Python, Cloud Computing, Automation`).
4.  **View Recommendations**: The system will display the top recommended career paths with their match scores and key skills.

## Dependencies

This project requires the following Python libraries:

- `pandas`
- `scikit-learn`

These can be installed using pip:

```bash
pip install -r requirements.txt
```

## Project Structure

- `ArtificialIntelligenceproject3.ipynb`: The main Jupyter Notebook containing the project logic.
- `raw_skills.csv`: (Expected) CSV file containing career roles and their associated skills.
- `requirements.txt`: Lists the Python dependencies.
- `README.md`: This file.
- `LICENSE`: The project license.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

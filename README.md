Data Visualization Chatbot with Insights Generation

This project is a Gradio-based chatbot application that integrates with the Ollama LLM (Llama2) to assist users in uploading datasets, generating visualizations, and obtaining insights. The tool also allows users to combine multiple visualizations and insights into actionable business recommendations.

Technical Problem to Solve
Analyzing and visualizing data can be challenging for users without technical expertise in programming or data visualization tools. This project addresses the following problems:

Simplifying the process of dataset analysis and visualization.
Automating the generation of insights from visualizations using an LLM.
Allowing users to combine insights from multiple visualizations for comprehensive analysis.
Features
Dataset Upload and Processing: Upload Excel datasets and generate a structured summary using Llama2.
Visualization Suggestions: Receive suggestions for appropriate visualizations based on dataset columns.
Generate Visualizations: Create bar charts, line charts, and scatter plots based on user requests.
Insights from Visualizations: Generate meaningful insights for uploaded visualizations using Llama2.
Combined Insights Generation: Upload multiple visualizations and insights to create actionable business recommendations.
How to Run
Clone this repository to your local machine:

bash
Copy code
git clone <your-repository-url>
cd <your-repository-folder>
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Ensure you have the Ollama CLI installed and configured:

Follow Ollama's installation guide.
Launch the Gradio interface:

bash
Copy code
python data_visualization_chatbot.py
Access the application in your browser at the default Gradio URL.

How to Verify the Output
Test Cases
Dataset Upload: Upload the provided sample dataset (sample_data.xlsx) and verify that a summary file (dataset_summary.txt) is generated in the datasets/summaries/ directory.
Visualization Generation: Test creating bar charts, line charts, and scatter plots using the sample dataset and ensure output images are saved in the visualizations/ directory.
Combined Insights: Upload at least two visualizations and their insights. Verify that a combined_insights.txt file is created in the project directory.
Example Dataset
Use the sample dataset provided in the datasets/raw/ folder or create a sample dataset in .xlsx format with columns such as Category, Sales, Date, etc.

Figures and Output Verification
Ensure that the saved visualizations and insights files match the requests made in the Gradio interface.
Validate combined insights by comparing with the individual insights uploaded.
License
This project is licensed under the MIT License. See the LICENSE file for details.

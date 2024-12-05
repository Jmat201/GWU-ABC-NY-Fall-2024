# GWU-ABC-NY-Fall-2024
Business Practicum Project done for Agricultural Bank of China New York, in Fall 2024


# SAR-Generation

## Project Goals
1. Identify and choose the optimal LLM model for local deployment without using cloud solution or cloud hosted services. 
2. Performance Enhancement through integration with LlamaIndex and using RAG to search relevant document
3. Set up a local MySQL or PostgreSQL server database with Jupyter Notebook or Google Colab 
4. The LLM should extract data from this database to create detailed SAR narratives.
5. Format and Design a Jupyter Notebook or Google Colab format for clear SAR narrative presentation.
6. Analyze hallucination occurrences in narratives and how to mitigate them. 
7. Fine-tuning the LLM model for optimal narrative generation.


---

## Potential Roadblocks and Barriers to Success
- Selecting and running a suitable LLM model locally.
- Efficiently integrating GPT index and RAG for improved performance.
- Handling the setup and connection between MySQL and Jupyter Notebook or Google Colab.
- Ensuring the generated narratives meet industry standards for SARs.
- Ensuring the generated narratives have minimal to no hallucination risk.

## Preferred Methodology
The project will be student-driven, with the team acting as consultants to develop, test, and optimize the SAR narrative generation tool. They will be responsible for all aspects of the development process, including model selection, data integration, and presentation format.

## Data Requirements and Availability
Students will use synthetic or anonymized data to simulate the SAR narrative generation process. Real-world datasets are not required for this project.

## Analytics Requirements
- Data engineering involving MySQL setup and integration with Jupyter Notebook or Google Colab.
- Use of LLMs and additional tools like GPT index (LlamaIndex) and RAG.
- Tuning and fine-tuning of LLM models for optimal results.

## Preferred Tooling
- **Programming languages:** Python and SQL.
- **Collaboration tools:** GitHub, Jupyter Notebook or Google Colab.
- **Database:** MySQL.
- **AI Tools:** Selected GenAI LLM model, GPT Index (LlamaIndex), RAG.


## Installation Instructions
To enhance your development experience, it is recommended to install the `vuerd-vscode` extension for Visual Studio Code. This extension provides a visual editor for ER diagrams, which can be very useful for database design and management.

### Steps to Install `vuerd-vscode` Extension:
1. Open Visual Studio Code.
2. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or by pressing `Ctrl+Shift+X`.
3. In the Extensions view search bar, type `vuerd-vscode`.
4. Click on the extension named `vuerd-vscode` by `dineug`.
5. Click the `Install` button.

Alternatively, you can install the extension directly from the Visual Studio Code Marketplace by visiting [this link](https://marketplace.visualstudio.com/items?itemName=dineug.vuerd-vscode).

---

### Linking to Google Colab and Saving to GitHub

#### Linking to Google Colab:
1. **Open Google Colab:**
   Go to [Google Colab](https://colab.research.google.com/).
   You can simply go to Google Colab and you can choose 'GitHub' on the box which you can see when you just go to the Colab site and login. 
   Colab will automatically redirect you to github in order to authorize your github account. Then you can choose repository to use at Google Colab!

2. **Open a Notebook:**
   You can either create a new notebook or open an existing one.

3. **Mount Google Drive:**
   To access files from your Google Drive, run the following code in a Colab cell:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')

4. **Saving to GitHub:**



# Diagnostic Tool for Assessing and Increasing the Sustainability of Renewable Energy Projects
A user-friendly Excel-based tool designed to assess and visualize alignment with Sustainable Development Goals (SDGs), tailored for researchers, policymakers, and organizations to measure and report project impacts.

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [License](#license)
6. [Contributing](#contributing)
7. [Contact](#contact)

## Introduction
The DTAI-SDG Tool simplifies the complex process of evaluating projects against the United Nations Sustainable Development Goals (SDGs). Developed to assist in the structured assessment and visualization of alignment with SDGs, this tool aids in the decision-making process by providing clear, traffic-light insights into how well projects align with each SDG and how decision-makers can make relevant decisions to better achieve the sustainability of renewable projects.

## Features
- **Color-coded Visualization**: Utilizes a unique color-coding system to highlight SDG alignment directly within Excel.
- **Customizable Criteria**: Offers flexibility to adapt assessment criteria based on specific project needs or guidelines.
- **Automated Macros**: This package includes built-in macros for automated data processing and reporting, reducing manual workload and potential for error.
- **Interactive Questionnaire**: Features an interactive questionnaire format that captures user inputs to assess SDG alignment.

## Function Breakdown in Main Worksheet
| Function                              | Description                                                                                                          | Interface               |
|:---------------------------------------------|:---------------------------------------------------------------------------------------------------------------------|:-----------------------:|
| **Select Renewable Energy Type**      | Displays a dedicated Excel sheet for the chosen energy type and resets the questionnaire.                             | ![Logo](images/Logo_1.png)       |
| **Select Questionnaires**             | Shows the question list and resets previous responses as needed.                                                     | ![Logo](images/Logo_2.png)      |
| **Submit the User's Answer**          | Collects and stores the user's responses in the Master List. Providing an option to rename the Master List.           | ![Logo](images/Logo_3.png)      |
| **Generate the Overview Result**      | Aggregates responses into the Stand-alone Complex (SAC) sheet, highlighting the project's impact on SDGs.           | ![Logo](images/Logo_4.png)   |
| **Customize Thematic Category**       | Enables users to define custom tags for each question, supplementing predefined generic tags.                        | ![Logo](images/Logo_5.png)     |
| **Capture the Current View**          | Visualizes the evaluation of the relationship between RESs and SDGs in a new diagrammatic sheet; allows renaming.    | ![Logo](images/Logo_6.png)      |

## Function Breakdown in Master List
| Function           | Description                                                                                                                  | Interface             |
|:-------------------|:-----------------------------------------------------------------------------------------------------------------------------|:---------------------:|
| **Analyze SDG**    | Displays the analysis results as a traffic light indicator on the right-hand side of the Sankey Diagram, representing the overall performance of certain projects on specific SDGs. | ![Logo](images/Logo_7.png)   |
| **Analyze Tags**   | Displays the analysis results as a traffic light indicator on the left-hand side of the Sankey Diagram, representing the overall performance of project-level decisions. | ![Logo](images/Logo_8.png)

## Getting Started with the Excel SDG Assessment Tool
To begin using the Excel SDG Assessment Tool, follow these steps:
1. Download the Tool:
- Navigate to the GitHub repository.
- Download the **DTAI-SDG_Release Candidate.xlsm** file to your computer.
2. Download the Sankey Diagram:
- Ensure that the Sankey Diagram file is downloaded into the **same folder** as the Excel tool for proper integration.
3. Open the Excel File:
- Locate and open the DTAI-SDG_Release Candidate.xlsm file in Microsoft Excel.
4. Enable Macros:
-When you open the file, you might see a security warning asking if you want to enable macros. Click "**Enable Content**" to ensure the full functionality of the tool.
These steps will prepare you to start using the tool with all its features activated and ready for analysis.

## Usage 
1. Start by navigating to the "Questionnaire" sheet in the Excel workbook.
2. Enter your project data in the designated fields and select applicable SDGs.
3. Use the macro-enabled buttons to process data and generate the report:
 - Click the "Target" button to generate the "Master List" of the questionnaire.
 - View results in the "Master List" sheet, by clicking "Analyse SDG" and/or "Analyse Tags" to evaluate the project's sustainbility.
4. Save or print the output directly from Excel for presentation or further analysis.

## License
This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/).

![CC BY-NC 4.0](https://i.creativecommons.org/l/by-nc/4.0/88x31.png)

Under this license, you are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material

The licensor cannot revoke these freedoms as long as you follow the license terms. However, under the following terms:
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- **NonCommercial** — You may not use the material for commercial purposes.

For more details and the full license text, please see the link above.

## Contribution Guidelines

1. **Fork the Repository**
   - Navigate to the GitHub repository and click on the 'Fork' button.
2. **Create a New Branch**
   - In your local clone of the forked repository, create a new branch by running:
     ```
     git checkout -b feature-branch
     ```
3. **Make Changes and Test Your Code**
   - Implement your modifications and ensure to test your code thoroughly.
4. **Submit a Pull Request**
   - Once your changes are ready, push your changes back to your GitHub repository and submit a pull request to the original repository. Include a detailed description of your changes.
5. **Cite Our Framework**
   - If you use our framework to generate a paper, please ensure to cite us! Find the paper links in the **Reading List**.

## Contact
For any questions, suggestions, or issues, please contact us through the GitHub issue tracker associated with the repository.

## Reading List
**Users of this tool should refer to the following paper, in which the tool is introduced**:

- Tian J., Culley S.A., Maier H.R., Zecchin A.C. and Hopeward J. (2024)  [Diagnostic Approach and Tool for Assessing and Increasing the Sustainability of Renewable Energy Projects](https://www.mdpi.com/2071-1050/16/24/10871). Sustainability, 16(24), 10871. DOI: 10.3390/su162410871 (OPEN ACCESS).

- Tian J., Culley S.A., Maier H.R. and Zecchin A.C. (2024)  [Is renewable energy sustainable? Potential relationships between renewable energy production and the Sustainable Development Goals](https://www.nature.com/articles/s44168-024-00120-6), npj Climate Action, 3, 35 (OPEN ACCESS).


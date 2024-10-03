
# CV to HTML/CSS/JS-Portfolio Website Generator

## Overview

The **CV to HTML/CSS/JS-Portfolio Website Generator** is an AI-powered application designed to transform your CV (in PDF or DOCX format) into a beautiful and responsive static HTML portfolio. Utilizing advanced tools such as CrewAI and Google Gemini, this project streamlines the process of showcasing your skills and experiences in a professional manner.

Try now: https://huggingface.co/spaces/Sobit/cv-2-website

Full tutorial: https://medium.com/@nepalsobit1

![image](https://github.com/user-attachments/assets/0de1018d-a5f8-4d7f-b766-36ec79a144c9)

![image](https://github.com/user-attachments/assets/546b6c7b-13f3-4e5c-bb2f-083d5b0ffdfe)

## Features

- **CV Analysis**: Analyzes your CV to extract key skills, experiences, and accomplishments.
- **Portfolio Generation**: Generates a fully responsive HTML/CSS/JS portfolio website based on the analysis.
- **Modern Design**: Employs a clean layout with sections for skills, projects, experiences, certifications, publications, and contact details.
- **Easy Deployment**: The output is a complete HTML document ready for deployment.

## Technologies Used

- **CrewAI**: Tool used for creating AI agent for CV analysis and portfolio generation.
- **Google Gemini**: Language model for understanding and generating content.
- **Gradio**: Framework for creating user-friendly web interfaces.
- **pdfplumber**: For extracting text from PDF files.
- **python-docx**: For reading DOCX files.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- pip (Python package installer)


### Usage

1. Download the notebook file and run all the cells to host on your own.

## OR

1. Clone this repo.
```
   git clone https://github.com/sobit-nep/cv-to-portfolio-crewai-agent.git
```

3. Install all the required dependencies.
```
   pip install -r requirements.txt
   ```
4. Start the gradio app by running,
```
   python gradio_app.py 
   ```

6. Click on the **Upload** button to upload and generate your portfolio.

7. The preview webpage for generated code will be displayed, and you can download the complete code by clicking on the **Download Code** button.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to create an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to CrewAI and Google Gemini for their powerful tools that made this project possible.
- P.S. As I've used the freely available Gemini model here, the output isn't that convincing. I tried OpenAI's gpt 4-o and the result was 100x better in terms of responsiveness and UI.

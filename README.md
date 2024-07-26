# LLM Science Teacher

## Overview
The **LLM Science Teacher** is an interactive chatbot designed to answer science-related questions. It utilizes a language model to generate responses tailored to the age of the user, providing age-appropriate explanations for various scientific concepts.

## Project Details
- **Author**: Ahmad Makki
- **Course**: MS Data Science
- **Student ID**: MSDSF23M022

## How It Works
The project uses a Natural Language Processing (NLP) model to process and respond to questions. The chatbot interacts with users by:
1. Asking for the user's age.
2. Generating responses based on the user's input and age, ensuring that explanations are suitable for the user's understanding level.

## Key Features
- **Age-Specific Responses**: The chatbot adjusts its explanations based on the age provided by the user, making it accessible and educational for a wide range of ages.
- **Interactive Interface**: Users can ask questions through a simple interface, and the chatbot provides real-time answers.
- **Speech Recognition**: The chatbot can listen to and interpret spoken questions, making the interaction more natural.

## Dependencies
The project requires the following libraries:
- `transformers`: For language model operations.
- `torch`: PyTorch for model handling.
- `pyttsx3`: For text-to-speech functionality.
- `speech_recognition`: For recognizing spoken input.

Ensure these dependencies are installed before running the project.


## Usage
1. The chatbot will greet the user and ask for their age.
2. Users can ask science-related questions either by typing or speaking.
3. The chatbot will provide responses appropriate to the user's age group.

## Limitations
- The chatbot currently supports only English language input and output.
- The quality of responses depends on the underlying language model and the specificity of the questions asked.

## Future Work
- Improve the language model for more accurate and diverse responses.
- Add support for more languages and subjects beyond science.
- Enhance the user interface for better accessibility and interaction.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any questions or inquiries, please contact Ahmad Makki at [makkia52@example.com].


# Medical Chatbot

A conversational AI chatbot designed to provide information and assistance related to medical topics. This project uses natural language processing to answer questions about medical conditions, treatments, and general health advice.

**Disclaimer:** This chatbot is for informational purposes only and is not a substitute for professional medical advice, diagnosis, or treatment. Always consult with a qualified healthcare provider for medical concerns.

## Features

- Interactive web-based chat interface
- Natural language processing for understanding medical queries
- Data indexing for efficient information retrieval
- Research and experimentation capabilities
- Customizable prompts and responses

## Project Structure

- `app.py`: Main application file
- `store_index.py`: Data indexing script
- `src/`: Source code directory
  - `helper.py`: Utility functions
  - `prompt.py`: Prompt management
- `templates/`: HTML templates
- `static/`: Static assets (CSS, JS)
- `data/`: Data files
- `research/`: Research notebooks and experiments
- `requirements.txt`: Python dependencies
- `setup.py`: Package setup

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Harshil-Patel23/Medical-chatbot.git
   cd Medical-chatbot
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. (Optional) Run setup:
   ```bash
   python setup.py install
   ```

## Usage

1. Index the data (if needed):

   ```bash
   python store_index.py
   ```

2. Run the application:

   ```bash
   python app.py
   ```

3. Open your browser and navigate to `http://localhost:5000` (or the specified port) to access the chat interface.

## Research and Development

The `research/` directory contains Jupyter notebooks for experimentation and development:

- `trials.ipynb`: Experimental trials and testing

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the terms specified in the LICENSE file.

## Contact

For questions or support, please open an issue on GitHub.

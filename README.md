# Python and Streamlit Trivia Quiz

## Overview
This Streamlit application provides an interactive way to test your knowledge of Python, Streamlit, and related web technologies through a trivia quiz format. Users can enter their names, answer the quiz questions, and submit their answers to see their scores and the correct answers. Additionally, the application features a leaderboard to compare scores among participants.

## Features
- **User Input for Names**: Participants can enter their names to start the quiz.
- **Dynamic Questionnaire**: Displays multiple-choice questions about Python, Streamlit, and web technologies.
- **Scoring System**: Calculates the user's score based on correct answers.
- **Leaderboard**: Visualizes scores of all participants in descending order, showcasing top performers.
- **Correct Answers Display**: After submission, the app displays the correct answers for users to learn.

## Installation

To run this application, you need Python installed on your system. This application uses Streamlit, pandas, and Plotly for data handling and visualization.

1. **Clone the repository**:
   ```
   git clone https://github.com/SubaashNair/PythonQuiz_streamlit/tree/main
   ```
2. **Navigate to the app directory**:
   ```
   cd path/to/app
   ```
3. **Install the requirements**:
   Make sure you have pip installed and then run:
   ```
   pip install -r requirements.txt
   ```
   The `requirements.txt` should include:
   ```
   streamlit
   pandas
   plotly
   ```

## Running the Application

To launch the application, run the following command in your terminal:

```
streamlit run app.py
```

Replace `app.py` with the path to the script if your terminal's current directory is not the same as the script's location.

## How to Use

After launching the application, follow these steps:

1. Enter your name in the text input box.
2. Answer the quiz questions presented. Each question has multiple-choice answers.
3. Click on "Submit Quiz" to submit your answers.
4. View your score, the correct answers, and the leaderboard displaying the scores of all participants.

## Contributing

Feel free to fork the repository and submit pull requests to contribute to this project. Whether it's adding new questions, enhancing the user interface, or fixing bugs, all contributions are welcome.

## License

[MIT License](LICENSE.md)

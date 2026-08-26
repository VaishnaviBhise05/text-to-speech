#  Text-to-Speech using Python

A simple Text-to-Speech (TTS) application built with Python that converts user-entered text into spoken audio using the `pyttsx3` library. The application works offline and provides a quick way to hear text read aloud.

##  Features

-  Accepts text input from the user
- Converts text into speech
-  Works offline (No internet required)
-  Simple and lightweight
- Built with Python

##  Technologies Used

- Python
- pyttsx3

##  Project Structure

```
text-to-speech/
│── text_to_speech.py
│── requirements.txt
│── README.md
```

##  Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/text-to-speech.git
```

### 2. Navigate to the project folder

```bash
cd text-to-speech
```

### 3. Install the required library

```bash
pip install pyttsx3
```

##  Usage

Run the program:

```bash
python text_to_speech.py
```

Enter any text when prompted:

```
Enter the text:
```

The program will read the entered text aloud through your computer's speakers.

## Example

**Input:**

```
Enter the text: Welcome to Python programming.
```

**Output:**

```
 The system speaks:
"Welcome to Python programming."
```

##  Code

```python
import pyttsx3

engine = pyttsx3.init()

text = input("Enter the text: ")
engine.say(text)
engine.runAndWait()
```

## 🎯 Future Improvements

- Add voice selection (Male/Female)
- Control speech rate
- Adjust volume
- Save speech as an audio file
- Create a simple GUI using Tkinter

## 📄 License

This project is licensed under the MIT License.

---

⭐ If you found this project helpful, don't forget to star the repository!

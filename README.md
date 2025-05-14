
# Speech-to-Text Transcription Using Python  

## **Description**  
This project demonstrates the implementation of a simple Speech-to-Text system using Python's `SpeechRecognition` library. It transcribes audio data from a `.wav` file into text using Google's Speech-to-Text API.  

## **Key Features**  
- Lightweight and quick transcription for small audio files.  
- Utilizes Google's Speech-to-Text API for accurate results.  
- Requires no pre-trained models or local installations.  

## **Requirements**  
- Python 3.7 or above  
- `SpeechRecognition` library installed (`pip install SpeechRecognition`)  
- A valid `.wav` audio file  

## **Steps in the Code**  
1. **Initialize Recognizer**: An object of `sr.Recognizer()` is created to process the audio.  
2. **Load Audio**: The `.wav` file is read and converted into audio data using `sr.AudioFile`.  
3. **Transcribe Audio**: The `recognize_google()` method processes the audio and outputs the transcribed text.  

## **Advantages**  
- Easy-to-use library, no need for additional model downloads.  
- Ideal for small transcription tasks.  
- Minimal setup required.  

## **Error Handling**  
- The script gracefully handles errors, displaying a user-friendly message if an issue arises.  

## **How to Use**  
1. Replace the `audio_file` variable's path with the path to your `.wav` file.  
2. Ensure the `.wav` file is accessible and correctly specified.  
3. Run the script, and the transcribed text will be displayed.  

## **Installation**  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/sony928/Speech-to-Text-Transcription.git  

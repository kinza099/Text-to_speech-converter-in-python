# Text-to_speech-converter-in-python

The Text-to-Speech Converter is a Python program that allows you to convert text into spoken words using the power of text-to-speech synthesis.

Here I'm explaining how the program works:

The program starts by importing the necessary libraries: sys and pyttsx3.

The TTS engine is initialized using pyttsx3.init(). This creates an instance of the TTS engine.

Inside the while loop, the user is prompted to enter the text they want to convert to speech using the input() function.

The program checks if the user wants to quit by comparing the input text with "QUIT". If the user enters "QUIT" (in any case), the program prints a goodbye message and exits using sys.exit().

If the user didn't enter "QUIT", the TTS engine's say() function is used to set the text that needs to be spoken.

The runAndWait() function is called to run the TTS engine and wait until the speech is finished.

This program uses the pyttsx3 library to convert text to speech. It continuously prompts the user to enter text and converts it to speech using the TTS engine. The program can be terminated by entering "QUIT".

# Desktop-Voice_Assistant

##Functionality

The script provides the following functionalities:

speak(audio): Function to convert text to speech using pyttsx3.

wishMe(): Function to greet the user based on the current time.

takeCommand(): Function to capture audio from the microphone and convert it to text using speech_recognition.

sendEmail(to, content): Function to send an email using the smtplib module.

## Main program:

Greet the user.
Continuously listen for user commands using takeCommand().
Perform various tasks based on the recognized commands, including:
Searching Wikipedia.
Opening YouTube, Google, or Stack Overflow.
Playing music from a specified directory.
Telling the current time.
Opening Visual Studio Code.
Sending emails.

## Usage
Install the required dependencies mentioned above.

Replace 'youremail@gmail.com' with your Gmail email address and 'your-password' with your password in the sendEmail() function.

Run the script.

Jarvis will greet you and start listening for your commands. You can give voice commands such as:

"Wikipedia search <query>"
"Open YouTube"
"Open Google"
"Open Stack Overflow"
"Play music"
"What's the time?"
"Open Code"
"Send email to Mirza"
Jarvis will execute the corresponding task based on your command.

Note: Make sure your microphone is working correctly for speech recognition to function properly.

Feel free to modify the script according to your needs and add additional functionalities to extend Jarvis's capabilities.

## License
The Jarvis Voice Assistant script is released under the MIT License.

## Acknowledgments
The script is inspired by the virtual assistant featured in the "Iron Man" movie series. Special thanks to the developers and contributors of the pyttsx3, speech_recognition, and wikipedia libraries for providing the necessary tools to build the voice assistant.

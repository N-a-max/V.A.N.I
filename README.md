# V.A.N.I
VANI (Virtual Assistant for Navigation and Interaction) is a personal AI assistant designed to perform various tasks using voice commands. Built using Python and libraries such as pyttsx3, speech_recognition, and pyautogui, VANI is capable of interacting with users through both speech and text.
Key Features:
Voice Interaction: VANI can listen to voice commands and respond in a natural, human-like manner using pyttsx3 for text-to-speech functionality. The assistant is designed to be conversational and intuitive, with speech rate and voice customization options.

Basic Commands:

Time and Weather: Users can ask for the current time or weather updates for any city.

Open/Close Applications: VANI can open or close applications such as Notepad, Microsoft Edge, Camera, Settings, and WhatsApp.

WhatsApp Messaging: VANI can send messages via WhatsApp Web by searching for contacts and typing messages automatically with pyautogui.

Emotion-Based Responses: VANI detects emotional keywords (e.g., happy, sad, angry, stressed) in user speech and provides customized, comforting responses based on the detected emotion. The responses are pre-configured and aim to offer support and comfort.

Notepad Interaction: VANI can write into a Notepad file by listening to the user's dictation.

Extensive Voice Command Recognition: Built to recognize and act on a wide range of voice commands, from opening apps to sending messages, making it versatile in everyday tasks.

Technologies Used:
pyttsx3: For text-to-speech functionality.

speech_recognition: For converting speech to text.

pyautogui: To automate mouse movements and keyboard actions for app interactions.

requests: For fetching live weather updates.

Personalization:
VANI can be personalized by adding custom contacts to a dictionary, making it able to send WhatsApp messages to specific people upon request. It also responds to different emotional states expressed through voice input, offering tailored responses that make the assistant more engaging and emotionally aware.

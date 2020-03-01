# Voice-based-IOS-Form-filling-apllication-for-Blind-People
We intend to build and deliver a voice base form filling application in which voice gets recognized and converted into text. It will use apple SF speech recognizer for this purpose in order to help blind people using accumulating features of apple for smart phone application.
❖INTRODUCTION
• We develop Speech Recognition mobile app to satisfy 96.06% people
including blind people to fill any kind of form in their local language.
• Speech recognition is an ability of a machine or program to
distinguish words and expressions in a dialect and change it to a
machine-intelligible arrangement.
• The sound is matched with words and helps the user to recognize
words.
• Keywords: Speech to Text Interface, iOS, Blind people
❖OBJECTIVE
• The main objective of the project is to develop a Speech to Text
interface using SFSPEECHRECOGNIZER for Form filling application
and screen reader which is helpful for blind people, which is replaces
keyboard for answering the questions in iOS.
• The proposed framework associates with the client’s first language
which is used in both screen reader and speech to text.
• The app prompts a set of questions, created by the app developer to
fill the form
❖SPECIALITY OF OUR PROPOSED SYSTEM:
▪ Our proposed framework can be used in different languages
according to their Interest.
▪ People including visually impaired can also use our app to fill the
form
▪ Screen reader technology (voice over for IOS)is used to communicate
with visually impaired to fill the form or to understand the given
information in the form
❖FLOWCHART OF OUR PROPOSED SYSTEM
 
❖METHODOLOGY
➢ Voice based Form filling Mobile Application in iOS:
• Voice based Form filling Mobile Application is developed in iOS.
• The app is developed in the platform named Xcode.
• The Speech Recognition Extension which supports 8 Indian
Languages and 20 Foreign Languages including Sri Lankan Tamil .
All the form filling data by the user are stored in Cloudstitch, which is
an interactive computer application for analysis. •
• The Fusion Tables Control is used for storing the Form Filled Values,
hich are provided by users by means of speech.
• Fusion Tables is a web service for data management similar to File
Database and it can be used for fetching, viewing and sharing data
tables.
➢ SF Speech Recognizer:
• iOS has a built-in SFspeech transcription system, which allows you to
convert any audio recording into a text stream.
• It takes a few steps to configure, so let’s walk through them.
➢ TRANSCRIPTION:
• Here’s how these objects interact during a basic Speech Recognizer
transcription:
•
• The code required to complete a transcription is quite simple
• First, add import Speech to the top of your Swift file, to bring in the
Speech framework.
• Second, request permission to transcribe audio:
• Third, add a key to your Info.plist called
NSSpeechRecognitionUsageDescription, then give it a string
describing what you intend to do with the transcriptions.
• Finally, write a method to perform transcription on an audio URL.
This URL should be a recording you’ve already made, that is stored
locally on the device:
• Note: the isFinal property is there because you may get an initial
transcription back containing some or all of the text, but it’s only
considered final – i.e. as good as it gets – when the isFinal flag is true
➢ SCREEN READER( VOICEOVER FOR IOS ):
• VoiceOver is the screen reader built into IOS, the operating
system on Apple’s mobile devices. With VoiceOver, someone with
a visual impairment can use a few simple gestures to hear
aloud what is displayed on the screen for people who are
sighted
❖CONCLUSION
• Mobile App plays a vital role in the lives of all people in India, the
people with vernacular medium are in more percentage and this
Voice based form filling app using sfspeechrecognizer will help
them to fill the form in their local language and it will play vital
role for blind people .
• It also helps to connect the blind people and move towards Digital
India.

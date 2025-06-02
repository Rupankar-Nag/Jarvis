# Jarvis

'''
JARVIS - A Voice-Activated Desktop Assistant

Key Features:
- Voice-activated key board ("alt + x")
- Opens applications and websites
- Controls system settings
- Uses Google's Gemini API for intelligent responses
- use app_paths.py to open desktop app


In Development:-
- Closing app
- Playing music


In code:-
- Integrates with Spotify API for media control (Can't run premium reqired )
- Power controlls are commented
- It wakes with("alt + x") but it can also wake with "jarvis" word when microphone is working constantly(It's commented) 


# app_paths.py
#app_map use to open app, example:-
app_map = {
     
}
#to open settings
settings_map = {
    "settings": "start ms-settings:",
}
# app_dict use to close
app_dict = {
    "chrome": "chrome.exe",
}


Dependencies:
- speech_recognition
- pyttsx3
- google-api (Gemini)
- Keyboard
- os 
- webbrowser
- (if you use spotify,{spotipy,spotipy.oauth2})
- yt_dlp (to play song)

Spotify API:- 

google API key :- 


Devaloper: Rupankar Nag

Last Update: 26-04-2025
'''

## Exp4 - Run the get started live api cookbook code

### Objective
- Install all the dependencies and run the code in the LIVE API cookbook.<br>
  https://github.com/google-gemini/cookbook/blob/main/quickstarts/Get_started_LiveAPI.py
- The code runs as a python script.

## Notes
- The code includes streaming audio in and streaming audio out.
- You need to wear earphones or the bot will hear itself speaking and respond. This will make operation unstable.
- Latency is very low.
- Downloading PyAudio on mac can be a challenge. I first downloaded PortAudio with brew and then pip installed PyAudio.
- If you are using Gemini to help you debugging and writing code, remember to specify that your system is running python 3.9. Otherwise it could write python 3.11 code which won't work on your system.
- This code demonstrates the potential power of the Live API. It's like chatting with a virtual human.

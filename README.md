# Gemini Live API Experiments

### My experiments with the Gemini Live API
<br>
<br>

## Experiments

- Exp1 - Text in text out<br>
  https://github.com/vbookshelf/Gemini-Live-API-Experiments/tree/main/Exp1-Test%20in%20text%20out

- Exp2 - Text in audio out - no streaming<br>
  https://github.com/vbookshelf/Gemini-Live-API-Experiments/tree/main/Exp2-Text%20in%20audio%20out%20no%20streaming

- Exp3 - Text in audio streamed out<br>
  https://github.com/vbookshelf/Gemini-Live-API-Experiments/tree/main/Exp3-Text%20in%20audio%20streamed%20out


<br>

## Resources

- Gemini API Docs<br>
  https://ai.google.dev/gemini-api/docs/live

- Cookbook: Multimodal Live API - Quickstart<br>
  https://github.com/google-gemini/cookbook/blob/main/quickstarts/Get_started_LiveAPI.ipynb

- Cookbook: Google code to run locally to test the Live API<br>
(Wear earphones to prevent the bot from hearing itself speak and then responding to what it said.)<br>
https://github.com/google-gemini/cookbook/blob/main/quickstarts/Get_started_LiveAPI.py

<br>

## Notes

1- It appears that chat context memory is enabled by default - the llm remembers past conversation turns.<br>
2- Installing PyAudio on a mac is not easy.<br>
3- On the free plan it looks like only a specified number of conversation turns are allowed. The connection is then terminated.<br>

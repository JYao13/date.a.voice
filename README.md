# date.a.voice
Date.A.Voice is an icebreaker style dating game that allows you to go on a date with multiple possible voice assistants, built using the Alexa Conversations API. The personality of each partner determines how they will react to your actions and words. Try to make your partner happy, and you will be find success!

# lambda contains the the game's logic and database:
  - index.js contains the game's progression logic, shuffle algorithm and API handlers 
  - DateScores.json contains all Alexa responses in JSON format and scores attributed
  - RequestMap.json is the array of keys/values used to access DateScores.json for responses to interact with Alexa's platform

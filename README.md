# Google-Bard <img src="https://www.gstatic.com/lamda/images/favicon_v1_150160cddff7f294ce30.svg" width="35px" />

This code is a command-line interface to Google's Bard chatbot. It allows users to interact with the chatbot by sending messages and receiving responses. The code includes functions for saving and loading conversations and resetting the conversation.

## Dependecies
Before you begin playing with the source code, you might need to install dependencies just as shown below:
```
pip3 install -r requirements.txt
```

## Authentication
Go to https://bard.google.com/

- Log in with the account
- F12 for console
- Copy the values
  - Session: Go to Application → Cookies → https://bard.google.com → `__Secure-1PSID`. Copy the value of that cookie.

## For Quick chat (For one-time question answering)

```
python bard.py --no-quick_chat --session <__Secure-1PSID>
```

## For long conversation

```
python bard.py --quick_chat --session <__Secure-1PSID>
```


- Note that if you got the error then go to the https://bard.google.com/ and clear all the cookies and follow the Authentication part.

Credits:
- [discordtehe](https://github.com/discordtehe) - Derivative of his original reverse engineering
- [acheong](https://github.com/acheong08/Bard)

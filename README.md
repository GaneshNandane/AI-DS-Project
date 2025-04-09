You provide the target Messenger contact name.
The script checks if the latest message is from them.
If yes, it:
Copies the message using screen automation

![aids](https://github.com/user-attachments/assets/a285dc98-c96f-4acd-affa-2a6d5b58c8b5)

Sends the copied message to OpenAI's API
Gets the response and pastes it back into Messenger
 Dependencies
pyautogui
time
pyperclip
openai
Make sure your screen resolution and coordinates match the ones in the script
This script uses hard-coded screen coordinates for clicks and drags. You may need to adjust them based on your screen setup.
Disclaimer

This project is for educational purposes only. Automating interactions on platforms like Messenger may violate their terms of service. Use responsibly.

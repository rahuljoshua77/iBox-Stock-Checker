#  iBox Stock Product Checker
Request URL - Check stock - Send to Telegram - Repeat!
 
# Config.py

token_bot: read the docs https://sendpulse.com/knowledge-base/chatbot/create-telegram-chatbot 

add the bot to the group/channel

username_target: use username channel/grup for public, for private you can use chat id like below:

      1. Open Telegram K version WEB with PC (chrome): https://web.telegram.org/k/

      2. Open inspect element, click arrow icon like in the screenshot 

![image](https://user-images.githubusercontent.com/73378179/145967159-a5f7f6eb-1457-40aa-ab09-7169ec22571a.png)

      3. Pointing to group/Channel private that you want to send the notification
![image](https://user-images.githubusercontent.com/73378179/145967273-d1b228b3-618c-4446-bc16-e551f5748aed.png)

      4. Check element in inpect element, find the peer, excample peer="-123456790", like screenshot below:

![image](https://user-images.githubusercontent.com/73378179/145967456-55dcf4f1-4092-47f2-a623-96089ffb6638.png)         

      5. Find the peer, and then add 100 in the first after -, example the peer="-123456790", add 100 after -, then become: -100123456790

      6. Then Paste it in the config file

      7. Run the script

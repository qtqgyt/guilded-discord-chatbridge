# guilded-discord-chatbridge
Chat bridge for guilded and discord.
# Setup
## Windows (Assuming you found out how to install dotenv on Windows)
### Pre setup
1. Goto your Guilded Server
![image](https://user-images.githubusercontent.com/104375741/233507981-6e4f0832-14e3-4a2d-9298-b1e5a0cd5fe3.png)
2. Open "Manage Bots"
![image](https://user-images.githubusercontent.com/104375741/233508135-7f6ee929-1571-41c8-ac2c-c193bb3ef708.png)
3. Click "Create a bot"
![image](https://user-images.githubusercontent.com/104375741/233508347-499d16da-ecd6-4756-99af-dd0f5ece8a08.png)
4. Enter a name for your bridge.
![image](https://user-images.githubusercontent.com/104375741/233508401-0661ca3b-4846-466b-b1b0-82c972848ebe.png)
5. Click the API tab.
![image](https://user-images.githubusercontent.com/104375741/233508807-7bd0b1c1-15e9-4318-9e08-f3113713cd1f.png)
6. Click "Generate Token"
![image](https://user-images.githubusercontent.com/104375741/233508939-bab47906-5224-451f-be69-16c599d55fb5.png)
7. Goto where you cloned the bot into. (Downloaded the code)
8. Find the .envtemplate file.
9. Rename it to .env![image](https://user-images.githubusercontent.com/104375741/233756054-5ec2d890-7113-4eef-bfbe-e43e6b4d44c0.png)
10. Open the file, and modify the values as such. (GUILDED_IMAGE and DISCORD_IMAGE are optional.)
### Running it
1. Install Python 3.9.13 (IMPORTANT) from https://www.python.org/downloads/windows/.
2. Open Command Prompt (normal user)
3. Go into the directory that you cloned the code into.
4. Run pip install -r requirements.txt
5. Run python3 launch.py
6. Your done!

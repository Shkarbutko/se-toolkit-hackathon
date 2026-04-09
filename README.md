# A bot for quickly selecting items
Description: A Telegram bot that helps indecisive users choose between multiple options by providing a confident recommendation

Demo:
<img width="2058" height="1319" alt="image" src="https://github.com/user-attachments/assets/72713ad4-e60f-42c5-9f66-26793fefd18e" />
<img width="2055" height="1388" alt="image" src="https://github.com/user-attachments/assets/d8d6d9d1-6c70-49e1-9086-df02153d365f" />

Product context:
End-user: People who struggle with everyday decisions, such as choosing what to eat, what to watch or what to buy
Problem: Many people struggle with making decisions when faced with multiple choices, leading to hesitation, stress or wasted time
Solution: My bot

Features:
- Users input options manually
- The bot selects one option randomly
- Basic Telegram interaction with buttons
- Backend stores users, sessions, and option
- Recommendation presets
- Users provide scores for each option
- The bot provides explanations for recommendations with calculates scores 

Usage:
1. Start the bot
2. Select a recommendation preset
3. Enter multiple options with scores
4. Press “Choose for me”
5. Receive a recommendation with explanation

Deployment:
Ubuntu 24.04
Visual Studio Code, Python, WSL
Steps:
1. Run VS Code
2. Install requirements extensions
3. Run WSL
4. Start backend with uvicorn on local computer
5. Start bot in another terminal

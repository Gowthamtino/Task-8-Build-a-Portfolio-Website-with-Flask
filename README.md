# Task-8-Build-a-Portfolio-Website-with-Flask
Objective: Create a simple rule-based chatbot in Python that responds to user inputs using if-else statements.

Tools: Python 3.x, any code editor (VS Code, PyCharm, etc.)

How It Works:

Runs in a loop until the user types "bye".

Uses if-elif-else to check keywords in user input.

Converts input to lowercase for case-insensitive matching.


Code:

print("🤖 Chatbot: Hello! I’m your friendly chatbot. Type 'bye' to exit.")

while True:
    user_input = input("You: ").lower().strip()
    if user_input == "bye":
        print("🤖 Chatbot: Goodbye! Have a great day! 👋")
        break
    if "hello" in user_input or "hi" in user_input:
        print("🤖 Chatbot: Hi there! How can I help you?")
    elif "how are you" in user_input:
        print("🤖 Chatbot: I’m doing great, thanks for asking! How about you?")
    elif "your name" in user_input:
        print("🤖 Chatbot: I’m ChatBot 1.0, your rule-based assistant.")
    elif "weather" in user_input:
        print("🤖 Chatbot: I can’t check the live weather, but I hope it’s sunny where you are! ☀️")
    elif "help" in user_input:
        print("🤖 Chatbot: Sure! You can ask me about my name, how I’m doing, or just say hello.")
    else:
        print("🤖 Chatbot: I’m not sure about that. Try asking something else.")

How to Run:

1. Save as chatbot.py


2. Open terminal in the file’s folder


3. Run: python chatbot.py


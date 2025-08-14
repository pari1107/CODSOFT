# rule_based_chatbot.py

from datetime import datetime

def chatbot():
    print("Hello! I'm RuleBot. Ask me anything or type 'bye' to exit.")

    while True:
        user_input = input("You: ").lower().strip()

        if not user_input:
            print("Bot: Please say something.")
        elif "hello" in user_input or "hi" in user_input:
            print("Bot: Hello there! How can I assist you today?")
        elif "how are you" in user_input:
            print("Bot: I'm just a bunch of code, but thanks for asking!")
        elif "your name" in user_input:
            print("Bot: I'm RuleBot, your simple chatbot friend.")
        elif "bye" in user_input:
            print("Bot: Goodbye! Have a great day!")
            break
        elif "thank" in user_input:
            print("Bot: You're welcome!")
        elif "time" in user_input:
            print("Bot: The current time is", datetime.now().strftime("%H:%M:%S"))
        else:
            print("Bot: Sorry, I didn't understand that. Can you rephrase?")

# Run the chatbot only if this file is executed directly
if __name__ == "__main__":
    chatbot()

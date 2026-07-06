# Basic_Chatbot
Goal: Build a simple rule-based chatbot. Scope: Input from user like: "hello", "how are you", "bye". Predefined replies like: "Hi!", "I'm fine, thanks!", "Goodbye!". Key Concepts Used: if-elif, functions, loops, input/output. 
# -----------------------------------------------
# Project Name:
# Basic Rule-Based Chatbot
#
# Objective:
# Create a simple chatbot that replies
# according to predefined user messages.
#
# Programmer:
# Your Name
# -----------------------------------------------

# Function for chatbot responses
def chatbot():

    print("=========================================")
    print(" Welcome to Python Chatbot ")
    print(" Type 'bye' to exit.")
    print("=========================================")

    while True:

        # Take input from user
        user = input("\nYou: ")

        # Convert input to lowercase
        user = user.lower()

        # Decision Making
        if user == "hello":
            print("Bot: Hi! Nice to meet you.")

        elif user == "hi":
            print("Bot: Hello!")

        elif user == "how are you":
            print("Bot: I'm fine, thanks! How are you?")

        elif user == "what is your name":
            print("Bot: My name is Python Chatbot.")

        elif user == "who made you":
            print("Bot: I was created using Python programming.")

        elif user == "what can you do":
            print("Bot: I can answer simple predefined questions.")

        elif user == "thank you":
            print("Bot: You're welcome!")

        elif user == "thanks":
            print("Bot: My pleasure!")

        elif user == "bye":
            print("Bot: Goodbye! Have a nice day.")
            break

        else:
            print("Bot: Sorry, I don't understand that.")

# Call Function
chatbot()

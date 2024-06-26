def main():
    print("Chatbot: Hi, I'm a simple chatbot. You can start chatting with me or type 'quit' to exit.")
    
    while True:
        user_input = input("You: ")
        
        if user_input.lower() == 'quit':
            print("Chatbot: Goodbye!")
            break
        
        response = respond(user_input)
        print("Chatbot:", response)

if __name__ == "__main__":
    main()

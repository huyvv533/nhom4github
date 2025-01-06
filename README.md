# nhom4github
def greet_user(name: str) -> str:
    """
    Returns a greeting message for the user.
an cut kiẹt
    Args:
        name (str): The name of the user. huy da sưa xong

    Returns:
        str: A greeting message.
    """
    return f"Hello, {name}! Welcome to the Python project."


def main():
    """
    Main function to execute the program.
    """
    user_name = input("Enter your name: ")
    message = greet_user(user_name)
    print(message)
if __name__ == "__main__":
    main()

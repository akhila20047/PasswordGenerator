# Java Password Generator

This is a simple Java program that generates random passwords of specified length. The generated passwords include a combination of lowercase letters, uppercase letters, numbers, and special characters.

## How to Use

1. Clone or download this repository.
2. Ensure you have Java installed on your system.
3. Compile the `PasswordGenerator.java` file.
    ```
    javac PasswordGenerator.java
    ```
4. Run the compiled Java class.
    ```
    java PasswordGenerator
    ```
5. You will be prompted to enter the desired length of the password.
6. The program will generate and display a random password of the specified length.

## Customize

You can customize the password length by modifying the `length` variable in the `main` method of the `PasswordGenerator.java` file.

## Security Considerations

- This password generator uses `SecureRandom` to ensure secure generation of random characters.
- It is recommended to use passwords of sufficient length (e.g., at least 12 characters) and complexity to enhance security.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

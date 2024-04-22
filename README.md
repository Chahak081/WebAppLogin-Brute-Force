# WebAppLogin-Brute-Force
"WebAppLogin-Brute-Force" is a Python script built for brute-forcing web application login pages. It employs the requests library to automate login attempts by iterating through a provided password list. Upon successful login, it outputs the discovered username and password combination.


## Usage

### Obtaining Password List

To perform brute-force attacks using the `WebAppLogin-Brute-Force` script, you will need a list of potential passwords. One widely used and comprehensive password list is the "rockyou.txt" file, which contains a vast collection of common passwords.

You can download the "rockyou.txt" file from the following link:
[Download rockyou.txt](https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt)

After downloading the file, place it in the same directory as the `WebAppLogin-Brute-Force` script or specify the path to the file when running the script.

### Running the Script

1. Ensure you have Python installed on your system. If not, you can download and install it from [python.org](https://www.python.org/).

2. Install the required dependencies by running:

3. Clone the repository or download the `WebAppLogin-Brute-Force.py` script to your local machine.

4. Open a terminal or command prompt and navigate to the directory containing the script.

5. Run the script using the following command:

  `python WebAppLogin-Brute-Force.py`

6. Follow the prompts to input the target web page URL, username, password file (including the "rockyou.txt" file), and login failure string.

7. The script will start the brute-force attack, attempting to log in with each password from the list. If a successful login is found, it will display the discovered username and password.



## Contribution

Contributions are welcome and encouraged. Here are some ways you can contribute:

- Report bugs or suggest improvements by [creating an issue](link_to_repository_issues).
- Submit your fixes or enhancements by [creating a pull request](link_to_repository_pull_requests).
- Share the project with others who might benefit from it.
- Provide feedback and suggestions on how to improve the project.

Your contributions help make this project better for everyone. Thank you for your support!





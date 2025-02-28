# CipherBox
CipherBox is an open-source web application designed to empower users with the ability to encrypt and decrypt strings using state-of-the-art cryptographic techniques. With an intuitive user interface, our application ensures data security and privacy by enabling users to safeguard their sensitive information effortlessly. Join us in advancing data security in the digital realm and contribute to this project.


## Project Structure
```
- /css
  - styles.css        # CSS styles for the application
- /js
  - app.js            # JavaScript logic for the application
- /images             # Image assets 
- /crypto             # Folder for cryptographic algorithm modules
  - aes.js            # Example: AES encryption module
  - rsa.js            # Example: RSA encryption module
  - ...
- README.md           # Project documentation
- /public
  - index.html        # Main HTML file for the web application
- LICENSE             # License file 
```
- **crypto**: Contains JavaScript files for each algorithm. Each file must contain a function for Encryption and Decryption each. For eg. aes.js contains aesEncrypt, aesDecrypt. Make 'n' number of files, The more the merrier :wink:. Refer the files for standard logic.
- **app.js**: imports each function from the respective JavaScript file in /crypto directory.

<hr>

#### Before contributing, please review the [CONTRIBUTING GUIDELINES](./CONTRIBUTING.md).
#### Our Code of Conduct:   [CODE OF CONDUCT](./CODE_OF_CONDUCT.md)
#### Don't forget to register for [Hacktoberfest](https://hacktoberfest.com/) to get your rewards.
<hr>

## Resources:
- [Git Tutorial for Beginners](https://www.youtube.com/watch?v=DVRQoVRzMIY)
- [What is a Pull Request?](https://www.youtube.com/watch?v=8lGpZkjnkt4)
- [**CryptoJS Documentation**](https://cryptojs.gitbook.io/docs/#documentation)


## Project setup instructions:
- **Fork the repository** to your GitHub account by clicking the "Fork" button at the top-right corner of this page. This will create a copy of the repository under your account.
- **Clone your forked repository** to your local machine using Git. Replace `your-username` with your GitHub username:

   ```
   git clone https://github.com/your-username/CipherBox.git
   cd CipherBox
   ```
- **Create a new branch** for your contribution. Replace *'feature/your-feature-name'* with a descriptive branch name related to your contribution.
- Commit your changes with a descriptive commit message:
  ```
  git commit -m "Add your descriptive message here"
  ```
  - Push your changes to your forked repository on GitHub:
  ```
  git push origin feature/your-feature-name
  ```
  <hr>
## Getting started with contributions

- ### Create a Pull Request (PR)

Visit the [CipherBox](https://github.com/gdsc-jssstu/CipherBox) repository on GitHub.
Click the "Compare & pull request" button next to your recently pushed branch.
Follow the PR template and guidelines. Provide details about your changes.
Submit the PR.

- ### Review and Merge

The maintainers will review your PR and may request changes or provide feedback.
Once your PR is approved, it will be merged into the main repository.

<hr>

## Final version of the project

<!--- Place the link to the Figma file inside () --->
Click [here](https://www.figma.com/file/HRAxLh7LUXvFwDYZCaRf7H/Cybersec?type=design&node-id=0-1&mode=design&t=KYTiXyLrb9LlJSW9-0) for the UI design and prototype of the project.

<hr>

## Intended final project:
In its intended final version, **CipherBox** aspires to become a robust and versatile string encryption web application, offering users a secure and user-friendly experience. Here are the key features and goals we envision:
-  **Comprehensive Cryptographic Suite**: CipherBox will offer a comprehensive suite of cryptographic algorithms, including industry-standard ciphers like AES, RSA, MD5, SHA-256 and DES, providing users with a wide range of encryption options to meet various security requirements.
-  **User-Friendly Interface**: Our goal is to provide an intuitive and user-friendly interface, making it easy for both beginners and experts to use CipherBox effectively. We aim to ensure that users can encrypt and decrypt strings with minimal effort.



 <hr>

## Thank You

Thank you for contributing to **CiphorBox**! Your contributions help make this project better for everyone.
If you have any questions or need further assistance, please don't hesitate to reach out to us.

<hr>

### Maintainers
Any Doubts? Feel free to contact us.
- [Tushar Singh](https://github.com/theinit01)

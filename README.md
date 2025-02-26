# Secure Data Hiding in Image Using Steganography  

This project demonstrates how to securely hide and retrieve messages within images using Python-based steganography. By manipulating pixel values, the project embeds messages imperceptibly, ensuring secure communication.  

## Features  
- Real-time message embedding in an image.  
- Password-protected decryption for secure access.  
- Simple and user-friendly process.  
- Easily extensible to include advanced techniques.  

---

## Requirements  
Ensure you have the following installed before running the project:  
- Python 3.13.3 
- OpenCV (`pip install opencv-python`)  

---

## How It Works  

1. **Prepare an Image**  
   Select an image (e.g., `pic.jpg`) to use as the cover image. Place it in the same directory as the script.  

2. **Run the Script**  
   Use the following command in your terminal:  
   ```bash
   python steganography.py
3. **Enter the Secret Message**
Enter the message you want to hide and set a password to protect it. The script will embed the message into the image and save it as encryptedImage.jpg.

4. **View the Encrypted Image**
The encrypted image will open automatically after the process. It looks identical to the original but contains your secret message.

5. **Decrypt the Message**
Run the script again and provide the password to retrieve the hidden message. If the password matches, the original message will be displayed.

**Example**
***Encryption:***

    Input:
        Image: pic.jpg
        Secret Message: Hello, world!
        Password: mypassword
    Output:
        Encrypted Image: encryptedImage.jpg

***Decryption:***

    Input:
        Encrypted Image: encryptedImage.jpg
        Password: mypassword
    Output:
        Original Message: Hello, world!

***Future Enhancements***
1. Add encryption to the message for an extra layer of security.
2. Build a user-friendly graphical interface.
3. Support larger messages or files (e.g., audio or video).
4. Improve robustness against image compression and noise.

***Acknowledgments***

This project showcases the power of Python for implementing steganography and demonstrates practical applications for secure data hiding.


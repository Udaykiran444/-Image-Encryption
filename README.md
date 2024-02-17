


**Image Encryption Decryption**
This project is a graphical application built with Tkinter in Python, providing functionalities for encrypting and decrypting images using the Advanced Encryption Standard (AES) algorithm.

**Description**
The Image Encryption Decryption application allows users to select an image file, encrypt it, decrypt it, reset it to the original format, and save the encrypted image. The encryption process involves dividing the image into blocks and performing mathematical operations using a randomly generated key. Similarly, decryption reverses the process to retrieve the original image.
**
Features**
Open and display images: Users can select an image file from their system, which will be displayed in the application window.
Encrypt images: The selected image can be encrypted using the AES algorithm.
Decrypt images: Encrypted images can be decrypted to retrieve the original image.
Reset images: Users can revert the edited image back to its original format.
Save encrypted images: Encrypted images can be saved to the user's system.

**Dependencies**
This project relies on the following libraries:

Tkinter: For building the graphical user interface.
Pillow (PIL): For image processing tasks.
OpenCV (cv2): For image manipulation and processing.
NumPy: For numerical operations.
Getting Started
To run the application, follow these steps:

Ensure you have Python installed on your system.
Install the required dependencies using pip:
Copy code
pip install tkinter pillow opencv-python numpy
Clone or download the repository to your local machine.
**Run the main.py file using Python:**
python main.py
**Usage**
Launch the application.
Click on the "Choose" button to select an image file.
Use the "Encrypt" button to encrypt the selected image.
To decrypt an encrypted image, use the "Decrypt" button.
Click on "Reset" to revert the edited image to its original format.
Use the "Save" button to save the encrypted image to your system.
To exit the application, click on the "EXIT" button.
**Contributions**
Contributions to this project are welcome. Feel free to submit issues or pull requests.

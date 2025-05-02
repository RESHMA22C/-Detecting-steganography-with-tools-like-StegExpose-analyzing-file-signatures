# Detecting-steganography-with-tools-like-StegExpose-analyzing-file-signatures
# Name: Reshma C
# Reg No:212223040168
## AIM:
To detect hidden data using steganography detection tools like StegExpose and analyze file signatures for authenticity and manipulation.

## DESIGN STEPS:
### Step 1:
Install StegExpose or use the JAR version to detect steganography in image files.

### Step 2:
Run StegExpose on a directory of suspected image files using the command:

### Step 3:
Analyze file signatures using tools like file, binwalk, or xxd to check for inconsistencies or embedded content.

# PROCEDURE:
Download a .jpeg image from a trusted website or use own image.
![image](https://github.com/user-attachments/assets/fac56dc3-5841-47e4-b98d-b62be1d60022)

Create a text file named secret with a confidential message:
![image](https://github.com/user-attachments/assets/1ba5993a-6b2b-4ada-8099-b6b5b9c39933)

# Step 2: Install and Verify Steghide Tool

 • To install Steghide on Kali linux,run:

 • Confirm the installation by checking its version image

![image](https://github.com/user-attachments/assets/58fe8c85-0fc4-42d4-a184-4377f7b886fb)

# Step 3: Embed the Secret Message into the Image
• Use the following command to embed secret
![image](https://github.com/user-attachments/assets/6a9949a5-e16e-40b0-883c-1522b464c1e7)

![image](https://github.com/user-attachments/assets/ce317e69-9ae6-4945-9fac-f2903fc34e39)

# Step 4: Delete the Original Secret File
• After embedding, delete the plaintext file:
![image](https://github.com/user-attachments/assets/aebf59b5-42ae-4c0b-ae9a-036597d69d7c)

## OUTPUT:
List of Images with Steganography Detection Scores and File Signature Details
![image](https://github.com/user-attachments/assets/671c257c-6f77-4e11-a900-097d235ccde4)

![WhatsApp Image 2025-05-02 at 09 08 34_50f6fa78](https://github.com/user-attachments/assets/311b2127-8264-4cbc-a462-953295fbd4c2)

# Step 2: Verify the Extracted Message
• Display the extracted file content to verify:

• Ensure the message matches the original secret content.

• Another command to see the same secret message is

# Step 3: Retrieve Information About the Embedded Data
• To gather details about embedded content in the image:
![image](https://github.com/user-attachments/assets/fbb808c9-3000-40a2-b696-5baf82f9d361)

• This will display file type, size, and whether data is embedded.

## RESULT:
Hidden data was successfully detected and file signatures were analyzed for irregularities.

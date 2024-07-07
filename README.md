# PRODIGY_CS_02

This Python code implements a simple image encryption scheme using the XOR operation. Here's a breakdown of its functionality:
 * Input:
   * The program prompts the user to enter the path of the image file to be encrypted.
   * It also asks for a numerical encryption key.
 * Encryption Process:
   * The code opens the image file in read-binary mode ('rb').
   * It reads the entire image data into a variable and closes the file.
   * The image data is then converted into a byte array for easier manipulation.
   * The program iterates through each byte in the array and performs a bitwise XOR operation with the encryption key. XOR operation flips the bits whenever the corresponding bits in the data and key are different. This scrambling process effectively encrypts the image data.
 * Output:
   * The encrypted byte array is written back to the original image file, effectively replacing the original image data.
   * Finally, the program prints a message indicating successful encryption.
Important points to note:
 * This is a relatively simple encryption method and might not be suitable for high-security applications.
 * The decryption process would involve performing the XOR operation again with the same key to retrieve the original image data.
 * This code snippet lacks error handling mechanisms for potential issues like invalid file paths or incorrect key input.

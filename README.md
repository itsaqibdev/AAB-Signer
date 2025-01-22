# AAB Signer

<p align="center">
  <img src="https://raw.githubusercontent.com/itsaqibdev/AAB-Signer/refs/heads/main/logo.webp" alt="AAB Signer Logo" width="150"/>
</p>

A simple, cross-platform GUI application for signing Android App Bundles (AAB) using Java.

## Requirements

- Java Runtime Environment (JRE) 11 or later

## Running the Application

1. Download `AABSigner.jar`
2. Double-click the JAR file, or run from terminal:
   ```bash
   java -jar AABSigner.jar
   ```

## Features

- Modern, user-friendly interface
- Cross-platform (works on both Windows and macOS)
- Drag and drop support for AAB and keystore files
- Automatic alias detection from keystore
- Password visibility toggle
- Progress indication during signing
- Error handling and validation

## Usage

1. Select your AAB file using the browse button or drag and drop
2. Select your keystore file using the browse button or drag and drop
3. Enter your store password and key password
4. Click "Fetch Alias" to automatically detect available aliases
5. Select or enter the alias you want to use
6. Choose the output location for the signed AAB
7. Click "Sign AAB" to start the signing process

## Notes

- Make sure Java is properly installed on your system
- Keep your keystore and passwords secure
- The signed AAB will be created in the location you specify

# Fileuploader

FileUploader is an application that enables users to easily set up a server for uploading files. Users can access this server either via LAN connection or remotely through a Ngrok URL. When utilizing Ngrok, the URL will be conveniently provided along with a QR code for easy access.

![Fileuploader Screenshot](screenshot.png)

## Features

- **Ngrok Integration**: Utilizes Ngrok for secure tunneling to expose the local server to the internet, allowing remote access to the file uploader.
- **File Upload**: Users can upload multiple files simultaneously.
- **Stylish Interface**: Provides a user-friendly interface with file upload functionality and visual file type icons.
- **Local IP Display**: Displays the local IP address and port for accessing the file uploader interface locally.

## Requirements

- Python 3.x
- Flask
- Requests
- Pillow (PIL)
- Tkinter (for displaying QR code)
- qrcode
- Ngrok

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/Suomimuumi/Python-Fileuploader
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:

    Run the app from init.exe file.

4. Access the file uploader interface:

   - Locally: Visit [http://localhost:8080](http://localhost:8080) in your web browser.
   - Remotely: Use the Ngrok URL provided after starting Ngrok.

## Configuration

Author: Arttu Väisänen

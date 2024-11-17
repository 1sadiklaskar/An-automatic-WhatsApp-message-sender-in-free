
# WhatsApp Automatic Message Sender Using Python

This Python project allows you to automatically send WhatsApp messages at a specified time using the `pywhatkit` library. It opens WhatsApp Web in your browser and sends a message to a contact at the scheduled time.

## **Features**

- **Schedule WhatsApp Messages**: Set a specific time (in 24-hour format) to send your message automatically.
- **Customizable Messages**: Send any custom message to a contact.
- **Easy to Use**: Just set the recipient's phone number, message, and time.
- **Built with Python**: Uses the `pywhatkit` library to interact with WhatsApp Web.

## **Requirements**

Before you run this project, make sure you have the following installed:

- **Python 3.x**: Make sure Python 3.x is installed on your machine. You can download it from [here](https://www.python.org/downloads/).
- **pywhatkit library**: Install the required library using `pip`.

You can install the library by running the following command in your terminal or command prompt:

```bash
pip install pywhatkit
```

## **Setup & Usage**

### 1. **Clone the Repository**

To get started, clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/whatsapp-auto-message-sender.git
cd whatsapp-auto-message-sender
```

### 2. **Configure the Script**

- Open the `whatsapp_auto_message_sender.py` file in a code editor (e.g., VSCode, Sublime Text).
- Modify the following variables in the script:
  - **phone_number**: Enter the recipient's phone number in the format `+<CountryCode><PhoneNumber>`. For example: `+14155552671`.
  - **message**: Change the message to whatever you want to send.
  - **hour** and **minute**: Set the time when you want the message to be sent (in 24-hour format).

Example of script configuration:

```python
# Phone number to send the message to (include the country code)
phone_number = '+1234567890'  # Change this to the recipient's phone number

# Message you want to send
message = "Hello! This is an automatic message sent via Python."

# Time to send the message (24-hour format)
hour = 15  # 3 PM
minute = 30  # 30 minutes past the hour
```

### 3. **Run the Script**

Once you've configured the script, run it using the following command:

```bash
python whatsapp_auto_message_sender.py
```

### 4. **WhatsApp Web Login**

The script will open WhatsApp Web in your default browser. You need to **scan the QR code** using your phone's WhatsApp app to log in if you aren't already logged in.

Once logged in, the script will automatically send the message at the scheduled time.

## **Important Notes**

- **WhatsApp Web Login**: The script opens WhatsApp Web in your default browser. Ensure you're logged into WhatsApp Web, and your phone is connected to the internet.
- **Timing**: The message will be sent with a slight delay after the scheduled time, as the script needs a few seconds to open the browser and send the message.
- **One-time Use**: If you want to send another message, you’ll need to rerun the script. It doesn't send recurring messages automatically.
- **Time Zone**: The script uses the local system time. Make sure the time you provide is accurate.

## **Contributions**

Feel free to contribute to the project! You can:

- Open issues to report bugs or suggest new features.
- Submit pull requests with bug fixes, improvements, or new features.

## **License**

This project is open-source and available under the [SADIKLASKAR License](LICENSE).

## **Contact**

For any questions or feedback, please feel free to reach out to me via GitHub or email.

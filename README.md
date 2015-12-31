# HyperBit

HyperBit is an alternate client for the Bitmessage network. This is a very early release and should mainly be used for testing.

If you have any questions or feature requests please join the `hyperbit` channel (BM-2cUXYTknxwZgp47DKayzKwNfipQRQCmb2m). If you find any bugs be sure to report them to BM-87ZQse4Ta4MLM9EKmfVUFA4jJUms1Fwnxws. 

This version only supports channels (no person-to-person messages yet).

# Windows

Extract hyperbit.zip.

Run hyperbit.exe.

If you receive a Windows Firewall notification, make sure to allow access.

# Running from source

## Requirements

- Python 3.4.3 or later
- PyQt5
- quamash (requires libffi)
- cryptography (requires OpenSSL)
- appdirs

## Windows

Install Python 3.4.4 from [https://www.python.org/downloads/release/python-344/](https://www.python.org/downloads/release/python-344/). Make sure to select "Add python.exe to Path".

Install the PyQt5 binary package from [https://riverbankcomputing.com/software/pyqt/download5](https://riverbankcomputing.com/software/pyqt/download5)

Open a command prompt and run this command:

    pip install quamash cryptography appdirs

Run HyperBit:

    python c:\path\to\hyperbit\hyperbit.py

If you receive a Windows Firewall notification, make sure to allow access.

## Ubuntu

Install dependencies:

    sudo apt-get install python3-pip python3-pyqt5 libffi-dev libssl-dev
    sudo pip3 install quamash cryptography appdirs

Run HyperBit:

    python3 /path/to/hyperbit/hyperbit.py


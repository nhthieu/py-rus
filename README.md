# Remote Control Project

A simple Remote Control project for the Networking Course, implementing socket programming in Python.

## Introduction

The project is divided into two parts:

1. Server: Contains the code to manipulate the system that the file is running on. This includes:

   > - Keylogging
   > - Taking screenshots
   > - View/kill processes/apps
   > - Start app
   > - Shutdown

2. Client: Contains the code to communicate with the server. This includes:

   > - Connect to server
   > - Send commands
   > - Receive commands
   > - Disconnect from server

## Prerequisites

1. Make sure you have Python 3.6 or higher installed.
2. Disable Windows Defender (since the project uses keylogging)
3. You need to install the required libraries located in the _required.txt_ file.

Run the following command to install the libraries:

```
pip install -r required.txt
```

## Run

- To run the server, locate to the server folder and run the following command:

```
python server.py
```

- When the server is running, the address is displayed in the console.

- To run the client, locate to the client folder and run the following command:

```
python client.py
```

- Keylog and screenshots file will be saved in the _tmp_ folder.

## For non-programmers

This project comes with pre-built .exe files for both the server and client.

## Screenshots

![screenshot](https://ik.imagekit.io/ifzn1ow2v/rc_screenshot_QWoPmTs0e.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1657960718590)

![screenshot](https://ik.imagekit.io/ifzn1ow2v/rc_server_screenshot_JegqL-NoF.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1657960950444)

## Contributions

Special thanks to the following people for their contributions:

- Nguyen Ho Trung Hieu: 20126038
- Vu Hoai Nam: 20126045
- Truong Do Truong Thinh: 20126056
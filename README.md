#### Secure Messaging Web Application

## Pre-Encryption - Using HTTP

The original set up of this web application uses HTTP protocol to transmit data between the parties within the chat box. Here I will show screenshots demonstrating how this is NOT a secure channel of communication. Even if the people communicating are in what they think is a secure "Chat Room" that has a 4 letter pass phrase to enter, it is still not safe due to the insecure nature of HTTP.


# Note the "this is a test message" within the chat!
![Chat Log](chatLogPreEncryption.png "Showing the chat log")


# As you can see, the data transmitted is NOT encrypted.
**Look towards the bottom of this screen shot to see the data**
![Wireshark Capture](wiresharkPlaintext.png "WireShark Capture")
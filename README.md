# FFMPEG_Server_Client_Project

The server simply sends the .ts video stream packets over the network socket, which the client reads and stores in the output_file.
The key steps are:
1) Creating an output file to store the video stream.
2) Reading packets from the network socket.
3) Writing the packets to the output file.
4) Decoding the .ts file and displaying the video frames using SDL.

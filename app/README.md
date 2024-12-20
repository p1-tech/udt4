recvfile receives a file from a UDT server and saves it to a local file.

sendfile acts as the sending end of a file transfer.

recvfile return codes:

| Return Code | Description |
| ----------- | ----------- |
| 0 | Success |
| 1 | Failed to connect to server |
| 2 | Failed to send file name |
| 3 | File not found on server |
| 4 | Failed to receive file |
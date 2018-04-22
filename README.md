# Socket-Programming-in-C-Language 

### QUESTION 1

There are two directories in this question Client and Server containing the respective codes of client.c and server.c. 

**Error Handlers:**

- IP Address converting handler
- Socket creating and connection handler
- File availability handler

**Code Snipet:**

  ```bash
  # To run the server
  cd Q1/Server
  gcc server.c -o server
  ./server
  # Now the server is listening to the clients(if no errors in starting the server).
  ```

```bash
# To check the server-client connection
cd Q2/Client
gcc client.c -o client
./client
# Now all the files present on the server and available to us will be displayed 
# We will be asked to choose one among them
# Type the file name and the file will be downloaded
```

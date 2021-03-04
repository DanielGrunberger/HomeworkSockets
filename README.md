# HomeworkSockets

#The code implements 3 things :#  

###Client### - The client can send to the server the following commands:  
  DIR [Directory] - List the files on the given directory  
  COPY [PATH_ONE] [PATH_TWO] - Copy file from PATH_ONE to PATH_TWO  
  DELETE [PATH] - Delete from given path (The path includes the file to delete)  
  EXECUTE [PATH] - Run program on given path  
  TAKE_SCREENSHOT - The server takes a screenshot and saves it (on the server)  
  SEND_PHOTO - The server sends the last screenshot taken to the client  
    
 ###Server### - Waits for a connection from client and runs the commands  
   
 ###Protocol### - The protocol between client and server. It is responsible for creating valid messages, extracting the data from messages and checking that the message is valid.  
 
 





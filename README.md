# 2b IMPLEMENTATION OF SLIDING WINDOW PROTOCOL
## AIM
## ALGORITHM:
1. Start the program.
2. Get the frame size from the user
3. To create the frame based on the user request.
4. To send frames to server from the client side.
5. If your frames reach the server it will send ACK signal to client
6. Stop the Program
## PROGRAM
```python
import time

frame_size = int(input("Enter the number of frames: "))

for i in range(1, frame_size + 1):
    print("Sending Frame", i)
    time.sleep(1)

    print("Frame", i, "received by server")
    print("ACK", i, "received by client")

print("All frames sent successfully")
```

## OUPUT

<img width="313" height="437" alt="image" src="https://github.com/user-attachments/assets/53452ef1-e012-4983-ab18-58ed7b7e79e5" />

## RESULT
Thus, python program to perform stop and wait protocol was successfully executed


CMPE-277 – Assignment 1:


Activity Lifecycle
In this application, We have incremented the thread counter whenever the Main Activity restarts to demonstrate that when a new activity (Activity B, Activity C) is opened and we go back to the previous activity, onRestart() method is called. We increment the thread counter by 5.
On the other hand, when a dialog Activity is opened, and we go back to the previous activity, onRestart() method is not called, so the thread counter remains unchanged.
Home screen:

<img width="322" alt="Screenshot 2024-10-06 at 8 16 47 PM" src="https://github.com/user-attachments/assets/9946bbdb-bbd7-4211-b64a-5b54e8c39832">






Activity B opened:

<img width="324" alt="Screenshot 2024-10-06 at 8 18 31 PM" src="https://github.com/user-attachments/assets/42b7a87b-8055-4a2c-9f0f-b3f946b46c5a">





Count incremented by 5:


<img width="324" alt="Screenshot 2024-10-06 at 8 19 48 PM" src="https://github.com/user-attachments/assets/3b27938f-c211-4848-a7cc-72b4cc14b481">


Dialog opened:

<img width="354" alt="Screenshot 2024-10-06 at 8 59 15 PM" src="https://github.com/user-attachments/assets/57d3d827-5918-47ab-8522-e25c5617c9f3">


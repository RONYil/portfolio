1.Connect to the car and log in to the server where the car is located.  
website: http://(the name of our car).local:8888/
passward: nle23
2.Upload mode_weights_3.pth to the server.
3.Upload deploy.ipynb, or create a new ipynb file on the server to copy the code.
4.Step by step running code
note:The code may run erratically, you can ask chatgpt or your teacher, but all the basic structure of the deployment is there.
The code contains three structures in order
1. Process the image as you did before
2. Deploy the model based on the pth file
3. Running the loop will also run the car and let it grab the picture (I don't know much about this part, but I wrote some for you from memory). If there is a problem, log in to the server and view the demo file of the car, which has a specific explanation. After the image is captured, the model makes predictions and prints the results. (The execution part is replaceable, and you can replace the printing with letting the wheels of the car turn.)
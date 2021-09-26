# data-science projects

For potato-tomato disease problem. Its' an end to end application very useful in agriculture domain.
There are 2 major kind of disease that happens to potato leaves:
early blight -> caused due to fungus
late blight  -> caused due to special type of mircro organism.

If farmer can detect this kind of leaves at early stage then its possible to control lots of waste and improve economy.
Since treatment for early and late blight are totally different, its important to find out what kind of disease is there in the potato plant.

So idea here is to develop a mobile application or feed image of potato leaves to a website and application will tell what kind of disease it is.

In the back end, will have deep learning and convolutional neural network working to predict such disease.

Architecture design:
Please refer attached images basic_architechture*.PNG

Execution:
1. Run api/main.py and it will open http://localhost:8000/predict 
  Postman can be used to send POST query to webpage and upload a file, model will predict the disease.
  
2. Will deploy the predict function to GCP.
  
<img width="942" alt="frontend_image" src="https://user-images.githubusercontent.com/26452961/134792088-0ba8d6b2-d474-475d-a655-401a63aa1318.PNG"><img width="812" alt="image_detection" src="https://user-images.githubusercontent.com/26452961/134792092-748f61a2-c06c-4f05-8058-f5e1f7653dd7.PNG">
<img width="911" alt="basic_architechture3" src="https://user-images.githubusercontent.com/26452961/134792093-1199f2c9-9ba4-43f6-9eaa-75c6af663d96.PNG">


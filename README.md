# LW-TASK-6-Face-Recognition-and-AWS


In this task, my team has created an Face recognition model which on recognizing perform the following tasks:-
1. Send email to the developer on recognising the face.
2. Send a Whatsapp message to the developer notifying an AWS instance being launched along with a user created EBS volume.
3. Will launch the AWS instance and will create the Volume as per the User requirements and then automatic attach the volume to the instance launched.

Additional things to be noted for the working of the model properly:-
1. Set the environment variables in the local system for sender and receiver email.
2. Set the environment variable in the local system for the Whatsapp Number.
3. Create a folder named as "dataset" wherever the Face recognition.ipynb is present.
4. Login to your aws account using AWS CLI first in order to launch the insatnce. 

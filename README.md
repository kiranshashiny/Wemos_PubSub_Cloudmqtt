# Wemos_PubSub_Cloudmqtt
Code to demonstrate Publish and Subscribe of data to Cloudmqtt.com using Wemos Wifi module

## Connects to CLoudmqtt.com and publishes "hello world" every few seconds.

It is assumed that you have created an instance in the Cloudmqtt.com

For this demo, I have the Cat service, and an instance created.

Go to Details on the cloudmqtt.com page, and get the servername, User, and the Password and fill that in the code appropriately.

The Port number used is 19757.

I have set the Arduino Serial Monitor port baud to 9600, so after uploading the code, enable the serial monitor and set the baud to 9600 to view the connections and other publish messages. At the same time go to Cloudmqtt.com -> Websocket and look for the published messages.

Possible scenarios where this might not work are - 

	Incorrect Port Number. ( 19757 in my case )
	
	Incorrect User name and password.

and if all fails- restart the instance to get it working again.

Use this code for all other Publish and Subscribe scenarios.



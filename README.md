# asyncable_restj
This project is a simple REST webservice that supports both asynchronous as well as synchronous calls. Perfect fit for IOT applications but scaleable for much more !

# Details
The design consists of three main components: Message Publisher, Message Broker, Message Consumer all running in the same host.  The broker used in this implementation is MQTT which makes this project a great fit for IOT applications. Furthermore, since the design of this webservice associates one publisher, one broker and one consumer, this design decision makes the webservice scale-able for real world web applications that are much bigger than just small IOT.  
